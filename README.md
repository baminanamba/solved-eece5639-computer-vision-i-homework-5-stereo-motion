Download Link: https://assignmentchef.com/product/solved-eece5639-computer-vision-i-homework-5-stereo-motion
<br>
<ol>

 <li>Estimate the accuracy of the simple stereo system we discussed in class (identical cameras, translatedfrom each other with coplanar image planes), assuming that the only source of noise is the localization of corresponding points in the two images. Hint: Take the partial derivatives of <em>Z </em>with respect to <em>x</em>, <em>T</em>, and <em>f</em>. Discuss the dependence of the error in depth estimation as a function of the baseline width and the focal length.</li>

 <li>(Old exam problem) Consider a room 10 × 4 × 4 with world coordinate system (<em>X,Y,Z</em>) as shown in Figure 1. The room has a stereo rig with two identical cameras with focal length <em>f </em>= 1. Camera 1 is mounted on a wall such that its center of projection is located at the point <em>C</em>1 with <strong>world coordinates </strong>(10<em>,</em>1<em>,</em>3). Camera 2 is mounted on a tripod and it has its center of projection located at the point <em>C</em>2 with <strong>world coordinates </strong>(7<em>,</em>1<em>,</em>2). The optical axes of both cameras are parallel to the floor of the room, the image axes <em>X</em><sub>1 </sub>and <em>X</em><sub>2 </sub>are parallel to the world axis <em>Y </em>and the image axes <em>Y</em><sub>1 </sub>and <em>Y</em><sub>2 </sub>are parallel to the world axis <em>Z </em>as shown in Figure 1. The image plane of each camera is located at <em>Z<sub>i </sub></em>= 1, <em>i </em>= 1<em>,</em></li>

</ol>

Figure 1: Room with a stereo rig.

<ul>

 <li>Find the transformation from the World to the Camera 1 coordinate system.(b) Find the transformation from the World to the Camera 2 coordinate system.</li>

</ul>

(c) A feature matching algorithm run on an stereo pair from the two cameras has found that a point <em>p</em><sub>1 </sub>in the image from Camera 1 and a point <em>p</em><sub>2 </sub>in the image from Camera 2 are images of the same 3D point <em>P</em>. The point <em>p</em><sub>1 </sub>has <strong>Camera 1 coordinates </strong>(−3<em>/</em>10<em>,</em>1<em>/</em>10<em>,</em>1) and the point <em>p</em><sub>2 </sub>has <strong>Camera 2 coordinates </strong>(−3<em>/</em>7<em>,</em>2<em>/</em>7<em>,</em>1). Find the <strong>world coordinates </strong>of the 3D point <em>P </em>with images <em>p</em><sub>1 </sub>and <em>p</em><sub>2</sub>.

1

<ol start="3">

 <li>Consider an optical system with its camera coordinate system coinciding with the world coordinatesystem. The camera has unit focal length. At time <em>t </em>= 0, a point is located at (<em>X,Y,Z</em>) = (30<em>,</em>60<em>,</em>10) and it is moving with a constant speed (<em>u,v,w</em>) = (−5<em>,</em>−10<em>,</em>−1) towards the observer.

  <ul>

   <li>Determine the location of the object at the image at time <em>t </em>= 0. (b) Determine the image coordinates of the focus of expansion (FOE) (c) Determine the time of the object collision with the observer.</li>

  </ul></li>

 <li>(Old exam problem) Consider an imaging system with a unit focal length with its image plane located at <em>z </em>= 1 and with view direction towards the positive Z axis (The center of projection is located at (0<em>,</em>0<em>,</em>0) ) An object point is located at (10<em>,</em>20<em>,</em>0) at time <em>t </em>= 0, and it is moving with constant acceleration. The initial velocity of the point is (0<em>,</em>0<em>,</em>0). The point is observed at (50<em>,</em>100<em>,</em>20) at time <em>t </em>= 2 . Will the optical flow vectors corresponding to this point meet at a point (focus of expansion)? If yes, what are the coordinates of this point? If not, what is the locus of the FOE (curve on which the FOE moves over time)?</li>

</ol>

2