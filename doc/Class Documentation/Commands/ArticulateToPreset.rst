=========================================
frc2019.robot.commands.ArticulateToPreset
=========================================

------------
Dependencies
------------
- `org.team3197.frc2019.robot.RobotMap <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html>`_
- `org.team3197.frc2019.robot.RobotMap.ElbowPreset <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-elbowpreset>`_
- `org.team3197.frc2019.robot.RobotMap.MaxSpeeds <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-maxspeeds>`_
- `org.team3197.frc2019.robot.subsystems.Arm <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/Subsystems/Arm.html>`_
- `edu.wpi.first.wpilibj.buttons.Trigger <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/buttons/Trigger.html>`_
- `edu.wpi.first.wpilibj.command.Command <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/command/Command.html>`_

--------
Commands
--------

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public ArticulateToPreset(ElbowPreset target, ElbowPreset targetWithTrigger, Trigger toggle, Arm arm)
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
