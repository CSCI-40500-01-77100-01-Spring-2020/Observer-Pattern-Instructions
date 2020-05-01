# Observer Pattern Homework Assignment

## Overview

This assignment involves an implementation of the Observer pattern using the UML class diagram in the [slides]. For this project, we will be using Java; an overview of Java can be found in the lecture notes section of our Bb course. You are not allowed to use any built-in or third-party Observer types, instead, you must use the ones provided in the starter code. The starter code contains *abstract* types for `Observer`s and `Subject`s and two simplified corresponding *concrete* types. All functionality applicable to all `Observer`s, e.g., is implemented in the abstract type. The concrete classes are very simple, having only a single `int` instance (member) field (data).

**Your submission must compile and run in the standard environment on our Linux lab machines (Ubuntu)**. If you work in some other environment, it is your responsibility to port your code to this environment and to make sure that it works there. **Do not wait until the last minute to compile and test on our lab machines** - past experience shows that last-minute problems often occur and lead to low project scores.

Java tools should be available on our lab machines. Java is very similar to C++, it is easy to use if you know C++ (they are both statically-typed compiled languages).

## Instructions

1. "Accept" the project [invitation] in GitHub Classrooms. This will create a personal private repository.
1. Clone the repository you just created. Information on using Git and GitHub can be found in our Bb class.
1. You are to fill-in the code marked with `TODO` in the starter code.
    1. While you are allowed to add fields, the **only code you should write** is where the TODO comments are.
    1. **No other parameterized constructors or methods are necessary**. You may add a default (no-arg) constructor if desired.
    1. You are also **not allowed** to modify the parameters or return types of any of the methods in the starter code.
	1. Points will be subtracted for any **modifications to the starter code**.
	1. Only additions are allowed, the additions being additional fields and code within the existing methods.
    1. You are not allowed to use any built-in or third-party Observer types.
    1. You may import additional packages but only from the [standard Java library][api].
1. The code you fill-in will implement the functionality of the Observer Pattern as described in the [slides] and our textbook.
1. Once you enter the code with correct functionality, the tests will be begin to pass (they initially fail).
1. **You are not allowed to modify the test code**. You are only allowed to edit the following files and **not add any additional files**. Submitting changes to test code will result in a **grade of 0** for this assignment:
    1. `Subject.java`
    1. `IntegerContainer.java`
    1. `IntegerObserver.java`
1. You may run the tests locally at any time to see if they pass. Instructions are included in the starter code.
1. **You must add comments** to your code. Code without additional comments **will receive a grade of 0**.
1. **Get started early**. Ensure that your environment is properly working **ahead of the deadline**.

## Project Submission

On or before the due date listed on Bb, you should submit the following. Submit your project by following this step:

1. Push all materials to [GitHub Classrooms][invitation].

You can submit up to 24 hours after the deadline; if you do so, your project score will be reduced by 10%. If you submit more than 24 hours after the deadline, the submission will not be accepted and you will receive zero points for this project.

If the grader has problems compiling or executing your code, she/he will e-mail you; you must respond within 48 hours to resolve the problem. Please check often your email accounts after submitting the project (for about a week or so) in case the grader needs to get in touch with you.

## Academic Integrity

The project you submit must be entirely your own work. Minor consultations with others in the class are OK, but they should be at a very high level, without any specific details. The work on the project should be entirely your own: all **design**, **programming**, **testing**, and **debugging** should be done only by you, independently and from scratch. Sharing your code or documentation with others is not acceptable. Submissions that show excessive similarities will be taken as evidence of cheating and dealt with accordingly; this includes any similarities with projects submitted in previous instances of this course. Using (e.g., online) resources outside of this course to complete this assignment is **disallowed** and will be considered plagiarism. Any citations are also disallowed.

Academic misconduct is an extremely serious offense with **severe** consequences. Additional details on academic integrity are available from the [Committee on Academic Misconduct](http://www.hunter.cuny.edu/studentaffairs/student-conduct/academic-integrity/cuny-policy-on-academic-integrity). I strongly recommend that you check this URL. If you have any questions about university policies or what constitutes academic misconduct in this course, please contact me immediately.

[slides]: https://docs.google.com/presentation/d/1BmSFYmVT91mRXXgGedU8IEAylh5pcTPv_5UpqlcFqaM/edit#slide=id.p43
[invitation]: https://classroom.github.com/a/V6jQd7gA
[api]: https://docs.oracle.com/javase/8/docs/api
