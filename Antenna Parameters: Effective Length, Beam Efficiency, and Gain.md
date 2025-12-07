Here is the comprehensive Markdown file, rewritten in a narrative lecture style with zero information loss. I have included the placeholder for the image exactly where the text references it so you can easily link your file later.

-----

# Antenna Parameters: Effective Length, Beam Efficiency, and Gain

In this lecture note, we will explore the fundamental parameters that define the quality and performance of an antenna. We will cover how we measure an antenna's "electrical" size, how efficient its beam is, and its ability to concentrate power (gain).

## 1\. Effective Length of an Antenna ($l_{eff}$)

When we deal with antennas, physical size isn't the only thing that matters. We need a concept that relates the physical structure to the actual electromagnetic signals it handles. This is called the **Effective Length**.

### The Transmitter vs. Receiver Perspective

The meaning of effective length shifts slightly depending on whether the antenna is sending or receiving:

  * **For a Transmitter:** It indicates how effectively the antenna can transmit electromagnetic wave energy.
  * **For a Receiver:** It shows how effectively it can receive electromagnetic wave energy.

### The Formal Definition

In the context of a receiving antenna, effective length helps us understand the relationship between the invisible electric field in the air and the tangible voltage we can measure at the antenna's port.

So, effective length is defined as the **ratio of the induced voltage ($V$) to the incident field ($E$)**. Specifically, we measure the induced voltage at the receiving antenna under an **open-circuited condition** relative to the incident electric field intensity (or strength).

Mathematically, we express this as:

$$
\text{Effective length} = \frac{\text{open circuit voltage}}{\text{incident field strength}}
$$

Or, in symbolic notation:

$$
l_{eff} = \frac{V_{oc}}{E} \quad \text{meters (or wavelengths)}
$$

**Where:**

  * $l_{eff}$ is measured in **meters** or **wavelengths ($\lambda$)**.
  * $V_{oc}$ is the induced voltage under the open-circuited condition at the antenna terminal.
  * $E$ is the uniform exciting field responsible for that voltage.

-----

## 2\. Beam Efficiency (B.E.)

Another parameter frequently used to judge the **quality** of transmitting and receiving antennas is **Beam Efficiency**.

To understand this, we must look at the geometry of how an antenna radiates energy. An antenna doesn't just shoot a laser beam of energy; it creates a complex "pattern" in space.

### Visualizing the Pattern

Please refer to Figure (1) below. It illustrates the anatomy of an antenna's radiation pattern.
<img width="788" height="551" alt="image" src="https://github.com/user-attachments/assets/671ee0dc-05b7-4b8a-b51e-b8b15398a12b" />


As you can see in the diagram:

  * **Major Lobe (Main Beam):** This is where we *want* the energy to go. It is directed along the $z$-axis ($\theta = 0$).
  * **Minor Lobes:** This includes **Side Lobes** and **Back Lobes**. This is energy "leaking" in unwanted directions.
  * **Beam Widths:** The diagram highlights the **FNBW** (First Null Beamwidth) and the **HPBW** (Half Power Beamwidth), which define the thickness of the main beam.

### Defining Beam Efficiency

Beam efficiency ($BF$ or B.E.) is a dimensionless quantity that tells us what percentage of the total power is actually contained within the main beam (specifically within a defined cone angle).

It is defined as:

$$
B.E. = \frac{\text{Power transmitted (received) within cone angle } \theta_1}{\text{Power transmitted (received) by the antenna}} \quad \text{(dimensionless)}
$$

**Crucial Details:**

  * $\theta_1$ represents the **half angle** of the cone within which we are calculating the power percentage.
  * This cone is usually defined **between the nulls or minimums** (see the "First Null" in the diagram above).

### Why is this important?

In high-precision engineering, stray signals received through minor lobes are noise. Therefore, a **very high beam efficiency** (usually in the **high 90s**) is necessary for antennas used in:

  * Radiometry
  * Astronomy
  * Radar
  * Other applications where received signals through the minor lobes must be minimized.

-----

## 3\. Gain of an Antenna ($G$)

Finally, we arrive at the most common "figure of merit" for antennas: **Gain**.

In practice, we rarely use omni-directional antennas (which radiate equally everywhere) because they waste power. Instead, we use directional antennas to concentrate power.

**Gain** is the property that measures the ability of an antenna (or antenna system) to:

1.  Concentrate radiated power in a desired direction.
2.  Absorb incident power from that desired direction.

We can define Gain in several specific ways, often referred to as "directively" or "antenna gain."

### Definition A: Relative to a Test Antenna

When we do not account for efficiency (pure directivity), gain is defined as the ratio of maximum radiation intensity in a given direction to the maximum radiation intensity from a **reference antenna** produced in the same direction with the same power input.

$$
Gain(G) = \frac{\text{Maximum radiation intensity from test antenna}}{\text{Maximum radiation intensity from reference antenna with same power input}}
$$

### Definition B: Relative to an Isotropic Antenna ($G_0$)

If we choose an **isotropic antenna** as our reference (a theoretical point source that radiates perfectly equally in all directions), the symbol $G$ changes to $G_0$.

$$
Gain(G_0) = \frac{\text{Max. radiation intensity test antenna}}{\text{Radiation intensity from isotropic antenna with same power input}}
$$

Symbolically:

$$
(G_0) = \frac{\Phi_m}{\Phi_0} \quad ...(i)
$$

**Where:**

  * $\Phi_m$ = max. radiation intensity from the test antenna.
  * $\Phi_0$ = radiation intensity from the isotropic antenna.

**Decibel Representation:**
Because gain ratios can be large numbers, gain is often expressed in decibels:

$$
dB \text{ gain} = 10 \log_{10} G \quad ...(ii)
$$

### Definition C: The Receiver Perspective

There is another definition for Gain that treats the antenna involved as a **receiving antenna**.

Here, gain is defined as the ratio of the maximum power received by the test antenna ($P_1$) to the maximum power received by the reference antenna ($P_2$), assuming the power input is the same in both cases.

$$
Gain (G) = \frac{\text{Max. power received from test antenna } (P_1)}{\text{Max. power received from reference antenna } (P_2)}
$$

For the same power input in both cases:

$$
G = \frac{P_1}{P_2} \quad ...(iii)
$$

### Real-World Example: The Half-Wave Dipole

To give you a concrete value to memorize: A standard **half-wave dipole antenna** has a theoretical gain of:

  * **1.64** (as a raw ratio)
  * **2.15 dB** (over an isotropic antenna)
