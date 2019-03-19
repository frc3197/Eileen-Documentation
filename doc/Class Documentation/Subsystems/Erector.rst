=============================
frc2019.robot.subsystems.Erector
=============================
Subsystem for the climber. The climber is currently under revision.

------------
Dependencies
------------
- `com.revrobotics.CANSparkMax <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMax.html>`_
- `com.revrobotics.ControlType <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/ControlType.html>`_
- `com.revrobotics.CANSparkMax.IdleMode <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMax.IdleMode.html>`_
- `com.revrobotics.CANSparkMaxLowLevel.MotorType <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMaxLowLevel.MotorType.html>`_
- `org.team3197.frc2019.robot.RobotMap <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html>`_
- `org.team3197.frc2019.robot.RobotMap.DeadbandType <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-deadbandtype>`_
- `org.team3197.frc2019.robot.commands.defaults.Erect <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/defaults/Erect.html>`_
- Implements the `org.team3197.frc2019.robot.utilities.Drivable <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/utilities/Drivable.html>`_ Interface.
- `org.team3197.frc2019.robot.utilities.FunctionCommand <>`_
- `edu.wpi.first.wpilibj.SpeeedControllerGroup <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/SpeedControllerGroup.html>`_
- Inherits properties of `edu.wpi.first.wpilibj.command.Subsystem <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/command/Subsystem.html>`_
- `edu.wpi.first.wpilibj.smartdashboard.SmartDashboard <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/smartdashboard/SmartDashboard.html>`_

--------
Commands
--------

~~~~~~~~~~~~~~~~
public Erector()
~~~~~~~~~~~~~~~~
Constructor for the Subsystem Erector.

Motors are set to brake mode.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void initDefaultCommand()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Associates the `Erect <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/defaults/Erect.html>`_ command with the Subsystem Erector. 

~~~~~~~~~~~~~~~~~~~~~~
public void resetPID()
~~~~~~~~~~~~~~~~~~~~~~
Resets the last encoder values so that the PID will zero out.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void drive(double speed, boolean hold)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Drives the motor, moving up the climber.