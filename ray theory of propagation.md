# Ray theory of Propagation

**Ray theory** serves as a simplified framework for analyzing exactly how light waves propagate and transmit through an optical fiber.

According to this theory, light moves through the fiber in the form of **rays**. These rays travel in a straight path along the fiber's axis and strictly obey the laws of **geometrical optics**.

Essentially, this approach is used to gain a clearer visualization of light propagation. It allows us to approximate key characteristics, such as the fiber's light acceptance and its specific guiding properties.

***

These are the three fundamental rules that describe exactly how light rays travel and behave.

### 1. Light Travel in Uniform Media
When light rays travel through a "homogeneous" medium—meaning the material is consistent throughout—they don't bend or curve. They simply travel in **straight lines**.

### 2. The Law of Reflection
This law comes into play when light hits the boundary between two materials that have different refractive indices.

Upon reflecting from this boundary, the rule is simple: the angle at which the light hits (the **angle of incidence**, $\theta_i$) is exactly equal to the angle at which it bounces off (the **angle of reflection**, $\theta_r$). Both angles are measured with respect to the plane of incidence.

$$\theta_i = \theta_r$$


### 3. Snell’s Law of Refraction
This law describes what happens when light passes *through* the boundary into the second medium.

First, the refracted ray will always lie within the same "plane of incidence" as the incoming ray. Second, the relationship between the materials and the angles is governed by this equation:

$$n_1 \sin \theta_1 = n_2 \sin \theta_2$$

Where:
* **$n_1$**: Refractive index of the first medium
* **$n_2$**: Refractive index of the second medium
* **$\theta_1$**: Incident angle
* **$\theta_2$**: Refracted angle


***

**A Note on Optical Fibers:**
Applying these principles, an optical fiber is capable of carrying two specific types of rays: **meridional rays** and **skew rays**.

Here is the decluttered breakdown for **Meridional Rays**. This section explains how a specific type of light ray travels through the fiber.

### What are Meridional Rays?
**Meridional rays** are defined by a specific path: they always pass directly through the central **axis** of the fiber.

Because they constantly cross the middle, they create high optical intensity right at the center of the fiber’s core. These rays are the standard model used to illustrate the fundamental transmission properties of optical fibers.

Generally, meridional rays strictly follow the standard laws of reflection and refraction.

---

### Classification: Bound vs. Unbound Rays
Meridional rays are split into two categories based on whether they stay inside the fiber or escape.

**1. Bound Rays ( The Good Ones)**
* These rays remain trapped inside the core.
* They propagate along the fiber axis by bouncing off the walls via **Total Internal Reflection**.
* Essentially, these are the rays actually doing the job of transmitting data.

**2. Unbound Rays (The Lost Ones)**
* These rays are refracted *out* of the fiber core.
* Instead of bouncing back in, they pass into the cladding and eventually escape the fiber entirely.
* **Why do they happen?** They are often caused by imperfections at the interface between the core and the cladding. These imperfections cause rays that *should* have been bound to refract out and become lost.

<img width="578" height="254" alt="image" src="https://github.com/user-attachments/assets/20aaf728-5fdb-4b4e-acc2-75d2b4bc161e" />

***

These are the more complex rays that take a spiral path rather than a straight zigzag.

### What are Skew Rays?
Unlike meridional rays, **skew rays** never pass through the central axis of the fiber. instead, they corkscrew or spiral their way down the fiber .

This unique path creates a distinct intensity pattern:
* **Low Intensity at the Center:** Since they avoid the middle, the center of the fiber remains dark.
* **High Intensity at the Rim:** The light is concentrated towards the outer edges of the fiber core.

### Key Characteristics
Skew rays play a major role in how we understand fiber performance:

1.  **Larger Acceptance Angle:** They have a wider acceptance angle than meridional rays, meaning the fiber can capture light entering from steeper angles. This is crucial for calculating the fiber's total light acceptance.
2.  **Increased Capacity:** The addition of skew rays significantly increases the amount of light a fiber can carry (its light capacity). This is especially true for fibers with a large Numerical Aperture (N.A.).
3.  **Increased Loss:** The downside is that they also increase the total amount of signal loss within the fiber.

### The "Leaky Ray" Phenomenon
Skew rays tend to propagate very close to the edge of the fiber core.

A significant portion of these rays are technically considered **"leaky rays"**.
* **The Theory:** Ideally, you would expect them to reflect totally at the core-cladding boundary.
* **The Reality:** Because the fiber boundary is curved (circular), these rays don't reflect perfectly. Instead, they partially refract (leak) out of the core and are lost.

<img width="816" height="404" alt="image" src="https://github.com/user-attachments/assets/a308a9f8-cdc3-4d68-bdb2-2fad4b63841f" />

***
### **Limitations of Ray Theory**.

While Ray Theory is great for visualizing how light moves, it is an approximation. It has three major blind spots where the physics gets a bit more complicated.

### 1. The Energy Illusion
The ray model gives the impression that 100% of the light's energy is strictly confined inside the core during Total Internal Reflection.

* **The Reality:** In the real world, the optical energy actually spreads slightly into the **cladding region** (a phenomenon often called the evanescent field). 
### 2. Ignoring Field Patterns
Ray theory treats light simply as straight lines. Because of this, it completely fails to consider the **discrete field patterns** (or modes) that form as light propagates inside the fiber.

### 3. The Breakdown with Size
The ray model stops working effectively when the size of the fiber core becomes very small—specifically, when it is comparable to the wavelength of the light being transmitted.

* **Not for Single Mode:** Because of this size issue, Ray Theory is not entirely justified for analyzing **Single Mode Fibers**.
* **Missing Interference:** It only describes the *direction* of a wave component; it does not account for the **interference** that happens between these components.




