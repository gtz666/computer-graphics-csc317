# Computer Graphics CSC317 _Winter 2021_

![_image courtesy Tim Jeruzalski_](images/bunny-rigid-body.gif)

**CSC317H1F LEC 0101 2001** Monday 11:00-13:00, [UC 140](https://map.utoronto.ca/?id=1809#!m/494517)
Tutorial: Wednesday 11:00-12:00, [UC 140](https://map.utoronto.ca/?id=1809#!m/494517)
 
**CSC317H1F LEC 0201 2101** Monday 15:00-17:00, [AH 400](https://map.utoronto.ca/?id=1809#!m/494578)
Tutorial: Wednesday 16:00-17:00, [AH 400](https://map.utoronto.ca/?id=1809#!m/494578)

Prof. [Karan Singh](https://www.dgp.toronto.edu/~karan/)
karan@dgp.toronto.edu  
  
Office hours: BA 5258, Mondays 13:00-15:00 or by appointment
															
- [Course Overview](#course-overview)
- [Required Textbook](#required-textbook)
- [Lecture Schedule](#lecture-schedule)
- [Marking Scheme](#marking-scheme)
- [Assignment Policies](#assignment-policies)

## Course Overview

This course introduces the basic concepts and algorithms of computer graphics.
It covers the basic methods needed to model and render 3D objects, including
much of the following: graphics displays, basic optics, affine and
perspective transformations, windows and viewports, visibility,											
illumination and reflectance models, parametric representations, curves and surfaces, texture mapping, graphics
hardware, ray tracing, graphics toolkits, animation systems.


**Prerequisites:** C/C++ Programming, Linear Algebra, Calculus,([course
codes](https://artsci.calendar.utoronto.ca/course/csc317h1).


## Discussion Board

Please post your questions about the lectures, readings, and assignment due dates on the
[Quercus discussion
board](https://q.utoronto.ca/courses/280982/discussion_topics). We will monitor
this board and attempt to answer questions as they appear. Near deadlines
responses may take longer, so please start assignments early. If your question
is not being answered, you may ask it again at the tutorial or office hours.

For questions specific to each assignment, please post your questions as a GitHub issue
on the assignment repository.


## Required Textbook


![The Book.](https://www.cs.cornell.edu/~srm/fcg4/K22616_cover-300.jpg)

This class involves  **_required [reading](https://en.wikipedia.org/wiki/Reading)_** from:

[_Fundamentals of Computer Graphics, Fourth (or Fifth)
Edition_](https://www.cs.cornell.edu/~srm/fcg4/), Steve Marschner, Peter Shirley,
et al. 2015.

Digital e-book are available at [CRC
Press](https://www.routledge.com/Fundamentals-of-Computer-Graphics/Marschner-Shirley/p/book/9780367505035).


## Marking Scheme

| % | Item |
| ----: | :-------------- |
| 9% | Assignment 1 | 
| 9% | Assignment 2 | 
| 9% | Assignment 3 | 
| 9% | Assignment 4 | 				  
| 9% | Assignment 5 | 
| 9% | Assignment 6 | 
| 9% | Assignment 7 | 
| 9% | Assignment 8 | 
| 12% | 4 Quercus quizzes |
| 16% | Take home term test |

## Lecture Schedule

_Assignment dates still based on Fall offering. Will be updated soon._

| Week | Topic / Event | Slides | Videos
| ---- | :------------ | ------ | ------
| 1 (12/09)   | Introduction, Raster Images(Chapter 3)  [Assignment 1 (Raster Images) due 19/09](https://github.com/karansher/computer-graphics-raster-images) (for students on the waitlist: zip your `src` directory and send to the TA email address (csc317tas@cs.toronto.edu) so that you get a timestamp) | [intro](https://github.com/karansher/317-lectures/blob/main/lecture0.pdf)
 [raster](https://github.com/karansher/317-lectures/blob/main/lecture1.pdf) |
| 2 (19/09)   | Ray Casting(Sections 4.1-4.4)[Assignment 2 (Ray Casting) due 26/09](https://github.com/karansher/computer-graphics-ray-casting) | [raycast](https://github.com/karansher/317-lectures/blob/main/lecture2.pdf) | 
| 3 (26/09) | Ray Tracing(Sections 4.5-4.9) Quiz1 | [Assignment 3 (Ray Tracing) due 03/10](https://github.com/karansher/computer-graphics-ray-tracing) | [raytrace slides](https://github.com/karansher/317-lectures/blob/main/lecture3.pdf) | 
| 4 (03/10) | Bounding Volume Hierarchy(Section 12.3) | [Assignment 4 (Bounding Volume Hierarchy) due 10/10](https://github.com/karansher/computer-graphics-bounding-volume-hierarchy) | [bounding volume](https://github.com/karansher/317-lectures/blob/main/lecture4.pdf)  | 
| 5  (17/10)  | Meshes(Section 12.1 & skim Chapter 11) | [Assignment 5 (Meshes) due 16/02](https://github.com/karansher/computer-graphics-meshes) | | 
| 6  (24/10)  | Shading(Review Chapters 6,7,8.1,8.2 & Read Sections 11.4,11.5 & 17)  Quiz2 | Object-based Rendering Transformations and Projections [Assignment 6 (Shader Pipeline) assigned due 12:00 09/03](https://github.com/karansher/computer-graphics-shader-pipeline) | |
| 7  (31/10)  | Real-time graphics pipeline, review for mid-term
| **Thursday, March 3** | 24-hour take-home exam due 12:00 04/03 (11% of grade) _tentative date_
| 8  (14/11)  | TBD
| **Monday, March 14** | Drop date (consider if current grade is <50%)
| 9  (21/11)  | [Assignment 7 (Kinematics) due 12:00 noon 16/3](https://github.com/karansher/computer-graphics-kinematics) (**Note:** inverse kinematices `I,i` related portion only worth 10%)
| 10 (28/11)  | [Assignment 8 (Mass-Spring Systems) due 12:00 noon 31/3](https://github.com/karansher/computer-graphics-mass-spring-systems) <!-- Course Evaluations Nov. 20 - Dec 7 --> |
| 11 (5/12)  | The future of Computer Graphics
| 12 (8/12)  | _Study for exam next week_.
| Final | Final exam (20% of grade)



## Reading Schedule

| Week | Topic / Event |
| ---- | :------------ |
| 1    | Raster Images: Chapter 3 [intro slides](https://github.com/karansher/317-lectures/blob/main/lecture0.pdf) ,[raster slides](https://github.com/karansher/317-lectures/blob/main/lecture1.pdf) , [recording]
| 2   | Ray Casting: Sections 4.1-4.4 [raycast slides](https://github.com/karansher/317-lectures/blob/main/lecture2.pdf) , [recording]
| 3   | Ray Tracing: Sections 4.5-4.9 [raytrace slides](https://github.com/karansher/317-lectures/blob/main/lecture3.pdf) ,  [recording]
| 4   | Bounding Volume Hierarchy: Section 12.3 [bounding volume slides](https://github.com/karansher/317-lectures/blob/main/lecture4.pdf) ,
| 5  | Meshes: Section 12.1 & skim Chapter 11 [mesh slides](https://github.com/karansher/317-lectures/blob/main/lecture5.pdf)
| 8  | Shading: Review Chapters 6,7,8.1,8.2 & Read Sections 11.4,11.5 & 17 [transforms and shading slides](https://github.com/karansher/317-lectures/blob/main/lecture6.pdf)
| 9  | Kinematics: Sections 15.1-15.5 & 16.1-16.4 (https://github.com/karansher/317-lectures/blob/main/lecture7.pdf)
| 10  | Mass Spring Systems: Section 16.5 & ["Fast Simulation of Mass-Spring Systems" [Tiantian Liu et al. 2013]](http://graphics.berkeley.edu/papers/Liu-FSM-2013-11/Liu-FSM-2013-11.pdf)(https://github.com/karansher/317-lectures/blob/main/lecture8.pdf)
| 11| Advanced Topics 🏆 Showcase 🏆(https://github.com/karansher/317-lectures/blob/main/creative-vis-comm-csc317.pdf)
| 12| Review(https://github.com/karansher/317-lectures/blob/main/lecture-review.pdf)



[Academic Honesty (required reading)](#academic-honesty)

![_image courtesy Gavin Barill (class of 2017)_](images/gavin-barill-snowglobe.jpg)

## Assignment Policies

Assignments must be submitted electronically, using [MarkUs](https://markus.teach.cs.toronto.edu/2022-01).

Code that you submit to us must work on the CS Teaching Lab machines in order to earn credit.
																	   
																				
																			  
																				
																				
				   

0.007% off for every minute late.

All assignments must be completed individually.
		   
																				
																		
																			 
						
																			
																			  
																				
														  

### Academic Honesty

Any code must belong to the student submitting it. Submitted assignments will
be automatically analyzed to identify suspicious levels of code similarity.
Consequences of committing an academic offence can be severe.
																		
																		
													 
																			   
																  
																	   
																			  
											  
																				
																			  
																		 

By enrolling in this course, students acknowledge that they have read and understand the University of Toronto's definitions and policy on Academic Integrity. 
</article>
