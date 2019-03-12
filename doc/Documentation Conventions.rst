=========================
Documentation Conventions
=========================
This describes the conventions for how documentation should be written.

As a rule of thumb, all documents should start with a title surrounded by "=" like this::

    =============
    Example Title
    =============

The hierarchy should then go as follows::

    =====
    Title
    =====

    ----------
    Categories
    ----------

    ~~~~~~~~~~~~~~~~
    Functions/Topics
    ~~~~~~~~~~~~~~~~

~~~~~
Index
~~~~~
1. Small Description for what the entire repository is for.
2. Category called "Code-Related." Includes everything that doesn't have to do with direct class documentation like I2C, Raspberry Pi, GRIP etc.
3. Class Documentation goes underneath. Class Documentation should exist inside a two-column table. First column gives link to class and its address (org.team3197.frc2019.robot.ExampleClass.exampleClass), while second column describes in general what the class does. 
4. Category called Updating/Installing Firmware." Usually will be carried over from previous years, but links go here. If there are any changes, instructions should be updated.
5. Category called Diagrams/Configurations. Contains motor controller mappings, button mappings on the Xbox Controller, etc. Diagram for controller highly recommended.
6. Category called helpful resources. Will accumulate over time, but this includes anything that is helpful as an external reference. This includes WPILib/Java/REVRobotics documentation, language basics, a link to this very page.

~~~~~~~
Classes
~~~~~~~
1. Write a description of the entire class in general.
2. List all functions within the class.

~~~~~~~~~~
Interfaces
~~~~~~~~~~
