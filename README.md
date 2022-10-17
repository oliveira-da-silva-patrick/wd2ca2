# README - How this repository has been created

## Introduction

This GitHub repository has been created by Oliveira Da Silva Patrick (020152332A).

This link has been used to learn markdown: https://www.markdownguide.org/basic-syntax/

I prefer using the GitHub Desktop app. The screenshot provided were taken on that same app.
Alternatively, you can create the repository with the browser version of GitHub but the file
upload is limited. Visual Studio Code is also really useful as commiting and publishing code
can be done through the same editor.

## Tutorial

Open the app and click on 'Create a New Repository on your Hard Drive...'.
   
![Create repository](images/01-create-repo.png)

In the new window, add the name of the repository. The name here is 'wd2ca2'.
Agree to create the README file.
We don't need a Git Ignore but we need a License. Let's select the MIT License.

![Setting up the new repository](images/02-setting-up-new-repo.png)

A local repository has been created now and you should have a similar window.

![Local Repository on Desktop app](images/03-new-repo-desktop-app.png)

The repository looks like this in the Finder.

![Local Repository on Finder](images/04-new-repo-finder.png)

When you change something on the repository, the changes become visible on the desktop app.

![Changes on Desktop app](images/05-repo-after-first-changes.png)

We need to commit these changes and to publish them afterwards.
Normally, you work with others on a project and/or the project is multi-layered.
It's best to create new branches and to merge them at a later time.
So, the next step is creating a new branch 'development' and to commit the changes to that branch.

![Creating a new branch](images/06-creating-new-branch.png)

![Naming the new branch](images/07-naming-new-branch.png)

We need to specify that we want to take the changes to the new branch.

![Taking the changes to the new branch](images/08-taking-changes-to-new-branch.png)

Now, we are in the new branch with the changes. Add a commit title and description and click on commit.

![Commiting to branch](images/09-repo-in-new-branch.png)

The changes disappeared from the repo screen. You can confirm in the 'History' tab 
that the changes have been committed.

![Commit history](images/10-changes-history.png)

Push your commits.

![Pushing the commits](images/11-pushing.png)

Don't forget this is the first commit. This means that the current branch will be
pushed. We are currently in the development branch, this mean not in the main branch.

Because the repository does not exist yet on GitHub, an additional window to set it up
will appear.

![Pushing for the first time](images/12-preparing-push.png)

Now, you can open the repository on your browser. Notice the main branch not being there.

![Repository on browser](images/13-repo-browser.png)

Let's go back to the main branch.

![Switching branch](images/14-switching-branch.png)

This branch is empty. Imagine we finished working on the development branch and 
now desire to merge the two branches. So, let's merge them.

![Merging branch](images/15-merging-branches.png)

![Merging branch](images/16-select-branch.png)

Now, you should have everything you made on your local repository online.
To update your local repository with the online repository, use fetch.

![Fetching](images/17-fetch.png)