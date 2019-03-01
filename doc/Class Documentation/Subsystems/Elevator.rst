==============================
frc.robot.subsystems.Elevator
==============================

------------
Dependencies
------------
- `com.revrobotics.CANDigitalInput <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANDigitalInput.html>`_
- `com.revrobotics.CANDigitalInput.LimitSwitchPolarity <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANDigitalInput.LimitSwitchPolarity.html>`_
- `com.revrobotics.CANPIDController <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANPIDController.html>`_
- `com.revrobotics.CANSparkMax <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMax.html>`_
- `com.revrobotics.CANSparkMax.IdleMode <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMax.IdleMode.html>`_
- `com.revrobotics.CANSparkMaxLowLevel.MotorType <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMaxLowLevel.MotorType.html>`_
- `org.team3197.frc2019.robot.RobotMap <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html>`_
- `org.team3197.frc2019.robot.RobotMap.DeadbandType <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-deadbandtype>`_
- `org.team3197.frc2019.robot.commands.defaults.Elevate <https://2019-frc.readthedocs.io/en/documentation/Class%20Documentation/Commands/defaults/Elevate.html>`_
- `edu.wpi.first.wpilibj.SpeedControllerGroup <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/SpeedControllerGroup.html>`_
- `edu.wpi.first.wpilibj.buttons.Trigger <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/buttons/Trigger.html>`_
- `edu.wpi.first.wpilibj.command.Subsystem <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/command/Subsystem.html>`_
- `edu.wpi.first.wpilibj.smartdashboard.SmartDashboard <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/smartdashboard/SmartDashboard.html>`_

--------
Commands
--------

~~~~~~~~~~~~~~~~~
public Elevator()
~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void initDefaultCommand()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void drive(double speed, boolean hold)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public double resetEncoderPosition()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public double getEncoderPosition()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public double getRawEncoderPosition()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~
public boolean get()
~~~~~~~~~~~~~~~~~~~~
This function gets the bottomLimit.

TODO: Figure out why it needs it's own class.
