# HPC0: Introduction to Linux

HPC0 is our introductory course to the linux command line. It is a key prerequisite course prior to HPC1 and provides a gentle introduction for users to the unix shell. The initial set up steps often require several helpers to provide one-to-one support for users who struggle with the initial configuration of SSH clients.

## Learning objectives

- Understand the purpose of the Linux Shell
- Effectively manage Files and Directories at the command line
- Understand the structure of the linux filesystem
- Create files, directories and other objects
- Create Pipes and Filters to join together commands
- Understand how to find help from the command line
- Find files and directories from the command line
- Use command line tools to search for patterns in data, filter, remove and edit data

## Instructor todo

- [ ] - Familiarise yourself with course slides
- [ ] - Have existing access to ARC4 via MobaXTerm or a terminal
- [ ] - Send a reminder email at most 24h before the start of the session outlining [pre course prep](#Pre-course-prep)

## Pre-course prep

This course doesn't explicitly require pre course prep however it is encouraged to request participants do the following steps so that more can be covered in the workshop itself.

### Recommended setup steps

- Users register for HPC accounts using the [HPC account request form](https://leeds.service-now.com/it?id=sc_cat_item&sys_id=4c002dd70f235f00a82247ece1050ebc)
- Set up personal computer for connecting to HPC (HPC account required)
    - An overview can be found [here (including screenshots)](https://hackmd.io/xBKb6Az3QmewUsVF3ab2qg#Pre-workshop-prep)
    - For Windows, downloading MobaXTerm and configuring a session with ssh Gateway settings
    - For MacOS/Linux, creating a `~/.ssh/config` file with ProxyJump rule to `remote-access.leeds.ac.uk`

## Lesson resources

- **HPC0 slides** - [https://bit.ly/hpc0linux](https://arctraining.github.io/rc-slides/hpc0.html)
- **Exercises** - https://drive.google.com/file/d/1dV8fMS_n6GOFZO_rmFfUBwnuBFGj6C58/view?usp=sharing
- **Example hackpad** - https://hackmd.io/@sparrow0hawk/HyPvxsWUu/edit 
- **Bash commands crib sheet** - https://drive.google.com/file/d/0B4hIpRJzq8DPVG5xdEJWcGlRTkU/view?usp=sharing

## Delivery plan

| Time     | Session                          | No. of helpers  | Learner activities |
| -------- | ------------------------------- | ---------------  | -----------------  |
| 00:00     | Introduction and connecting to ARC | 4-5          | Welcome to the course <br> Introductions and arrangements <br> Connecting to ARC setup: <br> - A demo for windows users of downloading MobaXTerm and setting up a session. <br> - A demo from a terminal of setting up the ssh config file and `ssh user@arc4.leeds.ac.uk`. *Crucially highlighting the ARC prompt and MOTD as ways to confirm they have successfully logged in.* <br> <br> If time start on the slides |
| 00:50     | Break                           |                 |  |
| 01:00     | Navigating the shell            | 2               | Chalk and talk through the slides covering: <br> - what is the shell/bash <br> - Filesystem basics and forward/back slashes <br> Get to exercise 1 where we `git clone` workshop files and start to introduce commands for navigation like `cd`, `ls`, `mkdir`, `pwd`, `touch`, `nano`, `mv` <br> <br> Highlight extensible behaviour of commands using options e.g. `ls -l` and explain how to find help with `man <command>`  |
| 01:50     | Break                           |                 |  |
| 02:00     | Data transformation in the shell            | 2               | Review exercise 1 answers <br> Introduce commands `head`,`tail`,`cat`, `cut`, `sort`, pipes and redirects <br> <br> Give 5mins for exercises 2 and 3. Take suggestions and demonstrate them on shared screen <br> <br> If time show the command `wc` and explain approaches to exercise 4 |
| 02:50     | Wrap up & Questions             |                 | - Cover how to connect to the HPC in the future <br> - sign post HPC1 <br> - Encourage people to attempt further exercises |
| 03:00     | Close                           |                 |  |

## Example Agenda

Here is an example agenda that can be shared in a session hackpad.

| Time     | Agenda                          |
| -------- | ------------------------------- |
| 1300     | Introduction, connecting to ARC |
| 1350     | Break                           |
| 1400     | Navigating the shell            |
| 1450     | Break and Exercise 1            |
| 1500     | Data transformation in the shell|
| 1550     | Wrap up and questions           |
