# Overview of Electric Propulsion

While chemical rockets provide the high thrust necessary to escape Earth's gravity, electric propulsion is the technology that enables sustained exploration and efficient maneuvering in the vacuum of space.

## What is Electric Propulsion?
Electric propulsion uses electrical or electromagnetic energy to accelerate a propellant to extremely high velocities to produce thrust. Unlike chemical rockets, which rely on the energy stored in chemical bonds to create high-pressure gas, EP systems decouple the energy source from the propellant.

The primary trade-off in propulsion is between **thrust** and **efficiency**, reported in terms of specific impulse ($I_{sp}$), which can be thought of as "gas mileage" for a rocket engine. Chemical rockets burn fuel to produce high-pressure gas expelled for massive thrust, but with low efficiency. **Electric propulsion provides much higher efficiency than chemical rockets but at the cost of much lower thrust.**

<div class="grid cards" markdown>

-   <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/13/RS-88_test_firing.jpg/2560px-RS-88_test_firing.jpg" style="height: 220px; width: 100%; object-fit: cover; border-radius: 4px;">

    /// caption
    Chemical rocket engines, with their high thrust, are a great choice for launching spacecraft into orbit.
    ///

-   <img src="https://upload.wikimedia.org/wikipedia/commons/9/9e/Ion_Engine_Test_Firing_-_GPN-2000-000482.jpg" style="height: 220px; width: 100%; object-fit: cover; border-radius: 4px;">

    /// caption
    Electric propulsion devices aren't used in atmospheric flight, but they are used often for in-space maneuvering.
    ///

</div>

## Why Use Electric Propulsion?
As we move from launch to orbit, the mission requirements change. EP is the tool of choice for several reasons:

* EP is ideal for scenarios where efficiency matters more than high thrust.

* High efficiency enables spacecraft to carry significantly less propellant, reducing both launch mass and total mission cost.

* This makes it a great choice for satellite station-keeping, orbit transfers, and deep-space exploration.

!!! tip "A Prolific Technology"
    Fun fact: Electric propulsion devices are currently the most prolific propulsion devices in use, beating out all chemical rocket engines in terms of active systems in space today.

The theoretical foundation of our work starts with Tsiolkovsky's rocket equation. This formula dictates how much "change in velocity" ($\Delta v$) we can get out of our hardware.
$$
\Delta v = v_e \ln \left( \frac{m_0}{m_f} \right)
$$
Because EP systems use electric fields to accelerate particles to incredible speeds, our exhaust velocity $v_e$ is an order of magnitude higher than chemical systems. A higher $v_e$ means we can achieve a higher $\Delta v$ with a much smaller propellant mass $m_0$, allowing for more scientific instrumentation or longer mission lifetimes.

## History of Electric Propulsion

While chemical rockets dominated the early space race, the concept of using electricity to power spacecraft has existed for over a century.

### Early Concepts (1900s)
* 1906: The Goddard Proposal: Robert Goddard, the father of American rocketry, was among the first to propose using electrically accelerated charged particles to produce thrust.

* Theoretical Constraints: While the physics were understood, these early ideas remained purely theoretical for decades due to the lack of compact, high-output power sources needed to ionize and accelerate propellant.

### First Practical Designs (1950s-1960s)
As the Space Age began, the US and USSR began competing to turn theory into hardware.

* Cold War Research: In the 1950s, both nations launched separate research initiatives into electric thrusters to solve the "mass ratio" problem of chemical rockets.

* 1964: SERT-1 Mission: NASA’s Space Electric Rocket Test (SERT-1) successfully tested an ion thruster in space for the first time, proving that beam neutralization, a critical theoretical hurdle, worked in a vacuum.

* Soviet Innovation: While the US focused on ion engines, the Soviet Union pioneered Hall-effect Thrusters (HETs), which would eventually become a backbone of modern satellite propulsion.

<div class="grid cards" markdown>

-   <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/SERT-1_spacecraft.jpg/2560px-SERT-1_spacecraft.jpg" style="height: 220px; width: 100%; object-fit: cover; border-radius: 4px;">

    /// caption
    The SERT-1 spacecraft, with an ion thruster mounted on the right.
    ///

-   <img src="http://www.astronautix.com/graphics/z/zspt100.jpg" style="height: 220px; width: 100%; object-fit: cover; border-radius: 4px;">

    /// caption
    The SPT-100 is a prolific Soviet, and later internationalized, Hall thruster.
    ///

</div>

!!! tip "Stuhlinger and Huntsville's EP Legacy"
    Ernst Stuhlinger was a German-American physicist and a key member of Wernher von Braun's engineering team, authoring the seminal 1964 textbook *Ion Propulsion for Space Flight*, the first comprehensive engineering reference that turned electric propulsion from a sci-fi concept into a rigorous academic discipline.

    He was the first director of the Space Science Lab at NASA Marshall, and after retiring he became a researcher and professor of astrophysics and space science at UAH. The Stuhlinger Medal is the highest honor in the field, awarded biennially to individuals who have made outstanding contributions to the science, technology or development of EP.

### Adoption in Satellites (1970s-1990s)
During this era, EP moved from experimental to operational.

* Station-Keeping: Electric propulsion became the standard for station-keeping and attitude control, allowing satellites to maintain their correct position and orientation with minimal propellant.

* USSR Deployment: The Soviet Union began widely deploying Hall thrusters on their communications satellites.

### The Modern Era (2000s-Present)
EP has proliferated all areas of spaceflight, from low Earth orbit to deep space, across all types of government and commercial spacecraft.

