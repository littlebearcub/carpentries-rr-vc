# Introduction to Version Control
A colleague suggests using version control to manage their work. Version control is better than mailing files back and forth:

Nothing that is committed to version control is ever lost, unless you work really, really hard at it. Since all old versions of files are saved, it’s always possible to go back in time to see exactly who wrote what on a particular day, or what version of a program was used to generate a particular set of results.

As we have this record of who made what changes when, we know who to ask if we have questions later on, and, if needed, revert to a previous version, much like the “undo” feature in an editor.

When several people collaborate in the same project, it’s possible to accidentally overlook or overwrite someone’s changes. The version control system automatically notifies users whenever there’s a conflict between one person’s work and another’s.

Teams are not the only ones to benefit from version control: lone researchers can benefit immensely. Keeping a record of what was changed, when, and why is extremely useful for all researchers if they ever need to come back to the project later on (e.g., a year later, when memory has faded).

Version control is the lab notebook of the digital world: it’s what professionals use to keep track of what they’ve done and to collaborate with other people. Every large software development project relies on it, and most programmers use it for their small jobs as well. And it isn’t just for software: books, papers, small data sets, and anything that changes over time or needs to be shared can and should be stored in a version control system.

## Recording the history of your projects
### What is version control?
Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.

## Question?
How do you record the history of your projects?

### Bad - Run on file names
![](../fig/phd101212s.png)

[PhD Comics](http://www.phdcomics.com)

### Good - Informatively named files
```
   2013-10-14_manuscriptFish.doc
   2013-10-30_manuscriptFish.doc
   2013-11-05_manusctiptFish_intitialRyanEdits.doc
   2013-11-10_manuscriptFish.doc
   2013-11-11_manuscriptFish.doc
   2013-11-15_manuscriptFish.doc
   2013-11-30_manuscriptFish.doc
   2013-12-01_manuscriptFish.doc
   2013-12-02_manuscriptFish_PNASsubmitted.doc
   2014-01-03_manuscriptFish_PLOSsubmitted.doc
   2014-02-15_manuscriptFish_PLOSrevision.doc
   2014-03-14_manuscriptFish_PLOSpublished.doc
```

## Better - Saving everything together at once

Everytime you make a save, you zip the entire directory that your project files are in and save it with a date.

## Best - Version Control

![](../fig/motivation-01.png)

[Code for `RNeXML` `R` package, plus RNeXML publication in `RMarkdown`](https://github.com/ropensci/RNeXML)

## How does a version control system work?
- Version control systems start with a base version of the document and then save just the changes you made at each step of the way.
- You can think of it as a tape: if you rewind the tape and start at the base document, then you can play back each change and end up with your latest version.

![](../fig/play-changes.png)

[Software Carpentry](https://software-carpentry.org/)

- You can then think about "playing back" different sets of changes onto the base document and getting different versions of the document.

![](../fig/merge.png)

[Software Carpentry](https://software-carpentry.org/)

## Why use Git and GitHub

### Why use Git?
- Makes you fearless
- Easy to set up
- Allows you to take a snapshot of every stage of your project history
- Takes up minimal space
- Creates a easy navigable map to the history of all changes made

### Features of using a Hosting Service Like GitHub
- Backup of your project
- No need for a server: easy to set up
- GitHub's strong community: your colleagues are probably already there
- Provides tools to help enhance collaboration
- A common location to share off your work

### Example
![](../fig/motivation-01.png)

[Code for `RNeXML` `R` package, plus RNeXML publication in `RMarkdown`](https://github.com/ropensci/RNeXML)
