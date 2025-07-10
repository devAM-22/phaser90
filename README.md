**Phase 90 Clone by Aapo Manni – 2025**

This folder includes schematics and SPICE models used in an MXR Phase 90-like clone.
Original LTspice schematics were made by Barbarach at: https://barbarach.com/breadboard-a-simple-phaser/

---

### Added Features (12.6.2025):

* **Tone knob**
  Adds the ability to control the tone of the output signal using a simple RC low-pass filter.

* **Faster LFO**
  The value of resistor R6 has been lowered from 10k to 2k, enabling a faster LFO rate and thus a stronger phasing effect.

* **Square-wave LFO**
  The original MXR Phase 90 uses a triangle-wave LFO signal, resulting in a smooth phase effect.
  This version includes the option for a square-wave LFO signal, which creates a more tremolo-like effect.
  The user can switch between LFO signals using an SPDT switch.

* **LFO indicator LED**
  An indicator LED has been added to the LFO oscillator to help visualize the LFO rate.

* **Miscellaneous changes**
  JFETs have been changed from J1113 to BF256B for a cleaner effect.
  Resistors R22, R23, R30, and R33 have been changed from 10k to 22k to allow better JFET biasing and improved phasing.

---
### EDIT (30.6.2025):

* **Bill of materials**
  The first version of the bill of materials has been added. It includes a price estimation for all the required parts.

### EDIT (10.7.2025):

* **KiCad schematic**
  Added first version of the schematic, which will later be turned into a PCB or perfboard layout.
  This version doesn't yet include the tremolo effect selector or the bypass switch. 

### TODO:

* Breadboard testing
* Proper biasing
* Layout (PCB or perfboard)
* Effect case graphic design

---

**Note:**
LTspice allows the user to listen to what the effect sounds like before building it on a breadboard.
This can be done using the `.wave` and `wavefile` commands included in `Phase 90.sch`.
However, it's important to check that the file paths in these commands are correct before running the simulation.
These commands are CPU-intensive, so it's wise to keep the file and simulation durations as short as possible.

---

**In case of more questions contact:**

manni.aapo@gmail.com
