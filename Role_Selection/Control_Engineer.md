# Mapping/Localization Engineer
___
Autonomous Systems Interview Practice project


So, you're interested in a role as a Control Engineer? Great choice! Below, you will find one general question, as well as a list of Perception/Sensor Engineer-specific questions. To complete the project, you'll need to complete the general question along with three questions from the role-specific list, with at least one of them needing to be marked as requiring code with [Code]. While it isn't required to use code in the other two, we highly encourage you to either code, diagram or draw any relevant information for your answers in the other questions as well.

Make sure not to just select questions in areas you are most comfortable with! You likely won't get so lucky in a real interview situation.

## Required question

Explain a recent project you've worked on. Why did you choose this project? What difficulties did you run into this project that you did not expect, and how did you solve them?

## Control Engineer questions

Pick three of these questions, including at least one marked [Code].

- What are some of the typical variables of motion that kinematic models often simplify or ignore in their calculations? In what situations might these models therefore fail, and how can you improve upon these types of models?


- An important consideration in control is the latency in between the calculation of a control movement and the actuation of said control movement. Given a 100ms delay, how would you account for this your controller?


- What is the bicycle model in kinematics? Make a diagram of it. How does this compare to the movement of a four-wheeled vehicle like a car, and why is it often sufficient in many cases to approximate the movement of a more complex vehicle?


- Describe how you could implement the Ackerman steering model for a four-wheeled robot, including describing the model itself. How does this compare to a steering model in which two of the wheels are turned at the same angle with respect to an axle? Is this model an approximation of ideal steering conditions?


- What is the differential drive model, and why is it particularly popular for robotics applications? How does this differ from a modern car?


- What are the primary differences between kinematic and dynamic models of control? In what situations are these types of models most similar, and when do they diverge? Include in your answer any necessary diagrams that may help to illustrate your point.


- Hans B. Pacejka produced tire models colloquially referred to as the “magic formula” for tire models. Explain the basis of his models, as well as how you would implement one of these in a robotics system. What forces must be considered in utilizing one of his tire models?


- Explain the concepts of slip angles and slip ratios with regards to tires. How would you account for these within a control model? In what situations would accounting for these be unimportant?


- [Code] How does a linear-quadratic regulator (LQR) differ from PID control? Does it require a given time horizon, and does it require continuous or discrete timesteps? Code an instance of a LQR given your own selection of time horizon and discrete/continuous, assuming you otherwise already have any necessary inputs.


- Suppose you built a line following robot. You created a line on the ground, put the robot on the line, but the robot oscillates back and forth rapidly once it is on the line. How would you fix this?


- Explain how model predictive control can be used to optimize control actuations over a given time horizon. What additional information can MPC take into account that PID control typically does not? How do you determine the constraints involved with MPC?


- [Code] In PID Control, if a robot is in between two waypoints of a desired trajectory, how is the cross track error determined? Code a method to calculate this. What information does this require from any other subsystems outside of the control system, and how would you account for any potential noise in that data (or alternatively, do you need to)?

### Relevant Nanodegree Projects

---
If you put these on your resume, make sure you know your code and the topic in-depth before the interview!

- Self-Driving Car Engineer - PID Control, Model Predictive Control (MPC)

- Flying Car Engineer - Building A Controller, Fixed-Wing Control

- Robotics Software Engineer - Robotic Arm: Pick and Place


For bonus points (both in getting the interview and for use in your interview), use the skills you learned in the above projects toward a novel solution to another problem in this area!