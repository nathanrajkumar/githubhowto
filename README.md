# githubhowto

hey bro! Welcome to git.  This stuff is super important to know when you jump into development.

So what is GIT and why is it important?

Github is a version control tool.  Specifically, it helps a team of devs keep track of:

1. What changes were done
2. Who made those changes
3. When those changes were done
4. Where those changes were done

and if the PR is good,

4. Why those changes are there in the first place.  

What is version control?  

Version control is a way to keep track of changes to your code (i.e version 1, version 2, etc)

In the real world, devs may send out a release version of all the fixes and features in one fell
swoop.  This is important cause if something messes up, you can rollback to a pervious version.

What is a PR?

PR stands for Pull Request.  A PR is created when you make changes to a piece of code or documentation.
Its basically a form that you fill detailing the fix (the why) and what changes were done.

Okay, cool, so GIT has a few common commands you're going to need to know:

CLONE
FETCH
PULL
COMMIT
PUSH
CHECKOUT
MERGE

Git is a way of saving your work through a repository.  If you've gotten this far, this means you
have done a git clone.  This clones the repo on your local computer which means everything saved in GIT
gets put on a folder on your computer.  

Git works like a tree.  Your main branch is your master branch.  You would never poush anything onto the master branch as
a dev.  Mainly cause if stuff breaks, it could break it for everything and people will be pissed.  Instead you will need
to fork a new branch, a feature branch, by running git checkout then make your changes here.

When you make and save your changes, you can run a git fetch which tests the save onto Github to make sure
your changes dont have merge conflicts.

you will then commit your changes with a new message something like git commit -m "made a few changes"

then push your code.

After you push your code, you will need to make a pull request and an admin will approve and merge it.

If this doesnt make sense, cool, no worries, I can run it down and eventually it will become old hat.  We can use this
repo to look at code together or pass doco as well. 
