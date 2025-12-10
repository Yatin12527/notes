### The Analog-to-Digital Conversion Process

<img width="1151" height="375" alt="image" src="https://github.com/user-attachments/assets/46b76400-11bf-453c-a828-8ad2c36bd1f0" />


The goal of ADC is to convert a natural analog signal (which is continuous in both time and amplitude) into a digital signal (which consists of discrete numbers). As shown in the block diagram, this happens in three distinct stages:

**1. Sampling (Discretizing Time)**
The process begins with the **Sample and Hold** circuit.
* **The Action:** The system measures the analog input signal only at specific, periodic moments in time (defined as $t = nT$). It effectively "freezes" the signal value for a brief moment to read it.
* **The Technical Result:** This converts the signal into a **"Sampled Signal."** It is now **discrete in time** (defined only at specific points) but it still has **continuous amplitude** (the value itself is still a precise, un-rounded decimal).

**2. Quantization (Discretizing Amplitude)**
Next, the signal passes through the **Quantizer**. The computer cannot store the "continuous amplitude" from the previous step because it would require infinite memory.
* **The Action:** The system maps the precise sampled value to the nearest available fixed level. The total number of available levels is determined by the formula $2^B$, where $B$ is the number of bits.
* **The Technical Result:** This converts the "continuous amplitude" into a **discrete value**. For example, a precise 4.3 volts might be forced (quantized) to a flat 4.0 volts.

**3. Encoding (Binary Translation)**
Finally, the signal enters the **Encoder** (Logic Circuit).
* **The Action:** The specific quantized level selected in the previous step is translated into a unique **binary word** (a sequence of 0s and 1s) of length $B$ bits.
* **The Technical Result:** The output is now a fully **Digital Signal** ($x(n)$). Unlike the input, this signal exists only at discrete time points and has only discrete values.

***

**Summary of the Transformation:**
* **Input:** Continuous Time, Continuous Amplitude.
* **After Sampling:** Discrete Time, Continuous Amplitude.
* **After Quantization/Encoding:** Discrete Time, Discrete Amplitude (Digital).
