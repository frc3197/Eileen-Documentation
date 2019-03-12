======================================
frc2019.robot.subsystems.CargoManipulator
======================================
The Cargo Manipulator sucks in Cargo and deposits them. In contains one motor driving an axle 
containing a set of wheels that feed the Cargo (large rubber balls) in and out of a large, polycarb shovel.

------------
Dependencies
------------
- `com.revrobotics.CANSparkMax <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMax.html>`_
- `com.revrobotics.CANSparkMax.IdleMode <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMax.IdleMode.html>`_
- `com.revrobotics.CANSparkMaxLowLevel.MotorType <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/CANSparkMaxLowLevel.MotorType.html>`_
- `org.team3197.frc2019.robot.RobotMap <https://2019-frc.readthedocs.io/en/documentation/Class%20Documentation/RobotMap.html>`_
- `org.team3197.frc2019.robot.commands.defaults.Manipulate <https://2019-frc.readthedocs.io/en/documentation/Class%20Documentation/Commands/defaults/Manipulate.html>`_
- Implements the `org.team3197.frc2019.robot.utilities.Drivable <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/utilities/Drivable.html>`_ Interface.
- Inherits properties of `edu.epi.first.wpilibj.command.Subsystem <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/command/Subsystem.html>`_

--------
Commands
--------

~~~~~~~~~~~~~~~~~~~~~~~~~
public CargoManipulator()
~~~~~~~~~~~~~~~~~~~~~~~~~
Constructor for the CargoManipulator class. 

The motor is set to Brake mode.

The motors are brushless.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void initDefaultCommand()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Associates the `Manipulate <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/defaults/Manipulate.html>`_ command with the subsystem CargoManipulator.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public void drive(double speed, boolean hold)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Drives the roller motors.