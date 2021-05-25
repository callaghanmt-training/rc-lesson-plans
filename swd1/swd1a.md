# SWD1a: Introduction to Python Programming

HPC1 is our introductory course to high performance computing (HPC) at Leeds. It covers the concepts of what HPC is and what distinguishes it from more traditional computational research as well as introduces users to the HPC systems used at Leeds. The workshop has a strong practical element, aiming to familiarise users with SGE scheduler commands and the principles of submitting batch jobs and simple job troubleshooting.

This course is delivered over Microsoft Teams as four 3h workshops over four weeks. Previously, the course has been delivered as an all-day workshop in person.

## Learning objectives

- Understand how HPC can be used to support their research
- Use different models of parallel computing
- Be able to use Linux effectively : SSH, directory management, command line etc
- Manage data on the HPC clusters
- Use the HPC batch system effectively
- Use the module system to load and manage pre-installed applications
- Write scripts to run codes and applications
- Examine how well code scales and apply techniques to benchmark code

## Instructor todo

- [ ] - Familiarise yourself with course slides
- [ ] - Have existing access to ARC4 via MobaXTerm or a terminal
- [ ] - Send a reminder email at most 24h before the start of the session outlining [pre course prep](#Pre-course-prep)

## Pre-course prep

This course **does** require pre course prep as we expect users to have HPC accounts and to have a means of SSH-ing to ARC4 already configured prior to the start of the course.

### Recommended setup steps

In May 2021 this course was run using [Google Colaboratory](colab.research.google.com/), so all users require a google account to access that platform.

Otherwise instructions will need to be provided to users around installing a basic python setup. We would recommend by default using Anaconda or Miniconda by following the available videos on [our website](https://arc.leeds.ac.uk/help/videos/).

## Lesson resources

- **Workshop Slides** - https://arctraining.github.io/python-2021-04/
- **Github repository** - https://github.com/ARCTraining/python-2021-04
- **Research Computing website** - https://arc.leeds.ac.uk/
- **Example Hackpad** - https://hackmd.io/@sparrow0hawk/BylIv-1vu

## Delivery plan

### Session 1

| Time     | Session                          | No. of helpers  | Learner activities |
| -------- | ------------------------------- | ---------------  | -----------------  |
| 00:00     | Introduction, connecting to ARC and what and why HPC? | 2 (more if help required with connecting)          | Welcome to the course <br> Introductions and arrangements <br> Connecting to ARC (do a quick poll to confirm if extensive instruction is required) <br> Ask users to complete Hackpad section explaining why they think they want to use HPC <br> <br> Start on the slides, talk through users reasons in Hackpad, introduce concepts of high throughout v high performance, define cores, memory, nodes |
| 00:50     | Break                           |                 |  |
| 01:00     | Login, HOME directory and looking around Exercise 1            | 2               | Cover slides up to slide 30. <br> Demonstrate `$HOME` directory, brief recap of basic linux commands, explain what the prompt is, work through with the class the exercises  |
| 01:50     | Break and answer             |                 |  |
| 02:00     | Simple job submission, qstat, qdel            | 2               | - Have everyone clone the `hpc1-files` repository <br> - navigate to the `hpc1-files/1_R/` directory and walk through the basic job submission scripts <br> have everyone submit a job and highlight `qsub`, `qstat`, `qacct` <br> - show scheduler outputs of `.e/.o` files |
| 02:50     | Wrap up & Questions             |                 | - Remind about next week <br> - attempt to write own job script for `hpc1-files/2_Python/example1.py` <br> - Encourage people to attempt their own job submission |
| 03:00     | Close                           |                 |  |

### Session 2

| Time     | Session                          | No. of helpers  | Learner activities |
| -------- | ------------------------------- | ---------------  | -----------------  |
| 00:00     | Welcome back, Data Transfer and Module system | 2 (more if help required with connecting)          | Welcome back <br> Check if anyone managed to run the `example1.py` job <br> <br> Highlight data transfer on MobaXTerm using drag/drop, signpost `rsync` and `scp` commands for terminal and highlight `rclone` for OneDrive integration <br> <br> Describe module system with basic commands `module add|rm|info|switch|avail|list`  |
| 00:50     | Break                           |                 |  |
| 01:00     | Interactive sessions, requesting multiple cores, specialist node types  | 2               | Explain concept of requesting interactive sessions with `qrsh`, highlight that it is usually impractical to do serious work this way <br> <br> Use files in `hpc1-files/3_Parallel_Executables` to showcase requesting multiple cores using both `smp` and `ib`. Highlight that code must be written to take advantage of multiple cores <br> <br> Also explain alternate node types such as GPGPU and high memory nodes and how they can be requested in a job script  |
| 01:50     | Break    |                 |  |
| 02:00     | Mop up and user-guided section | 2               | - Cover any sections not fully addressed <br> - open this section up for any specific questions users have (typically how do I know how much memory/time to request) |
| 02:50     | Wrap up & Questions             |                 | - Sign post `arcdocs` <br> - explain about getting in touch |
| 03:00     | Close                           |                 |  |                         |                 |  |

## Example Agenda

Here is an example agenda that can be shared in a session hackpad.

## Agenda Day 1


| Time     | Agenda                                     |
| -------- | ------------------------------------------ |
| 0900     | Intro, using Google Colab, What is Python? |
| 0950     | Break                                      |
| 1000     | Python basics, Handling data               |
| 1050     | Break                           |
| 1100     | Python packages and Pandas                 |
| 1150     | Questions                                  |
| 1200     | Close                                      |



## Agenda Day 2


| Time     | Agenda                                          |
| -------- | ----------------------------------------------- |
| 0900     | Mount google drive onto colab, using pandas     |
| 0950     | Break                                           |
| 1000     | Indexing and subsetting, Data types and formats |
| 1050     | Break                                           |
| 1100     | Combining dataframes                            |
| 1150     | Questions                                       |
| 1200     | Close                                           |



## Agenda Day 3

| Time     | Agenda                                          |
| -------- | ----------------------------------------------- |
| 0900     | Indexing and subsetting, Data types and formats |
| 0950     | Break                                           |
| 1000     | Merging dataframes                              |
| 1050     | Break                                           |
| 1100     | Loops and functions                             |
| 1150     | Questions                                       |
| 1200     | Close                                           |




## Agenda Day 4

| Time     | Agenda                                          |
| -------- | ----------------------------------------------- |
| 0900     | Finishing off merging, loops and functions      |
| 0950     | Break                                           |
| 1000     | loops and functions cont., plotting with plotnine|
| 1050     | Break                                           |
| 1100     | Bringing it all together                        |
| 1150     | Questions                                       |
| 1200     | Close                                           |
