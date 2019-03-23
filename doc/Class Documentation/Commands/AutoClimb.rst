================================
frc2019.robot.commands.AutoClimb
================================
AutoClimb automatically drives the motors for the climber.
The climber is a two-part system, with knives in the front and a tower in the back.
The knives drive downwards to lift the robot up in front, while the tower lifts the robot up in the back.
By driving both with gyro correction, you can achieve a perfect climb upwards. Once at the desired height, the wheels on the bottom of the tower are driven, driving the robot forwards.
Once more than half of the robot is supported by the hab, the tower can be safely retracted and the robot driven forwards to a stable position.

AutoClimb is currently a work-in-progress and is subject to drastic changes.

------------
Dependencies
------------
- `org.team3197.frc2019.robot.RobotMap.Channel <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-channel>`_
- `org.team3197.frc2019.robot.RobotMap.DeadbandType <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-deadbandtype>`_
- `org.team3197.frc2019.robot.RobotMap.GyroSensitivity <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-gyrosensitivity>`_
- `org.team3197.frc2019.robot.RobotMap.MaxSpeeds <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html#public-static-enum-maxspeeds>`_
- `org.team3197.frc2019.robot.subsystems.Climber <>`_
- `org.team3197.frc2019.robot.subsystems.Erector <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Subsystems/Erector.html>`_
- `org.team3197.frc2019.robot.utilities.FunctionCommand <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/utilities/FunctionCommand.html>`_
- `edu.wpi.first.wpilibj.AnalogGyro <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/AnalogGyro.html>`_
- Inherits properties of `edu.wpi.first.wpilibj.command.Command <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/command/Command.html>`_
- `edu.wpi.first.wpilibj.smartdashboard.SmartDashboard <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/smartdashboard/SmartDashboard.html>`_

--------
Commands
--------

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public AutoClimb(Climber climber, Erector erector)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~
protected void execute()
~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
protected boolean isFinished()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~
protected void end()
~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~~
private double getAngle()
~~~~~~~~~~~~~~~~~~~~~~~~~

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
private void resetGyroAngle()
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
