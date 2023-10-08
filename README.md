${\color{#717d7e}table of contents}$

${\color{#f5cba7}side note}$

---
# Vision-Only Robot Navigation in a Neural Radiance World

### Abstract Highlights
- We propose an algorithm for navigating a robot through a 3D environment represented as a NeRF using only an onboard RGB camera for localization. 


- trajectory optimization algorithm that avoids collisions with high-density regions in the NeRF based on a discrete time version of differential flatness that is amenable to constraining the robot's full pose and control inputs.


- We also introduce an optimization based filtering method to estimate 6DoF pose and velocities for the robot in the NeRF given only an onboard RGB camera.


### Introduction
- ${\color{#717d7e}Planning\ in\ SDF}$
- ${\color{#717d7e}Deep\ learning\ geometric\ representation\ called\ NeRFs}$
- $\textcolor{#f5cba7}{Optimal\ control\ remains\ a\ fundamental\ tool\ in\ robotic\ motion\ planning}$


Combines trajectory planner and the filter in a receding horizon loop to provide a full navigation pipeline for a robot to dynamically maneuver through an environment using only an RGB camera for feedback.









---


### Testing
<style>H1{color:Blue;}asdasdasd</style>

```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
$\textcolor{#f5cba7}{blah blah blah}$
