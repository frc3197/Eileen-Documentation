=================================
frc2019.robot.subsystems.Elevator
=================================
Subsystem for the elevator. The elevator consists of a baby carriage and a pulley system that brings it up.
The baby carriage is what holds the arm.

------------
Dependencies
------------
- `com.revrobotics.CANDigitalInput <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANDigitalInput.html>`_
- `com.revrobotics.CANDigitalInput.LimitSwitchPolarity <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANDigitalInput.LimitSwitchPolarity.html>`_
- `com.revrobotics.CANPIDController <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANPIDController.html>`_
- `com.revrobotics.CANSparkMax <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMax.html>`_
- `com.revrobotics.CANSparkMax.IdleMode <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMax.IdleMode.html>`_
- `com.revrobotics.CANSparkMaxLowLevel.MotorType <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMaxLowLevel.MotorType.html>`_
- `org.team3197.frc2019.robot.RobotMap <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html>`_
- `org.team3197.frc2019.robot.RobotMap.DeadbandType <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-deadbandtype>`_
- `org.team3197.frc2019.robot.commands.defaults.Elevate <https://2019-frc.readthedocs.io/en/documentation/Class%20Documentation/Commands/defaults/Elevate.html>`_
- Implements the `org.team3197.frc2019.robot.utilities.Drivable <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/utilities/Drivable.html>`_ Interface.
- `org.team3197.frc2019.robot.utilities.FunctionCommand <>`_
- `edu.wpi.first.wpilibj.SpeedControllerGroup <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/SpeedControllerGroup.html>`_
- LimitReset inherits properties of `edu.wpi.first.wpilibj.buttons.Trigger <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/buttons/Trigger.html>`_
- Inherits properties of `edu.wpi.first.wpilibj.command.Subsystem <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/command/Subsystem.html>`_
- `edu.wpi.first.wpilibj.smartdashboard.SmartDashboard <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/smartdashboard/SmartDashboard.html>`_

--------
Commands
--------

~~~~~~~~~~~~~~~~~
public Elevator()
~~~~~~~~~~~~~~~~~
Constructor for the subsystem Elevator.

Motors are brushless.

Motors are set to brake mode.

Limit Switches are normally open.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void initDefaultCommand()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Associates the `Elevate <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/defaults/Elevate.html>`_ command with the Subsystem Elevator.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void drive(double speed, boolean hold)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Drives the motor that pulls the elevator up and down.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void resetEncoderPosition()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Resets the encoder position.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public double getEncoderPosition()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Gets the encoder position with the position of the encoder at reset subtracted.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public double getRawEncoderPosition()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Gets the encoder position.

~~~~~~~~~~~~~~~~~~~~
public boolean get()
~~~~~~~~~~~~~~~~~~~~
This function gets the bottomLimit.

TODO: Figure out why it needs it's own class.

------------------------
private class LimitReset
------------------------
- Inherits the properties of `edu.wpi.first.wpilibj.buttons.Trigger <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/buttons/Trigger.html>`_

~~~~~~~~~~~~~~~~~~~~
public boolean get()
~~~~~~~~~~~~~~~~~~~~
Gets the bottom limit.