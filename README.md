# How to contribute to Master Course Repositories

For us all to have a consistent environment teaching it would be fantastic to have some guidelines on how to contribute to master course repositories (for those that have them).

This is an attempt at creating consistency so we can dive into a new course and know exactly what we need and where to go.

*Please make a pull request to update this document if you have any suggestions or changes.*

## Current Courses using this format

- [DMIT2008 - Intermediate Frontend Dev](https://github.com/dmit-2008/master-course)
- [CPSC1520 - Intro to Frontend Dev](https://github.com/CPSC-1520/master-course/tree/master)
- [SDEV1001 - Programming Fundamentals](https://github.com/SDEV-NAIT/SDEV1001?tab=readme-ov-file)
- [SDEV1150 - Front End Development Fundamentals](https://github.com/SDEV-NAIT/SDEV1150)
- [SDEV2401 Rapid Backend Development](https://github.com/SDEV-NAIT/SDEV2401/tree/main)
- [SDEV1000 - Logic and Problem Solving](https://github.com/SDEV-NAIT/SDEV1000)

*Please add your repo here if you have one via pull request*

## Expectations

If you are teaching a course (with a master-course), you should be doing the following:
- creating and updating course content and examples
- fixing typos and errors
- adding notes that might have helped you and might help another instructor in the future.

Please clean up content and make it easier for the next instructors to teach the course.

## How to contribute

1. Clone the repository locally.
2. Add your changes to the repository and push them up:
  - Push the changes if they fall under  **Things that you can just push up to the Repository** (see below)
  - Create a pull request if the changes fall under **Things that require a pull request** (see below)
3. Notify your fellow instructors or update an issue named "Recent Changes in the Repository"

### Should I make a pull request or just push directly to the existing repository?

#### Things that you can just push up to the Repository.
- **Typos**, just push up the changes no notification needed, unless you are chatting with the other instructors.
- **Links**
  - If the need to be updated or if they're broken.
- **Examples and Notes**
  - just push them up and **make a reference to them in the lesson plan** in the README of the topic.
  - *Add a comment to an issue for "Recent Updates" to this course, if there isn't one please create it.* Note: There should only be one of these issues.
- Adding information to "Personal Resources"
  - *Add a comment to an issue for "Recent Updates" to this course, if there isn't one please create it.* Note: There should only be one of these issues.

#### Things that require a pull request.
- **Changing the Order of the Topics.**
  - Some type of rationale needs to be provided to be discussed in the pull request, needs more than one reviewer if multiple people are involved.
- **Changing the Weighting or the Due Dates of an assignment/lab/in-class/quiz.**
  - The rationale needs to be discussed (to be discussed in the pull request), needs more than one reviewer if multiple people are involved.
- **Creating a new assignment/lab/in-class/quiz**
  - The Assignment should be in Master course first in a pull request before you updated the starter-kit.
    - If you create in the starter kit first please make a pull request referencing it in the master course as well.
  - The old assignment can be moved to an "old_assignments" folder in the folder of that specific assignment.
  - In the "README.md" of the assignment there should be a link to the the assignment template that is being used (one per assignment.) *There should also be a reference to this in the master course readme as well.*
  - Add a comment to an issue for "Recent Updates" to this course, if there isn't one please create it. There should only be one of these issues.
  - **Ask for at least one Reviewer if multiple people are involved or teaching it in future semesters**
- **Updating the course Calendar**
  - many people depend on this so it should be discussed in a pull request.

#### What should be Pull Request Contain?
- A title describing what you're doing.
- A description that describes your rationale or discussions that have been given.
- Any issues that had discussions that would be relevant to the pull request.
- The actual work inside of the master-course repository and any supporting links that are needed.

## Syncing with Learning Management Systems
At the End of the School year:
- Sync all of the examples with brightspace, moodle, or what ever learning management system that we are using with the primary master.
- Ensure that it's up to date with the course outline.

## What should a master-course should it contain
There are a couple of courses that use the "master course" format for their repository.
Note: Materials that are better managed on brightspace should be on brightspace and not on the github, hopefully folks agree that this is a better way to update assignments/examples.
Below is a list of things that should be contained in the master course repository.

The effort is to limit the number of places we need to access information while getting the benefits of using git to manage the course content.
- 1 Starter Kit for Each assignment, Lab and In Class
    - Do not make a copy, this is so that we can be consistent.
    - this is only for the assignments that use github classroom.
- 1 Master Course Repository (with the following files and directories.)
  - **assignments/**
    - 1 folder for each assignment
      - a README.md that links to the starter kit.
      - the folder for the assignment starter
      - the folder for assignment solutions
  - **labs/in-class-assessments/quiz** (use only the folders that are applicable.)
    - 1 folder for each
      - README.md
        - Link to the starter kit.
        - Folder for the current assignment start
        - Folder for the solution of the current assignment
        - folder for "past/old assignments"
  - **admin/** (optional)
    - this should have the planning calendar attached or linked in some way shape or form.
    - any other non code that we want to manage iwth github.
    - *Note: Course Outlines should be managed in brightspace or the learning management system.*
  - **1 folder for each topic taught in the course.**
    - README.md for the
      - this should contain lesson plans for each day taught
    - Folders for every example (start and end)
      - preferrably have a readme for this.
      - SHould be referenced in the topic README.md
    - Any notes needed or links to notes needed should be in here.
      - SHould be referenced in the topic README.md
  - **README.md** for the course
    - Description for the course
    - **Table for Assignments**
      - Link to each assignment in the repo
      - Weighting
      - Due Date (can be a week)
    - **Link to the Topics**
      - should link to the README.md in the folder.
      - SHould be in the order of things taught
    - Notes that might helpful for the course (optional)
      - How to set up the environment
      - How to set up the assignments
    - Website External to course (optional)
      - Link external website if you
    - Personal Resources from Instructors
      - Should have an instructor name
        - Under the instructor name just random links and notes that the instructor found useful.

