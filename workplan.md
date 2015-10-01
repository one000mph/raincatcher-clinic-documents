![](media/image1.png)

**Work Plan** **asdlkfja;lwkjkj5 TESTING**

Project Team

> ***Fall Semester***
>
> Cherlyn Chan and more stuff
>
> Michael Lertvilai
>
> Joži McKiernan
>
> Nithya Menon and more stuff here
>
> Heather Seaman
>
> Project Advisor(s): Prof. Brian Bryce
>
> Project Liaison(s): David Zielski
>
> October 2015/2016

<span id="_Toc" class="anchor"></span>ABSTRACT

The RainCatcher Clinic Team at Harvey Mudd College will design, build,
and test a device for monitoring and reporting on the performance of
rain catchment tanks in Kenya, Uganda, and the Navajo Nation. This work
plan presents the initial design and approach for the project. It
describes multiple potential alternative solutions, which will be useful
based on the prototyping and testing process. The team will focus on
building a working prototype in the fall such that the team can make
additional improvements and have a design ready to be tested at field
locations come spring. This project is heavily constrained by the
self-sufficient, remote location, and low-budget nature of the project.

TABLE OF CONTENTS

TOC \\o 2-3 \\t "Abstract Heading, 4,Appendix Heading, 5,Heading, 6"

ABSTRACT PAGEREF \_Toc \\h 3

1.  **introduction PAGEREF \_Toc1 \\h 1**

    1.  <span style="font-variant:small-caps;">Raincatcher PAGEREF
        > \_Toc2 \\h 1</span>

    2.  <span style="font-variant:small-caps;">Project Statement PAGEREF
        > \_Toc3 \\h 2</span>

        1.  *Objectives PAGEREF \_Toc4 \\h 2*

        2.  *Constraints PAGEREF \_Toc5 \\h 2*

        3.  *Functions PAGEREF \_Toc6 \\h 3*

    3.  <span style="font-variant:small-caps;">Deliverables PAGEREF
        > \_Toc7 \\h 4</span>

2.  **Background PAGEREF \_Toc8 \\h 6**

    1.  <span style="font-variant:small-caps;">Power PAGEREF \_Toc9 \\h
        > 6</span>

    2.  <span style="font-variant:small-caps;">Volume Sensing PAGEREF
        > \_Toc10 \\h 10</span>

    3.  <span style="font-variant:small-caps;">System Control PAGEREF
        > \_Toc11 \\h 13</span>

    4.  <span style="font-variant:small-caps;">Data Transmission PAGEREF
        > \_Toc12 \\h 14</span>

3.  **technical approach PAGEREF \_Toc13 \\h 17**

    1.  <span style="font-variant:small-caps;">Design alternatives
        > PAGEREF \_Toc14 \\h 17</span>

        1.  *Power PAGEREF \_Toc15 \\h 17*

        2.  *Volume Sensing PAGEREF \_Toc16 \\h 21*

        3.  *System Control PAGEREF \_Toc17 \\h 23*

        4.  *Data Transmission PAGEREF \_Toc18 \\h 25*

        5.  *Housing PAGEREF \_Toc19 \\h 28*

    2.  <span style="font-variant:small-caps;">Preliminary design
        > PAGEREF \_Toc20 \\h 29</span>

        1.  *Power PAGEREF \_Toc21 \\h 29*

        2.  *Volume Sensing PAGEREF \_Toc22 \\h 30*

        3.  *System Control PAGEREF \_Toc23 \\h 30*

        4.  *Data Transmission PAGEREF \_Toc24 \\h 31*

        5.  *Housing PAGEREF \_Toc25 \\h 32*

    3.  <span style="font-variant:small-caps;">testing PAGEREF \_Toc26
        > \\h 32</span>

4.  **Project Management PAGEREF \_Toc27 \\h 35**

    1.  <span style="font-variant:small-caps;">Work Breakdown Structure
        > PAGEREF \_Toc28 \\h 35</span>

    2.  <span style="font-variant:small-caps;">Schedule PAGEREF \_Toc29
        > \\h 36</span>

    3.  <span style="font-variant:small-caps;">Division of labor PAGEREF
        > \_Toc30 \\h 37</span>

5.  **References PAGEREF \_Toc31 \\h 38**

<!-- -->

A.  **team member profiles PAGEREF \_Toc32 \\h 42**

<!-- -->

1.  <span id="_Toc1" class="anchor"></span>introduction

RainCatcher is the client for the 2015-2016 Global Clinic Project. The
Clinic team will develop a system for capturing and reporting
performance data on the status of RainCatcher’s rainwater catchment
tanks in Kenya, Uganda, and the Navajo Nation. This section describes
RainCatcher as an organization, presents the project statement, and
defines the deliverables for the project.

1.  <span id="_Toc2" class="anchor"></span>Raincatcher

RainCatcher is a nonprofit organization that installs rain catchment and
filtration systems to provide clean water to isolated or underdeveloped
communities. Most of these communities receive ample rainfall but have
no way of storing rain. They rely upon distant, and often contaminated,
sources of groundwater for drinking and washing. RainCatcher chooses to
provide clean water adjacent to schools so that children can receive an
education and bring water home instead of walking for hours each day to
fetch water. The construction and installation of these tanks are funded
by donors from around the world.

Once the tanks are installed, RainCatcher is committed to maintaining
its systems for ten years. While most of the system is quite durable,
the taps and gutters on the tanks are prone to failure. There is
currently no good way to check whether or not the catchment systems are
functioning normally, and communities are generally reluctant to report
any malfunctions. The sites do not have reliable Internet service, which
makes communication difficult. As a result, local agents make quarterly
visits to each tank site, and U.S. agents make an annual trip. These
visits are a significant financial burden on RainCatcher. RainCatcher
seeks a way to remotely monitor its systems to make the maintenance
process more efficient. RainCatcher also hopes to use the monitoring
data to engage their donors by showing them data from the tank’s use.

1.  <span id="_Toc3" class="anchor"></span>Project Statement

The 2015-16 RainCatcher Clinic Team will design, develop, build, and
test a system to monitor and communicate the water volume for each of
RainCatcher’s systems.

1.  <span id="_Toc4" class="anchor"></span>Objectives

Objectives for the monitoring system include:

-   Minimize costs

<!-- -->

-   Minimize the possibility of theft

<!-- -->

-   Report data

<!-- -->

-   Be simple to install and maintain

<!-- -->

-   Reliably log data daily and send data as close to daily as possible

    1.  <span id="_Toc5" class="anchor"></span>Constraints

The design must meet the following constraints:

-   Operate within the temperature range of -20°C to 50°C

<!-- -->

-   Operate under high winds and varying environmental elements

<!-- -->

-   Be self-sustaining, in regards to power and operation

<!-- -->

-   Cost less than \$30

<!-- -->

-   Not interfere with the structural integrity of the tank without
    > increasing the risk of tank failure

<!-- -->

-   Maintain the health standard of the water without introducing
    > further impurities

    1.  <span id="_Toc6" class="anchor"></span>Functions

The design should perform the following primary functions:

-   Measure water volume

