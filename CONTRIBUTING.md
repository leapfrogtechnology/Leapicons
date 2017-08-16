# Contribution Guidelines

Thanks for taking the time to contribute.
Following are the  set of guidelines for contributing to Leapicons.

## Code of Conduct

This project and everyone participating in it is governed by the Leapicons [Code of Conduct](https://github.com/leapfrogtechnology/Leapicons/blob/master/CODE-OF-CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to opensource@lftechnology.com.

## Pull Requests

Please create a Pull Request for any new icons and bug fixes. Please follow the following guidelines for creating a PR:

### Branching:

-__Always make a branch from the dev branch__. Work on a new branch created from the dev branch. Never create branch from the master and always send a *pull request* to the dev branch.
-__Name branch appropriately__. Name your branches with the related category your icons fall under. For example if creating Weather icons; the branch would be named *weather*.

Guidelines for pull requests:

- __Make your commit messages as descriptive as possible.__ Include as much information as you can. Explain anything that the file diffs themselves won’t make apparent.
- __Document your pull request__. Explain your fix, link to the relevant issue, add screenshots when adding new icons.
- __Include only related work__. If your pull request has unrelated commit, it won't be accepted.

Take a look at this **free** tutorial if working on your first Pull Request:
[How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)

## Requesting a new Icon

Before creating an icon request, please search to see if someone has requested the icon already. If there is an open request, please add a :+1:.

If the icon has not already been requested, [create an issue](https://github.com/leapfrogtechnology/Leapicons/issues/new) with a title of `Icon request: <icon name>` and add as much information as possible.

## Bug Reports

Before reporting an issue, please search to see if someone has filed a similar issue before. If there is already an open issue, please add a :+1: and/or leave a comment with additional information.

When creating a new issue make sure to include the following:
- Version of Leapicons in use. Are you running from source/master? Are you using a released build? Which release?
- Your environment. What is your operating system? 32 or 64 bits?
- Step to reproduce. Even if the step is only one line change, __include it!__ Include the actual result and what you expected.
- A screenshot of any visual bug.

Here is what a great bug report would look like:
```
Check not rendering properly

Version: Release v3.1.0
Downloaded from: Import using webpack
OS: Mac OSX

How to reproduce:
 - Import `check` icon
 - Add to a React component/view
 - Run the react app
 - Notice that the `check` isn't rendering correctly which seems a encoding problem
Actual result:
 - Import `check` icon
 - Add to a React component/view
 - Run the react app
 - Check is displayed with correct encoding (e.g UTF-8)

No console output
...
```
