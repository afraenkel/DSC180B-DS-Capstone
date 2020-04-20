# Project Checkpoints

## Introduction (relevant to all checkpoints)

-   Each project checkpoint is taken from the proposal
    schedule. Students can create their own rubric on which to be
    graded, or choose the default (e.g. data ingestion; EDA)

-   Each project checkpoint needs individual level tasks alongside
    group-wide ones (so not all grading is group-level).

-   After each project checkpoint, the proposal/schedule can be
    revised based on current progress.
    
### What is turned in?

-   A pdf **report** is turned into canvas. It should be modeled after
    the result replication reports from DSC 180A and consist of pieces
    of your final report.
    -   The report should have a beginning page with your group name,
        the members of the group, the list of tasks the checkpoint
        attempts to cover, and the group members that worked on each
        task.
    -   Appended to the end of the report, include a paragraph
        decsribing any necessary revisions to your project proposal.
    -   Appended to the end of the report, include an updated backlog
        of tasks and schedule through the next project checkpoint.

-   An updated **code repository** reflecting the work informing your
    report.
    
## Project Checkpoint #1

**Default Task for the project checkpoint #1**: The first project
checkpoint will likely mimic project checkpoint #1 in 180A:

**Part 1**:

-   Write a survey of the data you are using, the relationship and
    appropriateness of the data to the problem under examination, and
    the context in which the data was created.
-   Summarize relevant details of the data generating process,
    describing the population that the data represents, whether that
    population is relevant to the question at hand, while addressing
    possible questions of data reliability.
    
**Part 2**:

-   Describe relevant details of the data ingestion process that may
    affect the validity/applicability of the results -- i.e. describe
    decision choices from the standpoint of how those choices affect
    the conclusions you can draw from the data.
-   Address any data privacy concerns and how your data pipeline
    handles them.
-   Lay out the schema and justify the decisions (what's the unit
    corresponding to an observation?). Only describe the most relevant
    attributes for your problem.
    
**Note**: you will write the 'introduction' to your project later in
the quarter.

**Note:** this is just a guide for the checkpoint. It may be more
appropriate to only address a portion of these question (if the data
collection portion of your project is longer than most) or go beyond
these questions (including EDA, if your data and problem remains
unchanged from last quarter).

## Project Checkpoint #2

**Default Task for the project checkpoint #2**: The second project
checkpoint will likely mimic project checkpoint #2 in 180A.

1. Overall, your checkpoint report should statistically assess the
   quality of the data, justify the data-cleaning logic, and
   explain/analyze the features/statistics/targets needed needed for
   your project. **This portion should make it clear that your data is
   capable of approaching the main question of your project.** In
   particular, your EDA should serve as a sort of baseline that allows
   you to assess and contextualize your eventual project
   results. *Remember to structure your report as laid out above in
   the 'What is turned in?' section.
   
2. Your code should follow the standards from last quarter. In
   particular, while notebooks may contain large portions of your EDA,
   you should take care to:
   * Create helper functions in library code for reuse in notebooks.
   * Be sure that notebooks never take long to run (if they do, that
     processing code should be a part of your pipeline and output
     smaller, intermediate data that is quick to read).
   * Create *small* test data that you version with your code (your
     repo should not be more than << 10MB without notebooks). Include
     the target `test` in your run.py so that if you clone your
     project repo, run `python run.py test`, then run the notebooks,
     everything appears as it should (the *content* of the
     graphs/figures will be nonsense, because it's run on test data,
     but it still *runs*).
   * Include an `env.json` in your `config` directory that includes a
     key `"repository"` and with value the url of your repository
     (e.g. `https://github.com/afraenkel/DSC180B-DS-Capstone`).
   * In checkpoint 3, you'll have to include a Docker image, so start
     working on that now!
     
**Note:** As before, you may choose to increase or reduce the scope of
this checkpoint depending on your project (e.g. if you still have data
ingestion being worked on). However, the work should remain reasonably
consistent with the default task; if you have concerns, ask your
domain expert.


## Project Checkpoint #3

[[TO BE COMPLETED]]


