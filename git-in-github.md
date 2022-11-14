
## Overview
> 1. In this activity you are going to learn how to collaborate using GitHub. 
> 1. Create a git repository hosted at GitHub
> 1. Build README.md file
> 1. Commit changes to repository
> 1. Collaborate by forking and editing partners file
> 1. Explore GitHub features: graphs, diff, blame, ect.

## Step-by-Step
### Create a repository with a `README.md` file
Follow along with your instructor and perform these steps:
1. Go to your GitHub profile. The url should be http://github/your-user-name.
2. To create a new GitHub repository, click the green "new" button, under the repositories tab. <br><br>
    > Repository: A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project   files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.<br>
<img width="1092" alt="rr-vc-2-1" src="https://user-images.githubusercontent.com/57642282/201413235-bd0e2d4f-d768-4679-b4e3-d91dc9696e20.png">
3. Name your repository organization-your-name, e.g. "yorku-janedoe"<br>
4. In the details write "Tips to organizing research".<br>
5. Click the initiate a README.md file option. <br><br>

> README.md: A text file containing information about the files in a repository that is typically the first file a visitor to your repository will see. A README file, along with a repository license, contribution guidelines, and a code of conduct, helps you share expectations and manage contributions to your project.<br>

6. Select to make the repository public.
![Screenshot to create a new GitHub Repository and select its settings](/carpentries-rr-vc/assets/img/rr-vc-2-2.png)

### So far
- A repository is a directory (folder) that houses both the files of a project AND the git history of the project.
- Once the repository is created you will be directed to the repository page which now has its own web address.
- Each repository on GitHub has a unique url so you can easily share.
- The git history is a detailed history of all the changes made to that file. One of the features of using GitHub is the ability to view your repository history which are displayed in the Graphs section of your GitHub repository page.
- At this point in the git history of your work-organization-your-name repository there is only one commit.

### Edit the README.md file
- Go back to the work-organization-your-name repository main page. Click on `README.md`, then click "edit this file". Add the following information into the readme.md file:
  - Name?
  - What kind of scientist do you you tell people you are at dinner parties?
  - In the past month, what are the three main activities you have been doing at work?
  - What are the three most important tools/strategies you use for organizing your work?
![Screenshot to edit your README.md file](/carpentries-rr-vc/assets/img/rr-vc-2-3.png)
*tip*: Notice that you can use markdown syntax. Use [this guide](https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github/) for GitHub's flavor of `Markdown`. Use the "Preview" button to view the formatting of your `README.md` file.

### Commit
- Commit takes a snap shot of your project. Each commit includes a commit message that concisely defines changes made or project state at the time of the commit.<br>
> Commit: A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.<br>
1. Summarize the changes that you have made in 50 characters or less and click the green "commit button".
![Screenshot to commit changes your README.md file](/carpentries-rr-vc/assets/img/rr-vc-2-4.png)
2. Check out the git history. You should now see two commits.

## Edit and collaborate with your partner
### Collaborate
Now it is time to collaborate with your partner. Navigate to your partner's repository by typing the url directly into your address bar. In order to edit someone else's repository you usually follow this simplified work flow:
1. Fork their repository to your user account
2. Make edits and commit
3. Create a pull request that merges your changes into their repository.

_tip_: Depending on the project there are variations on the above work flow. Often the rules for contributing to a project are outlined in a file called `CONTRIBUTING.md` within the repository. One of the more often used works flows is [GitHub Flow](https://guides.github.com/introduction/flow/).

### Forking
- **Forking** creates a copy of a git repository into your own account.<br>
> Fork: A fork is a personal copy of another user's repository that lives on your account. Forks allow you to freely make changes to a project without affecting the original upstream repository. You can also open a pull request in the upstream repository and keep your fork synced with the latest changes since both repositories are still connected.<br>
- Forking allows you to make changes to a repository without affecting the main repository of the project.
- This is one of the most exciting aspects of GitHub - you essentially encouraged to copy and play with anyone's code!

1. To fork your partner's repository click the "fork" button in the top left hand part of your screen.
2. When it asks where you would like to fork the repository, choose your user account (if you are new to GitHub, this should be the only option).

### Make edits and commit
- You should now have a copy of your partners repository, `work-organization-their-name`.
- GitHub keeps track of the entire git history of the project and all forked copies made of the project.

1. Edit your partners repository by clicking the edit button.
2. Paste in the answers to your questions under theirs and make a commit.

### Create a pull request
- A **pull request** is the final step in the collaboration process, essentially asking if the edits made to your copy can be incorporated into another repository.<br>
> Pull: Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date.<br><br>
> Pull Request: Pull requests are proposed changes to a repository submitted by a user and accepted or rejected by a repository's collaborators.<br>
1. Make sure you are in your copy of your partner's repository by looking at the url - your user name should preface the repository name.
2. Click the green "New Pull Request" button. You will get an overview of the changes you made to the repository.
3. Click the "Create a Pull Request" button to continue the pull request. Your partner will now get a notification of a pull request on their main repository, as will you if your partner made changes.
4. Accept this pull request.

### Explore GitHub features
Now that you have accepted the pull request. Take a few minutes to explore the git history using the Graphs section of the repository.

### Extra Exercise *after* class:

- Find a way to practice by contributing more. You don't have to be a great at programming to help with projects. Many projects are in need of spelling or general editing. There is a whole Twitter community that helps beginner Git users find projects to practice using git.

- Check it out if you want to contribute to more projects: https://twitter.com/yourfirstpr.

- If you are interested in practicing this process try adding a quote to this repository: https://github.com/TheCodingCollective/quotes.

