# Linear Current Distribution in Antennas

## Introduction to Radiative Fields

Let's dive into the concept of **Linear Current Distribution**. To understand how practical antennas behave, we first need to look at the mathematical expression for the radiative field. Specifically, we are looking at the magnetic field intensity, denoted as $H_{\phi}$.

The fundamental expression for the radiative field is given as follows:

$$H_{\phi} = \frac{\omega I_0 dl \sin\theta}{4\pi c r} \sin\omega\left(t - \frac{r}{c}\right)$$

Now, to make this equation more useful for our analysis, we need to substitute some standard wave relationships. Recall that angular frequency is defined as $\omega = 2\pi f$ and the relationship between speed, frequency, and wavelength is given by $\frac{c}{f} = \lambda$.

When we substitute these values into our original equation, we get:

$$H_{\phi} = \frac{2\pi f I_0 dl \sin\theta}{4\pi c r} \sin\omega\left(t - \frac{r}{c}\right)$$

By simplifying the constants (canceling out the $\pi$ terms and substituting $f/c$ with $1/\lambda$), we arrive at a cleaner expression:

$$H_{\phi} = \frac{I_0 dl \sin\theta}{2\lambda r} \sin\omega\left(t - \frac{r}{c}\right)$$

If we are only interested in the magnitude of this field (ignoring the time-varying sinusoidal component), we can isolate the amplitude. This gives us our first key equation, which we will label as **equation (i)**:

$$|H_{\phi}| = \frac{I_0 dl}{2\lambda r} \quad \text{...(i)}$$

## Practical vs. Theoretical Current Distribution

Here is where reality diverges slightly from theoretical simplifications. Due to **non-uniform current distribution**, the radiation behavior we just derived requires nuance when applied to the real world.

As stated in the text, the ideal radiation cannot be strictly true for practical antennas. In a practical scenario, the current will naturally taper off. This results in distributions that are generally:

1.  **Linear**
2.  **Sinusoidal**, or
3.  **Co-sinusoidal**

To visualize this, let's look at the current distribution patterns for practical antennas.

As seen in **Figure (1)** above, we have two distinct models:
<img width="800" height="391" alt="image" src="https://github.com/user-attachments/assets/48c7f585-d893-40b7-8b01-d08f921f41fc" />
  * **(a) Linear current distribution:** This forms a triangular shape where current peaks at the center and decreases linearly to the ends.
  * **(b) Sinusoidal current distribution:** This forms a smooth curve, typical of half-wave dipoles ($l = \lambda/2$).

### The Effect on Power and Equivalent Length

Why does this shape matter? This non-uniform effect **reduces the amount of power radiated** and makes the antenna equivalent to a "shorter" one that carries the same uniform current.

To mathematically account for this "shortening" effect without changing our entire model, we use the concept of **mean value**. The actual length of this equivalent shorter antenna is obtained by finding the mean value of the current over the length concerned.

Accordingly, our previous **equation (i)** is modified. We replace the standard current and length element with average values, leading to **equation (ii)**:

$$|H_{\phi}| = \frac{I_{av} l}{2\lambda r} \quad \text{...(ii)}$$

Where the variables are defined as:

  * $I_{av} =$ **Average current**
  * $l =$ **Length of the short or linear antenna** (as opposed to the differential current element length of $dl$)

## Conclusion

From the discussion above, a crucial principle becomes clear: the **current distribution depends upon the length**, which effectively dictates the direction of emission of radiations.

-----

*End of Section. The text indicates the next section begins Unit-II, covering topics like Babinet's principles.*
