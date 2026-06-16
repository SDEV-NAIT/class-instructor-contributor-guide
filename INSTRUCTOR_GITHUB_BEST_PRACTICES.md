# Instructor GitHub Best Practices

## You reading this, should be able to use github at a basic level
- cloning repositories, branching, pushing code, tracking issues, creating pull requests, reviewing pull requests, merging. If you are unable then should take some a day or two to get up to speed.
- If you need training or help please ask a fellow instructor, if you don't know who to ask please ask the program chair for a suggestion.
- This is mainly focused on instructors who are teaching courses that are somewhat programming focused that use github for their course content.
- Where can I learn this?
  - [GitHub Learning Lab](https://lab.github.com/)
  - [SDEV1001 - Version Control Module](https://github.com/SDEV-NAIT/SDEV1001/tree/main/Module-2/version-control)
  - [W3 Schools](https://www.w3schools.com/git/git_intro.asp)

- Please refer to [How to contribute](#how-to-contribute) for more information on how to contribute to the course repositories.

## Expectations for instructors using a course that uses a primary repoitory on github.

If you are teaching a course (with a GitHub primary-course), you should be doing the following:
- creating and updating course content and examples
- fixing typos and errors
- adding notes that might have helped you and might help another instructor in the future.

Please clean up content and make it easier for the next instructors to teach the course.

## Commit at a Regular Pace.

- Make small incremental commits at a regular interval (multiple per day if possible). Until you're done.
- This allows for other instructors to see what you're working on.
- Please refer to the [Should I make a pull request or just push directly to the existing repository?](#should-i-make-a-pull-request-or-just-push-directly-to-the-existing-repository) section for more information on when to make a pull request and when to just push up changes.

## During the term instructors should be doing all their daily examples in a workbook repository that is accessible to the students, and encouraging students to do the same.
- Course leads should guide you on how to set this up for your sections of the course.

## You are expected to contribute, even if you're not a course lead.

If you are teaching a course (with a GitHub primary-course), you should be doing the following:
- creating and updating course content and examples
- fixing typos and errors
- adding notes that might have helped you and might help another instructor in the future.

Please clean up content and make it easier for the next instructors to teach the course.

## Pull requests are expected to be reviewed by others in a timely fashion (1 or 2 days)

- If you make a pull request, please ask for a review from at least one other instructor, if multiple people are involved or teaching it in future semesters.
- Please send this pull request to another instructor for review quickly after creating it (within the day.)

## Issues, Problems and Discrepancies in the course should have a github issue created.
- If you find an issue with the course content or anything related to the course please create a github issue in the primary course repository with a clear description of the issue (and how to reproduce it if possible if applicable).
  - To create a new Github Issue go to the top tab under github, click "Issues" then click "New Issue" and fill out the template.
- Please notify your fellow instructor that an issue has been created.

## Prototypes, Learning Projects, Experiments are Recommended to be added to the primary course repository. Please Clearly state if a project is a prototype, learning project, or experiment.
- Suggestions:
  - put this in a experiments folder
  - put it in a seperate branch (naming should include `experiment_` or `prototype_` as a prefix to the branch name)

## Course Content should be managed in Github as the primary source of truth and should be updated in brightspace as a reflection of the content in github.
- This does not mean Brightspace instances should be empty, but their should at least be a duplicate of everything on Github as well
  - If your course isn't using github yet, first focus on the examples that are using code, then move on to the rest of the content.
- Should be organized in a way that makes sense to the instructors reading the repository.
  - If you'd like a template of the suggested structure please use:
    - [SDEV1001](https://github.com/SDEV-NAIT/SDEV1001) which is organized by module
    - Or [SDEV1150](https://github.com/SDEV-NAIT/SDEV1150) which is organized by weeks.

**IMPORTANT NOTE** Follow [new course best practices](NEW_COURSES_PRACTICES.md) for more details on this.

## Instructors should avoid doing anything in the danger zone in the github settings tab.
- This includes deleting repos, organizations, changing visibility and anything in that section.
- This is unless you know exactly what your are doing and have confirmed it with one of the NAIT enterprise owners (Either Dan, Laurel, Nathan, Steve, and Tom)
- You shouldn't be doing this, if you're considering doing this ask the folks above for help and guidance.

# Intercession Clean up Duties

## Course Leaders are expected to identify the example/slides/notes/etc. that other intructors are recommended to use for the upcoming semester.
- This could be in module readme for example, with clear links to which examples/slides/notes/etc. that are recommended to be used for the upcoming semester.

## Course Leaders are expected to clean up the content and make it easier for the next instructors to teach the course.
This includes fixing the following:
- Example instructions that aren't clear.
- Outdated examples.
- Typos and errors.
- Notes that might have helped you and might help another instructor in the future.
- Slides that are incomplete or broken in someway.

## Course leads should be addressing issues during intercession and cleaning/closing issues that are no longer relevant.

## Course leads should provide a clear way to set up a work book for a section for this course.
- For you a course leader reading this you can use [Copying starter examples and slides tool](https://github.com/SDEV-NAIT/nait-slide-builder#copying-starter-examples-and-slides-for-new-classes-used-at-the-start-of-the-semester) to create a repo that other instructors can fork.

## Course Leaders are expected to Sync their course with Learning Management Systems (Brightspace for now)
At the end of the school year:
- Sync all of the examples with Brightspace, Moodle, or whatever learning management system that we are using with the primary repository.
- Ensure that it's up to date with the course outline.

# Reference

## How to contribute

1. Clone the repository locally.
2. Add your changes to the repository and push them up:
  - Push the changes if they fall under **Things that you can just push up to the Repository** (see below)
  - Create a pull request if the changes fall under **Things that require a pull request** (see below)
3. Notify your fellow instructors or update an issue named "Recent Changes in the Repository"

## Should I make a pull request or just push directly to the existing repository?

**IMPORTANT NOTE**: If you're developing the course only course leads should be able to make major changes to the main branch, any other instructor who wish to make qualitative changes should create a new branch, a pull request, and have the course lead review before merging.

If you're unsure about this please ask your course lead or one of the enterprise owners (Either Dan, Laurel, Nathan, Steve, and Tom) for guidance.

#### Things that you can just push up to the Repository.
- **Typos**, just push up the changes no notification needed, unless you are chatting with the other instructors.
  - such as spelling errors, grammatical errors, or duplicated lines
- **Links**
  - If they need to be updated or if they're broken.
- **Examples and Notes**
  - just push them up and **make a reference to them in the lesson plan** in the README of the topic/module.
  - *Add a comment to an issue for "Recent Updates" to this course, if there isn't one please create it.* Note: There should only be one of these issues.
- Adding information to "Personal Resources"
  - *Add a comment to a new or existing Github Issue for "Recent Updates" to this course, if there isn't one please create it.* Note: There should only be one of these issues.

#### Things that require a pull request.
- **Changing the Order of the Topics/Modules.**
  - A justification needs to be provided to be discussed in the pull request, needs more than one reviewer if multiple people are involved.
- **Changing the Weighting or the Due Dates of an assignment/lab/in-class/quiz.**
  - The rationale needs to be discussed (to be discussed in the pull request), and needs more than one reviewer if multiple people are involved.
- **Creating a new assignment/lab/in-class/quiz**
  - The Assignment should be in the primary course first in a pull request before you update the starter kit (the student template repository).
    - If you create it in the starter kit first please make a pull request referencing it in the primary course as well.
  - The old assignment can be moved to an "old_assignments" folder in the folder of that specific assignment.
  - In the "README.md" of the assignment there should be a link to the assignment template that is being used (one per assignment.) *There should also be a reference to this in the primary course README as well.*
  - Add a comment to an issue for "Recent Updates" to this course, if there isn't one please create it. There should only be one of these issues.
  - **Ask for at least one reviewer if multiple people are involved or teaching it in future semesters**
- **Updating the course Calendar**
  - many people depend on this so it should be discussed in a pull request.

#### What should a Pull Request Contain?
- A title describing what you're doing.
- A description that describes your rationale or discussions that have been had.
- Any issues that had discussions that would be relevant to the pull request.
- The work inside of the primary-course repository and any supporting links that are needed.


