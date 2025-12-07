### **Q: Explain in detail various dipoles used for mobile communication.**

#### **1. The Standard: Half-Wave Dipole Antenna**
Think of this as the "standard" or "parent" antenna. It is called a **Half-Wave Dipole** (or **Hertz Antenna**) because its total physical length is exactly half the length of the radio wave it is trying to catch ($\lambda/2$).

Because the length matches the wave perfectly, it resonates naturally—like a tuning fork. It operates across a massive range (3 kHz to 300 GHz).

**Why use it?**
It is lightweight, very cheap ("cost-efficient"), and easy to connect because its electrical resistance (impedance) matches standard cables well.

**The downside?**
It is an "independent" element, meaning it usually needs a stand or mount, and it radiates signal in all directions (omnidirectional).

![Half-wave Dipole Antenna](https://github.com/user-attachments/assets/235188e5-da6d-4847-97a3-3371923c4935)

---

#### **2. The Upgrade: Folded Dipole Antenna**
Imagine taking that standard Half-Wave antenna and connecting a second wire parallel to it to form a closed loop. This is the **Folded Dipole**. One wire is solid, and the other is split in the middle to plug in the cable.

**Why fold it?**
By folding it back, you change the electrical properties. Specifically, it has a **higher input impedance** and a **wider bandwidth** than the standard version. "Wider bandwidth" just means it can pick up a broader range of channels without needing adjustment. This makes it perfect for TV antennas (where you need many channels).

![Folded Dipole Antenna](https://github.com/user-attachments/assets/6d2168f9-1981-477d-87fe-66fbd0d026da)

---

#### **3. The Miniature: Short Dipole Antenna**
Sometimes, the radio wave is huge (low frequencies have waves that are miles long), and you simply cannot build an antenna that big. In this case, you use a **Short Dipole**.

An antenna is considered "Short" if its length ($L$) is tiny compared to the wave—specifically, less than 1/10th of the wavelength ($L < \lambda/10$).

Because it is so short, it doesn't resonate naturally. One end is left open-circuited, and the other is fed by an AC source. It is mainly used for **Low Frequency (3 kHz – 30 MHz)** receivers where a full-sized antenna is impossible to build.

![Short Dipole Antenna](https://github.com/user-attachments/assets/7c07380d-94b5-4535-a21c-5e2e5432ab8f)

---

#### **4. The Radio Version: FM Dipole Antenna**
This is a specific version of the dipole designed for FM Radio (88 MHz – 108 MHz). Unlike the others which are often horizontal, this one is **vertically polarized** (it stands up or hangs down).

**Why use it?**
It is the ideal "cheap and cheerful" solution. It is extremely low cost and works great in attics or roof spaces as a temporary solution. It gives much better reception than the tiny antennas built inside radios.

![FM Dipole Antenna](https://github.com/user-attachments/assets/94ad8200-d1b7-44cb-9c18-c20948c61a93)

---

#### **5. The Multi-Tasker: Fan Dipole Antenna**
What if you want to listen to five different radio bands, but you only have one cable coming into your house? You use a **Fan Dipole** (also called a Parallel Dipole).

This antenna connects several dipoles of **different lengths** to a single central feed line. It looks like a fan or whiskers spreading out.

**How does the signal know which wire to use?**
Physics does the work for you. When a signal comes in, it "looks" for the wire that matches its length (resonance). It flows into that wire and ignores the others because they present a high resistance (impedance) to that specific frequency.

**The Catch (Textbook Note):**
Designing this is simple mechanically (often an "Inverted V" shape), but tuning it is tricky. Because the wires are close together, they can **interfere with each other**. You have to do "cautious trimming" (cutting the wires very carefully) to get the resonance right.

![Fan Dipole Antenna](https://github.com/user-attachments/assets/59aeacfd-a5ae-4138-996e-a4028e763ddd)
