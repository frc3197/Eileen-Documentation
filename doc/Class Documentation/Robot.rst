===============
frc.robot.Robot
===============
The class frc.robot.Robot 
(inheriting methods from wdu.wpi.first.wpilibj.TimedRobot) 
is the main class that contains the functions that initializes the robot.

Subsystems should be initialized here.

Example:: 

    public static SubsystemBoi subsystemBoi = new SubSystemBoi();

Network tables should also be initialized here.

Example:: 

    public static NetWorkTableInstance ntInst = NetworkTableInstance.getDefault();
    public static NetworkTable table;

------------
Dependencies
------------

- `edu.wpi.first.wpilibj.TimedRobot <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/TimedRobot.html>`_
- `edu.wpi.first.wpilibj.command.Scheduler <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/command/Scheduler.html>`_
- `edu.wpi.first.networktables.NetworkTable <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/networktables/NetworkTable.html>`_
- `edu.wpi.first.networktables.NetworkTableInstance <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/networktables/NetworkTableInstance.html>`_

--------
Commands
--------

~~~~~~~~~~~~~~~~~~~~~~~
public void robotInit()
~~~~~~~~~~~~~~~~~~~~~~~
Initializes the Robot.

~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void robotPeriodic()
~~~~~~~~~~~~~~~~~~~~~~~~~~~
Code that runs periodically goes here.

~~~~~~~~~~~~~~~~~~~~~~~~~~
public void disabledInit()
~~~~~~~~~~~~~~~~~~~~~~~~~~
Initializes disabled mode.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void disabledPeriodic()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Code that runs periodically while the robot is disabled goes here.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void autonomousInit()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Initializes autonomous mode.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void autonomousPeriodic()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Code that runs periodically while the robot is in autonomous goes here.

~~~~~~~~~~~~~~~~~~~~~~~~
public void teleopInit()
~~~~~~~~~~~~~~~~~~~~~~~~
Initializes teleop mode.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void teleopPeriodic()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Code that runs periodically while the robot is in teleop goes here.

~~~~~~~~~~~~~~~~~~~~~~
public void testInit()
~~~~~~~~~~~~~~~~~~~~~~
Initializes test mode.

~~~~~~~~~~~~~~~~~~~~~~~~~~
public void testPeriodic()
~~~~~~~~~~~~~~~~~~~~~~~~~~
Code that runs periodically while the robot is in test goes here.
