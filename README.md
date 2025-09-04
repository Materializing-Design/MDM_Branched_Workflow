# MDM Template

This is a template repo to start an MDM project with a branched workflow. 

It has 2 branches: `main` and `process`. 

The `main` branch is responsible for the project development and the `process` branch is responsible for reflective journalling. At the end of the project, the `process` branch will be merged with the `main`, and this will weave the reflective journalling history with the development history.  

> [!IMPORTANT]
> This branch **must** stay separate from the `process` branch until the end of the project.
> <br> End of project is denoted by the closing statement in the `process` branch. 

## Process
To capture design process, MDM samples from two distances: up close in commit messages in the `main` branch, and reflective journaling at a distance in the `process` branch.      

### Commit Messages 
When you use Git/GitHub, your development is discretized and packed into chunks called commits. 

Committing to git is integral to the _development_ process. Commits also allow developers to leave _commit messages_.

By reflecting on the immediate work done at the time of committing in these commit messages, we dovetail this 'what' (code changes) with the 'why' (commit message), enabling us to capture "reflection in action" (Schon, 1983) or "hot reflection". 

At the end of the project, these commit messages become part of the design corpus for this repo (including the reflective journaling) that then gets a grounded theory analysis to validate the design reasoning of the research-creation project.  

> [!NOTE]
> Reflection in action is different from reflective journaling which is intended to capture design thinking and proceess at a distance.
>
> Those live in the `process` branch of the repository. 

### Reflective Journaling 
This is the reflective journaling branch where you write and capture while you aren't making. 

The structure inside the folder is only a suggestion, modify it to your liking but the journal as a whole must capture 
1. The intention when/before starting the project 
2. Any reference materials - pictures, videos, links, text docs, etc.
3. Your reflections over time in a `journal.md` file.
4. A closing statement


When the project ends and you've written the closing statement, you may merge this branch with the `main` branch which will then weave all journal commits and the development commits.  

To avoid merge conflicts, please make sure you don't create a second process folder (or whatever you named your process folder(s) in this branch) in the `main` branch.  


### For Teams 
To avoid merge conflicts, team members should make subfolders inside the process folder and add to their own folders only (for sanity and security).  

You may also create sub-branches from the `process` branch for each team member and everyone may commit to their own branch. <br>
This will allow you to keep your journaling separate and avoid merge conflicts. Then you can either have periodic syncs with the `process` branch or sync at the end of the project. 

In any case, you will still need to have separate subfolders for each team member. 
