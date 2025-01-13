Challenge 20 Cypress & GitHub Actions Project

# lights_camera_action

I took the starter code for this quiz program and created a CI/CD pipeline using GitHub Actions and Cypress to test the program when a pull request is made.

# Table Of Contents

- [lights_camera_action](#lights_camera_action)
- [Task](#task)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Video](#video)
- [Repository](#repository)

## Task

As applications scale and develop, software engineers want to ensure that certain quality checks are met prior to merging to important branches; thus, you'll want to familiarize yourself with Continuous Integration (CI) and Continuous Deployment (CD) that are common practices used to ensure consistency, quality, and deployment of latest code once all checks have been met and merged to main.

## User Story

```md
AS A software engineer looking to integrate a CI/CD pipeline in a codebase
I WANT a full-stack application that runs test cases when a Pull Request is made to the develop branch and automatically deploys to Render when the code is merged to main
SO THAT I can ensure that all code integrations are clean and pass the proper requirements and that the application is constantly updated when major releases are made to the main branch
```

## Acceptance Criteria

```md
GIVEN a full-stack application
WHEN I upload new features to the application
THEN I should be making Pull Requests to a develop branch first
WHEN I create a Pull Request to a develop branch
THEN I should be executing a GitHub Action that checks the Cypress component tests
WHEN I see that the tests pass on GitHub Action
THEN I should see those test results on GitHub Action and merge the code
WHEN I push the code from the develop branch to the main branch
THEN I should see that another GitHub Action triggers and should automatically deploy to Render
```

## Video

- This <insert link> will take you to <insert YouTube> to view the <insert walkthrough video> of this application.

## Repository

- This <insert link> will take you to my <insert GitHub Repository>.
