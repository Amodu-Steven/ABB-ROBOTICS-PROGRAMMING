# ABB-ROBOTICS-PROGRAMMING.



 ### [YouTube Demonstration](https://www.youtube.com/watch?v=nK9CvXnekrM)

<h2>Description</h2> This project involves programming an ABB IRB 1200 industrial robot to perform automated drawing tasks using ABB's RobotStudio simulation software. The robot was programmed to draw geometric shapes (dodecagon, nonagon, square) and write text ("SALFORD" and "AMODU") on multiple workpieces using a pen tool attached to the end effector. <br /><h2>Languages and Utilities Used</h2>

<b>RAPID</b> (ABB's proprietary robotics programming language)

<b>RobotStudio</b>

<b>FlexPendant Interface</b>

<h2>Environments Used </h2>
<b>ABB RobotStudio 6.04.00.01</b>

<b>IRB 1200 5kg/0.9m Robot</b>

<b>SolidWorks</b> (for CAD components)
<h2>Program walk-through:</h2><p align="center"> Robot Station Setup: <br/> <img src="media/image16.png" height="80%" width="80%" alt="Robot Station Setup"/> <br /> <br /> Program Structure on FlexPendant: <br/> <img src="media/image18.png" height="80%" width="80%" alt="Program Routines"/> <br /> <br /> Motion Types Implementation: <br/> - <b>Move J</b>: Joint movement for positioning between points<br/> - <b>Move L</b>: Linear movement for straight-line drawing<br/> - <b>Move C</b>: Circular movement for curved paths<br/> <br /> Coordinate Systems Configuration: <br/> <img src="media/image5.png" height="80%" width="80%" alt="Coordinate Systems"/> <br /> <br /> Zone Data Settings for Path Precision: <br/> <img src="media/image4.png" height="80%" width="80%" alt="Zone Data Configuration"/> <br /> <br /> FlexPendant Controls: <br/> <img src="media/image25.png" height="80%" width="80%" alt="FlexPendant Interface"/> <br /> <br /> Final Output - Drawn Shapes and Text: <br/> <img src="media/image26.emf" height="80%" width="80%" alt="Robot Drawing Results"/> </p><h2>Key Features</h2>
<b>Modular Programming</b>: Separate routines for shapes, text, and names

<b>Precision Control</b>: Implemented zone data (Fine, Z0, Z1) for accurate path following

<b>Multiple Motion Types</b>: Utilized Move J, Move L, and Move C commands appropriately

<b>Tool & Work Object Setup</b>: Proper configuration of TCP and coordinate systems

<b>User Interface</b>: Interactive program selection on FlexPendant

<h2>Skills Demonstrated</h2>
Industrial robot programming and simulation

Path planning and motion control

Coordinate system management

Offline programming with RobotStudio

Robotic cell setup and calibration

<br /> <br />
