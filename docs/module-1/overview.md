# Overview of Electric Propulsion

While chemical rockets provide the high thrust necessary to escape Earth's gravity, Electric Propulsion (EP) is the technology that enables sustained exploration and efficient maneuvering in the vacuum of space.

## What is Electric Propulsion?
Electric propulsion uses electrical or electromagnetic energy to accelerate a propellant to extremely high velocities to produce thrust. Unlike chemical rockets, which rely on the energy stored in chemical bonds to create high-pressure gas, EP systems decouple the energy source from the propellant.

The primary trade-off in propulsion is between **thrust** and **efficiency**, reported in terms of specific impulse ($I_{sp}$), which can be thought of as "gas mileage" for a rocket engine. Chemical rockets burn fuel to produce high-pressure gas expelled for massive thrust, but with low efficiency. **Electric propulsion provides much higher efficiency than chemical rockets but at the cost of lower thrust.**

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

* 1964: SERT-1 Mission: NASA’s Space Electric Rocket Test (SERT-1) successfully tested an ion thruster in space for the first time, proving that beam neutralization—a critical theoretical hurdle—worked in a vacuum.

* Soviet Innovation: While the US focused on Ion engines, the Soviet Union pioneered Hall-effect Thrusters (HETs), which would eventually become a backbone of modern satellite propulsion.

!!! tip "Stuhlinger and Huntsville's EP Legacy"
    Ernst Stuhlinger was a German-American physicist and a key member of Wernher von Braun's engineering team, authoring the seminal 1964 textbook *Ion Propulsion for Space Flight*, the first comprehensive engineering reference that turned electric propulsion from a sci-fi concept into a rigorous academic discipline.

    He was the first director of the Space Science Lab at NASA Marshall, and after retiring he became a researcher and professor of astrophysics and space science at UAH. The Stuhlinger Medal is the highest honor in the field, awarded biennially to individuals who have made outstanding contributions to the science, technology or development of EP.

### Adoption in Satellites (1970s-1990s)
During this era, EP moved from experimental to operational.

* Station-Keeping: Electric propulsion became the standard for "station-keeping" and attitude control, allowing satellites to maintain their orbital slots with minimal propellant.

* USSR Deployment: The Soviet Union began widely deploying Hall thrusters on their communications satellites, proving the long-term reliability of the tech.

### The Modern Era (2000s-Present)
EP is no longer just for small adjustments; it is now used for interplanetary travel.

* 1998: Deep Space 1: NASA’s Deep Space 1 mission was the first to use ion propulsion as its primary means of interplanetary travel, paving the way for the Dawn mission to the asteroid belt.

* Commercial Mainstream: EP is now the default for commercial satellite constellations (like Starlink) due to its extreme efficiency.

* Current Systems: The field today focuses on the two dominant architectures: Gridded Ion Thrusters (GITs) and Hall-effect Thrusters (HETs).

* Future Horizons: Ongoing research is currently pushing into high-power systems for deep-space exploration, including concepts like VASIMR (Variable Specific Impulse Magnetoplasma Rocket), as well as miniaturized systems for small satellites.