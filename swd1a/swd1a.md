# SWD1a: Introduction to Python Programming

SWD1a is our introductory course to programming in Python for people with little or no previous programming experience. It uses plotting and visualising data as its motivating example based on an established research dataset. The course is suitable for attendees from all research domains and we will use a Web based programming environment (a Jupyter Notebook) which means you will be able to apply the ideas you learn on the course straightaway without having to install any software at home or at work.

This course is delivered over Microsoft Teams as four 3h workshops over four weeks. Previously, the course has been delivered as an all-day workshop in person.

## Learning objectives

- How to run Python programs
- Storing data in computer programs (using variables and data types)
- Using built in functions in programs
- Avoiding and fixing errors in programs
- Using software other people have written (libraries)
- Reading tabular data and simple statistical analysis
- Plotting data
- Storing multiple values using lists
- Repeating things using loops
- Creating functions
- Making programs do different things for different data (Conditionals: IF statements)
- Writing simple tests: making sure our programs behave properly
- Programming style

## Instructor todo

- [ ] - Familiarise yourself with course slides
- [ ] - [Own a Google account](https://colab.research.google.com/) and have previously accessed [Google Colaboratory](https://colab.research.google.com/)
- [ ] - Send a reminder email at most 24h before the start of the session outlining [pre course prep](#Pre-course-prep)

## Pre-course prep

This course **does** require pre course prep as we expect users to have either a Google account for accessing Google Colaboratory or an installed instance of Jupyter notebook/lab.

### Recommended setup steps

In May 2021 this course was run using [Google Colaboratory](colab.research.google.com/), so all users require a google account to access that platform.

Otherwise instructions will need to be provided to users around installing a basic python setup. We would recommend by default using Anaconda or Miniconda by following the available videos on [our website](https://arc.leeds.ac.uk/help/videos/).

## Lesson resources

- **Workshop Slides** - https://arctraining.github.io/python-2021-04/
- **Github repository** - https://github.com/ARCTraining/python-2021-04
- **Research Computing website** - https://arc.leeds.ac.uk/
- **Example Hackpad** - https://hackmd.io/@sparrow0hawk/swd1a-intro-python
- **Tutorial datasete** - https://arctraining.github.io/python-2021-04/data/portal-teachingdb-master.zip

## Delivery plan

### Session 1

| Time     | Session                          | No. of helpers  | Learner activities |
| -------- | ------------------------------- | ---------------  | -----------------  |
| 00:00     | Introduction, setup environment and what is Python? | 2           |- Welcome to the course <br> - Introductions and arrangements <br> - Setting up python environment, a walk through of installing miniconda or connecting to Colab <br> - Ask users to complete Hackpad section explaining why they want to use Python <br> <br> - `print("hello world")` in notebook <br> - `helloworld.py` file and execution  |
| 00:50     | Break                           |                 |  |
| 01:00     | Variables and types, mathmatical functions, logic            | 2               | Working through examples of: <br> - assigning variables <br>- mathmatical functions <br> - types `int`,`float`,`str`,`bool` <br> - type conversion and errors `"2" + 2` <br> - builtin functions i.e. `type`, `print` <br> - logical comparisons|
| 01:50     | Break and answer             |                 |  |
| 02:00     | Data structures, user functions  | 2               | Work through: <br> - tuples <br> - lists (`.append(x)`,`[]`,`list()`) <br> - dictionaries (`{}`,`.keys()`,`.values()`,`.items()`) <br> - indexing <br> - `def` keyword <br> |
| 02:50     | Wrap up & Questions             |                 | - Remind about next week <br> - encourage people to use colab in their spare time and experiment |
| 03:00     | Close                           |                 |  |
### Session 2

| Time     | Session                          | No. of helpers  | Learner activities |
| -------- | ------------------------------- | ---------------  | -----------------  |
| 00:00     | Mount google drive onto colab, importing packages, pandas | 2 (more if help required with connecting)          | - Mounting google drive storage <br> - Using shell commands in notebooks (`! ls`) <br> - download exercise dataset <br> - introduce concept of python libraries, `import pandas` (have to be installed imported) |
| 00:50     | Break                           |                 |  |
| 01:00     | Introducing `pd.DataFrame` | 2               | Introduce pandas DataFrame structure as a highly functional representation of tabular data. Can read in data in a number of formats e.g. csv `pd.read_csv` function <br> <br> Introduce common pandas API methods `.dtypes()`, `.columns`, `.shape`,`.tail()`,`.head()`, indexing functions `.loc[]`, `.iloc[]` <br> <br> Using logical comparisons to create subsets of dataframes <br> <br> Using basic statistical functions such as `.count()`,`.nunique()`,`.mean()` |
| 01:50     | Break    |                 |  |
| 02:00     | Combining dataframes | 2               | Introduce ideas around combining dataframes, importance of matching indexes, differing join concepts <br> `.concat` <br> <br> Also introduce writing out data from a pandas Dataframe `.to_csv`|
| 02:50     | Wrap up & Questions             |                 | - Sign post pandas documentation <br> - explain about getting in touch |
| 03:00     | Close                           |                 |  |                         |                 |  |

### Session 3

| Time     | Session                          | No. of helpers  | Learner activities |
| -------- | ------------------------------- | ---------------  | -----------------  |
| 00:00     | Combining dataframes (cont.) and builtin in plot    |2  | Pick up from previous week, introduce ideas around grouping and `.groupby` function <br> <br> Also introduce the minimal plotting API within pandas `.plot()`. Explain this uses another package `matplotlib` and in this forms allows for quick visualisation |
| 00:50     | Break                           |                 |  |
| 01:00     | For loops and automating processes | 2               | Introduce concept of looping, repeating code task given an iterable. `for x in collection` and `while condition is true` <br> <br> Highlight how this allows us to repeat common code processes, e.g. performing common operation across many files |
| 01:50     | Break    |                 |  |
| 02:00     | User defined functions  | 2               | More in depth introduction to user defined functions. Cover `def` keyword, input arguments, indented block, docstrings, `return` statement |
| 02:50     | Wrap up & Questions             |                 |  |
| 03:00     | Close                           |                 |  |                         |                 |  |

### Session 4    

| Time     | Session                          | No. of helpers  | Learner activities |
| -------- | ------------------------------- | ---------------  | -----------------  |
| 00:00     | Finishing off merging, loops and functions         | 2  | Use this time to refresh ideas around merging, loops and functions or finish any material not covered previously
| 00:50     | Break                           |                 |  |
| 01:00     | Plotting with plotnine  | 2               | Introduce the plotnine library as an alternative plotting library modelled on R library ggplot2 <br> <br> Showcase concepts around data, geometry and aesthetics, use [carpentries ggplot2 lesson as template](https://swcarpentry.github.io/r-novice-gapminder/08-plot-ggplot2/index.html). |
| 01:50     | Break    |                 |  |
| 02:00     | Bringing it all together  | 2               | Wrap up any unfinished material and open us sessions to general questions and questions around transitioning knowledge to work area. <br> <br> Reflecting back on why attendees said they hoped to get out the course will help prompt this. |
| 02:50     | Wrap up          |                 |  |
| 03:00     | Close                           |                 |  |                         |                 |  |


## Example Agenda

Here is an example agenda that can be shared in a session hackpad.

## Agenda Day 1


| Time     | Agenda                                     |
| -------- | ------------------------------------------ |
| 0900     | Introduction, setup environment and what is Python? |
| 0950     | Break                                      |
| 1000     | Variables and types, mathmatical functions, logic               |
| 1050     | Break                           |
| 1100     | Data structures, user functions                 |
| 1150     | Questions                                  |
| 1200     | Close                                      |



## Agenda Day 2


| Time     | Agenda                                          |
| -------- | ----------------------------------------------- |
| 0900     | Mount google drive onto colab, importing packages, pandas     |
| 0950     | Break                                           |
| 1000     | Introducing pd.DataFrame                        |
| 1050     | Break                                           |
| 1100     | Combining dataframes                            |
| 1150     | Questions                                       |
| 1200     | Close                                           |



## Agenda Day 3

| Time     | Agenda                                          |
| -------- | ----------------------------------------------- |
| 0900     | Combining dataframes (cont.) and builtin in plot|
| 0950     | Break                                           |
| 1000     | For loops and automating processes              |
| 1050     | Break                                           |
| 1100     | User defined functions                          |
| 1150     | Questions                                       |
| 1200     | Close                                           |




## Agenda Day 4

| Time     | Agenda                                          |
| -------- | ----------------------------------------------- |
| 0900     | Finishing off merging, loops and functions      |
| 0950     | Break                                           |
| 1000     | Plotting with plotnine                          |
| 1050     | Break                                           |
| 1100     | Bringing it all together                        |
| 1150     | Questions                                       |
| 1200     | Close                                           |
