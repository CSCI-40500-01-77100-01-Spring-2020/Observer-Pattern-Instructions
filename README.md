# Observer Pattern Testing Homework Assignment

## Overview

In this assignment, the starter code consists of an *incorrect* implementation of the Observer Pattern. The problem is that `Subject`s only record the *last* attached `Observer`. Thus, although multiple `Observer`s may attach to a given `Subject`, only the last one will be notified of any state changes. Despite this, the current testing code does *not* result in a failure.

## Goal

The goal of this assignment is *not* to fix the code implementing the Observer pattern. Instead, you are to *fix the testing code*. The problem with the test code is that it is not properly testing the pattern implementation. As stated above, although the pattern implementation is incorrect, the tests pass. Your job is to *fix the tests* so that the *test fails*. **YOU ARE NOT TO FIX THE BUG IN THE PATTERN IMPLEMENTATION**. A correct assignment submission is one where the *test fails* because of the aforementioned bug regarding the capacity of `Subject`s for attaching only a single `Observer`.

This assignment will get you familiar with writing test code and show that it is possible to write bugs in test code.

## Notes

As before, **your submission must compile and run in the standard environment on our Linux lab machines (Ubuntu)**. If you work in some other environment, it is your responsibility to port your code to this environment and to make sure that it works there. **Do not wait until the last minute to compile and test on our lab machines** - past experience shows that last-minute problems often occur and lead to low project scores.

Java tools should be available on our lab machines. Java is very similar to C++, it is easy to use if you know C++ (they are both statically-typed compiled languages).

## Instructions

1. "Accept" the project [invitation] in GitHub Classrooms. This will create a personal private repository.
1. Clone the repository you just created. Information on using Git and GitHub can be found in our Bb class.
1. You are to *only* fix the test code in the starter code.
    1. You are *not* allowed to change code other than the test code.
    1. You must *only* change the code in the test methods.
    1. No other modifications (e.g., instance field, method, and constructor additions/removals, parameter changes, return type changes) should be necessary. If you feel otherwise, contact me ASAP.
	1. Points will be subtracted for any **modifications to the structure of the starter code**.
    1. You are not allowed to use any built-in or third-party Observer types.
    1. You may import additional packages but only from the [standard Java library][api] and the [JUnit4 library][junit4api]. JUnit is a popular unit testing framework for Java.
1. Once you enter the code with correct functionality, the tests will be begin to **fail** (they initially pass).
1. You are only allowed to edit the files in the `tests` directory.
1. You may run the tests locally at any time to see if they fail. Instructions are included in the starter code.
1. **You must add comments** to your code. Code without additional comments **will receive a grade of 0**.
1. **Get started early**. Ensure that your environment is properly working **ahead of the deadline**.

## Hints

1. The bug is in the `Subject` code. You should only have to alter the test code for `Subject`s and *not* `Observer`s.
1. Once you change the test code, fix the bug in the `Subject` code to make sure that the tests pass again. But, **do not** commit the bug fix. This is just to ensure that your test fix is correct.

## Project Submission

On or before the due date listed on Bb, you should submit the following. Submit your project by following these steps:

1. Push all materials to [GitHub Classrooms][invitation].

You can submit up to 24 hours after the deadline; if you do so, your project score will be reduced by 10%. If you submit more than 24 hours after the deadline, the submission will not be accepted and you will receive zero points for this project.

If the grader has problems compiling or executing your code, she/he will e-mail you; you must respond within 48 hours to resolve the problem. Please check often your email accounts after submitting the project (for about a week or so) in case the grader needs to get in touch with you.

## Academic Integrity

The project you submit must be entirely your own work. Minor consultations with others in the class are OK, but they should be at a very high level, without any specific details. The work on the project should be entirely your own: all **design**, **programming**, **testing**, and **debugging** should be done only by you, independently and from scratch. Sharing your code or documentation with others is not acceptable. Submissions that show excessive similarities will be taken as evidence of cheating and dealt with accordingly; this includes any similarities with projects submitted in previous instances of this course. Using (e.g., online) resources outside of this course to complete this assignment is **disallowed** and will be considered plagiarism. Any citations are also disallowed.

Academic misconduct is an extremely serious offense with **severe** consequences. Additional details on academic integrity are available from the [Committee on Academic Misconduct](http://www.hunter.cuny.edu/studentaffairs/student-conduct/academic-integrity/cuny-policy-on-academic-integrity). I strongly recommend that you check this URL. If you have any questions about university policies or what constitutes academic misconduct in this course, please contact me immediately.

[slides]: https://docs.google.com/presentation/d/1BmSFYmVT91mRXXgGedU8IEAylh5pcTPv_5UpqlcFqaM/edit#slide=id.p43
[invitation]: https://classroom.github.com/a/8YCoUGo7
[api]: https://docs.oracle.com/javase/8/docs/api
[junit4api]: https://junit.org/junit4/javadoc/latest/
