=======================================
frc2019.robot.utilities.FunctionCommand
=======================================
Used for Abstraction and Standardization of Programs.

------------
Dependencies
------------
- Inherits properties of `edu.wpi.first.wpilibj.command.InstantCommand <http://first.wpi.edu/FRC/roborio/release/docs/java/edu/wpi/first/wpilibj/command/InstantCommand.html>`_
- Implements the `frc2019.robot.utilities.FunctionWrapper <https://eileen-documentation.readthedocs.io/en/latest/Class%20Documentation/utilities/FunctionWrapper.html>`_ Interface
--------
Commands
--------

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
public FunctionCommand(FunctionWrapper function)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Constructer for FunctionCommand. Standardizes functions that are constructed using FunctionCommand.

TODO: Figure out why this stuff is needed.

~~~~~~~~~~~~~~~~~~~~~~~~~~~
protected void initialize()
~~~~~~~~~~~~~~~~~~~~~~~~~~~
Calls the function being created by the Constructor.
call() which is required by the Interface implemented, is called within initialize()
