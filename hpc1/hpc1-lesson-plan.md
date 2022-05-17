# HPC1: Introduction to HPC at Leeds

HPC1 is our introductory course to high performance computing (HPC) at Leeds. It covers the concepts of what HPC is and what distinguishes it from more traditional computational research as well as introduces users to the HPC systems used at Leeds. The workshop has a strong practical element, aiming to familiarise users with SGE scheduler commands and the principles of submitting batch jobs and simple job troubleshooting.

This course is delivered over Microsoft Teams as two 3h workshops over two weeks. Previously, the course has been delivered as an all-day workshop in person.

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

- Users register for HPC accounts using the [HPC account request form](https://leeds.service-now.com/it?id=sc_cat_item&sys_id=4c002dd70f235f00a82247ece1050ebc)
- Set up personal computer for connecting to HPC (HPC account required)
    - An overview can be found [here (including screenshots)](https://hackmd.io/xBKb6Az3QmewUsVF3ab2qg#Pre-workshop-prep)
    - For Windows, downloading MobaXTerm and configuring a session with ssh Gateway settings
    - For MacOS/Linux, creating a `~/.ssh/config` file with ProxyJump rule to `remote-access.leeds.ac.uk`

## Lesson resources

- **Presentation for HPC1** - https://bit.ly/hpc1intro
- **HPC1 exercises** - https://docs.google.com/document/d/1SPaZ2kmzYpMFIkiMSi-Qnu-ZqLaW4reSpVal3aOrmmk/edit
- **Github repository** - https://github.com/arctraining/hpc1-files
- **Documentation page on file transfer** -https://arcdocs.leeds.ac.uk/getting_started/file_transfer.html
- **Example Hackpad** - https://hackmd.io/@sparrow0hawk/HkMWqp9Id

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
| 00:00     | Welcome back, Data Transfer and Module system | 2 (more if help required with connecting)          | Welcome back <br> Check if anyone managed to run the `example1.py` job <br> <br> Highlight data transfer on MobaXTerm using drag/drop, signpost `rsync` and `scp` commands for terminal and highlight `rclone` for OneDrive integration <br> <br> Describe module system with basic commands `module add\|rm\|info\|switch\|avail\|list`  |
| 00:50     | Break                           |                 |  |
| 01:00     | Interactive sessions, requesting multiple cores, specialist node types  | 2               | Explain concept of requesting interactive sessions with `qrsh`, highlight that it is usually impractical to do serious work this way <br> <br> Use files in `hpc1-files/3_Parallel_Executables` to showcase requesting multiple cores using both `smp` and `ib`. Highlight that code must be written to take advantage of multiple cores <br> <br> Also explain alternate node types such as GPGPU and high memory nodes and how they can be requested in a job script  |
| 01:50     | Break    |                 |  |
| 02:00     | Mop up and user-guided section | 2               | - Cover any sections not fully addressed <br> - open this section up for any specific questions users have (typically how do I know how much memory/time to request) |
| 02:50     | Wrap up & Questions             |                 | - Sign post `arcdocs` <br> - explain about getting in touch |
| 03:00     | Close                           |                 |  |                         |                 |  |

## Example Agenda

Here is an example agenda that can be shared in a session hackpad.

### Agenda Day 1

| Time     | Agenda                                     |
| -------- | ------------------------------------------ |
| 0900     | Intro, connecting to ARC, what and why HPC?|
| 0950     | Break                                      |
| 1000     | Login, HOME directory and looking around <br> Exercise 1  |
| 1050     | Break and Answers                          |
| 1100     | Simple job submission, qstat, qdel         |
| 1150     | Questions                   |
| 1200     | Close                                      |

### Agenda Day 2

| Time     | Agenda                                     |
| -------- | ------------------------------------------ |
| 1300     | Intro, Data Transfer, Modules              |
| 1350     | Questions and break                        |
| 1400     | Interactive sessions, ib v smp, node types |
| 1450     | Questions and break                        |
| 1500     | User guided section, talking through <br> your hopes/fears for HPC |
| 1550     | Wrap up and questions                      |
| 1600     | Close                                      |
