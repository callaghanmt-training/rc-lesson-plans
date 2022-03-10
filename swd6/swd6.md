# SWD6: High Performance Python

SWD6 is one of our intermediate level courses in Python. 
It introduces a number of ways to both measure the efficiency of your code and improve it’s speed of execution by introducing strategies for fast and scalable computation with Python.
The course is suitable for those with a working knowledge of Python.
We will use a Web based programming environment (Jupyter Notebook / Colab), which means you will be able to apply the ideas you learn on the course straightaway without having to install any software at home or at work.
This course is delivered as an all-day workshop.

## Learning objectives

1. Understand how to profile Python code and identify bottlenecks
2. Understand how to choose the most appropriate data structure, algorithm, and libraries for a problem
3. Improve the execution time of Python code using:  
    - Vectorisation (with [NumPy](https://numpy.org/doc/stable/reference/ufuncs.html))  
    - Compilers (with [Numba](http://numba.pydata.org/))  
    - Parallelisation (with [Dask](https://docs.dask.org/en/latest/) and [Ray](https://www.ray.io/))  
    - GPUs (with [JAX](https://jax.readthedocs.io/en/latest/index.html), [CUDA/Numba](https://developer.nvidia.com/how-to-cuda-python), and [RAPIDS](https://developer.nvidia.com/rapids))  
4. Understand when to use each technique

## Instructor to do

- [ ] Familiarise yourself with [course book](https://arctraining.github.io/swd6_hpp/)
- [ ] [Own a Google account](https://colab.research.google.com/) and have previously accessed [Google Colaboratory](https://colab.research.google.com/)
- [ ] Send a reminder email at most 24 hours before the start of the session outlining [pre course prep](#Pre-course-prep)

## Pre-course prep

This course **does** require pre-course prep as we expect users to have either a Google account for accessing Google Colaboratory or an installed instance of Jupyter notebook/lab.

## Lesson resources

- [Workshop Book](https://arctraining.github.io/swd6_hpp/)
- [Github repository](https://github.com/ARCTraining/swd6_hpp)
- [Research Computing website](https://arc.leeds.ac.uk/)
- [Contact Research Computing](https://bit.ly/arc-help)

## Delivery plan

Six possible lessons:

1. Profiling
    - 40 mins content
2. Data Structures, Algorithms, and Libraries
    - 30 mins content
3. Vectorisation
    - 20 mins content
4. Compilers
    - 40 mins content
5. Parallelisation
    - 50 mins content
6. GPUs
    - 50 mins content

All have 10 mins of both exercises and solutions.

Delivery includes either lesson 5 or 6.

### Option 1: Including Parallelisation

| Time     | Session                                       | No. of helpers | Learner activities                                  |
| -------- | --------------------------------------------- | -------------- | --------------------------------------------------- |
| 09:00    | Overview                                      | 2              | Introduction, caution, time-space complexity, setup |
| 09:30    | 1. Profiling                                  | 2              | timeit, line_profiler                               |
| 09:50    | Break                                         |                |                                                     |
| 10:00    | 1. Profiling                                  | 2              | SnakeViz, pyinstrument, Eliot                       |
| 10:20    | 1. Profiling                                  | 2              | Exercises                                           |
| 10:30    | 1. Profiling                                  | 2              | Solutions                                           |
| 10:40    | 2. Data Structures, Algorithms, and Libraries | 2              | Built-ins functions, Data types/structure           |
| 10:50    | Break                                         |                |                                                     |
| 11:00    | 2. Data Structures, Algorithms, and Libraries | 2              | Modules, Algorithms                                 |
| 11:20    | 2. Data Structures, Algorithms, and Libraries | 2              | Exercises                                           |
| 11:30    | 2. Data Structures, Algorithms, and Libraries | 2              | Solutions                                           |
| 11:40    | 3. Vectorisation                              | 2              | Broadcasting, Vectorisation                         |
| 12:00    | Lunch                                         |                |                                                     |
| 13:00    | 3. Vectorisation                              | 2              | Exercises                                           |
| 13:10    | 3. Vectorisation                              | 2              | Solutions                                           |
| 13:20    | 4. Compilers                                  | 2              | CPython, Numba njit, signatures, vectorize          |
| 13:50    | Break                                         |                |                                                     |
| 14:00    | 4. Compilers                                  | 2              | Numba guvectorize, parallel                         |
| 14:10    | 4. Compilers                                  | 2              | Exercises                                           |
| 14:20    | 4. Compilers                                  | 2              | Solutions                                           |
| 14:30    | 5. Parallelisation                            | 2              | What is it, Parallelising a Python, Dask intro      |
| 14:50    | Break                                         |                |                                                     |
| 15:00    | 5. Parallelisation                            | 2              | Dask single machine, distributed, Ray               |
| 15:30    | 5. Parallelisation                            | 2              | Exercises                                           |
| 15:40    | 5. Parallelisation                            | 2              | Solutions                                           |
| 15:50    | Summary, wrap up, and questions               |                |                                                     |
| 16:00    | Close                                         |                |                                                     |

### Option 2: Including GPUs

| Time     | Session                                       | No. of helpers | Learner activities                                  |
| -------- | --------------------------------------------- | -------------- | --------------------------------------------------- |
| 09:00    | Overview                                      | 2              | Introduction, caution, time-space complexity, setup |
| 09:30    | 1. Profiling                                  | 2              | timeit, line_profiler                               |
| 09:50    | Break                                         |                |                                                     |
| 10:00    | 1. Profiling                                  | 2              | SnakeViz, pyinstrument, Eliot                       |
| 10:20    | 1. Profiling                                  | 2              | Exercises                                           |
| 10:30    | 1. Profiling                                  | 2              | Solutions                                           |
| 10:40    | 2. Data Structures, Algorithms, and Libraries | 2              | Built-ins functions, Data types/structure           |
| 10:50    | Break                                         |                |                                                     |
| 11:00    | 2. Data Structures, Algorithms, and Libraries | 2              | Modules, Algorithms                                 |
| 11:20    | 2. Data Structures, Algorithms, and Libraries | 2              | Exercises                                           |
| 11:30    | 2. Data Structures, Algorithms, and Libraries | 2              | Solutions                                           |
| 11:40    | 3. Vectorisation                              | 2              | Broadcasting, Vectorisation                         |
| 12:00    | Lunch                                         |                |                                                     |
| 13:00    | 3. Vectorisation                              | 2              | Exercises                                           |
| 13:10    | 3. Vectorisation                              | 2              | Solutions                                           |
| 13:20    | 4. Compilers                                  | 2              | CPython, Numba njit, signatures, vectorize          |
| 13:50    | Break                                         |                |                                                     |
| 14:00    | 4. Compilers                                  | 2              | Numba guvectorize, parallel                         |
| 14:10    | 4. Compilers                                  | 2              | Exercises                                           |
| 14:20    | 4. Compilers                                  | 2              | Solutions                                           |
| 14:30    | 6. GPUs                                       | 2              | Numba for CUDA GPUs                                 |
| 14:50    | Break                                         |                |                                                     |
| 15:00    | 6. GPUs                                       | 2              | RAPIDS, Diagnostics, JAX                            |
| 15:30    | 6. GPUs                                       | 2              | Exercises                                           |
| 15:40    | 6. GPUs                                       | 2              | Solutions                                           |
| 15:50    | Summary, wrap up, and questions               |                |                                                     |
| 16:00    | Close                                         |                |                                                     |


## Example Agenda

Here are example agendas that can be shared in a session hackpad.

### Option 1: Including Parallelisation

| Time      | Agenda                                                            |
| --------- | ----------------------------------------------------------------- |
| 09:00     | Overview                                                          |
| 09:30     | 1. Profiling (part 1)                                             |
| 09:50     | Break                                                             |
| 10:00     | 1. Profiling (part 2, exercises)                                  |
| 10:40     | 2. Data Structures, Algorithms, and Libraries (part 1)            |
| 10:50     | Break                                                             |
| 11:00     | 2. Data Structures, Algorithms, and Libraries (part 2, exercises) |
| 11:40     | 3. Vectorisation (part 1)                                         |
| 12:00     | Lunch                                                             |
| 13:00     | 3. Vectorisation (part 2, exercises)                              |
| 13:20     | 4. Compilers (part 1)                                             |
| 13:50     | Break                                                             |
| 14:00     | 4. Compilers (part 2, exercises)                                  |
| 14:30     | 5. Parallelisation (part 1)                                       |
| 14:50     | Break                                                             |
| 15:00     | 5. Parallelisation (part 2, exercises)                            |
| 15:50     | Summary, wrap up, and questions                                   |
| 16:00     | Close                                                             |

### Option 2: Including GPUs

| Time      | Agenda                                                            |
| --------- | ----------------------------------------------------------------- |
| 09:00     | Overview                                                          |
| 09:30     | 1. Profiling (part 1)                                             |
| 09:50     | Break                                                             |
| 10:00     | 1. Profiling (part 2, exercises)                                  |
| 10:40     | 2. Data Structures, Algorithms, and Libraries (part 1)            |
| 10:50     | Break                                                             |
| 11:00     | 2. Data Structures, Algorithms, and Libraries (part 2, exercises) |
| 11:40     | 3. Vectorisation (part 1)                                         |
| 12:00     | Lunch                                                             |
| 13:00     | 3. Vectorisation (part 2, exercises)                              |
| 13:20     | 4. Compilers (part 1)                                             |
| 13:50     | Break                                                             |
| 14:00     | 4. Compilers (part 2, exercises)                                  |
| 14:30     | 6. GPUs (part 1)                                                  |
| 14:50     | Break                                                             |
| 15:00     | 6. GPUs (part 2, exercises)                                       |
| 15:50     | Summary, wrap up, and questions                                   |
| 16:00     | Close                                                             |