<!-- -->

-   Process data

<!-- -->

-   Store data

<!-- -->

-   Send data

<!-- -->

-   Power the system

<!-- -->

-   Protect monitoring system from theft and weather conditions

Given the team’s success in implementing the primary functions, the team
will direct attention to these following secondary functions:

-   Visualize data via a web platform

<!-- -->

-   Measure water clarity

<!-- -->

-   Measure water temperature

<!-- -->

-   Measure tank cleanliness

<!-- -->

-   Detect rainfall

<!-- -->

-   Measure the exit flow rate of the water

<!-- -->

-   Report tank status when in need of maintenance

    1.  <span id="_Toc7" class="anchor"></span>Deliverables

By the end of the fall semester, the team will deliver:

-   Multiple design alternatives for the monitoring system

<!-- -->

-   An evaluation of these designs

<!-- -->

-   A schematic and a professional model of the preferred alternative

<!-- -->

-   A functional prototype

<!-- -->

-   A test plan for evaluating the prototype

<!-- -->

-   Project documentation and presentations including:

    -   Work Plan

    <!-- -->

    -   Midyear Report

    <!-- -->

    -   Design Review with RainCatcher

    <!-- -->

    -   Three internal Clinic presentations

By the end of the spring semester, the team will deliver:

-   An improved monitoring system, possibly including some secondary
    > functions

<!-- -->

-   Formalized test results

<!-- -->

-   Project documentation and presentations including:

    -   Final Report

    <!-- -->

    -   Detailed engineering drawings of the system

    <!-- -->

    -   Complete documentation of the fabrication process for the system

    <!-- -->

    -   Spring semester presentation at Harvey Mudd College

    <!-- -->

    -   Projects Day presentation

    <!-- -->

    -   Final Presentation to the Malibu Rotary Club or RainCatcher
        > Board of Advisors

1.  <span id="_Toc8" class="anchor"></span>Background

Based on initial research into possible solutions, the team broke the
overall system into several subsystems. These subsystems can be
visualized in the block diagram below, in Figure 1.

<span id="_Ref430790129" class="anchor"></span>Figure 1: Block diagram
of the subsystems of this project.

There are many ways to solve the problem at hand and build each
subsystem. This section will detail some of the most common methods
which can inform the design of the primary subsystems of this project:
power, volume sensing, system control, and data transmission.

1.  <span id="_Toc9" class="anchor"><span id="_Ref430737486"
    class="anchor"></span></span>Power

There are two main approaches to provide electrical power to a system
without access to an electrical grid. The first is to use stored energy,
and the second is to generate electricity. There are limitations
pertaining to the reliability and efficiency of large-scale energy
storage, but due to the low power requirements of this project, this
section will focus on small-scale batteries. Batteries store energy in
the form of chemical energy that can then be converted to electricity. A
basic schematic of a battery in a circuit is shown below in Figure 2.

![](media/image2.png)

<span id="_Ref430735128" class="anchor"></span>Figure 2<span
id="_Ref430735116" class="anchor"></span>: Schematic of a basic battery
\[1\].

As shown in Figure 2, a battery has three main components, the cathode,
anode, and electrolyte. The anode and cathode are metals, where the
metals are chosen based on their ability to oxidize (receive electrons)
and reduce (give away electrons), respectively. The electrolyte is the
conductive medium for the electrons to transfer through. Due to the
anode’s affinity to oxidize, electrons flow across the electrolyte from
the cathode to the anode \[2\]. Thus a charged battery has a surplus of
electrons in the anode and a lower number of electrons in the cathode,
which creates a charge differential. As soon as the circuit is
completed, the electrons begin to flow from the anode to the cathode,
which creates electricity and depletes the potential in the battery. In
a non-chargeable battery, once this potential is depleted and the anode
and cathode become neutralized, the battery is dead \[3\].

An alternative to relying on a disposable battery is to use a
rechargeable battery. A common system to recharge a battery involves
using solar energy. To recharge a battery, an external power source runs
current through the battery in the opposite direction, which causes an
electrochemical reaction to reset the original chemical compounds. The
forward reaction then becomes available for electrons to flow from the
anode to cathode again \[3\]. Rechargeable batteries can provide more
power over their lifetime than disposable ones, but they have a higher
self-discharge rate \[3\]. The following figure demonstrates a simple
way to construct a solar panel charging circuit.

Figure 3: Basic schematic for recharging batteries via solar panel
outputs

This circuit directly sends the electricity generated from the solar
panel to the batteries, but it doesn’t protect the system from being
damaged. Batteries can be damaged by being charged too quickly, for too
long, or with too much power. Solar panels can be damaged when current
switches direction after the batteries are fully charged \[4\]. Thus the
charging circuit needs to be improved.

Figure 4, shown below, shows how a diode can be added to the circuit to
prevent current from flowing in the wrong direction.

<span id="_Ref431246836" class="anchor"></span>Figure 4: Solar powered
battery charging with a diode to control the direction of current flow

The next level of protection to consider would be to control the power
being used to charge the battery. Figure 5 shows the LM317 voltage
regulator being used to control the current flowing out of the solar
panels into the battery.

<span id="_Ref431375998" class="anchor"></span>Figure 5: A LM317 voltage
regulator can be used to regulate the current into the charging
batteries.

A microcontroller can be used to monitor the voltage across the battery
and control the level of charging based on the charge of the battery. If
rapid charging is not needed, a trickle charge - that is, the
slow-charging current - can be run through the battery for long periods
of time without affecting the battery’s lifetime. The specifics of the
charging control method will depend on the batteries, and the power
available.

The two most commonly used and accepted form of rechargeable betters are
nickle

1.  <span id="_Toc10" class="anchor"><span id="_Ref430791609"
    class="anchor"></span></span>Volume Sensing

Sensing the volume of fluid in a tank is a solved problem for many
companies in the petrol industry and other companies dealing with tanks.
Most industrial solutions integrate multiple sensors and wireless data
reporting with proprietary software for remote management. The sensing
solutions, range from mostly mechanical to mostly electrical in nature.

One common mechanical solution is to use a float attached to a rod that
runs the length of the tank. The float contains a magnet; the rod
contains a number of switches along its length. As shown in Figure 6,
when the liquid level rises, so does the float, although it is
constrained to rise along the rod. The magnet activates a switch when
the float passes near enough to that point on the rod. The height of the
fluid in the tank can then be approximated by determining which switch
along the height of the tank was most recently activated, and the volume
of fluid can be calculated if the dimensions of the tank are known
\[5\]\[6\]^,^.

![](media/image6.png)

<span id="_Ref430790452" class="anchor"></span>Figure 6: A mechanical
float at low volume (left) and higher volume (right).

Other more “invasive” methods used industrially include resistance and
capacitance strips. These devices consist of strips, consisting of
either rods, tape, or other type of leads that project into the tank. As
the fluid in the tank changes, it alters the resistance or capacitance
of the sensing circuit because the water closes the circuit at different
heights.  This change can by measuring the impedance, and processed to
deduce the volume of fluid in the tank.

