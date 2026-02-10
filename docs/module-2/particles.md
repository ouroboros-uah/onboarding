# Single Particle Motion

As we have learned so far, to achieve the massive velocities required for deep-space missions, electric propulsion is a compelling option.

By turning a propellant into a plasma, we can decouple the energy source from the propellant itself. We use electromagnetic fields to accelerate these charged particles to extremely high exhaust velocities. Plasma is the "fourth state of matter" and powers stars, artificial lighting, and the thrusters we build with OUROBOROS.

## Plasma and Particles

A plasma is defined by the following criteria:
* **Unbound Particles**: A significant fraction of atoms have been ionized, meaning electrons have been liberated from their nuclei. This allows the medium to respond to electromagnetic fields.
* **Quasi-neutrality**: On a large scale, the plasma has equal densities of positive and negative particles, resulting in a net neutral charge. Local imbalances only occur in very small regions.
* **Collective Behavior**: Because of long-range electrostatic forces, plasma particles do not just collide like billiard balls; they respond together to external forces.

Therefore, it motivates us to begin by understanding the behavior of **single particles** and how they respond to electromagnetic fields.

## Motion in an Electric Field ($\vec{E}$)

An electric field does work on a charged particle, causing linear acceleration.

$$
\vec{F_{e}} = q\vec{E}
$$

Positive ions accelerate in the same direction as the $\vec{E}$ field; negative electrons accelerate in the opposite direction.

Charge ($q$) is an integer multiple ($z$) of the elementary charge ($e = 1.602 \times 10^{-19}$ C).

## Motion in a Magnetic Field ($\vec{B}$)

A magnetic field does no work on a particle; it only changes its direction, forcing it into a circular "gyration".

$$
\vec{F_{b}} = q(\vec{v} \times \vec{B})
$$

The magnetic force (Lorentz force) acts as the centripetal force pulling the particle into a circle. We set the magnitude of the magnetic force equal to the mass times the centripetal acceleration:

$$F_{magnetic} = F_{centripetal}$$

$$ |q| v_{\perp} B = \frac{m v_{\perp}^2}{r_B} $$

Solving, we can determine the radius of gyration, known as the **Larmor radius** or **gyroradius**.

$$ r_B = \frac{m v_{\perp}}{q B} $$

Similarly, we can solve for how fast the particle spins around the field line, known as the **cyclotron frequency** or **gyrofrequency**.

$$ \omega_{c} = \frac{qB}{m} $$

## Combined Fields and Drifts

When particles are subject to both fields, we use the Lorentz Force to determine their total motion:

$$ \vec{F} = m\vec{a} = q(\vec{E} + \vec{v} \times \vec{B}) $$