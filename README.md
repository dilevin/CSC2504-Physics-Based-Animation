# CSC2504-Physics-Based-Animation *Fall 2021*
![_image courtesy David Levin_](images/EolPenguinFallZoomedOut.gif)

- [Lectures](#Lectures)
- [Course Overview](#course-overview)
- [Resources](#helpful-resources )
- [Lecture Schedule](#lecture-schedule)
- [Grading](#grading)
- [Lateness Policy](#lateness-policy)

## Instructors
Prof. [David I.W. Levin](http://www.cs.toronto.edu/~diwlevin/)  
diwlevin@cs.toronto.edu  

## Lectures
Tuesday 13:00-15:00 (first two weeks online) **NOTE: link sent via Quercus to registered students**

Room: BA B026

## Office Hours
Tuesday 15:00-16:00 (first two weeks online)

[Discussion Board via Piazza](http://piazza.com/utoronto.ca/fall2021/csc2504)

## Course Summary

This course is a graduate-level seminar course on physics-based animation. It will involve reading state-of-the-art papers in the field and implementing algorithms from those papers. The course will feature a final project based on the topic. 
  
Students are expected to read background material as necessary and should be comfortable with elementary linear algebra, geometry,
and vector calculus. 

## Course Structure
This course is a graduate *seminar* course on physics-based animation which will involve reading, analyzing, implementing and commenting on both seminal and cutting-edge works in the field. Each week students will be assigned one of several roles (presenter, implementer, blogger, reviewer) and are charged with carrying out the associated responsibilites.

## Roles and Responsibilities ##

**Presenter:** Prepare a 20-30 minute conference style presentation about the paper. After your presentation you will take 10 minutes of questions from the audience.  

***Articles on reading papers***  
[How to read a research paper (CMU)](http://graphics.cs.cmu.edu/courses/15-869-F15/How%20to%20read%20a%20paper.pdf)

[How to read a realisitc rendering paper (Morgan McGuire)](https://morgan3d.github.io/advanced-ray-tracing-course/reading-research.pdf)


**Implementer:** You will have up to **two (2)** weeks to implement as much of the paper as you can. Each week you will demonstrate your progress and discuss, the things you have learned, and issues that have arisen.

**Blogger:** You will write a medium style blog post (i.e. like [this](https://medium.com/inside-machine-learning/what-is-a-transformer-d07dd1fbec04)) about the paper and submit it [here](http://physics.diwlevin.com). Posts are due one week after the implementation is finished.

**Reviewer:** You will submit a high-quality review of the paper. Submit your review using the review form [here](https://forms.gle/nyqVhPmquHRKpaA48)

## Final Project Details
Projects will be done in groups of no more than **three (3)** people. The project must involve implementing a physics algorithm that falls into the grand challenges listed below. Check with the instructor to ensure that your chosen project is of sufficient scope. 

**Deliverable:**  a micro-SIGGRAPH submission comprised of a **two (2) page** extended abstract and **five (5) minute** submission style video.

**Due Date:** December 21st, 11:59pm

### Grand Challenges (more details and examples coming soon)
All projects must fall into one of the grand challenge categories below:
1. Differentiable Physics Simulation
2. Direct Simulation from Computer-Aided-Design Tools
3. Biomechanical Simulation for Digital Humans
4. Machine Learning for Material Behaviour 
5. Simulation on non-traditional geometric representation

## Helpful Resources  
[Intro Physics-based Animation Course /w Video Lectures](https://github.com/dilevin/CSC417-physics-based-animation)

[The Variational Principles of Mechanics (Book)](https://search.library.utoronto.ca/details?1576571&uuid=24e9601f-a561-440e-b4f7-0162225ae73d)  

[Calculus of Variations](https://books.google.ca/books/about/Calculus_of_Variations.html?id=YkFLGQeGRw4C&printsec=frontcover&source=kp_read_button&redir_esc=y#v=onepage&q&f=false)

[Numerical Methods for Evolutionary Differential Equations (Book) ](https://search.library.utoronto.ca/details?8723030)

[Fluid Simulation for Graphics (Book)](https://dl.acm.org/citation.cfm?id=1457699)   

[Fluid Simulation for Graphics (Notes)](https://www.cs.ubc.ca/~rbridson/fluidsimulation/fluids_notes.pdf)   

[Real-time Collision Detection (Book)](https://dl.acm.org/citation.cfm?id=1121584)

[Real Time Physics (Website)](http://matthias-mueller-fischer.ch/realtimephysics/)  
  
[FEM Simulation of 3D Deformable Solids (Website)](http://www.femdefo.org)

[Matrix and Linear Algebra Identities (PDF)](https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf)

[Geometric Tools (Website)](https://www.geometrictools.com)

[Material Point Method SIGGRAPH Course (PDF)](https://www.seas.upenn.edu/~cffjiang/research/mpmcourse/mpmcourse.pdf)

[Two-Minute Papers (YouTube not strictly physics, but cool)](https://www.youtube.com/channel/UCbfYPyITQ-7l4upoX8nvctg) 

[Prof. Shinjiro Sueda's Rigid Body Mechanics Notes for Joints](https://github.com/sueda/redmax/blob/master/notes.pdf)

## Useful Software Tools
[Blender: Open-Source Modelling and Rendering Software](https://www.blender.org)

[libigl: Lightweight C++ Geometry Processing Library](https://libigl.github.io)

[gptoolbox: MATLAB Geometry Processing Library](https://github.com/alecjacobson/gptoolbox)

[Bartels: C++ and MATLAB Utilities for Physics Simulation](https://github.com/dilevin/Bartels)

## Lecture Schedule

| Week | Topic / Event |
| ---- | :------------ |
| 1    | Introduction and assign [**Paper 1:** Projective Dynamics](https://www.cs.utah.edu/~ladislav/bouaziz14projective/bouaziz14projective.html)
| 2    | Presentations for **Paper 1** and assign [**Paper 2:** Position Based Dynamics](https://www.cs.toronto.edu/~jacobson/seminar/mueller-et-al-2007.pdf)
| 3    | Presentations for **Paper 2** and assign [**Paper 3:** Large Steps in Cloth Simulation](https://www.cs.cmu.edu/~baraff/papers/sig98.pdf)
| 4    | Presentations for **Paper 3** and assign [**Paper 4:** Stable Fluids](https://dl.acm.org/doi/10.1145/311535.311548)
| 5    | Presentations for **Paper 4** and assign [**Paper 5:** Velocity-based shock propagation for multibody dynamics animation](https://dl.acm.org/doi/10.1145/1243980.1243986)
| 6    | Presentations for **Paper 5** and assign [**Paper 6:** Discrete Elastic Rods](http://www.cs.columbia.edu/cg/pdfs/143-rods.pdf)
| 7    | Presentations for **Paper 6** and assign [**Paper 7:** WRAPD: Weighted Rotation-aware ADMM for Parameterization and Deformation](https://www-users.cse.umn.edu/~brow2327/wrapd/)
| 8    | Presentations for **Paper 7** and assign [**Paper 8:** ADD: Analytically Differentiable Dynamics for Multi-Body Systems with Frictional Contact](http://crl.ethz.ch/papers/Geilinger20ADD.pdf)
| 9    | Presentations for **Paper 8** and assign [**Paper 9:** Fast Linking Numbers for Topology Verification of Loopy Structures](https://graphics.stanford.edu/papers/fastlinkingnumbers/)
| 10   | Presentations for **Paper 9** and assign [**Paper 10:** Kelvin Transformations for Simulations on Infinite Domains](https://cseweb.ucsd.edu//~viscomp/projects/SIG21KelvinTransform/)
| 11   | Presentations for **Paper 10**
| 12   | Surprise session

[Academic Honesty (required reading)](#academic-honesty)

## Grading

| % | Item |
| ----: | :-------------- |
| 15% | Presentations
| 10% | Reviewing 
| 15% | Blogger
| 25% | Implementation
| 30% | Final Project 
| 5%  | Participation 

## Lateness Policy

Project is **_due by 11:59pm_** on the due date.

0.007% off for every minute late.

### Academic Honesty

Academic honesty is a very serious matter and can result in very serious
consequences. Note that academic offences may be discovered and handled
retroactively, even after the semester in which the course was taken for credit.
This is a challenging class aimed at teaching you the fundamentals of computer
graphics. You wont learn much if you cheat but you might get a good grade if you
get away with it. If all you want is a good grade take an easier class where you
wont have to cheat!

For purposes of this class, academic dishonesty is defined as:

- Any attempt to pass off work on a test that didn't come straight out of your
  own head.
- Any collaboration on written or programming assignments (its ok to share ideas
  on programming assignments but the code MUST be your own) in which the
  collaborating parties don't clearly and prominently explain exactly who did
  what, at turn-in time.
- Any activity that has the effect of significantly impairing the ability of
  another student to learn. Examples here might include destroying the work of
  others, interfering with their access to resources (e.g., digital cameras), or
  deliberately providing them with misleading information.

### Email & GitHub Issues

- The GitHub issues are for answering questions about class or about the assignments. The TAs will be monitoring the posted issues.
- Appropriate use of the issues: clarifications on assignment, on lecture
  material, general concerns about the course, or other remarks that are
  appropriate for all students to see/participate in.
- Do NOT broadcast pieces of your code or answers to written assignments to the issues page. Specific or general implementation questions whose answer
  would benefit all students in the class are appropriate. However: the bulletin
  board is NO replacement for the tutorial hour. That should be the main forum
  for asking/answering questions of this sort.
- Questions of the form "I cannot find the problem with my code; here it is, can
  you help me" are unlikely to be replied, so don't count on it. If you have a
  question with code, take it to the TA office hours or to the tutorials.