Another common method of determining the volume of fluid in a tank is to
use an absolute or differential pressure sensor. Absolute pressure
sensors measure the pressure at the base of a water column (i.e. at the
bottom of a tank) relative to a vacuum. The volume of water in the tank
can be determined based on the height of the liquid and the dimensions
of the tank. In contrast, differential pressure sensors measure the
difference in pressure at the bottom of the tank and the ambient
pressure. The difference in pressure correlates with the amount of
liquid in the tank, as seen in Figure 7.

![](media/image7.png)

<span id="_Ref430790891" class="anchor"></span>Figure 7: Schematics of a
(left) absolute pressure sensor equipped to monitor a water tank and
(right) a differential pressure sensor equipped to monitor a water tank,
with high and low pressure valves marked.

In addition to the “contact” methods of measuring fluid levels above,
ultrasonic sensors, radar, or lasers can be used to measure volume in a
tank without directly touching the liquid. An ultrasonic sensor can be
mounted on the top of the tank with its sensing side facing down towards
the water.  The sensing begins with the sensor emitting an ultrasonic
pulse aimed at the surface of liquid in the tank. When the pulse reaches
the surface of the liquid, it bounces back towards the sensor, as seen
in Figure 8. The sensor measures the time between when the pulse is
emitted and when it is received. Because the pulse travels at known
speed through air, the distance between the top of the tank and the
height of the fluid in the tank can be calculated, and from there the
volume of fluid in the tank can be determined. The amount of fluid in
the tank can be measured in the same way using a laser or radar pulse
instead of an ultrasonic pulse simply by using the appropriate emitter
and detector for each type of wave.

![](media/image8.png)

<span id="_Ref430894361" class="anchor"></span>Figure 8: Schematic
representation of non-contact methods of level detection. The sensor
(black box) emits a pulse (red curves) which eventually bounces off the
surface of the water (purple curves) and is detected by the sensor.

All of these methods of volume monitoring require additional processing
and/or control. Thus, we will need to consider sensor compatibility with
various controllers in addition to factors such as size, accuracy, and
ease of installation when selecting a method for determining the level
of water in the tank.

1.  <span id="_Toc11" class="anchor"><span id="_Ref430738306"
    class="anchor"></span></span>System Control

The initial research reveals that a solution involving electronic
systems is more viable than a purely mechanical one. An electronic
solution needs a central unit to process information that streams
through the system. This task can be accomplished by a microcontroller,
a small integrated circuit containing a processing core, memory, and
programmable input/output peripherals. A microcontroller operates by
using a certain arrangement of logic and digital building blocks such as
registers, finite state machines and arithmetic logic units. A
particular microcontroller has its unique architecture that entails
specific trade-offs between performance, cost and complexity. For
example, a microcontroller with a simple architecture might be very
cheap but have a very low performance that cannot perform certain tasks
\[7\]. For this project, the desired microcontroller needs to perform
the following functions: accept inputs from water level sensors, format
and send the data to the transmission unit. These functions, along with
other constraints, play an important role in choosing an appropriate
microcontroller for this project.

![](media/image9.png)

Figure 9: A general architecture of a microcontroller \[8\].

1.  <span id="_Toc12" class="anchor"><span id="_Ref430738765"
    class="anchor"></span></span>Data Transmission

<span id="_Ref430736568" class="anchor"></span>

The methods used to transmit data from place to place are
well-established and diverse, however, for the purposes of this project
the team must choose a data transmission method which fits within the
constraints. Primarily, we must choose a method which will work in
remote areas which may potentially have low connectivity and
transmission speeds. The team has researched a transmission standard
called Global System for Mobile Communication (GSM), more commonly known
as 2G or 3G. In most parts of the world GSM transmits over 900/1800 MHz
frequency bands, however within US and Canadian borders GSM networks use
850/1900 MHz bands, thus the team must ensure compatibility of the
delivered prototype across global regions. GSM uses General Packet Radio
Service (GPRS), a best-effort protocol which uses Time Division Multiple
Access with a throughput up to 15 kilobytes/sec over a 2G network
\[10\]\[11\]. GSM devices are identified by the network and have their
permissions verified via a Subscriber Identity Module, often called a
SIM card. Given the availability of GSM network in the relevant
locations, the team can equip a microcontroller to transmit data to an
Internet-accessible server, as shown in Figure 8.![](media/image10.png)

<span id="ref430736568" class="anchor"></span>Figure 8: Overview of GSM
Network \[12\].

In some cases GSM networks will not be available, yet data still can
travel from place to place using technologies which do not rely upon
cellular networks. These include satellite and long-range packet radio
networks. Satellite transmission would require additional large hardware
components attached to the team’s system, as well as requiring a higher
level of power consumption to generate a strong radio signal which could
be received in space. If long-range radio waves are used to transmit
data, the team’s solution would require a network-connected radio
transceiver to upload sensor data to the Internet. Data packets can be
transmitted to a common base using the AX.25 protocol which is
traditionally used among amateur radio operators \[13\]. All three of
these technologies can be utilized with a micro-processing unit, but the
ease of integration, power-consumption, and financial costs associated
with each must be considered before choosing a primary implementation
strategy.

1.  <span id="_Toc13" class="anchor"></span>technical approach

Since the primary goal of this project is to produce a well-tested,
highly functional prototype, the team will begin prototyping and testing
as early as possible. In order to make sure there is enough time for
designs to fail and be revised, early prototyping is a fundamental part
of the design process. This section will discuss the design alternatives
considered by the team and will conclude with a description of the most
viable design that will be pursued for the first prototype. Early
prototypes will depend more heavily on commercial products for ease of
timely design, but many of these components may eventually be built
in-house to reduce costs.

The team has started by comparing multiple methods of meeting each
function. Section 3.1 enumerates the alternatives presently under
consideration and provides an initial comparison of the alternatives.
 Section 3.2 describes how the team plans to complete a detailed design
of the preferred alternative, and Section 3.3 addresses testing.

1.  <span id="_Toc14" class="anchor"><span id="_Ref272263111"
    class="anchor"></span></span>Design alternatives

In this section the team presents proposed design alternatives for each
distinct component of the system. The costs and benefits of each design
alternative are discussed as well as its effect upon related components.

1.  <span id="_Toc15" class="anchor"></span>Power

As discussed in the Section 2.1, there are a few different ways to power
a system off-grid. This section will outline three primary alternatives-
sustainable battery charging, disposable batteries, and rechargeable
batteries. The first method to provide electricity to the system is to
use a renewable source to charge rechargeable batteries, and power the
system from the batteries. Variations on this design are due to
different renewable energy sources, i.e. solar, a wind turbine, or a
water turbine in the tap of the tank to harness the flowing water
energy. A solar panel or wind turbine would need to be installed at the
top of the tank, whereas the water turbine would need to be fixed into
the tap.

The second and third if the system consumes low enough power to run for
a year on two to four AA (or similar) batteries, the client would be
satisfied. Given that on-site visits to each tank would never be
completely eliminated, even with good remote performance data, a minimal
amount of annual maintenance at each site could be considered. Batteries
are valuable at the field locations, so hiding and/or securing the
batteries will be an important aspect of either design.

