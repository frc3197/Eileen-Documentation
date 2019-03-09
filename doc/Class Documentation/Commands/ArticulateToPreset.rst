=====================================
frc2019.robot.commands.ArticulateToPreset
=====================================

------------
Dependencies
------------
- `org.team3197.frc2019.robot.RobotMap <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html>`_
- `org.team3197.frc2019.robot.RobotMap.ArmPreset <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-armpreset>`_
- `org.team3197.frc2019.robot.RobotMap.MaxSpeeds <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-maxspeeds>`_
- `org.team3197.frc2019.robot.subsystems.Arm <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Subsystems/Arm.html>`_
- `edu.wpi.first.wpilibj.buttons.Trigger <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/buttons/Trigger.html>`_
- `edu.wpi.first.wpilibj.command.Command <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/command/Command.html>`_

--------
Commands
--------

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public ArticulateToPreset(ArmPreset target, ArmPreset targetWithTrigger, Trigger toggle, Arm arm)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~
protected void execute()
~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
protected boolean isFinished()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
private double getWristSpeed()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
private double getElbowSpeed()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
