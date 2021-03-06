============================
frc2019.robot.subsystems.Arm
============================
Subsystem for the arm. The arm is a two-joint arm, with an elbow connected to the baby carriage, 
and a wrist that moves the Cargo Manipulator up and down. The arm contains both the Cargo Manipulator 
and the "Beak" (Hatch Mechanism).

------------
Dependencies
------------
- `com.revrobotics.CANDigitalInput <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANDigitalInput.html>`_
- `com.revrobotics.CANDigitalInput.LimitSwitchPolarity <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANDigitalInput.LimitSwitchPolarity.html>`_
- `com.revrobotics.CANSparkMax <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMax.html>`_
- `com.revrobotics.CANSparkMax.IdleMode <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMax.IdleMode.html>`_
- `com.revrobotics.CANSparkMaxLowLevel.MotorType <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMaxLowLevel.MotorType.html>`_
- `org.team3197.frc2019.robot.RobotMap <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html>`_
- `org.team3197.frc2019.robot.RobotMap.Channel <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-channel>`_
- `org.team3197.frc2019.robot.RobotMap.DeadbandType <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-deadbandtype>`_
- `org.team3197.frc2019.robot.RobotMap.GyroSensitivity <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-gyrosensitivity>`_
- `org.team3197.frc2019.robot.commands.defaults.Articulate <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/defaults/Articulate.html>`_
- Implements the `org.team3197.frc2019.robot.utilities.Drivable <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/utilities/Drivable.html>`_ Interface.
- `org.team3197.frc2019.robot.utilities.FunctionCommand <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/utilities/FunctionCommand.html>`_
- `edu.wpi.first.wpilibj.AnalogGyro <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/AnalogGyro.html>`_
- ResetGyro inherits properties of `edu.wpi.first.wpilibj.command.InstantCommand <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/command/InstantCommand.html>`_
- Inherits properties of `edu.wpi.first.wpilibj.command.Subsystem <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/command/Subsystem.html>`_
- `edu.wpi.first.wpilibj.smartdashboard.SmartDashboard <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/smartdashboard/SmartDashboard.html>`_

--------
Commands
--------

~~~~~~~~~~~~
public Arm()
~~~~~~~~~~~~
Constructor for Arm. 

Both motors are set to brake mode.

The motors are brushless.

Limit Switches are normally open.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void initDefaultCommand()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Associates the `Articulate <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/defaults/Articulate.html>`_ command with the subsystem Arm.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void drive(double speed, boolean hold)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Drives the motor. Elbow runs, but wrist does not. Default command that moves the motor.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void elbow(double speed)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Drives the elbow motor as well as defining limit behavior. Puts encoder data to the SmartDashboard. Used if drive() is not.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void wrist(double speed)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Drives the wrist motor. Puts Gyro and Encoder values to the SmartDashboard. Sets Deadband for input and applies rudimentary PID.

~~~~~~~~~~~~~~~~~~~~~~~~~
private double getAngle()
~~~~~~~~~~~~~~~~~~~~~~~~~
Gets the angle of the gyro on the arm.

~~~~~~~~~~~~~~~~~~~~~~~
public void resetGyro()
~~~~~~~~~~~~~~~~~~~~~~~
Resets the gyro value. Requires class below to call.

----------------------
public class ResetGyro
----------------------
- Inherits the properties of `edu.wpi.first.wpilibj.command.InstantCommand <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/command/InstantCommand.html>`_ (Command runs only once when called).
Class that allows ResetGyro() to work.

~~~~~~~~~~~
ResetGyro()
~~~~~~~~~~~
resets the gyro.

~~~~~~~~~~~~
initialize()
~~~~~~~~~~~~
Calls resetGyro()

----------------
public class Arm
----------------
ResetGyro() and initialize() are the only functions that are under the class ResetGyro.
Everything else exists under the class Arm.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public double getElbowEncoderPosition()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Gets the position of the encoder on the elbow.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public double getWristEncoderPosition()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Gets the position of the encoder on the wrist.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public double getWristEncoderPositionRaw()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
TODO: Figure out if this is used or not.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
private void resetEncoderPosition()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Resets both the wrist and elbow encoder positions.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
private void resetGyroAngle()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Resets the angle of the gyros.

~~~~~~~~~~~~~~~~~~~~~~~~~
private void toggleGyro()
~~~~~~~~~~~~~~~~~~~~~~~~~
Toggles whether the gyro is being used or not.