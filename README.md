# SHD-git
A git workshop being held at Science Hack Day in Ljubljana on Nov 25 2017.

## What is git?

Git is code versioning standard. There are many git hosting services available: GitHub, GitLab, BitBucket, Visual Studio Team Services,...

With git you can have your code safely on a remote server, ready to be accessed by whomever you grant access. With the proper use of git all previous versions of your documents are saved and available.

On Linux, chances are that git command line interface is already installed. On Windows and Mac computers I recommend you [download git tools](https://git-scm.com/downloads). You can open a bash terminal with right click in your preffered folder and clicking `Git Bash Here`.

## Create a GitHub account and a repository

We will be working with GitHub as the most standard for open source projects. If you don't have one yet navigate to [https://github.com](https://github.com) and create an account with them.

With a plus sign in the top right you can create a new repository that will hold your prject. It is recommended that you include a `README.md` file in your repository (like this one) that gives a description of your project.

## Basic git commands: clone, pull, add, commit, push

When first creating a local copy of a git repository you can use the `git clone` command. The actual url will depend on your username and repository, but for this repository this command yould look like this:
```
git clone git@github.com:MKolman/SHD-git.git
```
Once you have a local copy you will never have to call `git clone` for this repository again.

You have at your disposal the following basic commands:
 - `git pull` pull new changes from the remote server to your local copy,
 - `git push` push changes from your local copy to the remote server,
 - `git add <filename>` add all changes in `<filename>` to __staging__,
 - `git reset <filename>` reverse `git add`,
 - `git commit -m <message>` commit all changes that are in __staging__,
 - `git checkout <commit>` revert all files to what they were after commit `<commit>`,
 - `git status` view the current state of your local copy,
 - `git log` view the history of commits in this repository,
 - `git diff` show all unstaged changes in your local copy.

![git basics](img/git-basic.png)

So a typical workflow might look something like this:
```
$ git pull  # Get new changes from remote server
Already up to date.
$ touch new_file.txt  # Create a new file



## Branches



## Jokes
![git fire](img/git-fire.png)
