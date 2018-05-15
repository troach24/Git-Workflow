# Git Workflow

## Objectives

- Explain the benefits of branch workflow
- Create branches
  - git checkout -b branch-name
  - git checkout master
- Merge branches
- Resolve Merge Conflicts

## Notes

* Benefits of branch workflow
  - not all committing to same branch
  - SAFELY work on the same codebase
  - allows you to review code beore committing changes (specifically to master)
  - allows you to break up the work ito smaller chunks
    * Feature
    * Task
    * ~~Release~~
  - Allows us to assign work easier

## Resources

- [Understanding GitHub Workflow](https://guides.github.com/introduction/flow/)
- [Feature Branching Your Way to Greatness](https://www.atlassian.com/agile/software-development/branching)






### ***Matt's notes - start of breakout part II***
# Git Workflow for Teams

## Objectives

- Implement a branch workflow with collaborators/owners
- Implement a branch workflow with a 'gatekeeper'
- Use 'git stash' effectively

## Notes

- Feature branches
- Descriptive commit messages
- Implement a branch workflow with collaborators/owners
  - Everyone has write access/privs
  - work off of one repo
  - Don't merge your own code (someone else approves)
- Implement a branch workflow with a 'gatekeeper'
  - One person that's ultimately responsible at a high level (checks code quality, merge/approves pull requests)
  - Fork from gatekeeper's repo

## Resources

- [Git for Teams](http://gitforteams.com/)
- [Resetting, Checking Out, Reverting](https://www.atlassian.com/git/tutorials/resetting-checking-out-and-reverting)
- [Merging vs Rebasing](https://www.atlassian.com/git/tutorials/merging-vs-rebasing)