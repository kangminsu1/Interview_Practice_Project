# Mapping/Localization Engineer
___
Autonomous Systems Interview Practice project


So, you're interested in a role as a Mapping/Localization Engineer? Great choice! Below, you will find one general question, as well as a list of Perception/Sensor Engineer-specific questions. To complete the project, you'll need to complete the general question along with three questions from the role-specific list, with at least one of them needing to be marked as requiring code with [Code]. While it isn't required to use code in the other two, we highly encourage you to either code, diagram or draw any relevant information for your answers in the other questions as well.

Make sure not to just select questions in areas you are most comfortable with! You likely won't get so lucky in a real interview situation.

## Required question

Explain a recent project you've worked on. Why did you choose this project? What difficulties did you run into this project that you did not expect, and how did you solve them?

## Mapping/Localization Engineer questions

Pick three of these questions, including at least one marked [Code].

- How does Simultaneous Localization and Mapping (SLAM) differ from other localization approaches? What are the benefits and detriments of this over other approaches?


- [Code] Describe how a particle filter works, where it is useful, and how it performs against similar algorithms. Code an example of how you update the weights of the particles between steps.


- Describe the differences between dense mapping vs. sparse mapping. In what situations would you prefer the use of one over the other?


- [Code] Sparse mapping involves the use of “landmarks” in your map to assist with determining where your robot is in the environment. Given a set of detections and a map of landmarks (you may create a test set of these, which should not exactly match up), code a method to estimate where your robot is.


- Image-based localization concerns utilizing only camera images in order to determine location in an environment. Explain a method to implement such a system, as well as what the strengths and weaknesses of such an approach are.


- [Code] Why would you utilize an inertial measurement unit (IMU) in conjunction with GPS in localizing a moving robot? Implement a basic system that uses these together for accurate localization.


- [Code] How does GNSS+RTK (real-time kinematic) allow for higher accuracy than standard GPS systems? Implement a basic system that shows how this technique works.


- [Code] You have a robot in an environment with certain known landmarks, but its current position is unknown. Code a method to detect its new location over time when the robot has perfect movement and noisy sensor data. What would you need to change in this function if the robot's motion is also noisy?

### Relevant Nanodegree Projects

---
If you put these on your resume, make sure you know your code and the topic in-depth before the interview!

- Self-Driving Car Engineer - Kidnapped Vehicle
  
- Flying Car Engineer - Estimation
  
- Robotics Software Engineer - Where Am I?, Map My World Robot

For bonus points (both in getting the interview and for use in your interview), use the skills you learned in the above projects toward a novel solution to another problem in this area!