* 1998: Deep Space 1: NASA’s Deep Space 1 mission was the first to use ion propulsion as its primary means of interplanetary travel. This paved the way for the Dawn mission to the asteroid belt, also incorporating an ion thruster.

* Commercial Mainstream: EP is now the default for commercial satellite constellations (like Starlink) due to its extreme efficiency.

* Current Systems: The field today focuses on the two dominant architectures: Gridded Ion Thrusters (GITs) and Hall-effect Thrusters (HETs).

* Future Horizons: Ongoing research is currently pushing into high-power systems for deep-space exploration, including concepts like VASIMR (Variable Specific Impulse Magnetoplasma Rocket), as well as miniaturized systems for small satellites.

## Types of Electric Propulsion Devices

### Electrothermal Thrusters
Electrothermal propulsion is the "bridge" between chemical and electric systems. Electrical energy is used to heat the propellant directly, and the resulting hot gas expands through a conventional nozzle to create thrust, similar to a chemical rocket but without a combustion reaction. They are simpler and more compact than other EP thrusters, offering higher thrust but lower efficiency.

The two major types of electrothermal thrusters are:

* Resistojets: Heat the propellant by passing it over resistive heating elements.

* Arcjets: Use high-energy electric arcs to heat the propellant to much higher temperatures.

### Electrostatic Thrusters
Electrostatic thrusters are the most common EP devices used in spaceflight today due to their high efficiency and moderate power requirements. A neutral gas is bombarded with electrons, causing ionization, the disassociation of atoms into positive ions and free electrons. Strong electric fields accelerate these positive ions out of the thruster at extremely high speeds ($20-50$ km/s). An external electron gun (often a hollow cathode) injects electrons into the exhaust plume to neutralize it, preventing the spacecraft from building up a negative charge.

Three types of electrostatic thrusters are:

* Gridded Ion Thrusters (GIT): Use physical high-voltage grids to accelerate the ion beam.

* Hall-effect Thrusters (HET): Utilize a radial magnetic field and an axial electric field in an annular channel to accelerate ions.

* Field-Emission (FEEP): Use strong electric fields to pull ions directly off a liquid metal surface.

### Electromagnetic Thrusters
These are highly experimental systems and a major area of active research. They produce higher thrust than electrostatic systems but require significantly higher power. Electromagnetic thrusters use combined electric and magnetic fields to accelerate a plasma via the Lorentz Force.

Some examples of experimental electromagnetic thruster systems include:

* Magnetoplasmadynamic (MPD) Thrusters: Uses the Lorentz force on charged particles to create thrust.

* Pulsed Plasma Thrusters (PPT): Use high-voltage pulses to ablate solid propellant (often PTFE/Teflon) into plasma and accelerate it.

* VASIMR: A Variable Specific Impulse Magnetoplasma Rocket that uses RF ionization combined with a magnetic nozzle.

* Pulsed Inductive Thrusters (PIT): Use a high-power induction coil to create a rapidly changing magnetic field, inducing a circular current in a propellant gas to accelerate it via the Lorentz force.

## Our Focus: The Hall-effect Thruster
The main focus of Project OUROBOROS is the development of Hall-effect thruster (HET) systems. Originally developed in the 1960s by the USSR, HETs are now the primary choice for communication satellites and modern deep-space missions, and have been selected for flagship missions like the Lunar Gateway.

The operation of a Hall thruster relies on crossed electric and magnetic fields to create and accelerate plasma.

* A **radial magnetic field** is used to "trap" or impede the flow of electrons toward the anode, forcing them into a circular "Hall current" within an annular discharge channel.

* Neutral propellant (typically xenon) is injected into the channel where it is bombarded by the trapped, high-energy electrons, **creating a dense plasma**.

* Because the electrons are trapped, a strong axial electric field is maintained between the internal anode and the external cathode; this field **accelerates the heavy positive ions** out of the thruster at velocities of $15-30$ km/s.

* The external cathode (hollow cathode) also injects electrons into the exiting ion beam to **neutralize the plume**, preventing the spacecraft from building up a negative charge.

OUROBOROS engages with the EP community by contributing to major areas of active research. Some of these include:

* Magnetic Shielding: Ion bombardment of the channel walls reduces thruster lifetime. Magnetically-shielded thrusters are designed to align magnetic field lines tangent to the walls to prevent ion impact. Research also focuses on understanding how this affects the Hall current and the overall efficiency of the acceleration zone.

* Alternative Propellants: As xenon becomes increasingly expensive due to commercial demand, operators are on the search for cheaper or more mission-specific alternatives. Research falls into three main categories: noble gas alternatives (such as krypton or argon, which are cheaper but less efficient), condensable propellants (solids like iodine, magnesium, zinc, and bismuth that are sublimated), and molecular propellents (monopropellents, air molecules, water).

* Scaling: Researchers are developing 20kW+ systems for heavy cargo transport and human exploration, as well as miniaturized thrusters that can operate at low power levels (under 100W) while maintaining high efficiency.

* Plasma Instabilities and Modeling: The plasma discharge in a Hall-effect thruster is not perfectly stable, leading to oscillations that can degrade performance. The mechanisms behind this are poorly understood. Researchers are investigating low-frequency breathing mode oscillations (10-30 kHz) where the plasma density "breathes" in and out of the channel. One approach is using high-performance computing to create predictive models of plasma behavior to reduce the need for expensive "test-as-you-fly" vacuum chamber runs, but predictive power is limited by the problem of anomalous electron transport.



