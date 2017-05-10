 # Peaucellier Exact Straight Line Mechanism

# <a name="1"></a>Introduction
The main objective of this project is to create the Peaucellier Straight line mechanism and to analyse its working principles. This project would not have been possible without the mentorship and support of Dr. Pannirselvam, our Mechanics of Machines-I professor, Guru sir and Kennedy sir who helped us extensively throughout the building process at the Dynamics lab.
# Contents
1. [Introduction](#1)
2. [What is Peaucellier Mechanism?](#2)
3. [How did we go about doing this project?](#3)
4. [Why is it a straight line mechanism?](#4)
5. [How did we fabricate the mechanism?](#5)
6. [References](#6)
# <a name="2"></a>What is Peaucellier Mechanism?
It is a double rocker mechanism in which the end effector traverses a straight line when the rocker is driven using an actuator. This is a mechanism because one of its links is grounded.
# <a name="3"></a>How did we go about doing this project?
We followed an organised methodology for the smooth execution of the project. We built upon the project in the following phases:
1. In the first phase, we researched about the project using online resources and textbooks.
2. In the second phase, we approached the project analytically using mathematical principles involved in the working of the mechanism.
3. In the third phase, we began building the basic model for the mechanism using CAD tools.
4. In the fourth phase, we built the mechanism physically in the Dynamics lab.
# <a name="4"></a>Why is it a straight line mechanism?
When we perform position analysis on the mechanism, we found out that the X-component of the end-effector is independant of the angle of the driven rocker, hence always remains constant.

The following image shows the schematic of the mechanism:

![Page 1](https://github.com/Rajiv2605/Peaucellier-Mechanism/blob/master/mechanism_screenshot.PNG)

As shown in the above image, the longer links are of equal lengths and all the shorter links are of equal lengths. Hence, they form congruent triangles using which forms the basis of calculation for the position analysis. After this, we form a quadratic equation whose roots are the link lengths O<sub>4</sub>P and O<sub>4</sub>Q.

Now, using Cosine Rule, we proceed further in our calculations from which we get to an expression where the X-component of the end-effector is only a function of the link lengths which are constants(as all are rigid). Hence, the mechanism always moves in a straight line.

The following image shows the calculations involved in detail:

![Page 2](https://github.com/Rajiv2605/Peaucellier-Mechanism/blob/master/analysis_2.png)

You can refer to the link provided at the References section for a clearer view of the calculations involved in the mechanism.

# <a name="5"></a>How did we fabricate the mechanism?
Firstly, we designed our model in CAD with the dimensions of 10 cm and 4 cm. The following image shows our CAD model:

![CAD](https://github.com/Rajiv2605/Peaucellier-Mechanism/blob/master/cad.PNG)

We used the following components to build the mechanism:
1. Steel sheet(0.8 mm thick)
2. An A4 sized wooden base
3. Revolute joints
4. Rivets

All components were procured from the Dynamics lab at the Mechanical Department. Firstly, we marked the link lengths on the steel sheet and cut them out. We then made the node holes and connected the joints using revolute joints. Then, we drilled holes on the wooden base on which the mechanism was grounded using rivets.

The following image shows our final model:

![Final Model](https://github.com/Rajiv2605/Peaucellier-Mechanism/blob/master/actual_2.png)

You can check our mechanism videos in the link provided below and click "View Raw":
1. [CAD video](https://github.com/Rajiv2605/Peaucellier-Mechanism/blob/master/CAD%20video.mp4)
2. [Actual mechanism video](https://github.com/Rajiv2605/Peaucellier-Mechanism/blob/master/Final%20mechanism%20video.mp4)

# <a name="6"></a>References:
First of all, we would like to thank all the Faculty and Staff who played a vital role in mentoring us throughout the project without whom the project would not have been possible. Also, we used the following resources:
1. [Position analysis of Peaucellier Mechanism](http://me.lsu.edu/~ram/TEACHING/kinematics/Peaucellier.pdf)
2. [Kinematics and Dynamics of Machinery, by RL Norton](https://www.amazon.com/Design-Machinery-Robert-L-Norton/dp/0071236716)
