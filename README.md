# Gitopia

## What is Gitopia?

Gitopia is an idea for an Open Source Widget which will gameify the concept of Git Commits.

## Goals of Gitopia

- Provide programming accountability by having their GitHub README's Gitopia widget eventually display a certain character, level, health, and location within a story which progresses by pushing commits to a GitHub account.
- Provide assistance in the creation of commits, by eventually taking away character health when commits do not follow [the seven rules of a commit message](https://cbea.ms/git-commit/) - or showing something akin to a star on the widget when the last commit follows all of the rules. 
- After finding work as a software developer and feeling confident in my ability to create well-crafted issues and review code for all of the Project Guidelines, I plan on offering this project as an opportunity for others gain collaborate experience on an Open Source Project

## Project Guidelines

- New UML diagram created for every production version of the project, with OOP principles in mind
- Integration testing
- Comprehensive unit test coverage for behaviour - not implementation, avoidance of tests documented for appropriate reason
- Executed using TDD for majority of the project, only avoiding it/documenting avoidance when appropriate
- Every linter problem fixed, or exception made/documented for appropriate reason throughout project
- Major design patterns researched and implemented/ documented when appropriate
- Every code smell investigated and fixed, or exception made/documented for appropriate reason
- Git workflow of production->development->feature branches strictly adhered to
- Code written in clean, easy to understand, maintanable manner

## Stages of Gitopia Development

Each of the following versions reflects a point in which the development branch can be merged into production once all tests successfully pass:

- Research (current)
- 0.1: Fetches commit data from GitHub API, widget displays current total commits as "experience"
- 0.2: Stores commit data in a database, widget displays ongoing commits starting from 0 as "experience"
- 0.3: Experience is stored in database as levels, widget displays levels alongside experience 
- 0.4: Health is stored in database, widget displays health alongside level and experience
- 0.5: Quality of commits is assessed and database health decremented upon commit titles being too long, widget reflects change

## Questions which need to be answered as part of the Research stage:

- What are the overall tools that will be used for this project for version 0.2?
- In three high-level sentences, how will this project be executed using a widget, databases, and the GitHub API?
- Thinking about 99 bottles of OOP, which concepts and practices can be incorporated for this project?
- Thinking about POODR, which concepts and practices can be incorporated for this project?
- Considering the [refactoring guru website](https://refactoring.guru/) which are the major design patterns that could be implemented in this project?
- What would a UML diagram for version 0.2 look like?
- Considering [coding with jason](https://www.codewithjason.com/complete-guide-to-rails-testing/) when might TDD not be appropriate for this project?
- Considering the same book, how will integration testing be implemented for this project?
