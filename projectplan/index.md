# Project plan

This document contains the project plan for project retro game in the 7th semester. In this project a retro game must be realized by using a FPGA and/or micro controller, without a operation system. The project plan describes the organization and quality of the project and product. 


## Organization

### Project

#### Project members

This project has the following mebers:

* Jochem
* Joas
* Tim
* Bram
* Maarten

#### Stakeholders



#### Tasks and responsibilities

There are several roles within the project:

##### Scrum master

Joas

This person is responsible for the scrum process. The person leads the stand-ups and other meetings. 

##### Integrator

Jochem

This person is responsible for integrating all the newly added features or solved problems to the `development` branch and `main` branch.

##### Developers

Jochem, Joas, Tim, Bram and Maarten

This team is a responsible for all the development within the project. 

#### Planning

For this project the scrum work flow will be used. There will be three sprints. Each sprint takes 3 weeks of time and will have a sprint retrospective at the end of the sprint. In this retrospective all the project members and stakeholders will test and evaluate the past sprint. 

Planning of the sprints will be done in a GitHub project. This platform gives an added benefit of linking with all the repositories. A task is created using a user story. This user story will be added in the description and a short task name will be added in the title field. Tasks can be bound to a sprint and given a tag. 

#### Reports

### Product

#### Tooling

All the code, documents, change- and pull requests and problem reports, GitHub will be used. All the project members can access everything using a organization on GitHub. All the code is structured in repositories. Problem reports and change requests can be done by making a new issue in the desired repository. When committing a change for a certain issue, the issue will be referenced in the commit message. Also pull request are done by using Pull Requests in GitHub. 

#### Procedures

Gitflow will be used for this project. Bellow a future explanation is given about the Gitflow work flow for this specific project.

In every project there must be a `main` branch, with a stable released version of the product, and a `development` branch, where all tested development is based. 

##### Working on a new PR or CR

When starting working on a PR or CR, this must first be opened in a issue, as described above.

When solving a PR or CR a new `feature` branch must be opened. This branch is branched of the development branch and is given a name using the following template `feature-#<issue numbers>`. All development is done for a issue(s) is done on this branch.  When committing changes, the issues will be referenced by using the issue number given by GitHub.

When development is done on a issue, all the features of the product must be tested by the developer before opening a pull request. Opening a pull request is done in GitHub. A pull request must always be pull the desired feature branch to the development branch. The integrator is added as a reviewer. [In the description of the pull request all the solved issues are referenced](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue). The integrator will review the code, by testing all the changes, checking code style. If the review is rejected the developer will be named in the next stand-up. If approved, the integrator will pull the branch. 

##### Release

For releasing a new version of the product a few things have to be done. First of all a new `release` branch must be created. This branch has the following templated name: `release-<version number>`. This version number is based upon the [following system](https://semver.org/). In this `release` branch all the functionality is tested using the written tests. When all tests are approved a pull request can be opened to pull the `release` branch to the `main` branch.

After pulling the release to the `main`, a release can be created on GitHub. All the executables must be uploaded here. Embedded system build are not required to be uploaded. In the release notes all the changes must be described. 

#### Change control

#### Documents

#### Reviewing

## Quality

### Testing

### Requirements

### Reviews
