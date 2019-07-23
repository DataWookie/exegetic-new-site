---
title: "Procedure – Project Management"
draft: true
documents: ['Procedure']
---

This procedure refers to how we project manage our work for clients, specifically how we work internally as a team to collaborate and achieve the desired outcomes. Refer to <a href="https://www.exegetic.biz/internal/procedure-clients/">Procedure - Clients</a> for onboarding and setting up a new client. 

## Internal structure

- Each project will have at least one person working on it, namely the Lead Data Scientist, and then possibly 1 or more Junior Data Scientists.
- The Lead Data Scientist is responsible for overall project management, including managing timelines, expectations and requirements and communication with the client.
- Where necessary, when Juniors email the clients directly, they must always cc the Lead in on any communication sent.

## Task management

- We use Asana to manage the tasks associated with projects.
- The project, or client, will have a board on Asana, with the following columns (this is a superset - some might be excluded):
    - **Ideas/parked** (for pieces of work or ideas that have been mentioned or requested, but are not on any timeframe)
    - **Backlog** (where the backlog of tasks is listed)
    - **Priority** (the next tasks that need to be picked up in the project)
    - **Current** (the tasks that individuals are currently working on)
    - **Awaiting** feedback (this is to take note of tasks that are awaiting feedback from external sources, ie. the client, and the work is therefore on hold until such feedback or clarification has been received)
    - **Review** (when a piece of work is under review, whether peer review or a pull request has been made. Furthermore, assign a *sub-task* to the person whose review your require.)
    - **Deployed/complete** (when a task has been completed and/or the work has been merged into the `master` branch and deployed to live)
- Generally, cards move from left to right from one column to the next, but can move back and forth.
- The Lead on the project is mostly respnsible for adding cards to the backlog and assigning team members to each task.
- The person working on the card must then take ownership of the task and manage the progress of the card from one state to the next on the Asana board.
- When requesting a *peer review* of the piece of work, create a sub-task and assign to the relevant person.  
- When requesting a *final review* of the work, create a sub-task and assign to the relevant person and create a merge request for the feature branch into `develop` on Gitlab.
- When you have requested a review from someone, and they are busy reviewing, and possibly making edits to the code, **do not** work on the branch and edit the code yourself in parallel. Wait for final feedback and for the reviewer to tell you they have finished and the task is either ready for deployment or needs further revisions based on feedback.

### Task details

Where necessary, include the following information on the Asana card for a task that supports the overall project:

- A brief description of the context or background motivating for why this work is needed. This is especially relevant if the Lead is giving tasks to Juniors and the context needs to be explicitly documented so that everyone has the necessary information.
- The requirements of what is needed for the piece of work.
- Links to any background documents or mockups.
- The name of the git branch where the work has been implemented. 
- A due date.

## Time management

- Individual tasks need a timeframe that supports the overall progress of the project or work for the client. 
- Set a best estimate for a deadline for the task on the Asana card.
- If the deadline is approaching and the work is still far from complete, the individuals involved must communicate (ie. Junior and Lead), explaining the reasons, identifying any issues and setting a new expected deadline. Do not let the deadline fly by and then only bring any issues to attention. 