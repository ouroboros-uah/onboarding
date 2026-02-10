# Single Particle Motion

As we have learned so far, to achieve the massive velocities required for deep-space missions, electric propulsion is a compelling option.

By turning a propellant into a plasma, we can decouple the energy source from the propellant itself. We use electromagnetic fields to accelerate these charged particles to extremely high exhaust velocities. Plasma is the "fourth state of matter" and powers stars, artificial lighting, and the thrusters we build with OUROBOROS.

## Plasma and Particles

A plasma is defined by its unbound particles. A significant fraction of atoms have been ionized, meaning electrons have been liberated from their nuclei. This allows the medium to respond to electromagnetic fields. Because of long-range electrostatic forces, plasma particles respond together to external forces.

Therefore, it motivates us to begin by understanding the behavior of **single particles** and how they respond to electromagnetic fields, before diving into the macroscopic behaviors of plasmas.

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

!!! tip "Dot and Cross Products and the Right Hand Rule" 
    The study of electricity and magnetism relies heavily on vector operations. Two important operations are the dot and cross product.

    The **dot product** ($\vec{A} \cdot \vec{B}$) measures how much two vectors point in the same direction.

    The **cross product** ($\vec{A} \times \vec{B}$) produces a new vector that is perfectly perpendicular to the first two. 

    One tool we use to visualize the cross product is known as the **Right-Hand Rule**. Point your pointer finger in the direction of the first vector, and your middle finger in the direction of the second vector (order matters). Your thumb will be pointing in the direction of the resultant vector, $\vec{A} \times \vec{B}$.

    Using the Right Hand Rule, can you figure out what happens if we flipped the two vectors in the cross product (effectively calculating $\vec{B} \times \vec{A}$)? 

    **Note:** Electrons have a negative charge. So, the negative sign requires flipping the $\vec{v}$ vector when calculating \vec{F_{b}} = q(\vec{v} \times \vec{B}) for an electron.

The magnetic force (Lorentz force) acts as the centripetal force pulling the particle into a circle. We set the magnitude of the magnetic force equal to the mass times the centripetal acceleration:

$$F_{magnetic} = F_{centripetal}$$

$$ |q| v_{\perp} B = \frac{m v_{\perp}^2}{r_B} $$

Solving, we can determine the radius of gyration, known as the **Larmor radius** or **gyroradius**.

$$ r_B = \frac{m v_{\perp}}{q B} $$

To visualize this, think of a semi-truck (representing a heavy ion) and a go-kart (representing an electron). Imagine that both vehicles are in a parking lot and we want to put down some tire marks to annoy the cops. The semi-truck has so much momentum that it takes a massive, wide arc to turn. The go-kart is so light that the magnetic field snaps it into a tiny, tight circle.

Similarly, we can solve for how fast the particle gyrates, known as the **cyclotron frequency** or **gyrofrequency**.

$$ \omega_{c} = \frac{qB}{m} $$

## Combined Fields and Drifts

When particles are subject to both fields, we use the Lorentz Force to determine their total motion:

$$ \vec{F} = m\vec{a} = q(\vec{E} + \vec{v} \times \vec{B}) $$

These combined forces lead to particles experiencing net motion in space, referred to as a **drift**.

When an electric field is applied perpendicular to a magnetic field, the particle experiencing gyrating motion, but with a net drift velocity perpendicular to both fields:

$$ \vec{v}_{D} = \frac{\vec{E} \times \vec{B}}{B^{2}} $$

This net motion is known as the **$E \times B$ drift** (pronounced "E cross B") from the form of the equation. Note that the $E \times B$ drift velocity is independent of the particle's charge or mass, and is only dependent on the field strengths and directions.

!!! tip "$E \times B$ Drift"
    In Hall-effect thrusters, we use this $E \times B$ drift to trap electrons in a circular "Hall current" at the exit plane. They stay "stuck" in these sideways loops, colliding with and ionizing propellant, while the heavy ions shoot straight out to provide thrust.

To visualize this, let's revisit our semi-truck and go-kart analogy. Let's imagine we're doing the same thing, but now add hurricane-force winds blowing constantly in one direction. As the vehicle turns with the wind, it speeds up. Just like a car taking a corner too fast, the increased speed makes it harder for the "tires" (the magnetic field) to hold the turn, so the arc becomes wider.

As the vehicle swings back around and drives against the wind, it slows down. Now that it’s moving slower, our tires grip the ground much more easily, snapping it into a much tighter, sharper turn. Because the vehicle is constantly switching between wide turns (when running with the wind) and tight turns (when fighting the wind), it doesn't end up back where it started. Instead, it "shuffles" sideways across the parking lot, not in the direction of the wind, but sideways to both.

In a non-uniform magnetic field, the Larmor radius is constantly changing based on the local strength of the field. The resulting loops are elongated, since areas with a weak field result in a wider loop, and areas with a strong field result in a tighter loop.

Since one of the turns is tighter than the other, the particle walks through space with a non-zero net motion. The resulting drift velocity can be calcluated as follows:

$$ \vec{v}_{D,\nabla B} = \frac{1}{q}\frac{mv_{\perp}^{2}}{2B}\frac{\vec{B} \times \nabla \vec{B}}{B^{2}} $$

This is known as the **$\nabla B$ drift** (pronounced "gradient B" or "grad B"). Unlike the $E \times B$ drift, the $\nabla B$ drift velocity is dependent on the particle's energy and charge.

## Application: The Penning Trap

A practical application of these combined forces is the **Penning trap**. Think of this device as a "bottle" that captures charged particles using fields. 

We use a strong, uniform magnetic field pointing along the axis of the bottle. Because of the Larmor radius we just discussed, the particles are forced to spin in circles. They can move up and down the bottle, but they cannot leak out the sides.

However, even though the magnetic field keeps them from hitting the walls, the particles could still fly out the top or bottom. We apply an electric field (via electrodes at the ends) that pushes the particles back toward the center. If a positive ion tries to "leak" out the top, the electric "cap" repels it back down.

The end result is that the particles are trapped in a tiny "sweet spot" in the center, gyrating in circles and bouncing back and forth between the electric caps.

This is great for studying antimatter, since antimatter will be annihilated if it contacts regular matter. By using fields, we can confine antimatter particles for long periods of time.