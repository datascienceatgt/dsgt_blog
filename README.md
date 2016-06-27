# DS @ GT blog

The source code behind the DSGT blog. Located at [PUT BLOG LINK HERE WHEN DONE]().

## Setup

1. Navigate to the desired directory you'd like to store the folder.
2. In your terminal window, run ```git clone git@github.com:datascienceatgt/dsgt_blog.git```

You're ready to go!

## Git workflow

If you're new to git, do not jump right in! Git is simple but you can easily mess things up if you don't know what you're doing. Try [this tutorial](https://www.codecademy.com/learn/learn-git) first.

#### Branching

Whenever making changes, always make changes on a branch besides master. This will be done to ensure all code can be tested and will work before merging into the master branch.

To create a new branch off of your current branch

```git checkout -b [your branch's name]```

###### Branch naming

Always name a branch with these rules:

1. No spaces or unusual characters (#,$,%,^,&, etc.)
2. Always start the branch name with your initials
3. After initials, put an underscore and one or two words describing the branch

Example: ```rb_update_readme```

#### Making changes

After you make any large changes, commit and push your changes to github:

1. Add all changes - ```git add *```
2. Commit changes - ```git commit -m [your commit message here]``` **
3. Push commit to origin ```git push origin [your branch name]```

###### Commit messages

Short and sweet, should answer the statement "If this commit is merged, it will add ______"

#### Pull Requests

Pull requests (or PR for short) is where code from one branch is staged for merging into another branch (usually master). In Github, you can comment on code, make general comments, and collaborate on what needs to be updated before the branch's code is actually merged into the new branch.

There is one main rule we will follow with pull requests:

**NEVER MERGE YOUR OWN PULL REQUEST WITHOUT REVIEW**

###### PR Flow

Open a PR and tag one of the admins in the comments. We will come review the PR and comment for any changes to be made before merging it into your specified branch.

## Project Structure and Conventions

TODO

