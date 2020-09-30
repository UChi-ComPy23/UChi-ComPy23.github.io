# Syllabus

Course number: [CAAM 37830=STAT 37830](https://stat.uchicago.edu/academics/course-info/2020-2021-courses/autumn-2020-stat-37830/)

## People
Instructor:  [Brad Nelson](https://bnels.github.io/). William H. Kruskal Instructor in the Department of Statistics. Office Hours TBD.

TA: [Richard Zhu](http://richardzhu.info/about/). PhD student in the Committee on Computational and Applied Mathematics. Office Hours TBD.

TA: [Yian Chen](https://cam.uchicago.edu/people/profile/yian-chen/). PhD student in the Committee on Computational and Applied Mathematics.  Office Hours TBD.

## Course Format

This course is scheduled to meet MWF 12:40 PM–1:30 PM.  Due to Covid-19, this course will be held entirely remotely.

Videos will be pre-recorded for lectures, and posted to Canvas.  Additionally, any lecture material will be made available on GitHub.  A problem solving session will be held during regular class time (12:40-1:30 PM Central Time) on Fridays in order to address questions related to lecture material.  Some material may be posted without an accompanying video (e.g. self-contained Jupyter notebooks), but videos will be made for anything where a "walkthrough" would add significant value.  You can always request a video if one does not exist and you believe it would be valuable - if several requests are received a video will be made.

Homework will be posted Friday, and due the following Friday.  We plan to have a homework assignment every week.

There will be a course-long group project.  There will be a midterm checkpoint, and a final report.  Groups will be assigned a few weeks into the quarter.

Problem solving sessions and office hours will not be recorded, so you can feel free to ask any question you want.

We will open discussion topics on Canvas where you can ask (or answer) questions as well.  This may be the best way to get help at odd hours or find others to work with.

### What you need for this course

You will need
1. A computer, with the ability to install software and run programs
2. An internet connection

Videos for class material will be pre-recorded, so there won't be a need to tune-in in real time.  Office hours/problem solving sessions will be held over Zoom.

We will assume you are running some [UNIX-based operating system](https://en.wikipedia.org/wiki/Unix) on your computer.  For most people, this will mean either Mac or Linux.  We will not support troubleshooting Windows issues - if you have windows on your computer, consider using the [Windows Linux Subsystem](https://docs.microsoft.com/en-us/windows/wsl/install-win10), or dual-booting or single-booting some version of Linux.

In addition to a University of Chicago account, you'll need to create a [GitHub](https://github.com/) account as assignments will be distributed through GitHub classroom.  Any work you do will be kept in private repositories.  If you want, you can create a "burner" account that isn't associated with your primary account (if you already have one).

## Evaluation

* Weekly homework (50% of final grade, each weighted equally)
* Group midterm checkpoint (20% of final grade)
* Group final project/report (30% of final grade)

10% of group work (5% of total grade) will be based on teammate evaluations.  These evaluations will be kept confidential.  If you believe your score to be unfair, you can reach out to the instruction staff.  We will look at git logs/history if we need to resolve any disputes.

You can drop your lowest homework score (or just not do a homework) if you submit a successful pull request to improve the content of the course reader.  You can drop up to two homework grades in this way.  Please coordinate through [GitHub issues](https://github.com/caam37830/book/issues).

There are several things you will be evaluated on
1. Correctness - is your answer correct?  Does your code produce the correct output? (may use an autograder to check this)
2. Performance/efficiency - there are often many ways to implement an algorithm.  Some will be faster than others.  We'll let you know if we are looking for certain optimizations.
3. Style - your code should be reasonably easy to understand.  This is typically achieved through the use of docstrings, comments, and appropriately named variables.  
4. Team work - we'll ask your teammates to evaluate whether you performed a fair share of the work.

### Grading Policy

Letter grades will be assigned using the following hard cutoffs:

A: 93% or higher<br />
A-: 90% or higher<br />
B+: 87% or higher<br />
B: 83% or higher<br />
B-: 80% or higher<br />
C+: 77% or higher<br />
C: 60% or higher<br />
D: 50% or higher<br />
F: less than 50%<br />

We reserve the right to curve the grades, but only in a fashion that would improve the grade earned by the stated rubric.

### Late Work Policy
Late work generally won't be accepted - please see the above note about how to drop your lowest homework scores.  Groups will be expected to come to a consensus on how to get work done on schedule.

This is the first time this course is being offered.  If an assignment is taking an unreasonable amount of time to complete, please let us know.  If this is done a few days before the due date, the assignment may be adjusted.

In abnormal circumstances, please reach out to the instruction staff for accomodations.  Due to Covid-19, it is anticipated that "abnormal" circumstances may be more common.

### Collaboration Policy

You are encouraged to collaborate with others in the class and use the internet to help with solving problems.

When working with others, you can discuss problems and solutions, but **do not copy code**.  Note anyone you who contributed to your solution in a comment in your code.  Same goes for any written answers (write your own, acknowledge others).

If you find helpful information online (e.g. on stackoverflow), put a note about what you used as well as the url in a comment in your code.  There are only so many ways to call a function, and it is perfectly acceptable to copy and paste a line or two of code (with a comment).

You are welcome to make your solutions publicly available, but **please wait until after the assignment due date.**

The group project will be judged collectively - you do not need to say who did what.  This will all be recorded by git logs anyways.

## Textbook & Readings

There is no required textbook for this course. Readings will be posted in the [schedule](schedule.md).  We are also building an online [course reader](https://caam37830.github.io/book/).

A good reference which we may follow portions of is:
[Mastering SciPy by Francisco J. Blanco-Silva.](https://catalog.lib.uchicago.edu/vufind/Record/11908913). This is available as a free electronic resource through the University of Chicago Library.

We will cover a variety of topics that are not adequately covered in *Mastering SciPy*, including basic Python (and some advanced topics), use of computing resources, basic numerical and algorithmic analysis, and additional libraries.

Required, recommended, and optional readings will be posted in the schedule.  **Required** means that the reading covers something that you will want to know that we may not cover in lecture, either for homework or life in general.  **Recommended** means that the reading covers something you may find interesting/useful but may also not be necessary.  **Optional** means that the reading covers material that overlaps with other sources, but perhaps you will like the exposition better.

## List of Topics

We'll survey a variety of topics used in scientific computing in (roughly) the following order, and with (roughly) 1 week per topic.

1. Programming in Python
2. Dense linear algebra (numpy)
3. Sparse linear algebra (scipy)
4. Functions of one variable (scipy)
5. Symbolic computing (sympy)
6. Numerical optimization (scipy)
7. Graphs (networkx)
8. Data processing (pandas)
9. Machine learning (scikit learn)

In parallel, we will cover several practical topics, including

1. Version control with git
2. Unit testing
3. Package development
4. Cluster computing
5. Parallel & GPU computing

A detailed [schedule](schedule.md) will be maintained.

## Students with Disabilities

The University of Chicago is committed to ensuring equitable access to
our academic programs and services. Students with disabilities who have
been approved for the use of academic accommodations by​ ​Student Disability
Services​ ​(SDS) and need a reasonable accommodation(s) to participate fully
in this course should follow the procedures established by SDS for using
accommodations. Timely notifications are required in order to ensure that
your accommodations can be implemented. Please meet with me to discuss
your access needs in this class after you have completed the SDS
procedures for requesting accommodations.

Phone: (773) 702-6000<br />
Email: ​disabilities@uchicago.edu
