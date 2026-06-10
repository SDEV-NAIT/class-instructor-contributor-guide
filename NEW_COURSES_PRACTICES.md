# Developing a new course.

## Reference course if you're just starting
If you'd like a template of the suggested structure please use:
    - [SDEV1001](https://github.com/SDEV-NAIT/SDEV1001) which is organized by module
    - Or [SDEV1150](https://github.com/SDEV-NAIT/SDEV1150) which is organized by weeks.

## What should a primary course contain
There are a couple of courses that use the "primary course" format for their repository.
Note: Materials that are better managed on Brightspace should be on Brightspace and not on GitHub, hopefully folks agree that this is a better way to update assignments/examples.
Below is a list of things that should be contained in the primary course repository.

The effort is to limit the number of places we need to access information while getting the benefits of using git to manage the course content.
- 1 Starter Kit for Each assignment, Lab and In Class
    - Do not make a copy, this is so that we can be consistent.
    - This is only for the assignments that use GitHub Classroom.
- 1 Primary Course Repository (with the following files and directories.)
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
        - Folder for "past/old assignments"
  - **admin/** (optional)
    - This should have the planning calendar attached or linked in some way shape or form.
    - Any other non-code content that we want to manage with GitHub.
    - *Note: Course Outlines should be managed in Brightspace or the learning management system.*
  - **1 folder for each topic/module taught in the course.**
    - README.md for the topic/module
      - This should contain lesson plans for each day taught
    - Folders for every example (start and end)
      - Preferably have a README for this.
      - Should be referenced in the topic/module README.md
    - Any notes needed or links to notes needed should be in here.
      - Should be referenced in the topic/module README.md
  - **README.md** for the course
    - Description for the course
    - **Table for Assignments**
      - Link to each assignment in the repo
      - Weighting
      - Due Date (can be a week)
    - **Link to the Topics/Modules**
      - Should link to the README.md in the folder.
      - Should be in the order of things taught
    - Notes that might be helpful for the course (optional)
      - How to set up the environment
      - How to set up the assignments
    - Website External to course (optional)
      - Link to an external website if you have one
    - Personal Resources from Instructors
      - Should have an instructor name
        - Under the instructor name just random links and notes that the instructor found useful.