Using renewable energy to charge the system would raise the upfront cost
of the system, but it would be more sustainable and could withstand
higher power demands. Using new batteries each year would decrease the
initial cost of the system, but it would contribute to the ongoing cost
of the system and to other environmental concerns.

Since cost is the most limiting constraint and low-maintenance is
priority, the most viable method for renewable power is solar. Solar
panels, for the scale of power required, can be less than \$5 from
Sundance Solar. From research on Amazon, eBay, and turbine
manufacturers, wind turbines or water turbines would far exceed the \$30
budget alone and the requirement of wind at each tank is difficult to
guarantee. Additionally, dependence on mechanical systems and moving
parts increases the risk of system failure. Solar panels are less
complicated to install and would more reliably generate power. The
client seems to favor a minimally invasive solution, which, in addition
to cost, is another deterrent from a water turbine. Such a design would
need to adapt to multiple tap fitting sizes and would create high risk
for leaks or tank failure.

Ultimately, research into design alternatives for powering the system
come down to a combination of solar and batteries. Table 1 compiles some
of the product alternatives to build a system powered by solar charged
batteries or primary batteries. The product information is taken from
the specifications as reported by the vendors Amazon, Sundance Solar,
SunLabz, eBay, and DigiKey as accessed on September 21, 2015.

  ---------------------------- --------------------------------------- ---------------- -----------------
                               **Product**                             **Cost (USD)**   **Output**
  **Solar Panel**              EachBuyer, mini Panel for DIY charger   2.25             5V 160mA
                                                                                        
                               Sundance Solar, 700-10850-21            5.39             4V 100mA
  **Rechargeable Batteries**   AA NiMH AmazonBasics                    1.70 per unit    2,000 mAh
                               SunLabz, AA NiMH                        2.00 per unit    2,600 mAh
  **Charger IC**               TSM101AIDT                              0.75             -0.3 to Vcc-1.5
                               L7805 Voltage Regulator                 0.95             5 V
  **Disposable Batteries **    Amazon AA Duracell                      .40 per unit     1.5 V
                               Amazon AA AmazonBasics                  .30 per unit     1.5 V
  ---------------------------- --------------------------------------- ---------------- -----------------

<span id="_Ref430737940" class="anchor"></span>Table 1: Product
comparison chart for power components.

Because the system only needs to be awake to collect data once a day,
the batteries can be slow-charged gradually throughout the day. This
means that a low power solar panel will be sufficient. The exact number
of batteries that would be necessary to power the system will depend on
the other subsystems of this project.

Table 2 summarizes the three most viable design alternatives for
powering the system. The first is the only fully self-sufficient model,
where two batteries are used and recharged via solar. The second is to
use rechargeable batteries, and on each annual visit, the rechargeable
batteries can be removed, different batteries can be installed, and the
depleted batteries can be charged to be used at another site. The third
model is to buy and replace the disposable batteries at each location.
The pricing for these alternatives is based off of the product listed in
Table 1.

  ------------------------------------------- ------------------------------------------
  **Power Source**                            **Approximate Price**
  Solar Panel, 4 rechargeable batteries, IC   \$13 (one time cost)
  4 rechargeable batteries                    \$8 (one time cost, annual maintenance)
  4 disposable batteries                      \$1.50 (annual cost, annual maintenance)
  ------------------------------------------- ------------------------------------------

<span id="_Ref430738083" class="anchor"></span>Table 2: Cost comparison
of power design alternatives.

1.  <span id="_Toc16" class="anchor"></span>Volume Sensing

As discussed in the technical background Section 2.2, there are many
options for sensing the level of water in the tank. Key considerations
when evaluating possible sensor systems include cost, ease of
installation/calibration, power consumption, processor compatibility,
accuracy, precision, resolution, response/output format, and failure
rate.

A float mechanism may be costly because of the internal magnets and the
complicated installation process. The float requires little electronic
calibration and processing or control but may require significant
modifications to the tank during installation. Also, the float is
largely mechanical, and even though it would consume a small amount of
power, moving parts are the most prone to failure.

Commercial resistive water level sensors are very expensive, priced
about \$5 for a strip spanning a few inches and nearly \$40 for a sensor
about one foot long \[13\]\[14\].  However, it is also possible that a
non-commercial resistance sensor could be constructed in-house at a
lower cost. As RainCatcher’s tanks are 1.5-3m tall, several commercial
sensors would be needed to give useful water depth readings, resulting
in a high expense. In addition, the strips would need to be installed
along the length of the tank, increasing the invasiveness of
installation. A significant barrier to this method is not knowing the
impedance of the rainwater. Murky or contaminated water will have higher
impedance than pure water, making it difficult to detect small changes
in impedance due to the water level without using dangerous amounts of
current.

An absolute pressure sensor could be mounted by drilling into the side
of the tank or possibly dropping the sensor into the tank. The absolute
pressure sensors which meet the required functions and constraints are
about \$10-\$15 \[15\]. Calibration procedure is usually given by the
manufacturer. In addition, research suggests that the sensors require
fairly low current, about 1-2 mA.  In terms of compatibility, many
available absolute pressure sensors output voltage, which should be
compatible with most processors. One sensor provides 0.5% static
accuracy, which should meet system requirements. The most likely point
of failure for this method is the port on the sensor, to which we’d have
to connect a tube, which would be vulnerable to failure. In addition,
this method depends largely on ambient pressure and on the fluid having
constant density.

A differential pressure sensor costs more than an absolute pressure
sensor. This type of sensor also depends on the fluid having constant
density, but it is independent of ambient pressure. One of the least
expensive differential pressure options, MPX5050DP, has a maximum error
of 6.25% over an operating temperature of -40°C to 125°C and functions
at pressures up to 200 kPa \[16\]. This sensor requires 5V of power and
produces a DC voltage output. The difficulty of calibration and
installation depends on where in the tank the sensor is installed.

Of the many ultrasonic sensors available, cost suggests that the HC-SR04
is one of the most viable alternatives for this project. The HC-SR04 is
available for under \$3 and can be installed simply at the top of the
tank. It has a sensing range of 2-450cm and a precision of up to 3mm
\[17\]. A potential issue with an ultrasonic sensor is that the accuracy
of the measurement depends on the geometry of the tanks. Depending on
the radius of the signal, especially if the water level is low and the
signal is traveling long distances before returning, the sonar wave may
become too dissipated or interfere with the tank walls.

Investigation into other non-contact methods of measuring the water
level (lasers, radar sensor) demonstrated that they would be
prohibitively expensive. Radar level sensors ranged from about \$500 to
over \$5000. Cheap lasers exist, but consume large amounts of power and
might be difficult to align.

1.  <span id="_Toc17" class="anchor"></span>System Control

There are a large variety of microcontrollers that are capable of all
required functionalities described in Section 2.3. The system has to
cost less than \$30, so the microcontroller unit has to be relatively
cheap. Additionally, this project has a relatively short time limit of
only two academic semesters, so microcontrollers that have readily
programmable platforms are preferred. These microcontrollers will
shorten the time required to configure them to be functional.

