# CI/CD Practice — IBM

Learning repository for IBM's **Continuous Integration and
Continuous Delivery (CI/CD)** course.

This repository contains notes, exercises, and practical work
connecting course concepts with development and deployment workflows.

## Goals

- Understand continuous integration and continuous delivery.
- Practice working with branches, commits, and pull requests.
- Automate compilation and container image builds.
- Add tests and error handling.
- Gradually build a reproducible CI/CD lab.

## Progress

Last confirmed update: **November 15, 2026**.

- [x] Module 1: Introduction to CI/CD.
- [ ] Module 2: Continuous Integration — in progress.
- [ ] Complete the remaining modules.
- [ ] Implement and document a CI/CD lab.

Next lesson: **Tools of Continuous Integration (CI)**.

## Completed Practice

### Build and Deployment Workflow Analysis

A written exercise based on a familiar workflow:

1. Prepare a working branch.
2. Modify and compile the code.
3. Build a container image.
4. Deploy to a development environment.
5. Verify behavior through functional tests and logs.
6. Request review and integration through a pull request.
7. Restore the previous version if the change fails.

The exercise documented an existing Bash script used to automate
compilation and image builds. A proposed improvement was to track
the relationship between the source commit, build, and resulting image.

This was an analysis and documentation exercise.
No new CI/CD pipeline was implemented during this practice.

## Next Steps

- Continue the course from the last completed lesson.
- Prepare a small personal lab.
- Record the source commit and generated image reference.
- Verify that compilation failures stop the image build.
- Gradually incorporate these steps into a CI workflow.

## Documentation Approach

Each practice will document:

- What was implemented or executed.
- How the result was verified.
- What failed and how it was resolved.
- What remains a proposal or future task.

Examples will use lab code and data.

## Course

[Continuous Integration and Continuous Delivery (CI/CD) — IBM](https://www.coursera.org/learn/continuous-integration-and-continuous-delivery-ci-cd)
