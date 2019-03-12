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
2. Category called "Dependencies." List all dependencies and their links here.
3. Category called "Commands." List all functions within the class.
4. If there are any classes within the main class, act as if it is a large category, place it's functions underneath it, then end it with another category-level heading re-stating the main class.
#4 Example::

    ------------------------
    public class nestedClass
    ------------------------
    Class that is nested within mainClass.

    Functions below this are within the class nestedClass.

    ~~~~~~~~~~~~~~~~~~~~~~~
    public void initClass()
    ~~~~~~~~~~~~~~~~~~~~~~~
    Initializes nestedClass

    ~~~~~~~~~~~~~~~~~~~~~
    public void command()
    ~~~~~~~~~~~~~~~~~~~~~
    Does something.

    ----------------------
    public class mainClass
    ----------------------
    Functions above are placed within the class nestedClass.

~~~~~~~~~~
Interfaces
~~~~~~~~~~
Interfaces are special little snowflakes that need their own method of writing.

1. Write a description of the Interface. For example, that it is used for.
2. Category called "Dependencies." Interfaces usually do not have any dependencies. In here, you can state that the class is an interface.
3. Category called "Commands." Commands should be listed underneath in bullet points. Extra text about them is not needed as the interface only specifies requirements for classes that utilize it.

~~~~~~~~~~~~~~~~~~~~~~
Instructions and Other
~~~~~~~~~~~~~~~~~~~~~~
These aren't as standardized and can be written to your discretion. Usually includes a numbered list, and other stuff.