# Race-Car-Simulation

## Problem Statement
The goal of this mini project is to develop a race car simulation using the GLUT (OpenGL Utility Toolkit) library for computer graphics. The simulation should provide users with an immersive experience of driving a race car on a virtual racetrack. The project requires designing and implementing a visually appealing racetrack with varying terrain and obstacles Different camera views, such as a first-person view, third-person view, and top-down view, should be provided to enhance the user experience. <br>

## Hardware Requirement 
•	Minimum of 2GB of main memory<br>
•	Minimum of 3GB of storage<br>
•	Keyboard<br>
•	Mouse<br>
•	Display Unit<br>
•	Dual-Core or AMD with minimum of 1.5GHz speed	<br>

## Software Requirement
•	Windows – XP/7/8/10<br>
•	Microsoft Visual Studio C/C++ 7.0 and above versions<br>
•	OpenGL Files<br>
•	DirectX 8.0 and above versions<br>
Header Files:<br>
•	glut.h<br>
Object File Libraries:<br>
•	glut32.lib<br>
DLL files:<br>
•	glut32.dll <br>

## User-defined-functions
1.	cone():- This function generates a cone shape. Example usage: cone();<br>
2.	track(float R1, float R2):- This function draws the track using two radii values. Example usage: track(600, 540);<br>
3.	cylinder(float r, float l):- This function generates a cylinder with a given radius and length. Example usage: cylinder(3, 15);<br>
4.	tree(float a, float b):- This function generates a tree with a cone-shaped top. Example usage: tree(700, 700);<br>
5.	tree2(float a, float b):- This function generates a tree with a sphere-shaped top. Example usage: tree2(800, 800);<br>
6.	alloy(float R1, float R2):- This function generates the sides of the tires using two radii values. Example usage: alloy(2, 1.4);<br>
7.	actall(float R1, float R2):- This function draws the spokes of the wheel using two radii values. Example usage: actall(1.4, 0.8);<br>
8.	circle(float R):- This function draws a circle with a given radius. Example usage: circle(0.8);<br>
9.	rect(float p[], float q[], float r[], float s[]):- This function draws a quadrilateral using four sets of coordinates. Example usage: rect(p1, s1, q1, r1);<br>
10.	driver():- This function generates the car driver using various shapes. Example usage: driver();<br>
11.	scenery():- This function generates the scenery using other functions like track(), tree(), and tree2(). Example usage: scenery();<br>
12.	tri(float a[], float b[], float z[]):- This function draws a triangle using three sets of coordinates. Example usage: tri(p1, q1, r1);<br>
13.	wheels():- This function generates the wheels along with the axle using other functions like cylinder(), alloy(), and actall(). Example usage: wheels();<br>
14.	chassis():- This function generates the chassis of the car using various shapes and functions. Example usage: chassis();<br>

## Keyboard Interaction
Play the car animation:- After running the program, you should see a window displaying the car animation. Use the following keys to control the animation:<br>
•	Press 'w' or 's' to move the car forward or backward, respectively.<br>
•	Press 'a' or 'd' to rotate the car left or right, respectively.<br>
•	Press 'r' to reset the car to its initial position.<br>
•	Press 'q' or 'Esc' to quit the program.<br>
Interact with the animation:- Use the keyboard keys as mentioned above to control the car's movement and rotation. Experiment with different key combinations to see how the car behaves.<br>

## Screenshots
Initial bootup page of the application which allows user to select from displayed options:<br>

![image](https://github.com/alfiyasama/Race-Car-Simulation/assets/121941528/0c38c16f-4753-4a6b-951a-dfc773e28767)

Back view of Race Car which is displayed when user chooses option G or g to start or continue:<br>

![image](https://github.com/alfiyasama/Race-Car-Simulation/assets/121941528/cf276196-304c-4950-8859-771658935ff4)

back view of Race Car which is displayed when user chooses option B or b:<br>

![image](https://github.com/alfiyasama/Race-Car-Simulation/assets/121941528/17848371-c404-44e8-b27c-26c74f7981df)

back view of Race Car which is displayed when user chooses option B or b and then E or e to Stop simulation:<br>

![image](https://github.com/alfiyasama/Race-Car-Simulation/assets/121941528/7e137a90-885f-4004-87a8-eb476b2abc76)

side view of Race Car which is displayed when user chooses option S or s:<br>

![image](https://github.com/alfiyasama/Race-Car-Simulation/assets/121941528/f6b17065-4709-4c8d-8155-b2b655e7d839)

side view of Race Car which is displayed when user chooses option S or s and then E or e to Stop simulation:<br>

![image](https://github.com/alfiyasama/Race-Car-Simulation/assets/121941528/524f2331-fd4d-4053-b3ba-be1312676de7)

front view of Race Car which is displayed when user chooses option F or f:<br>

![image](https://github.com/alfiyasama/Race-Car-Simulation/assets/121941528/fcb62fbb-7582-493c-a6bd-312637d9c6c2)

side view of Race Car which is displayed when user chooses option F or f:<br>

![image](https://github.com/alfiyasama/Race-Car-Simulation/assets/121941528/a1970100-3889-4cbb-84e4-d3a4e8ef036a)
