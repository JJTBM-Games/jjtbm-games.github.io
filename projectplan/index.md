# Project plan

## Workflow

All project work will be contained within the GitHub organisation. For working with git and GitHub there are several procedures. 

### Feature implementation

First a new feature or change request must be added to the project on the GitHub project. When all desired details are added, a issue will automatically be created in the correct repository. The project makes use of the Gitlow standard. By default every repository has a `main` and `development` branch. For every newly implemented feature or bug fix, a new `feature` branch is created, branching of the `development` branch. The name of such feature branch must be as following: `feature-<desired name>`. When a commit is made to the feature branch, the number of the linked issue must be referenced.

When development is done by the developer, a pull request must be created. This pull request must pull the feature branch to the development branch. In the description a small summary of changes and additions must be given, in such way the integrator understands the changes and additions. The integrator must be tagged as the reviewer. The integrator reviews the code, tests the code and checks for the coding standards. When the pull request is accepted, the feature will be pulled to the development branch.

When a new version is up for release, a new `release` branch will be branched of from the development branch. This branch is pulled to the `main` branch. Also a release is made on GitHub.

### Documentation

All the documentation is made in markdown and added to the github.io repository of the organisation. When a commit is done on the `main` branch, automatically GitHub pages will be generated. 
