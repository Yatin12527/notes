
### **Detailed Explanation: Various Types of Dipole Antennas**

Overview:

Different types of dipole antennas are used in mobile communications depending on specific requirements like frequency, bandwidth, and space. Below are the five types detailed in the text.

### **1. Half-Wave Dipole Antenna**

_Also called: The Hertz Antenna._

-   **Definition:** A type of dipole antenna where the **dipole length is exactly half the wavelength** ($\lambda/2$) at the operating frequency.
    
-   **Operating Frequency:** It covers a massive range from **3 kHz to 300 GHz**.
    
-   **Structure:** It is a simple resonance structure compared to other antennas. It consists of two sections of wire (conductors) fed in the middle.
    
-   **Key Advantages:**
    
    -   **Impedance Matching:** Its input impedance is very similar to a standard transmission line's input impedance (making it efficient to connect).
        
    -   **Physical:** It is not heavy and is cost-efficient.
        
    -   **Independence:** It is an "independent" antenna—meaning it works on its own but is also used as the **fundamental element** for building more complex antennas (like those used in TV/Radio).
        
-   **Radiation Pattern:** Omnidirectional (radiates equally in all directions perpendicular to the wire).
    

**Reference to Fig: Half-wave Dipole Antenna**
<img width="441" height="366" alt="image" src="https://github.com/user-attachments/assets/235188e5-da6d-4847-97a3-3371923c4935" />


----------

### **2. Folded Dipole Antenna**

-   **Definition:** This antenna is a collection of **two** dipole antennas connected separately to form a thin wire loop.
    
    -   One dipole is continuous (unbroken).
        
    -   The other dipole is split at the middle to connect the feed line.
        
-   **Construction:** The ends of the two dipoles are folded back and connected in parallel.
    
-   **Technical Characteristics:**
    
    -   **Radiation Pattern:** Similar to a normal dipole.
        
    -   **Directivity:** It is **bi-directional** (radiates front and back).
        
    -   **Impedance:** The main reason to use this over a normal dipole is its **higher input impedance** and **high value of feed impedance**.
        
    -   **Bandwidth:** It provides a **wide bandwidth** (can operate over a larger chunk of frequencies).
        
-   **Availability:** These are typically available in two-wire and three-wire types.
    

**Reference to Fig: Folded Dipole Antenna**

<img width="467" height="447" alt="image" src="https://github.com/user-attachments/assets/6d2168f9-1981-477d-87fe-66fbd0d026da" />

----------

### **3. Short Dipole Antenna**

-   **Definition:** A dipole antenna where the length ($L$) is small compared to the wavelength ($\lambda$).
    
-   **Condition:** $L < \lambda$ (specifically, the wire leading to the antenna should be less than $1/10$ of the wavelength, i.e., $L < \lambda/10$).
    
-   **How it is Fed:** It is a simple wire where one end is **open-circuited** and the other is fed through an **AC voltage source**.
    
-   **Frequency Range:** **3 kHz – 30 MHz**.
    
-   **Application:** Because of its small size relative to the wave, it is applicable in **low-frequency based receivers** (where a full-size antenna would be impossibly large).
    

**Reference to Fig: Short Dipole Antenna**

<img width="525" height="326" alt="image" src="https://github.com/user-attachments/assets/7c07380d-94b5-4535-a21c-5e2e5432ab8f" />

----------

### **4. FM Dipole Antenna**

-   **Why it exists:** It is an ideal solution for **roof spaces or attics** because it provides better reception than internal radio antennas but at a **very low cost**.
    
-   **Construction:**
    
    -   It is a **half-wave dipole** that is **vertically polarized** (upright).
        
    -   It is most frequently used for VHF FM broadcasts.
        
-   **Frequency Range:** **88 MHz – 108 MHz**.
    
-   **Usage:** It is often used as a **temporary antenna** when a permanent one isn't available.
    

**Reference to Fig: FM Dipole Antenna**
<img width="536" height="406" alt="image" src="https://github.com/user-attachments/assets/94ad8200-d1b7-44cb-9c18-c20948c61a93" />


----------

### **5. Fan Dipole Antenna**

_Also called: Fanned Dipole or Parallel Dipole._

-   **Definition:** A **multi-band** wire antenna that connects several dipole antennas to a **single common coaxial feed line**.
    
-   **Concept:**
    
    -   It is very simple to design.
        
    -   Every dipole in the "fan" must be slashed (cut) for the approximate band center where you want it to resonate.
        
    -   **How it works:** Once a signal is transmitted, **only the resonating element** for that specific band is observed by the radio. The remaining dipoles (which are the wrong length for that frequency) present a **higher impedance** and are effectively ignored by the signal.
        
-   **Mechanical Design:** The design is not critical (it's forgiving). It can be arranged horizontally or in an **Inverted V shape**.
    
-   **Interference & Tuning (Crucial Note from Page 60):**
    
    -   Some arrangements benefit from spreading the wires, but nearby elements **can interfere with each other**, especially if they are tightly united in different directions.
        
    -   Therefore, this antenna requires **"cautious trimming"** of the elements to attain perfect resonance on different bands.
        

**Reference to Fig: Fan Dipole Antenna**
<img width="795" height="292" alt="image" src="https://github.com/user-attachments/assets/59aeacfd-a5ae-4138-996e-a4028e763ddd" />
