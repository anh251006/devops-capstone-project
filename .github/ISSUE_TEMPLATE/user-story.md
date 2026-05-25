---
name: User Story
about: Template for creating user stories
title: "[USER STORY] "
labels: user story
assignees: ''

---

**As a** Web Developer  
**I need** a standardized GitHub issue template for user stories  
**So that** project requirements are organized and easy for the team to understand  

### Details and Assumptions
* The repository will use GitHub Issues for project tracking
* The template will be stored in `.github/ISSUE_TEMPLATE/user-story.md`
* Team members will fill out the template when creating new user stories

### Acceptance Criteria

```gherkin
Given a developer creates a new issue in GitHub
When they select the User Story template
Then the issue should automatically populate with the predefined user story format
