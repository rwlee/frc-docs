.. include:: <isonum.txt>

FRC Glossary
============

.. glossary::

   accelerometer
      A common sensor used to measure acceleration in one or more axis.

   auto
      The first phase of each match is called Autonomous (auto) and consists of the robot's running pre-programmed instructions.

   call stack
      A specially-organized region of memory which helps the program keep track of what function it is in. As each function calls another, the call point is recorded and added to the top of the structure, forming a "stack" of references. Additionally, local variables will also be stored in this stack. See `call stack <https://en.wikipedia.org/wiki/Call_stack>`__ on Wikipedia for more info.

   central limit theorem
      A core concept in probability which states that when many independent variables are added up, the result tends to look like a "normal" (or Gaussian) distribution, regardless of whether the independent variables themselves are normally distributed. See `Central Limit Theorem <https://en.wikipedia.org/wiki/Central_limit_theorem>`__ on Wikipedia for more info.

   Classical Mechanics
      The branch of physics which studies and describes the motion of relatively large, relatively slow objects. See `Classical Mechanics <https://en.wikipedia.org/wiki/Classical_mechanics>`__ on Wikipedia for more info.

   COTS
      Commercial off the shelf, a standard (i.e. not custom order) part commonly available from a vendor to all teams for purchase.

   composition
      A formal software term for building (or "composing") software entities out of smaller component entities. See `object composition <https://en.wikipedia.org/wiki/Object_composition>`__ on Wikipedia for more info.

   CRTP
      Continuously Recurring Template Pattern - A software idiom in which a class `X`` derives from a class template instantiation using `X`` itself as a template argument. See `CRTP <https://en.wikipedia.org/wiki/Curiously_recurring_template_pattern>`__ on Wikipedia for more info.

   C++
      One of the three officially supported programming languages.

   declarative programming
      A style of software which focuses on describing *what* a program should do, rather than *how* it gets done. See `declarative programming <https://en.wikipedia.org/wiki/Declarative_programming>`__ on Wikipedia for more info.

   dependency injection
      A software design pattern where each class receives all objects it depends upon. Sometimes these are passed through the constructor, but not always. See `dependency injection <https://en.wikipedia.org/wiki/Dependency_injection>`__ on Wikipedia for more info.

   deprecated
      Software that has been replaced and will no longer receive new features. Deprecated software will be maintained for at least 1 year, but may be removed after that. For example, if a method is deprecated prior to the 2022 season, it will be usable in the 2022 season, but may be removed prior to the 2023 season. Teams are encouraged to not use deprecated methods in new code. WPILib always deprecates features at least one year prior to removing them from the codebase.

   design pattern
      A particular, intentionally-chosen style of organizing code. A design pattern intentionally excludes using certain features of a programming language to constrain developers into solutions that are well-suited to a particular problem-space. See `design pattern. <https://en.wikipedia.org/wiki/Design_pattern>`__ on Wikipedia for more info.

   DHCP
      Dynamic Host Configuration Protocol, the protocol that allows a central device to assign unique IP addresses to all other devices.

   encapsulation
      A software design pattern which uses a class to hide the implementation details of other classes. See `encapsulation <https://en.wikipedia.org/wiki/Encapsulation_(computer_programming)>`__ on Wikipedia for more info.

   event-driven programming
      A style of programming where certain parts of code generate "events" as a result of some input (sensors, user interaction, etc). Then, other parts of code listen for and respond to "handle" these events. See `event-based <https://en.wikipedia.org/wiki/Event-driven_programming>`__ on Wikipedia for more info.

   FMS
      Field Management System, the electronics core responsible for sensing and controlling the FIRST Robotics Competition field.

   FPGA
       Field-programmable gate array - a specialized integrated circuit consisting of many digital logic elements, which can be configured to act in different patterns. This allows its behavior to be changed after manufacturing. In the context of FRC, National Instruments provides a specific configuration for the RIO's FPGA which allows it to process the electrical inputs and outputs at a very high rate. See `FPGA <https://en.wikipedia.org/wiki/Field-programmable_gate_array>`__ on Wikipedia for more info.

   GradleRIO
      The mechanism that powers the deployment of robot code to the roboRIO.

   gyroscope
      A device that measures rate of rotation.  It can add up the rotation measurements to determine :term:`heading` of the robot. (“gyro”, for short)

   heading
      The direction the robot is pointed, usually expressed as an angle in degrees.

   imperative programming
      A style of programming that focuses on *what* the code should be doing, step by step, every loop. See `imperative programming <https://en.wikipedia.org/wiki/Imperative_programming>`__ on Wikipedia for more info.

   IMU
      Inertial Measurement Unit, a sensor that combines both an :term:`accelerometer` and a :term:`gyroscope` into a single sensor.

   Java
      One of the three officially supported programming languages.

   JSON
      JavaScript Object Notation. A standardized way of organizing data into named values. The organized data can be easily :term:`serialized`. While the original usage was in Javascript, it can be used and interested by most modern programming languages. See `JSON <https://en.wikipedia.org/wiki/JSON>`__ on Wikipedia for more info.

   KOP
      Kit of Parts, the collection of items listed on the Kickoff Kit checklists, distributed to the team via FIRST Choice, or paid for completely (except shipping) with a Product Donation Voucher (PDV).

   KOP chassis
      The KOP contains a drive base (chassis) distributed to every team (that did not opt out) as part of the :term:`KOP`. For the 2022 season, the KOP chassis is the `AM14U5 <https://www.andymark.com/products/am14u5-6-wheel-drop-center-robot-drive-base-first-kit-of-parts-chassis>`__.

   LabVIEW
      One of the three officially supported programming languages.

   NetworkTables
      A way to communicate key / value pairs of data between programs.

   mass
      the amount of matter in a physical object. Objects with more mass will resist changes in motion more than objects with less mass. See `mass <https://en.wikipedia.org/wiki/Mass>`_ on Wikipedia for more info.

   moment of inertia
      The property of an object that describes both how much mass it has, and how that mass is distributed relative to a certain axis of rotation. Objects with higher moments of inertia resist changes in rotational motion more than objects with lower moments of inertia. Increasing the moment of inertia is accomplished by adding more mass, or moving the mass further away from the axis of rotation. See `moment of inertia <https://en.wikipedia.org/wiki/Moment_of_inertia>`_ on Wikipedia for more info.

   permanent-magnet DC motor
      The classification of all legal motors for the FIRST robotics competition. This type of motor takes direct current as input, and uses it to create a magnetic field. In turn, this magnetic field interacts with a physical magnet to create a force that turns the output shaft. Electrical ("brushless") or mechanical ("brushed") means are used to ensure the electrically-generated magnetic field always points in a direction that creates forces when it interacts with the physical magnet, even as the motor's shaft rotates. See `permanent-magnet motor <https://en.wikipedia.org/wiki/Brushed_DC_electric_motor#Permanent-magnet_motors>`__ on Wikipedia for more info.

   retro-reflection
      The property of reflecting incoming light back at the same angle it came in at, rather than an incident angle (like a mirror), absorbing it, or scattering it. Most FRC vision processing targets are retro-reflective. See `retroreflector <https://en.wikipedia.org/wiki/Retroreflector>`_ on Wikipedia for more information.

   recursive composition
      A type of :term:`composition` in which the composite object may contain components of the same type as itself. For example, a command group may contain one or more command groups. See `recursive composition <https://en.wikipedia.org/wiki/Object_composition#Recursive_composition>`__ on Wikipedia for more info. See also :term:`recursive composition`.

   serialized
      The property of a data organization scheme that allows the description of the data to be sent in order, byte by byte, over some communication channel. Reading or writing a file on disk is done in this serial fashion (IE, the data is read or written byte by byte, not all at once). Sending data over a SPI or I2C bus is also done byte by byte, again requiring the data can be serialized.

   simulation
      A way for teams to test their code without having an actual robot available.

   software library
      A collection of code that can be imported into and used by other software. See `software library <https://en.wikipedia.org/wiki/Library_(computing)>`__ on Wikipedia for more info.

   solenoid valve
      A airflow-controlling valve which is actuated by a small electromagnet. Strictly speaking, the *solenoid* is the coil of wire which forms the electromagnet, and the *valve* is the mechanism which actually redirects airflow. However, the set of solenoid and valve together is often simply called "a solenoid". See `solenoid valve <https://en.wikipedia.org/wiki/Solenoid_valve>`__. on Wikipedia for more info.

   state machine
      A programming construct that divides a problem into many discrete, well-defined, mutually-exclusive "states", then defines how the problem is solved by moving between different states. See `state machine <https://en.wikipedia.org/wiki/Finite-state_machine>`__ on Wikipedia for more more info.

   telemetry
      The process of recording and sending real-time data about the performance of your robot to a real-time readout or log file. For the linguists among us, the word's roots are "tele" (remote) and "metry" (measurement). See `telemetry <https://en.wikipedia.org/wiki/Telemetry>`__ on Wikipedia for more info.

   teleop
      The second phase of each match is called the Teleoperated Period (teleop) and consists of drivers controlling their robots.

   torque
      A force applied at a distance from some axis of rotation

   trajectory
      A trajectory is a smooth curve, with velocities and accelerations at each point along the curve, connecting two endpoints on the field.
