# Syllabus

Course number: [CAAM 37830=STAT 37830](https://stat.uchicago.edu/academics/course-info/2023-2024-courses/autumn-2023-stat-37830/)

## People
Instructor:  [Tristan Goodwill](https://tristangdwl.github.io/). William H. Kruskal Instructor in the Department of Statistics. OH Tuesdays at TBD in Jones 316.

TA: Runxin Ni. OH Fridays 12 - 1 in Jones 226. runxin.ni @ uchicago.edu

TA: Bob Zhao. OH Tuesdays 2 - 3 in Jones 308. honglizhaobob @ uchicago.edu

## Course Format

This course is scheduled to meet TR 3:30 PM-4:50 PM in Eckhart 133. 

Homework will be posted Thursday, and due the following Thursday at 10 PM.  We plan to have a homework assignment every week, apart from Thanksgiving break.

There will be a course-long group project.  This will include a project proposal, a midterm checkpoint, and a final report.  Groups will be organized a few weeks into the quarter.

### Prerequisites

Multivariable calculus, linear algebra, prior programming experience (not necessarily in Python).

Because this is an introductory graduate-level course, the Prerequisites are fairly informal and minimal.  Since we're doing scientific computing, we'll assume some basic familiarity with high-school or introductory undergraduate physical science, and maybe some social science. We'll also assume familiarity with multivariable calculus and linear algebra.  We'll cover some ODEs and PDEs, but not at a level that requires significant prior experience.  Prior programming experience is assumed, but this can be informal.

### What you need for this course

You will need
1. A computer, with the ability to install software and run programs
2. An internet connection

We will assume you are running some [UNIX-based operating system](https://en.wikipedia.org/wiki/Unix) on your computer.  For most people, this will mean either Mac or Linux.  We will not support troubleshooting Windows issues - if you have Windows on your computer please download [Windows Subsystem Linux](https://docs.microsoft.com/en-us/windows/wsl/).

In addition to a University of Chicago account, you'll need to create a [GitHub](https://github.com/) account as assignments will be distributed through GitHub classroom.  Any work you do will be kept in private repositories.  If you want, you can create a "burner" account that isn't associated with your primary account (if you already have one).

## Evaluation

* Weekly homework (50% of final grade, each weighted equally)
* Group project proposal (5% of final grade)
* Group midterm checkpoint (15% of final grade)
* Group final project/report (30% of final grade)

10% of group work (5% of total grade) will be based on teammate evaluations.  These evaluations will be kept confidential.  If you believe your score to be unfair, you can reach out to the instruction staff.  We will look at git logs/history if we need to resolve any disputes.

There are several things your work will be evaluated on
1. Correctness - is your answer correct?  Does your code produce the correct output? (may use an autograder to check this)
2. Performance/efficiency - there are often many ways to implement an algorithm.  Some will be faster than others.  We'll let you know if we are looking for certain optimizations.
3. Style - your code should be reasonably easy to understand.  This is typically achieved through the use of docstrings, comments, and appropriately named variables.  
4. Team work - we'll ask your teammates to evaluate whether you performed a fair share of the work.

### Late Work Policy
Deadlines have a 2 hour grace period to compensate for technical issues. Work submitted after that grace period is considered late.

**Individual work:** Two 48 hour extensions will automatically granted per student, no questions asked. However, you do need to notify both of the TAs before the deadline. Beyond those, exceptions will only be granted in abnormal circumstances.

**Group work:** Project related extensions will be only be granted in abnormal circumstances.

If an assignment is taking an unreasonable amount of time to complete, please let us know.  If this is done a few days before the due date, the assignment may be adjusted.

### Regrade Requests

You will have one week from the day assignment grades are released to request a regrade. 

### Collaboration Policy

You are encouraged to collaborate with others in the class and use the internet to help with solving problems.

When working with others, you can discuss problems and solutions, but **do not copy code**.  Note anyone you who contributed to your solution in a comment in your code.  Same goes for any written answers (write your own, acknowledge others).

If you find helpful information online (e.g. on stackoverflow), put a note about what you used as well as the url in a comment in your code.  There are only so many ways to call a function, and it is perfectly acceptable to copy and paste a line or two of code (with a comment).

You are welcome to make your solutions publicly available, but **please wait until after the assignment due date.**

The group project will be judged collectively - you do not need to say who did what.  This will all be recorded by git logs anyways.

### The Use of NLP-based Tools

There are many natural language processing tools available, which can be used to generate good code efficiently. In this course, however, we will be developing skills and knowledge that are important to discover and practice on your own. Because use of AI tools inhibits development of these skills and knowledge, students are not allowed to use any AI tools, such as ChatGPT or DallE 2, in this course. Students are expected to present work that is their own without assistance from automated tools. If you are unclear if something is an AI tool, please check with your instructor. Using AI tools for any purposes in this course will violate the [University’s academic integrity policy](https://studentmanual.uchicago.edu/academic-policies/academic-honesty-plagiarism/) and be treated as such. 

## Textbook & Readings

There is no required textbook for this course. Readings will be posted in the [schedule](schedule.md).  We are also building an online [course reader](https://uchi-compy23.github.io/notes/).

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
7. Data processing (pandas)
8. Machine learning (scikit learn)
9. Fast Multipole Method

In parallel, we will cover several practical topics, including

1. Version control with git
2. Unit testing
3. Package development
4. Cluster computing
5. Parallel & GPU computing

Changes may be made based on interest and a detailed [schedule](schedule.md) will be maintained.

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
