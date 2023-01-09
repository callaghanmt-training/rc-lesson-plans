# HPC2: Installing and Managing Applications on the HPC

The purpose of the workshop is to introduce the application development environment available on the HPC service and give hands on practice managing, installing and compiling codes on the HPC service. This workshop will be most useful for researchers who need to manage and install their own applications and research codes.

## Learning objectives

* Understand what an executable is
* Understand the how filesystem configuration and environment variables relate to software
* Develop hands on experience with:
    * Building software using GNU Autotools
    * Using conda package manager
    * Building software using cmake
    * Interacting and using Singularity/Apptainer containers

    * Using Spack package manager

 

## Instructor todo

- [ ] - Familiarise yourself with course website
- [ ] - Have existing access to ARC4 via MobaXTerm or a terminal
- [ ] - Send a reminder email at most 24h before the start of the session outlining [pre course prep](#Pre-course-prep)

## Pre-requisites 

- Completed HPC0 or confident with Linux command line
- Experience of using the HPC (submitting jobs)

## Pre-course prep

This course requires users to have ARC4 accounts and to be familiar with how to log on and connect to HPC systems.

### Required setup steps

- Users register for HPC accounts using the [HPC account request form](https://leeds.service-now.com/it?id=sc_cat_item&sys_id=4c002dd70f235f00a82247ece1050ebc)
- Set up personal computer for connecting to HPC (HPC account required)
    - An overview can be found [here (including screenshots)](https://hackmd.io/xBKb6Az3QmewUsVF3ab2qg#Pre-workshop-prep)
    - For Windows, downloading MobaXTerm and configuring a session with ssh Gateway settings
    - For MacOS/Linux, creating a `~/.ssh/config` file with ProxyJump rule to `remote-access.leeds.ac.uk`

**You are expected to have experience of connecting to ARC4 before this tutorial, as no time will be made available for walking through connecting to HPC**

## Lesson resources

- **HPC2 Course website** - https://arctraining.github.io/hpc2-software/welcome.html

## Delivery plan

### Part 1

| Time      | Session                          | No. of helpers  | Learner activities |
| --------- | -------------------------------- | --------------- | -----------------  |
| 00:00     | Theory                           | 2               | This session will cover background information and concepts that the further sessions will build upon. The main topics to cover are:<br>- Files<br>- Software<br>- Build Tools<br>- Package Managers<br>- Platforms|
| 01:00     | Break                            |                 |                    |
| 01:10     | Conda                            | 2               | This session will introduce the Conda package manager <br> - It will distinguish between building code and installing pre-made code via Conda <br> - Highlight the `anaconda` module on HPC <br> - Explain the concept of Conda environments <br> - demonstrate creating environments, installing packages, removing packages, searching for packages, export environments  |
| 01:50     | Break                            |                 |                    |
| 02:00     | Autotools/CMake                  | 2               | This session will introduce build tools such as GNU Autotools and CMake <br> - Demonstrate building software with both tools <br> - Highlight how this can be done without administrative privileges <br> - Highlight using software documentation to guide build steps |
| 02:50     | Wrap up & Questions             |                 |                     |
| 03:00     | Close                           |                 |                     |


### Homework

Try and install something you need on HPC. Use the chat to get back in touch with the group and the team. Support available 2 weeks post last session.


### Part 2

| Time     | Session                          | No. of helpers   | Learner activities |
| -------- | -------------------------------- | ---------------  | -----------------  |
| 00:00     | Welcome back and homework       | 2                | Welcome back, walk through agenda for part 2. Invite people to outline how they got on with homework |
| 00:30     | Containers                      |                  |                    |
| 00:50     | Break                           |                  |                    |
| 01:00     | Containers (cont.)/Spack        | 2                |                    |
| 01:50     | Break                           |                  |                    |
| 02:00     | Spack                           | 2                |                    |                    
| 02:50     | Wrap up & Questions             |                  |                    |
| 03:00     | Close                           |                  |                    |


## Example Agenda

Here is an example agenda that can be shared in a session hackpad.

### Part 1

| Time     | Agenda                          |
| -------- | ------------------------------- |
| 0900     | Introduction, Theory            |
| 1000     | Break                           |
| 1010     | Conda                           |
| 1050     | Break                           |
| 1100     | Autotools/CMake                 |
| 1150     | Wrap up and questions           |
| 1200     | End                             |

### Part 2


| Time     | Agenda                          |
| -------- | ------------------------------- |
| 0900     | Welcome back and homework       |
| 0930     | Containers                      |
| 0950     | Break                           |
| 1000     | Containers (cont.)              |
| 1050     | Break and                       |
| 1100     | Spack                           |
| 1150     | Wrap up and questions           |
| 1200     | End                             |