A widely supported programmable platform is Arduino. This platform has
several libraries that abstracts away most of low-level programming and
also has a variety of development boards that significantly eases the
process of programming. As a result, Arduino-compatible microcontrollers
are examined. Table 3 compares price, performance and functionalities of
four chips from three different families. All data were extracted from
the datasheet of each chip provided by Digikey website as of 9/20/2015.

<span id="_Ref430738472" class="anchor"></span>

  ------------------------- --------------- ---------------- -------------- ---------------
                            **ATMega328**   **ATMega2560**   **ATTiny84**   **SAM3X8E**
  **Family**                megaAVR         megaAVR          tinyAVR        ARM Cortex-M3
  **Unit Price (USD)**      2.47            12.94            1.25           9.39
  **ADC Accuracy (bits)**   10              10               8              12
  **ADC Channel**           8               16               8              12
  **Digital Pin**           14              54               11             54
  **Speed (MHz)**           16              16               20             84
  ------------------------- --------------- ---------------- -------------- ---------------

<span id="_Ref430933991" class="anchor"></span>Table 3: Arduino
compatible chip comparisons.

The two low-end chips are ATMega328 and ATTiny84. ATMega328 is the
current official chip used on Arduino USB Board (UNO R3) \[18\]. It is
compatible with most existing Arduino libraries and shields, so
ATMega328 can be readily programmed without prolonged chip configuration
\[19\]. ATTiny84 has fewer pins and has a lower Analog to Digital
Converter (ADC) resolution than ATMega328. It is also not officially
supported by Arduino platform, but some modifications can be made to
make it compatible \[20\]. Even though ATTiny84 is not as readily
programmable and powerful as ATMega328, it costs less than half the
price of ATMega328. These two chips have both surface-mount and
through-hole counterparts, so they are very easy to use in a prototype
without the need for breakout boards.

The two high-end chips are ATMega2560 and SAM3X8E. Both chips have a
very high number of analog and digital pins. SAM3X8E also boasts a
better ADC accuracy of 12 bits and a relatively fast clock cycle of
84MHz. ATMega2560 and SAM3X8E are compatible with Arduino programming
platform, but they might not be supported by all libraries, especially
those written specifically for Arduino UNO. Despite the relatively high
costs, both chips can handle demanding tasks and also allow the project
to be readily expandable because of available pins. However, these two
chips do not have a through-hole version, so using them in a prototype
will be challenging.

1.  <span id="_Toc18" class="anchor"></span> Data Transmission

<span id="_Ref272263121" class="anchor"></span>

<span id="_Ref430900238" class="anchor"></span>

<span id="_Ref430739085" class="anchor"></span>

<span id="ref272263121" class="anchor"></span>In this project, one of
the primary concerns is the availability of a cellular network in
undeveloped areas of Kenya, Uganda, and the Navajo Nation. In cases when
a cell signal is available, it is straightforward to equip a
microcontroller to transmit the collected data. The existing cellular
network infrastructure is already designed to relay data to an Internet
server \[See Figure 8 in Section 2.4 above\]. The data can then be
formatted and presented to a user on a web page.

In cases when a cellular connection is not available, the team must
implement an appropriate secondary data handling system. Other
alternatives under consideration include satellite and radio
transmission. Both of these alternatives are feasible, however, they
require more hardware components, likely increasing overall financial
costs and power consumption. The cost associated with a
satellite-connected device is substantially more than that of a cellular
device, but it does guarantee global coverage. Radio transmission can be
done using packet network transmissions to a shared transceiver within
the range of the transmitting device. Cursory research suggests that
packet radio transmitters can transmit ranges of up to 60 kilometers, a
distance which is sufficient for many tank locations. Based on the GPS
coordinates of existing tank locations, as shown in Figure 9, it appears
that many of the tanks are located in regional clusters, increasing the
utility of a centrally located radio transmitter.

![](media/image11.png)

<span id="ref430900238" class="anchor"></span>Figure 9: GPS locations of
RainCatcher tanks in Kenya and Uganda.

An approach utilizing packet radio transmission instead of cellular
networks, however, may require installation and maintenance of many
additional network nodes, such as base transceiver stations. These
stations would need to be placed in the range of multiple tanks and
individually configured to upload data to the Internet. While radio is a
potentially feasible secondary alternative, it introduces significant
complexity and cost to the system. Both satellite and packet radio
technologies may utilize more power than an implementation using a
cellular network due to the fact that they do not rely upon existing
network infrastructure and attempt to transmit over longer ranges.

Formatting data will vary depending on the transmission or storage
method employed. The primary design alternative involves transmitting
formatted, packetized data over an existing cellular network. If data is
transmitted over a GSM cellular network it would be intuitive to send
the data in the body of one or more network messages. If packet radio is
used, data should be packetized according to the supported protocol
(AX.25) \[22\].

In instances where no network is available, the system must be able to
store data until a network becomes available or until a human manually
uploads the stored data to the Internet. All of the team’s design
alternatives will take into consideration the possibility of network
failure and be prepared to store data. The system must be equipped with
some amount of system memory wh![](media/image12.png)ich can store
sensor data until the available memory is filled. As shown in Figure 10
microcontrollers such as the Arduino Nano, can be integrated with simple
plug-and-play flash memory cards \[23\]. Since it is possible that data
will need to be manually uploaded from a personal computer, all system
installations will need to be accessible by humans.

<span id="ref430739085" class="anchor"></span>Figure 10: Micro SD Card
interfacing with an Arduino Nano \[24\].

1.  <span id="_Toc19" class="anchor"></span>Housing

Considering that the system will be exposed to environmental elements,
the electronics in the system must be water resistant such that the
bottom of the system is dry and precipitation will not enter the system
to short circuit anything.  If the system is to be mounted on the top of
the tanks, a basic concept would be simply a container with its lid with
its sides overlapping the sides of the compartment.  A viable design has
been commercially produced by Protocase, as shown in Figure 13.
Protocase is a company that makes electronic containers of varying
sizes, which can fit around this system.  Another option is to uniquely
model a container to be 3D printed with the similar outline to fit the
system snugly.

![](media/image1.jpeg)

<span id="_Ref430739202" class="anchor"></span>Figure 13: Sample of a
Protocase box to contain and protect electronics \[24\].

The printed circuit board and other electronics that are in the final
alternative would be stored within the box, but the wires and exterior
parts may lead out from the box.  When there are parts extending from
the box there should be sealant to fill the holes in the container.

The advantages of this design are that it can be mounted on any surface
and affords easy access to the electronics within.  It also serves the
purpose of protecting the electronics from weather and other
environmental conditions.  One disadvantage would be the ease of theft,
given the use of standard screws which easily be removed. Using
tamper-proof screws, however, would prevent the electronics to be easily
stolen.

If the team chooses to build the container in-house it may be necessary
to waterproof it manually.  This can be simply accomplished by applying
a sealant or liquid repellant coating.  More reliable coatings tend to
run at a higher cost, which may exceed the target budget of \$30 per
unit \[25\]\[26\].  If an entirely water-resistant system is preferred
after testing, using O-rings would further seal gaps between the screws
and container parts.

