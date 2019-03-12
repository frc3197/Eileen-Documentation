==================
2019-Documentation 
==================
.. image:: https://travis-ci.org/frc3197/2019-FRC.svg?branch=master
    :target: https://travis-ci.org/frc3197/2019-FRC

Code for 3197's Robot competing in the 2019 challenge, Destination: Deep Space

------------
Code-Related
------------
`I2C <https://2019-documentation.readthedocs.io/en/latest/I2C.html>`_

`VSCode Basics <https://2019-documentation.readthedocs.io/en/latest/VSCode%20Basics.html>`_

-------------------
Class Documentation
-------------------

+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|Package                                                                                                                                                            |Description                                   |
+===================================================================================================================================================================+==============================================+
|`frc2019.robot.Robot <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Robot.html>`_                                                      |Initializes Robot                             |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.OI <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/OI.html>`_                                                            |Assigns buttons to Controller                 |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.Main <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Main.html>`_                                                        |Starts all Robot Subsystems                   |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.RobotMap <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/RobotMap.html>`_                                                |Defines Motor Controller IDs and Constants    |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.commands.AlignTurn <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/AlignTurn.html>`_                            |Turns the Robot using vision from GRIP        |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.commands.ArticulateToPreset <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/ArticulateToPreset.html>`_          |Sets Arm to a Preset Position                 |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.commands.ElevateToPreset <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/ElevateToPreset.html>`_                |Sets Elevator to a Preset Position            |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.commands.test.DriveTrainRampTest <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/test/DriveTrainRampTest.html>`_|Soon to be erased from existence.             |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.commands.test.DriveTrainTest <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/test/DriveTrainTest.html>`_        |Soon to be erased from existence.             |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.commands.presets.Cargo <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/presets/Cargo.html>`_                    |[UNDER CONSTRUCTION]                          |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.commands.presets.LevelOne <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/presets/LevelOne.html>`_              |[UNDER CONSTRUCTION]                          |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.commands.presets.LevelThree <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/presets/LevelThree.html>`_          |[UNDER CONSTRUCTION]                          |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.commands.presets.LevelTwo <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/presets/LevelTwo.html>`_              |[UNDER CONSTRUCTION]                          |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.commands.defaults.Articulate <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/defaults/Articulate.html>`_        |Moves the Arm (Manipulator at End)            |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.commands.defaults.Drive <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/defaults/Drive.html>`_                  |Drives the Robot                              |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.commands.defaults.Elevate <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/defaults/Elevate.html>`_              |Moves the Elevator (Contains Arm)             |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.commands.defaults.Erect <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/defaults/Erect.html>`_                  |Moves the Erector (Climber)                   |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.commands.defaults.Manipulate <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/defaults/Manipulate.html>`_        |Moves the Manipulator (Cargo Shovel)          |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.commands.defaults.Speak <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Commands/defaults/Speak.html>`_                  |Moves the Beak on the Arm (Hatch Panel Hook)  |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.subsystems.Arm <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Subsystems/Arm.html>`_                                    |Defines the Arm (Moves Manipulator)           |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.subsystems.CargoManipulator <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Subsystems/CargoManipulator.html>`_          |Defines the Cargo Manipulator                 |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.subsystems.DriveTrain <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Subsystems/DriveTrain.html>`_                      |Defines the Drive Train                       |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.subsystems.Elevator <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Subsystems/Elevator.html>`_                          |Defines the Elevator (Contains Arm)           |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.subsystems.Erector <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Subsystems/Erector.html>`_                            |Defines the Erector (Climber)                 |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.subsystems.Hatch <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/Subsystems/Hatch.html>`_                                |Defines the Hatch Panel Mechanism (Beak)      |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.utilities.Drivable <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/utilities/Drivable.html>`_                            |Interface for various Subsystems              |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.utilities.FunctionWrapper <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/utilities/FunctionWrapper.html>`_              |Interface for FunctionCommand                 |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+
|`frc2019.robot.utilities.FunctionCommand <https://2019-documentation.readthedocs.io/en/latest/Class%20Documentation/utilities/FunctionCommand.html>`_              |Abstraction Stuff                             |
+-------------------------------------------------------------------------------------------------------------------------------------------------------------------+----------------------------------------------+


----------------------------
Updating/Installing Firmware
----------------------------
`Updating and Imaging the RoboRIO <https://2019-documentation.readthedocs.io/en/latest/Updating%20Instructions/Updating%20and%20Imaging%20the%20RoboRIO.html>`_

`Updating REV Spark Max Firmware <https://2019-documentation.readthedocs.io/en/latest/Updating%20Instructions/Updating%20Firmware%20of%20REV%20Spark%20Max's.html>`_

-----------------------
Diagrams/Configurations
-----------------------
`Motor Controller Spreadsheet <https://docs.google.com/spreadsheets/d/14p9fdd08mrI9wpgqd_k9QANKFcTs7CDPGgKoO7wAz68/edit?usp=sharing>`_

~~~~~~~~~~~~~~~~~~~~~~~~~
Controller Configurations
~~~~~~~~~~~~~~~~~~~~~~~~~
.. image:: https://raw.githubusercontent.com/frc3197/2019-Documentation/master/doc/Controller%20Configuration.png
   :width: 600
- Presets in brackets correspond to the Ctrl variant. For example, on Operator, ``A + Up`` is equal to Cargo Lv. 3.
- The ``A`` button on both controllers needs to be held in order to access their functions.
- ``X`` and ``Y`` control the Hatch Panel Mechanism, henceforth known as the "Bird."
- Driver ``Left Trigger`` and ``Right Trigger`` control the Forward Climber while Driver ``Left Bumper`` and ``Right Bumper`` control the Backward Climber.
- Left and Right on all joysticks are currently unused.
- CONTROLLER MAP CURRENTLY OUTDATED. WILL UPDATE SOON.

-----------------
Helpful Resources
-----------------
`WPILib Documentation <http://first.wpi.edu/FRC/roborio/release/docs/java/>`_ 

`Limelight Documentation <http://docs.limelightvision.io/en/latest/>`_

`REV Robotics Documentation <http://www.revrobotics.com/content/sw/max/sw-docs/java/com/revrobotics/package-summary.html>`_

`Java Documentation <https://docs.oracle.com/javase/8/docs/api/overview-summary.html>`_

`reStructuredText Basics <http://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html>`_

`Markdown Basics <https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code>`_

`Documentation Conventions <https://2019-documentation.readthedocs.io/en/latest/Documentation%20Conventions.html>`_