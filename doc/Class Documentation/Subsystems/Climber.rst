================================
frc2019.robot.subsystems.Climber
================================
Climber refers to the back-tower mechanism in the two-part climbing mechanism.
The tower mechanism drives up and down, elevating the robot at the back. Wheels are attached at the bottom that are able to be driven, moving the robot back and forth when properly supported.

Climber is a work-in-progress and is subject to drastic changes.

------------
Dependencies
------------
- `com.revrobotics.CANSparkMax <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMax.html>`_
- `com.revrobotics.CANSparkMax.IdleMode <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMax.IdleMode.html>`_
- `com.revrobotics.CANSparkMaxLowLevel.MotorType <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMaxLowLevel.MotorType.html>`_
- `com.revrobotics.ControlType <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/ControlType.html>`_
- `org.team3197.frc2019.robot.RobotMap.CANSparkMaxID <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-cansparkmaxid>`_
- `org.team3197.frc2019.robot.RobotMap.DeadbandType <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-deadbandtype>`_
- `org.team3197.frc2019.robot.commands.defaults.Climb <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/defaults/Climb.html>`_
- Inherits properties of `edu.wpi.first.wpilibj.command.Subsystem <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/command/Subsystem.html>`_

--------
Commands
--------

~~~~~~~~~~~~~~~~
public Climber()
~~~~~~~~~~~~~~~~
Constructor for Climber

Vertical motor is set to brake mode, while horizontal motor is set to coast mode.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void initDefaultCommand()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Associates the `Climb <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/defaults/Climb.html>`_ command with the subsystem Climber.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void driveVertical(double speed)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Drives the vertical motor.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void driveHorizontal()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Drives the horizontal motor.