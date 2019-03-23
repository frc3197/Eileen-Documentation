===================================
frc2019.robot.subsystems.DriveTrain
===================================
Subsystem for the drive train. The drive train consists of four omni wheels. Can be switched between arcade and tank drive.

------------
Dependencies
------------
- `java.util.HashMap <https://docs.oracle.com/javase/8/docs/api/java/util/package-summary.html>`_
- `com.revrobotics.CANDigitalInput <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANDigitalInput.html>`_
- `com.revrobotics.CANDigitalInput.LimitSwitchPolarity <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANDigitalInput.LimitSwitchPolarity.html>`_
- `com.revrobotics.CANPIDController <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANPIDController.html>`_
- `com.revrobotics.CANSparkMax <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMax.html>`_
- `com.revrobotics.CANSparkMax.IdleMode <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMax.IdleMode.html>`_
- `com.revrobotics.CANSparkMaxLowLevel.MotorType <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMaxLowLevel.MotorType.html>`_
- `org.team3197.frc2019.robot.RobotMap <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html>`_
- `org.team3197.frc2019.robot.RobotMap.CANSparkMaxID <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-cansparkmaxid>`_
- `org.team3197.frc2019.robot.RobotMap.Channel <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-channel>`_
- `org.team3197.frc2019.robot.RobotMap.DeadbandType <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-deadbandtype>`_
- `org.team3197.frc2019.robot.commands.defaults.Drive <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/defaults/Drive.html>`_
- `edu.wpi.first.wpilibj.SpeedControllerGroup <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/SpeedControllerGroup.html>`_
- Inherits properties of `edu.wpi.first.wpilibj.command.Subsystem <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/command/Subsystem.html>`_
- `edu.wpi.first.wpilibj.drive.DifferentialDrive <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/drive/DifferentialDrive.html>`_

--------
Commands
--------

~~~~~~~~~~~~~~~~~~~
public DriveTrain()
~~~~~~~~~~~~~~~~~~~
Constructor for DriveTrain

Motors are brushless.

All motors are set to Brake Mode.

Limit switches are normally open.

TODO: Figure out hashmaps and why they are needed here.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void initDefaultCommand()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Associates the `Drive <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/defaults/Drive.html>`_ command with the subsystem DriveTrain.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void tankDrive(double l, double r)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Drives the robot in tank drive. Right joystick controls right side, left controls left.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void arcadeDrive(double y, double r)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Drives the robot in arcade drive. Right joystick controls turning, left controls forward and backward.

TODO: Confirm that it's left and right that does the corresponding things.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
private void gyroDrive(double y, double r)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Currently not being used. Just does arcade drive.

TODO: Read through the commented code and figure out what it originally did?

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
private boolean goingStraight(double y, double r)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Checks whether or not the robot is going straight.

~~~~~~~~~~~~~~~~~~~~~~~~~
private void toggleGyro()
~~~~~~~~~~~~~~~~~~~~~~~~~
Toggles whether the gyro is being used or not.

~~~~~~~~~~~~~~~~~~~~~~~~~
private void toggleMode()
~~~~~~~~~~~~~~~~~~~~~~~~~
Changes which drive mode you are using: arcade or tank.