In regards to securing a solar panel, current literature has suggested
the effectiveness or welding or gluing solar panels, or using one-way
screws \[27\]\[28\].  Further testing may demonstrate that one method is
more effective than another.

1.  <span id="_Toc20" class="anchor"><span id="_Ref431196547"
    class="anchor"></span></span>Preliminary design

In order to ultimately meet the cost constraint of this project, design
alternatives for each subsystem will be tried in various combinations.
The following sections describe the most promising first alternative the
team will pursue, as broken down by subsystem.

1.  <span id="_Toc21" class="anchor"></span>Power

The team will begin prototyping using the solar powered design
alternative, aiming to build a fully self-sufficient system. Based on
the power constraints of the rest of the system, the power supply may
need to be adjusted. When a functional prototype has been built,
financial and power costs will need to be reevaluated. If the cost of
the solar power components can be minimized, while also fulfilling the
power requirements of the system, solar power could be a sustainable,
low-maintenance solution. Alternatively, systems that depend solely on
batteries will be explored.

1.  <span id="_Toc22" class="anchor"></span>Volume Sensing

Certain pressure sensors, ultrasonic sensors, and possibly a homemade
resistance sensor are the only sensing methods within the \$30 budget.
Within this category, ultrasonic sensors are the least expensive. They
also require less additional hardware compared to the pressure sensors.
At least one type of ultrasonic sensor (HCS04) is available for less
than \$5, and it operates over the temperature and distance ranges
expected. In addition, this sensor runs on 5V, well within the
capabilities of all power alternatives under consideration. The HCS04 is
also known to be Arduino-compatible, which will accelerate the sensing
prototype process. The installation of an ultrasonic sensor requires
only one opening at the top of the tank.  Although extensive testing of
the ultrasonic sensor is required before it is adopted as a final
design, the ultrasonic sensor is a clear frontrunner in fulfilling the
functional constraints of this project.

To ensure that other in-budget sensing possibilities are fully explored,
a differential pressure sensor will also be tested in a tank. The
homemade resistance sensor might be explored later in an effort to
reduce total cost, but it is a more invasive and likely less precise
solution.

1.  <span id="_Toc23" class="anchor"></span>System Control

The preliminary design of the system indicates that the performance and
the number of I/O pins are not the main concerns. The system is required
to transmit data only once every 24 hours, so the speed of the
microcontroller does not play an important role in selecting a specific
device. The cost of the system is also more important than the
functionalities; as long as the system can achieve basic functionality,
minimizing the cost is more critical than adding more features. As a
result, the low-end microcontrollers: ATMega328 and ATTiny84 are more
appropriate than their high-end alternatives.

ATMega328 surpasses ATTiny84 in terms of programmability since it is
widely supported and is readily compatible with the Arduino platform. It
can be directly programmed with Arduino IDE and with a development board
Arduino UNO R3, which is commercially available. The through-hole
counterpart of the chip will also allow the first prototyping phase to
be done on breadboard without the development board. Additionally,
ATMega328 has a more precise ADC converter than ATTiny84, so it can be
used to directly accept sensitive analog inputs from a larger variety of
analog sensors. This advantage will allow more alternatives for the
sensing part of the system. Even though ATMega328 costs twice as much as
ATTiny84, the price difference is only \$1.25. Consequently, ATMega328
is chosen for the preliminary prototyping and testing. However, if it is
necessary to reduce the price of the system further, the code written
for ATMega328 can be translated to a code for ATTiny84 to reduce costs.

1.  <span id="_Toc24" class="anchor"></span>Data Transmission

As stated previously, the primary transmission design will depend upon
the availability of a cellular network at the installation sites for
existing filtration systems. Preliminary research suggests that 2G
networks do exist throughout most of these regions, so an approach
utilizing a cellular network will be the primary design alternative. A
microcontroller will be equipped to connect to the cellular network
using a GSM module and SIM card. To allow for the extensibility of
RainCatcher’s involvement to new areas of the globe, the system will not
solely depend upon the availability of cellular networks but will also
be designed to collect and store data on an SD card for implementation
in locations where no network is available.

1.  <span id="_Toc25" class="anchor"></span>Housing

The preliminary housing design will consist of a surface mounted
container waterproofed using a sealant. The plastic used should be
strong enough to withstand harsh environmental conditions.  In the
prototyping phase the team will utilize a commercially available
container, however, cost may later be reduced by designing a custom
housing for the electronic components. The solar panels will be glued
permanently to the container. To protect the system against theft, the
fasteners used in the housing will be one-way screws which require a
special tool to remove.

1.  <span id="_Toc26" class="anchor"><span id="_Ref272263127"
    class="anchor"></span></span>testing

The team will need to concretely verify that the prototype meets the
constraints and performs according to the project’s objectives. The
first stage of testing will occur on campus, by either purchasing a
small-scale water tank or by otherwise simulating onsite conditions.
Once rigorous testing is completed, the next stage will involve field
testing in the Navajo Nation in New Mexico to quantify reliability.
 Finally, if the Navajo Nation testing proves promising, further work
will be done to polish the design and take it to Uganda or Kenya for the
final phase of testing.

To test the power system, the solar panels and power system will be left
outside during sunlight hours. The amount of power collected by the
panel will be tracked by the amount of charge in the batteries. A
critical variable in the function of the power subsystem is the incident
angle of sun rays. The testing procedure will determine the ideal angle
of incidence for maximizing energy storage. A third variable to consider
is the amount that cloud coverage affects the collection of power. Once
the team has confirmed that sufficient power can be supplied to the
system, the team will test the entire system using the collected solar
power. The control of the power of the system will also involve
extensive testing to ensure batteries are being charged safely over long
periods of time.

The sensors will be tested with the microcontroller to ensure a reliable
connection and accurate data measurement.  Subsequently, it will be
tested under environmental conditions similar to that of the existing
tanks, specifically in cases where moisture and flowing water will enter
the tank.

The majority of testing for the microcontroller is focused on the coding
and wiring of the circuit.  The system will be continually tested in
development until the microcontroller can send data reliably. Initial
testing will involve using Arduino for ease of programming, but
eventually, the circuit will be built with the stand-alone chip.  

To test data transmission, the team will set up the prototype and send
small packets of data through the cellular network. If this test is
successful, the prototype may be tested under disrupted network
conditions. A test will consist of disconnecting the system from the
cellular network and checking if the data collected is stored and later
transmitted upon reconnection. This would test the functionality of the
system when the cellular network is unreliable or variable. If the
cellular network solution fails, the team will consider the packet radio
implementation as a secondary approach.

The housing will be tested to ensure security and water-tightness.  To
test for water-tightness, the housing will be set on top of an elevated
flat surface positioned over a bucket.  Water will be poured over the
housing container and runoff will be retained in the bucket.  The major
test will be to check that the housing does not trap standing water. The
secondary test will be the amount of moisture found inside the system.
If an initial test is unsatisfactory, then further waterproofing methods
will be used and tested.

