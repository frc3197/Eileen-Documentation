=======================================
frc2019.robot.commands.ElevateToPreset
=======================================

------------
Dependencies
------------
- `org.team3197.frc2019.robot.RobotMap <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html>`_
- `org.team3197.frc2019.robot.RobotMap.ElevatorPreset <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-elevatorpreset>`_
- `org.team3197.frc2019.robot.RobotMap.MaxSpeeds <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-maxspeeds>`_
- `org.team3197.frc2019.robot.subsystems.Elevator <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Subsystems/Elevator.html>`_
- `edu.wpi.first.wpilibj.buttons.Trigger <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/buttons/Trigger.html>`_
- `edu.wpi.first.wpilibj.command.Command <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/command/Command.html>`_

--------
Commands
--------

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public ElevateToPreset(ElevatorPreset elevatorTarget, ElevatorPreset elevatorTargetWithTrigger, Trigger toggle, Elevator elevator)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~
protected void execute()
~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
protected boolean isFinished()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
private double getElevatorSpeed()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
