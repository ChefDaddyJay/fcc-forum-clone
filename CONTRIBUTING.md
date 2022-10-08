# freeCodeCamp forum clone's contributing guide

## Documentation

Please, make sure to read through the following documents:

- our [code of conduct](./CODE_OF_CONDUCT.md)
- and [README](./README.md)

## Issues

### Creating issues

Feel free to check out [our codebase](https://github.com/jdwilkin4/fcc-forum-clone). If you think, that something could be added, fixed, or improved on, first that there is no open issue for that by looking through the [issues tab](https://github.com/jdwilkin4/fcc-forum-clone/issues).

If you are confident, that your issue won't be a duplicate - go ahead and [create it](https://github.com/jdwilkin4/fcc-forum-clone/issues/new/)!

If you have some ideas about possible changes, please share your thoughts by creating a new thread in [the discussions](https://github.com/jdwilkin4/fcc-forum-clone/discussions).

### Picking up an issue to work on

Browse through the [opened issues](https://github.com/jdwilkin4/fcc-forum-clone/issues) and feel free to start working on that does not have have an assignee yet.

If you are a [collaborator](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-personal-account-settings/permission-levels-for-a-personal-account-repository#collaborator-access-for-a-repository-owned-by-a-personal-account), assign yourself to the issue you want to work on.

If you are not a collaborator, please leave a comment in the issue thread so we know that you are working on it.

In any case - make sure to use the issue thread to ask questions about the issue if you need!

## Making changes

If you are experienced with Git workflow, please read through the **How to contribute** section of our [README](./README.md).

If you are new to Git and GitHub, please read the follow sections below on how to get started.

### Installing git

If you don't have Git installed on your machine, [install it](https://help.github.com/articles/set-up-git/). If you are not sure if it is installed, please use the `git --version` command in the command line.

### Forking the repo

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

- Using GitHub Desktop:
  - [Getting started with GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/getting-started-with-github-desktop) will guide you through setting up Desktop.
  - Once Desktop is set up, you can use it to [fork the repo](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/cloning-and-forking-repositories-from-github-desktop).

### Creating a local copy of the repo (aka cloning)

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the copy to clipboard icon.

Open a terminal and run the following git command:

```
git clone url-you-just-copied
```

where `url-you-just-copied` is the url to this repository (your fork of this project).

### Installing dependencies

If you don't have Node.js installed on your computer, please read through [these instructions](https://nodejs.dev/en/). If you are not sure if Node.js is installed, please run the `node -v` command in the command line.

Then change to the project directory by using the `cd fcc-forum-clone` command. To install the dependencies, run the `npm install` command.

### Creating a new branch to start working on the issue

Change to the FCC forum clone directory on your computer (if you are not already there):

```
cd fcc-forum-clone
```

Now create a branch and switch to that new branch using the `git checkout` command. _One way to name a branch would be: `<number-of-issue>-<type-of-changes>-<what-the-issue-is-about>`_

```
git checkout -b your-new-branch-name
```

### Commit changes and pushing them

Commit the changes once you are happy with them.
If you go to the project directory and execute the command `git status`, you'll see there are changes.
Add those changes to the branch you just created using the `git add` command:

```
git add changed-file-name
```

Now commit those changes to your local branch using the `git commit` command. _Try to make commit message descriptive, but not super verbose!_

```
git commit -m "commit message"
```

Push your local branch and create a remote branch on GitHub using the command `git push` :

```
git push -u origin branch-name
```

### Pull Request

When you're finished with the changes, create a pull request, also known as a PR.

- Please follow all instructions in the template so that we can review your PR.
- Don't forget to [link PR to issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue) if you are solving one.
- Enable the checkbox to [allow maintainer edits](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/allowing-changes-to-a-pull-request-branch-created-from-a-fork) so the branch can be updated for a merge.
  Once you submit your PR, a team member will review your proposal. We may ask questions or request for additional information.
- We may ask for changes to be made before a PR can be merged, either using [suggested changes](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/incorporating-feedback-in-your-pull-request) or pull request comments. You can make any other changes in your fork, then commit them to your branch.
- As you update your PR and apply changes, mark each conversation as [resolved](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request#resolving-conversations).
- If you run into any merge issues, checkout this [git tutorial](https://github.com/skills/resolve-merge-conflicts) to help you resolve merge conflicts and other issues.

### Still a little bit lost?

- Check out [this video](https://www.youtube.com/watch?v=RGOj5yH7evk) from freeCodeCamp's YouTube channel on Git and GitHub basics.
- Don't be shy to ask us about anything related to the project and working on it. Depending on your question, use pull request threads, issue threads or the discussions.