Initially, testing will occur independently for each subsystem, but as
components prove promising, the full system will require additional
testing. The team will ensure that all subsystems cooperate well
together and use the expected power consumption. The complete prototype
will be tested under a variety of potentially detrimental environmental
conditions. To confirm self-sufficiency, the system will be run and
tested over multiple days. The team will conduct integrated testing
under low sunlight conditions, testing the effect of precipitation on
the system in the event of tank overflow. Finally, the system will be
tested under a variety of weather conditions such as extreme wind, heat,
and cold.

1.  <span id="_Toc27" class="anchor"></span>Project Management

The RainCatcher Clinic Team has developed a work breakdown structure
identifying the tasks to be performed, a Gantt chart laying out the
critical path through the project, and an initial partitioning of the
labor among team members.

1.  <span id="_Toc28" class="anchor"></span>Work Breakdown Structure

The work breakdown structure in Figure 14 shows how the project has been
hierarchically subdivided into more specific and manageable tasks.

***Activity Time (hours)***

Background research *(already complete) 10%*

Lab testing 45

Field testing 5

Existing solutions 2

RainCatcher 4

Team Meetings 15%

Teleconferences 30 × 5 × 1 = 150

Administrative Internal Team Meetings 30 × 5 × .5 = 75

Team Leader Meetings 7

Presentation and Preparation 10%

Orientation Day 3 × 5 = 15

Fall Review \#1 2 × 5 = 10

Fall Review \#2 3 × 5 = 15

Fall Review \#3 3 × 5 = 15

Fall Site Visit 6 × 5 = 30

Spring Presentation 6 × 5 = 30

Projects Day Presentation 6 × 5 = 30

Design 20%

Conceptual Design 50%

Research

Power Supply 6

Sensors 6

System Control 6

Data Transmission 6

Housing 2

Comparison of Alternatives 3 × 5 = 15

Detailed Design *(significant uncertainty in these initial estimates)
50%*

Component selection 10

Prototyping

> Integrating components 20

Iterative prototyping 40

Testing *(significant uncertainty in these initial estimates pending
results) 30%*

Test Plan

Initial component testing

Power 4

> Sensors 2

System Control 2

Transmission 4

Housing 2

Prototype testing

Spring Site Visit (Navajo Nation) 48 × 5 = 240

Components 30

In house 50

Field 20

Reports 15%

Team Charter 5

Work Plan

Background 20

Design Alternatives 20

Testing 5

Project Management 20

Other sections 10

Writing Center Review 2

Midyear Report 80

Final Report 80

Total Time 1326

<span id="_Ref270322113" class="anchor"></span>Figure 14 : Work
Breakdown Structure

1.  <span id="_Toc29" class="anchor"></span>Schedule

The Gantt chart in Figure 15 shows that the critical path for the fall
involves conceptual design, selection of a preferred alternative,
detailed design for that alternative, and sending the design for
manufacturing. The team anticipates testing, redesign, and further
testing in the spring; the details will be flushed out in the Midyear
report based on the fall progress.

![](media/image13.png)

<span id="_Ref430740069" class="anchor"></span>Figure 15 Gantt chart

1.  <span id="_Toc30" class="anchor"></span>Division of labor

The team anticipates the following division of the major tasks in the
project:

***Activity Owner***

Conceptual Design

Power Supply Nithya, Michael, Cherlyn

Sensors Nithya, Jozi

System Control Michael

Data Transmission Jozi, Heather, Michael

Housing Cherlyn

Detailed Design

Component selection All

Integrating components All

Iterative prototype All

Test Plan Cherlyn

Testing All

Presentation and Preparation All

Reports All

1.  <span id="_Toc31" class="anchor"></span>References

<!-- -->

1.  <span id="_Ref270362522" class="anchor"></span>“How do batteries
    work?” \[Online\].
    Available: http://www.qrg.northwestern.edu/projects/vss/docs/power/2-how-do-batteries-work.html.
    \[Accessed: September 24, 2015\].

2.  <span id="_Ref430890016" class="anchor"></span>“How does a battery
    work?” May 2012. \[Online\].
    Available: http://engineering.mit.edu/ask/how-does-battery-work.
    \[Accessed: September 24, 2015\].

3.  <span id="_Ref430890152" class="anchor"></span>“Cell Chemistries”
    May 2012. \[Online\].
    Available: http://www.mpoweruk.com/chemistries.htm. \[Accessed:
    September 24, 2015\].

4.  <span id="_Ref430890366" class="anchor"></span>“Solar Battery
    Charging” \[Online\].
    Available: http://www.reuk.co.uk/Solar-Battery-Charging.htm.
    \[Accessed: September 24, 2015\].

5.  <span id="_Ref430929906"
    class="anchor"></span>“IOM\_291.pdf,”\[Online\].
    Available:  http://www.dwyer-inst.com/PDF\_files/IOM\_291.pdf.
    \[Accessed: September 20, 2015\].

6.  <span id="_Ref430929907" class="anchor"></span>“Custom Fuel Tank
    Probes, Float Kits, and Tank Level Gauge by
    Veeder-Root,” \[Online\].
    Available: http://www.veeder.com/us/probe-float-kit-tank-level-gauge.
    \[Accessed: September 20, 2015\].[
    ](http://www.veeder.com/us/probe-float-kit-tank-level-gauge)

7.  <span id="_Ref430930108" class="anchor"></span>Harris, David Money.,
    and Sarah L. Harris. *Digital Design and Computer Architecture*.
    Waltham, MA: Morgan Kaufmann, 2013. Print.

8.  <span id="_Ref430930405" class="anchor"></span>“Definition of
    Microcontroller,” \[Online\].
    Available: http://www.pcmag.com/encyclopedia/term/46924/microcontroller.
    \[Accessed: September 24, 2015\].

9.  <span id="_Ref430930506" class="anchor"></span>“How to Send AX.25 UI
    Frames with Using Inexpensive PIC Microcontrollers”. TAPR/ARRL
    Digital Communications Conference Papers. 1998. \[Online\].
    Available: http://tnc-x.com/dcc.doc. \[Accessed: September
    23, 2015\].

10. <span id="_Ref430930691" class="anchor"></span>“How to Receive AX.25
    UI Frames with Using Inexpensive PIC Microcontrollers”. TAPR/ARRL
    Digital Communications Conference Papers. 2000. \[Online\].
    Available: http://tnc-x.com/dcc2.doc \[Accessed: September
    23, 2015\].

11. <span id="_Ref430930853" class="anchor"></span>“SMS GSM Modem
    Platform,” \[Online\].
    Available: http://www.sandcti.com/sms\_mms/sms\_gsm\_SAND.php.
    \[Accessed: September 24, 2015\].

12. <span id="_Ref430930914" class="anchor"></span>“Wireless
    infrastructure for remote environmental monitoring: Deployment and
    evaluation” Mobile and Wireless Networking (MoWNeT), 2013
    International Conference on Selected Topics in Networking.
    2013. \[Online\].
    Available: http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6613799.
    \[Accessed: September 12, 2015\].

13. <span id="_Ref430931021" class="anchor"></span>“Arduinothing - Water
    Sensor,” \[Online\].
    Available: http://arduinothing.wikispaces.com/Water+Sensor.
    \[Accessed: September 20, 2015\].

