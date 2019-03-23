==============================
frc2019.robot.subsystems.Hatch
==============================
Subsystem for the Hatch Mechanism. The Hatch Mechanism consists of a "beak" that moves up and down. It fits through the hole in the middle of the hatch panels, and moves upwards to pinch it.

------------
Dependencies
------------
- `com.revrobotics.CANSparkMax <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMax.html>`_
- `com.revrobotics.CANSparkMaxLowLevel.MotorType <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMaxLowLevel.MotorType.html>`_
- `org.team3197.frc2019.robot.RobotMap <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html>`_
- `org.team3197.frc2019.robot.commands.defaults.Speak <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/defaults/Speak.html>`_
- Implements the `org.team3197.frc2019.robot.utilities.Drivable <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/utilities/Drivable.html>`_ Interface.
- Inherits properties of `edu.wpi.first.wpilibj.command.Subsystem <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/command/Subsystem.html>`_

--------
Commands
--------

~~~~~~~~~~~~~~
public Hatch()
~~~~~~~~~~~~~~
Constructor for the Subsystem Hatch.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void initDefaultCommand()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Associates the `Speak <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/defaults/Speak.html>`_ command with the Subsystem Hatch. 

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void drive(double speed, boolean hold)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Drives the Hatch Mechanism.