# Computer Graphics CSC317/CSC2504 _Fall 2025_

![_image courtesy Tim Jeruzalski_](images/bunny-rigid-body.gif)

- [Lectures](#Lectures)
- [Tutorials](#Tutorials)
- [Course Overview](#course-overview)
- [Recommended Textbook](#recommended-textbook)
- [Lecture Schedule](#lecture-schedule)
- [Assignments](#assignments)
- [Lateness Policy](#lateness-policy)
- [Grading](#grading)
- [Academic Honesty (required reading)](#academic-honesty)

## Sections
|                | **LEC 0101/2001** | **LEC 0201** |
|----------------|--------------|--------------|
| Instructor     | Prof. [Karan Singh](https://www.dgp.toronto.edu/~karan/) | [Joonho Kim](http://www.ohnooj.com) |
| Contact        | karan@dgp.toronto.edu | joonho@dgp.toronto.edu |
| Lecture        | Tue 13:00–15:00 WI1017 | Tue 15:00–17:00 BA1130 |
| Tutorial       | Thu 13:00–14:00 MC252  | Thu 15:00–16:00 MC254 |
| Office Hours   | Tue 11:30–12:30 BA5258 | Wed 12:00–13:00 BA2272 |


**You can attend any office hours that fits your schedule*

## TAs
Karran Pandey **(Head TA)**\
Lulu Wei\
Sophia Yang\
Zhijie Wu\
Vishnu Nittoor\
Jialin Li\
Bo-Wei Wen

(TA Contact will be added soon)

## Links

- [MarkUs](https://markus.teach.cs.toronto.edu/markus)

**Use Assignment GitHub issue pages for questions/discussion**

## Programming Resources 

[www.cplusplus.com](http://www.cplusplus.com)

[OpenGL Tutorials at http://www.opengl-tutorial.org](http://www.opengl-tutorial.org)

[The Matrix Cookbook](https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf)

[Eigen Matrix Library](https://eigen.tuxfamily.org/dox/)

[CMake Guide](https://cliutils.gitlab.io/modern-cmake/)

## Course Overview

This course introduces the basic concepts and algorithms of computer graphics.
It covers the basic methods needed to model and render 3D objects, including
much of the following: graphics displays, basic optics, line drawing, affine and
perspective transformations, windows and viewports, clipping, visibility,
illumination and reflectance models, radiometry, energy transfer models,
parametric representations, curves and surfaces, texture mapping, graphics
hardware, ray tracing, graphics toolkits, animation systems.

**Prerequisites:** C/C++ Programming, Linear Algebra, Calculus, Numerical
Methods.

The student is expected to read background material on the hardware and local
software, and should be comfortable with elementary linear algebra, geometry,
and vector calculus. It is also assumed that the student is comfortable
programming in basic C++.

**_(Strongly)_ Recommended preparation:** Multivariable Calculus

## Recommended Textbook

![The Book.](https://www.cs.cornell.edu/~srm/fcg4/K22616_cover-300.jpg)

This class involves  **_required reading_** from:

[_Fundamentals of Computer Graphics, Fourth
Edition_](https://www.cs.cornell.edu/~srm/fcg4/), Steve Marschner, Peter Shirley,
et al. 2015.

Digital e-book are available at [CRC
Press](https://www.crcpress.com/Fundamentals-of-Computer-Graphics-Fourth-Edition/Marschner-Shirley/p/book/9781482229394).


## Lecture Schedule

Below is the schedule for the course with each row of the table showing the week beginning with Sunday.
* Tuesdays: Lecture days
* Wednesdays: Quiz due dates (time tbd)
* Thursdays: Tutorial/Office Hours
* Fridays: Assignment due dates **(11:59pm)** on Markus.

| Week | Sunday  | Mon           | Tue (Lectures)| Wed (Quiz Release+Due)| Thu (Tutorial+office Hours) | Fri (Assignment Due)| 
|------|:--------|--------------------|----------|-----------------------|-------------------|---------------------|
| 1    | Aug 31  | **Labour Day**     | [Introduction](lectures/lecture0.pdf)<br>[Lec 1](lectures/lecture1.pdf)<br>[Lec 1 JK](lectures/lecture0JK.pdf)   |                       | [Tut 1](tutorials/CSC317%Computer Graphics%Tutorial%1.pdf)             |                     |
| 2    | Sep 7   |                    | [Lec 2](lectures/lecture2.pdf)    | q1 released                   | Tut 2 | a1 + oh1                 |
| 3    | Sep 14  |                    | [Lec 3](lectures/lecture3.pdf)    |                       | Tut 3 | a2 + oh2                         |
| 4    | Sep 21  |                    | [Lec 4](lectures/lecture4.pdf)    | q2 released + q1 due     | Tut 4       | a3 + oh3                 |
| 5    | Sep 28  |                    | [Lec 5](lectures/lecture5.pdf)    |                       | Tut 5             |                     |
| 6    | Oct 5   |      | refresher+**Test 1 (ch1-4)**|                       |         | a4 + oh4                 |
| 7    | Oct 12  | **Thanksgiving**   | [Lec 6](lectures/lecture6.pdf)    | q3 released + q2 due     | Tut 6             |                     |
| 8    | Oct 19  |                    | [Lec 7](lectures/lecture7.pdf)    |                       |               | a5 + oh5                  |
| 9    | Oct 26  | **Reading Week** | **Reading Week** | **Reading Week** | **Reading Week** | **Reading Week**    |
| 10   | Nov 2   |                    | Lec7+[Lec 8](lectures/lecture8.pdf)    |                       | Tut 7       | a6 + oh6                  |
| 11   | Nov 9   |      | Lec 8 (**Drop Day**)   | q4 released + q3 due     | Tut 8        | a7 + oh7                 |
| 12   | Nov 16  |                |Guest lecture |                       |                   |                     |
| 13   | Nov 23  |    |**Test 2 (ch5-8)**+adv. topics | q4 due              |       | a8 + oh8 + showcase         |
| 14   | Nov 30  |               | wrap+showcase |                       |                   |                     |

You can find a series of short videos cut up by lectures and topics voicing over the lecture slides [here](https://drive.google.com/drive/folders/1cWDOSB-DHepfBlj_vdDsf9mU9sLP8sem?usp=sharing).

## Grading

| % | Item |
| ----: | :-------------- |
|64| Assignments (8% each) + 5% extra credit creative showcase
|12| 4 Quizzes (Online)
|12| Test 1 (ch 1-4)
|12| Test 2 (ch 5-8)

## Assignments

**Note: All assignments are available immediately. BUT we are only covering one assignment at a time. While  you are welcome to look ahead, future assignments
have not been debugged and we will not answer questions about them at tutorial or office hours until we cover them in lecture**

| Assignment |
| ---------- |
| [Assignment 1: Raster Images](https://github.com/ohnooj/computer-graphics-raster-images)|
| [Assignment 2: Ray Casting](https://github.com/ohnooj/computer-graphics-ray-casting)|
| [Assignment 3: Ray Tracing](https://github.com/ohnooj/computer-graphics-ray-tracing)|
| [Assignment 4: Bounding Volume Hierarchy](https://github.com/ohnooj/computer-graphics-bounding-volume-hierarchy)|
| [Assignment 5: Meshes](https://github.com/ohnooj/computer-graphics-meshes)|
| [Assignment 6: Shader Pipeline](https://github.com/ohnooj/computer-graphics-shader-pipeline)|
| [Assignment 7: Kinematics](https://github.com/ohnooj/computer-graphics-kinematics)|
| [Assignment 8: Mass-Sptring System](https://github.com/ohnooj/computer-graphics-mass-spring-systems)|
| [Showcase]()|

Assignments will be due on their respective Friday due dates at **11:59pm**.

### Lateness Policy

Every student is given ten (10) grace tokens which are automatically applied for assignments on Markus starting at midnight on the due date. Each grace token will provide an additional 12 hours period to submit your assignment without penalty.  Grace tokens do not replenish, so use them wisely.  Weekends count as late days.  You cannot choose which assignments to apply your grace tokens.  Once you run out of grace tokens, any **late assignments will be counted as 0 marks**.

For example, say you have 10 grace tokens.  If a1 is due on Friday 11:59pm and you submit your assignment on Sunday 4pm, you will have used 4 grace tokens: Friday 11:59pm -> Saturday 11:59am (1gt) -> Saturday 11:59pm (1gt) -> Sunday 11:59am (1gt) -> Sunday 11:59pm (1gt).  You will now have 6 grace tokens left for other assignments.

## Quizzes
There will be 4 online quizzes available through Quercus. Each quiz will cover the content of two assignments each, from assignment 1 to assignment 8. Each quiz will go live after the respective topics are covered in class and must be completed on Quercus by the end of the term (Nov 26).

[Academic Honesty (required reading)](#academic-honesty)

![_image courtesy Gavin Barill_](images/gavin-barill-snowglobe.jpg)



### Academic Honesty

Academic honesty is a very serious matter and can result in very serious
consequences. Note that academic offences may be discovered and handled
retroactively, even after the semester in which the course was taken for credit.
This is a challenging class aimed at teaching you the fundamentals of computer
graphics. You wont learn much if you cheat but you might get a good grade if you
get away with it. If all you want is a good grade take an easier class where you
wont have to cheat!

For purposes of this class, academic dishonesty is defined as:

- Any attempt to pass off work on a test, quiz or assignment that didn't come straight out of your
  own head.
- Any collaboration on written or programming assignments (its ok to share ideas
  on programming assignments but the code MUST be your own) in which the
  collaborating parties don't clearly and prominently explain exactly who did
  what, at turn-in time.
- Any activity that has the effect of significantly impairing the ability of
  another student to learn. Examples here might include destroying the work of
  others, interfering with their access to resources (e.g., digital cameras), or
  deliberately providing them with misleading information.

### Email & Bulletin Board Traffic

- Please use the TA Email List for all communications except for things that require a Professors dedicated attention. 
- Use github issue pages on assignment pages for questions
- Do NOT broadcast pieces of your code or answers to written assignments to the
  github issues. Specific or general implementation questions whose answer
  would benefit all students in the class are appropriate. However: the bulletin
  board is NO replacement for the tutorial hour. That should be the main forum
  for asking/answering questions of this sort.
- Questions of the form "I cannot find the problem with my code; here it is, can
  you help me" are unlikely to be replied, so don't count on it. If you have a
  question with code, take it to the TA office hours or to the tutorials.