14. <span id="_Ref430931057" class="anchor"></span>“8 eTape Liquid Level
    Sensor + Extras ID: 463 - \$39.95 : Adafruit Industries, Unique &
    Fun DIY Electronics and Kits,” \[Online\].
     Available: http://www.adafruit.com/products/463?gclid=CNX3vI3XkcgCFQ5rfgodLOoElA.
    \[Accessed: September 20, 2015\].

15. <span id="_Ref430931093" class="anchor"></span>“MPX5050DP Freescale
    Semiconductor | MPX5050DP-ND | DigiKey,” \[Online\].
    Available: http://www.digikey.com/product-detail/en/MPX5050DP/MPX5050DP-ND/464057.
    \[Accessed: September 20, 2015\].

16. <span id="_Ref430931143" class="anchor"></span>“MPXV7002 Integrated
    Silicon Pressure Sensor On-Chip Signal Conditioned, Temperature
    Compensated and Calibrated - Data Sheet -
    4mpxv7007.pdf,” \[Online\].
    Available: http://download.siliconexpert.com/pdfs/2015/1/28/7/24/33/412/fsl\_/manual/4mpxv7007.pdf.
    \[Accessed: September 21, 2015\].

17. <span id="_Ref430931257" class="anchor"></span>“HC-SR04
    User’s\_Manual,” \[Online\]. *Google Docs*.
    Available:  https://docs.google.com/document/d/1Y-yZnNhMYy7rwhAgyL\_pfa39RsB-x2qR4vP8saG73rE/edit?usp=embed\_facebook.
    \[Accessed: September 21, 2015\].

18. <span id="_Ref430931377" class="anchor"></span>“Arduino/Genuino
    UNO,” \[Online\].
    Available: https://www.arduino.cc/en/Main/arduinoBoardUno.
    \[Accessed: September 24, 2015\].

19. <span id="_Ref430931413" class="anchor"></span>“Arduino Comparison
    Chart,” May 2015, \[Online\].
    Available: https://learn.adafruit.com/adafruit-arduino-selection-guide/arduino-comparison-chart.
    \[Accessed: September 24, 2015\].

20. <span id="_Ref430931447" class="anchor"></span>“Tiny AVR Programmer
    Hookup Guide,” \[Online\].
    Available: https://learn.sparkfun.com/tutorials/tiny-avr-programmer-hookup-guide.
    \[Accessed: September 24, 2015\].

21. <span id="_Ref430931821" class="anchor"></span>“AX.25 Link-Layer
    Protocol Specification,” \[Online\].
    Available: https://www.tapr.org/pub\_ax25.html. \[Accessed:
    September 24, 2015\].

22. <span id="_Ref430932000" class="anchor"></span>“Atmel’s Self
    Programming Microcontrollers,” \[Online\].
    Available: http://www.atmel.com/Images/doc2464.pdf. \[Accessed:
    September 24, 2015\].

23. <span id="_Ref430932010" class="anchor"></span>“Mass Storage Device-
    USB Flash Drive,” \[Online\].
    Available: http://www.atmel.com/Images/pc\_peripherial\_flash\_drive\_diagram\_lg.jpg.
    \[Accessed: September 24, 2015\].

24. <span id="_Ref430931522" class="anchor"></span> “WP-20F
    Polycarbonate Electronic Enclosure with NEMA Rating,” \[Online\].
    Available: http://www.polycase.com/wp-20f\#. \[Accessed: September
    24, 2015\].

25. <span id="_Ref430931626" class="anchor"></span>Roach, Paul, Neil J.
    Shirtcliffe and Michael I. Newton. “Progress in superhydrophobic
    surface development,” \[Online\].
    Available: http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.493.5837&rep=rep1&type=pdf.
    \[Accessed: September 24, 2015\].

26. <span id="_Ref430931628" class="anchor"></span>“Hydrobead: Consumer
    Products,” \[Online\].
    Available: http://www.hydrobead.com/\#!consumer/component\_41229.
    \[Accessed: September 24, 2015\].

27. <span id="_Ref430932246" class="anchor"></span>“Solar Panel Theft:
    How Do You Prevent It?” \[Online\].
    Available: http://www.treehugger.com/solar-technology/solar-panel-theft-how-do-you-prevent-it.html.
    \[Accessed: September 24, 2015\].

28. <span id="_Ref430932247" class="anchor"></span>“Solar Panel
    Security- Anti-Theft Devices” \[Online\].
    Available: http://www.energymatters.com.au/panels-modules/solar-panel-security/.
    \[Accessed: September 24, 2015\].

<!-- -->

A.  <span id="_Toc32" class="anchor"></span>team member profiles

Cherlyn Chan is a junior engineering major at Harvey Mudd College.  She
is interested in pursuing mechanical engineering with some emphasis on
sustainability and environmental applications.  In her past internships
and education, she has gained experience in designing mechanical systems
in CAD and implementing sensors in electrical systems.  She has a
passion to use her knowledge in science and technology to serve those
who are lacking basic necessities, such as access to clean water.

Pichaya Michael Lertvilai is a senior engineering major at Harvey Mudd
College. His interest lies in the field of environmental engineering as
he believes that engineering approach is an essential part of the
solution to environmental problems the world is facing. RainCatcher
Global Clinic is an opportunity for him to use his engineering skills to
help solve one of the important environmental problems: clean water
availability. Throughout his education at Harvey Mudd College, Michael
has worked with various types of sensors, designed printed circuit
boards and built many microprocessor-based systems. His engineering
background in system design and electrical engineering will be able to
contribute to the success of the project.

Jožefa (Joži) McKiernan is a senior Mathematical and Computational
Biology major. While her primary interest is biology, she really loves
interdisciplinary work that applies biological principles, and is
considering a career in bioengineering or synthetic biology. Joži has
significant experience scripting and working with mathematical models.
She is also familiar with engineering and design thanks to college
classes and involvement in FIRST robotics. Joži works in the Writing
Center on campus. This semester, she is continuing to do biophysics
research on morning glory petal motion with Professor Gerbode.

Nithya Menon is a senior engineer at Harvey Mudd College. Her background
is split between computer science and engineering, where her engineering
focus is on electrical and mechanical systems, especially the
combination of the fields. The most important part of her interest in
technology is the element of global and social impact that drives her
forward. She would love to use her technical knowledge to boost people’s
potential for sustainable growth around the world. She has done work
with global education and the sustainable development goals, and being
able to affect change in these areas is something she is passionate
about.

Heather Seaman is a Senior Joint Computer Science and Mathematics Major
at Harvey Mudd College. Her interests include application development,
databases, networking, UX/UI design, as well as business and project
management. She has substantial web application development experience,
primarily with Node.js, but has also worked in Java, C++, Python, and
HTML/CSS. She has also completed significant data analysis problems
throughout her coursework at Harvey Mudd College. Heather’s interest in
the RainCatcher project stem from a desire to improve the lives of
people around the world by enhancing their quality of life and
efficiency in daily tasks.
