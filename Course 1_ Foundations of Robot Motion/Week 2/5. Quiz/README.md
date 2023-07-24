## Chapter 2.3 through 2.5, Configuration Space

### Question 1:
The tip coordinates for the two-link planar 2R robot of figure below are given by<br>

(In other words, link 1 has length 1 and link 2 has length 2.)  The joint angles have no limits. 
Which of the following best describes the shape of the robot's workspace (the set of locations the endpoint can reach)?<br>
&#10007; A circle and its interior.<br>
&#10007; A circle only (not including the interior).<br>
&#10003; Annulus or ring (the area between two concentric bounding circles).<br>

--------------------------------------------------------------------------------------------------------------------------------------------------------
### Question 2:
The chassis of a mobile robot moving on a flat surface can be considered as a planar rigid body.  Assume that the chassis is 
circular, and the mobile robot moves in a square room.  Which of the following could be a mathematical description of the C-space 
of the chassis while it is confined to the room? (See Chapter 2.3.1 for related discussion.)<br>
&#10003; [a,b] x [a,b] x S1<br>
&#10007; [a,b] x R1 x S1<br>
&#10007; [a,b] x [a,b] x R1<br>
&#10007; R2 x S1<br>

--------------------------------------------------------------------------------------------------------------------------------------------------------
### Question 3:
Which of the following is a possible mathematical description of the C-space of a rigid body in 3-dimensional space?<br>
&#10007; R3 x S3<br>
&#10007; R3 x T3<br>
&#10007; R3 x T2 x S1<br>
&#10003; R3 x S2 x S1<br>

--------------------------------------------------------------------------------------------------------------------------------------------------------
### Question 4:
A spacecraft is a free-flying rigid body with a 7R arm mounted on it.  The joints have no joint limits. Give a mathematical 
description of the C-space of this system.  (See Chapter 2.3.1 for related discussion.)<br>
&#10007; R3 x T10<br>
&#10003; R3 x S2 x T8<br>
&#10007; R3 x S3 x T7<br>
&#10007; R4 x S2 x T7<br>

--------------------------------------------------------------------------------------------------------------------------------------------------------
### Question 5:
A mobile robot is moving on an infinite plane with an RPR robot arm mounted on it. The prismatic joint has joint limits, but the 
revolute joints do not. Give a mathematical description of the C-space of the chassis (which can rotate and translate in the plane) 
plus the robot arm.  (See Chapter 2.3.1 for related discussion.)<br>
&#10007; R2 x S2 x S1 x [a,b]<br>
&#10007; R2 x S3 x [a,b]<br>
&#10003; R2 x T3 x [a,b]<br>
&#10007; R2 x T3<br>

--------------------------------------------------------------------------------------------------------------------------------------------------------
### Question 6:
Determine whether the following differential constraint is holonomic or not (nonholonomic).  See the example in Chapter 2.4.<br>
&#10007; Holonomic<br>
&#10003; Nonholonomic<br>

--------------------------------------------------------------------------------------------------------------------------------------------------------
### Question 7:
The task is to carry a waiter's tray so that it is always horizontal (orthogonal to the gravity vector), but otherwise free to move 
in any other direction. How many degrees of freedom does the task space (the C-space of a horizontal tray) have?  (Enter an integer number.)<br>
- Answer = 4

