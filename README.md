# Low Cost Myoelectric Transradial Prosthetic Arm

A low-cost, FDM 3D-printed myoelectric prosthetic arm designed for accessibility and affordability. This project explores how accessible 3D printing and off-the-shelf components can provide functional prosthetics for transradial amputees.

---

## Process

**Research Question:**  
How can a low-cost, FDM 3D-printed myoelectric arm, built with off-the-shelf components and accessible filaments such as PLA & TPU 85A, improve accessibility for transradial amputees?

**Methodology:**  
Mixed methods were used—both quantitative and qualitative—to gather cost data and document the iterative design process.

---

## Materials and Tools

- **Filaments:** PLA, Siraya Tech TPU 85A (0.24mm layer height; TPU extruder 215°C, bed 45°C)  
- **3D Printer:** Kingroon KP3S FDM printer  
- **Electronics:** Myoware EMG sensor, disposable electrodes, Arduino R4 WIFI, linear actuator, LiPo battery (5000mAh, 7.4V, 100C), Kevlar fishing line, jumper wires  
- **Software:** Fusion 360 (CAD), Blender (STL editing), Cura (slicing), Inkscape (vectorization)  
- **Other Tools:** Calipers, soldering iron, scale  

---

## Procedure

1. Measure finger sizing using calipers.  
2. Design fingers in Fusion 360, extrude, and export to Blender for beveling and routing holes for tendon lines.  
3. Export as STL and slice in Cura. Print hand (~12 hrs) and arm (~7 hrs).  
4. Assemble printed parts, route Kevlar tendon lines, and attach servos and microcontroller.  
5. Connect Myoware EMG to Arduino via jumper wires and test signal response.  
6. Record observations and iterate over multiple prototypes to refine flexion, grip, and EMG responsiveness.  

---

## Data Collection

### Quantitative
- Total cost of components accurately documented using Amazon prices.
- Cost analysis ensures the prosthetic remains accessible and affordable compared to industry-grade arms.

### Qualitative
- Observational notes and design documentation recorded over ~7 months.
- Photographs captured each prototype iteration.
- Notes, tables, and graphs used to evaluate usability, comfort, and assembly efficiency.

---

## Results and Findings

### Mechanical Developments
- Early designs with PLA were brittle; TPU 85A allowed human-like finger flexion.  
- Final joints are stable, flexible, and smooth.

### EMG Developments
- Initial EMG response was slow; optimization improved speed and accuracy.  
- Electrode placement refinements led to more pronounced signals for motor actuation.

### Functional Usability
- TPU 85A and adjusted tendon routing improved natural finger flexion.  
- Final hand integrates EMG control, demonstrating a functional and affordable proof-of-concept.

### Design Process
- Over 40 iterations over 7 months.  
- Key changes included pivoting from PLA → TPU 85A and rotational servo → linear actuator for improved curvature and grip.

### Cost
- Total cost: **$263.22** (materials + electronics).  
- Comparable EMG functionality to $3000+ commercial prosthetics.  
- Demonstrates feasibility of producing locally with low-cost equipment.

---

## Milestone Data

Photographs document the evolution of the prosthetic design, capturing key design shifts and improvements over the 7-month development period.

---

## Limitations

- Single-user testing; limited audience.  
- Home environment testing, not clinical trials.  
- Short-term evaluation; long-term durability untested.  
- Self-report bias due to lack of patient trials.  
- No FDA clearance; purely a research prototype.  

Mixed methods were chosen to evaluate both cost-effectiveness and accessibility, balancing quantitative data (cost) and qualitative observations (design, usability, and assembly).

---

## License

This project is released under the **GNU GPL v3 license**. Any modified or redistributed versions must remain open source under the same license.  

**Disclaimer:** This project is a research prototype and not a certified medical device.

---

## Figures

**Figure 1:** Bill of materials showing cost for all 18 components; Myoware sensor and TPU represent ~40% of total cost.  

**Figure 2:** Component costs by category, illustrating sensors and electronics as the largest contributors.  

---

## License

This project is released under the **GNU GPL v3 license**. Any modified or redistributed versions must remain open source under the same license.  

**Disclaimer:** This project is a research prototype and not a certified medical device.

---

## Figures

**Figure 1:** Bill of materials showing cost for all 18 components; Myoware sensor and TPU represent ~40% of total cost.  

**Figure 2:** Component costs by category, illustrating sensors and electronics as the largest contributors.

---

## Attribution

- **Fusion 360** – CAD modeling and design  
- **Blender** – STL editing and 3D object refinement  
- **Cura** – Slicing and 3D print preparation  
- **Inkscape** – Vectorization for appendage sizes  
- **Arduino IDE** – Microcontroller programming  
- **Myoware EMG** – Muscle signal detection  
- **Kingroon KP3S** – FDM 3D printing hardware  
- Open source communities and tutorials that supported learning in 3D printing, electronics, and prosthetic design
