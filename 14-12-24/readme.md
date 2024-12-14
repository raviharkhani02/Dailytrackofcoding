# Day 1
## Today's learning
- Git Markdown file `.md`

# Git learning
## - `git init` 

<b>Create a New Repository:</b>

- Running git init in a directory creates a new empty Git repository.
- It generates a .git folder where Git stores all its metadata, including commits, branches, and tags.
- If you accidentally delete the .git folder or need to reinitialize a repository, running git init again restores the Git structure without affecting your project files.

## - `git add`

- Key Purposes of git add:

    - Stage new files: Include newly created files in the next commit.

        -Example: git add newfile.txt

        Stage modified files: Include changes made to existing files.

        Example: git add modifiedfile.txt
    Stage specific portions of changes: With the -p or --patch option, you can selectively stage parts of changes within a file.

        Example: git add -p modifiedfile.txt
       tage all changes in the working directory: Using          the . or -A option stages all changes (new, modified, and deleted files).

        Example: git add .
        Stage deleted files: Mark deleted files for removal in the next commit.

        Example: git add deletedfile.txt

## - `git commit`
- The git commit command is used to save changes made to files in your local Git repository. It's a critical step in version control, as it creates a snapshot of your current project state that you can refer back to later. Each commit records a set of changes, along with a message that describes what was done, and is identified by a unique hash.

## - `git remote add orgin <url>`
- to connect to the local repository to github repository.

## - `git push`
- it pushes the local changes/commit to the github repository.(in cloud).
