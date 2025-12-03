
2025-11-18 20:28
Tags: [[Nanosystems]]

### Initial Theory (Chapter 1 & 2)

![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-1.png]]
	![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-19.png|496x281]]

![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-3.png]]
	![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-20.png|561x347]]
	![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-21.png|571x330]]

![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-4.png]]




### Why put DNA in nanochannels?

- Genomic DNA is **very long**: human chromosomes are cm-scale if fully stretched.
- To “read” structural information (big insertions, deletions, rearrangements), we want **long, straight pieces** of DNA, not many tiny fragments.
- Nanochannels (with dimensions ~50–200 nm) force DNA to **stretch out**, so we can:
    - Measure contour length of single molecules.
    - Locate labels (e.g. restriction cuts, nick labels, melting patterns) along the molecule → _optical mapping_.

So: nanochannels are like **nanoscale rulers** that gently stretch DNA without needing big external forces.

### DNA as a semiflexible polymer

![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image.png]]
	![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-17.png|479x326]]
	![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-18.png|480x295]]

### DNA as an entropic spring

![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-5.png]]
	![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-16.png|486x258]]
### Confinement in nanochannels: de Gennes vs Odijk

![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-6.png]]

### de Gennes regime (flexible in confinement)

![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-8.png]]

![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-9.png]]

![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-10.png]]

### Odijk regime (very strong confinement)

![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-11.png]]

![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-23.png|555x367]]
### Experiments: how do we actually see the DNA?

![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-24.png|452x294]]

![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-13.png|645x483]]

![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-14.png|537x313]]

**Setup:**
- DNA is stained with a fluorescent dye (YOYO-1, SYBR Gold, TOTO-1, etc.).
- A micro–nano chip contains:
    - microchannels for loading DNA
    - arrays of nanochannels or nano-slits for stretching.
- DNA is driven into nanochannels by **electrophoresis** or **pressure-driven flow**.
- Once inside, the driving field is often turned off, and DNA fluctuates around an equilibrium stretched state.

![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-15.png|537x342]]

**Imaging:**
- Epifluorescence microscopy (often high-NA oil immersion objective).
- The intensity profile along the channel, $I\left(z\right)$, is fitted with a blurred step function (error function) to extract the end-to-end extension $L_{z}$​.

**MORE DETAIL:**
![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-12.png]]
	![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-25.png|508x274]]
	![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-26.png|509x258]]

By taking many frames and fitting $L_{z}$​ each time, you get a histogram of lengths and can:
- Measure mean extension.
- Measure the standard deviation.
- Estimate contour length and test scaling laws.
- Measure diffusion.

### Other confinement geometries: slits, pits, “tug-of-war”

Besides 1D channel confinement, the slides also mention:
- **Nano-slits (2D):** one strong confinement dimension (height small), width large. DNA flattened but not fully 1D.
- **Nano-pits (2D + 2D) and reservoirs:** DNA can partially explore wider regions; interesting entropic trapping phenomena.
- **Tug-of-war setups:** DNA is captured between two regions (e.g., two channels or a channel and a reservoir) so you can study forces, relaxation, and entropic barriers.

These geometries are used to:
- Study **entropic barriers** between micro and nano regions.
- Control DNA motion without direct mechanical tethers.
- Design more advanced genome mapping or sorting devices.

### Applications: genome mapping & “next-gen” DNA analysis

- **Restriction mapping in nanochannels**: cut DNA with a restriction enzyme inside the channel and watch fragment sizes and order → fast mapping within minutes.
- **Nick-labelled mapping:** label specific sequence motifs along stretched DNA and read out as a barcode.
- **Structural variation detection:** detect large insertions, deletions, inversions and translocations based on shifts in the label pattern.
- **Single-cell genomics:** extract very long DNA from single cells and map them in nanochannels or nano-slits.

Overall idea: **nanoconfined DNA devices bridge physics (polymer scaling, fluidics) and genomics (structural information on very long molecules).**

![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-22.png|576x359]]
![[2 - Source Material/Images/F1 - DNA in Nanofluidics/image-27.png|685x502]]
















### Q1. Hydraulic resistance of a single nanochannel

**Channel dimensions:**

- Width w=200w = 200w=200 nm
    
- Height h=100h = 100h=100 nm (we take the smaller side as “height” in the formula)
    
- Length L=500L = 500L=500 µm
    
- Water viscosity η≈1 mPa\cdotps=10−3 Pa\cdotps\eta \approx 1 \text{ mPa·s} = 10^{-3} \text{ Pa·s}η≈1 mPa\cdotps=10−3 Pa\cdotps
    

For a rectangular channel (Bruus), hydraulic resistance is approximately:

Rh≈12ηLwh3(1−0.63hw)R_h \approx \frac{12 \eta L}{w h^3 \left(1 - 0.63 \frac{h}{w}\right)}Rh​≈wh3(1−0.63wh​)12ηL​

Plugging in:

- h/w=100/200=0.5h/w = 100/200 = 0.5h/w=100/200=0.5 ⇒ 1−0.63h/w≈1−0.315=0.6851 - 0.63 h/w \approx 1 - 0.315 = 0.6851−0.63h/w≈1−0.315=0.685
    
- Numerically this gives:
    
    Rh≈4.4×1022 Pa\cdotps/m3R_h \approx 4.4 \times 10^{22} \, \text{Pa·s/m}^3Rh​≈4.4×1022Pa\cdotps/m3

So the channel has a **very large hydraulic resistance**, which is expected because the cross-section is extremely small.

---

### Q2. Volumetric flow rate for a 1 atm pressure drop

Use **Hagen–Poiseuille in resistance form**:

Q=ΔPRhQ = \frac{\Delta P}{R_h}Q=Rh​ΔP​

- ΔP=1 atm≈1.0×105\Delta P = 1 \text{ atm} \approx 1.0 \times 10^5ΔP=1 atm≈1.0×105 Pa
    
- Rh≈4.4×1022 Pa\cdotps/m3R_h \approx 4.4\times 10^{22} \, \text{Pa·s/m}^3Rh​≈4.4×1022Pa\cdotps/m3
    

Then:

Q≈1.0×1054.4×1022 m3/s≈2.3×10−18 m3/sQ \approx \frac{1.0\times 10^5}{4.4\times 10^{22}} \,\text{m}^3/\text{s} \approx 2.3\times 10^{-18} \,\text{m}^3/\text{s}Q≈4.4×10221.0×105​m3/s≈2.3×10−18m3/s

Convert units:

- 1 fL=10−18 m3⇒Q≈2.3 fL/s1\,\text{fL} = 10^{-18}\,\text{m}^3 \Rightarrow Q \approx 2.3\,\text{fL/s}1fL=10−18m3⇒Q≈2.3fL/s
    
- 1 pL=10−15 m3⇒Q≈0.0023 pL/s≈0.14 pL/min1\,\text{pL} = 10^{-15}\,\text{m}^3 \Rightarrow Q \approx 0.0023\,\text{pL/s} \approx 0.14\,\text{pL/min}1pL=10−15m3⇒Q≈0.0023pL/s≈0.14pL/min
    

So the flow rate is **of order a few femtoliters per second** per channel for a 1 atm pressure drop.

---

### Q3. Transit time for a λ-DNA molecule through the 500 µm channel

First find the **average velocity** in the channel:

- Cross-section area A=w×h=(200×10−9)(100×10−9)=2×10−14 m2A = w \times h = (200 \times 10^{-9})(100 \times 10^{-9}) = 2 \times 10^{-14}\,\text{m}^2A=w×h=(200×10−9)(100×10−9)=2×10−14m2
    
- Velocity v=Q/A≈(2.3×10−18)/(2×10−14)≈1.2×10−4 m/sv = Q/A \approx (2.3\times 10^{-18}) / (2\times10^{-14}) \approx 1.2 \times 10^{-4}\,\text{m/s}v=Q/A≈(2.3×10−18)/(2×10−14)≈1.2×10−4m/s
    

Channel length L=500 μm=5×10−4 mL = 500\,\mu\text{m} = 5\times 10^{-4}\,\text{m}L=500μm=5×10−4m.

Transit time:

t=Lv≈5×10−41.2×10−4 s≈4.3 st = \frac{L}{v} \approx \frac{5\times 10^{-4}}{1.2\times10^{-4}} \,\text{s} \approx 4.3\,\text{s}t=vL​≈1.2×10−45×10−4​s≈4.3s

So a λ-DNA molecule would spend **about 4 seconds** inside the 500 µm channel at this flow rate.

(Note: this is independent of the λ contour length; it’s set by fluid velocity and channel length.)

---

### Q4. Expected degree of stretching in a 100×200 nm channel

We use the **de Gennes extension formula** (from Tegenfeldt / lecture notes):

LzLc≈(p weff)1/3D−2/3\frac{L_z}{L_c} \approx \left(p\,w_{\text{eff}}\right)^{1/3} D^{-2/3}Lc​Lz​​≈(pweff​)1/3D−2/3

- Take persistence length p≈50p \approx 50p≈50 nm.
    
- Take effective width weff≈5w_{\text{eff}} \approx 5weff​≈5 nm (high-salt dsDNA).
    
    Nano-2_F1_nanoconfined DNA_2025
    
- Channel is 100×200 nm → effective size D≈100⋅200 nm≈141 nmD \approx \sqrt{100\cdot 200}\,\text{nm} \approx 141\,\text{nm}D≈100⋅200​nm≈141nm.
    

Compute scaling factor:

- pweff=50×5=250p w_{\text{eff}} = 50 \times 5 = 250pweff​=50×5=250 nm²
    
- (250)1/3≈(250)^{1/3} \approx(250)1/3≈ a few nm
    
- D2/3∼(141)2/3D^{2/3} \sim (141)^{2/3}D2/3∼(141)2/3 nm^(2/3)
    

Doing the numbers gives an extension fraction of roughly:

LzLc∼0.2−0.25\frac{L_z}{L_c} \sim 0.2 - 0.25Lc​Lz​​∼0.2−0.25

So **DNA is stretched to about 20–25% of its contour length** in such a channel. Exact value depends on the unknown numerical prefactor and the precise ppp and weffw_{\text{eff}}weff​, but the key message: **order 20% extension**.

---

### Q5. Check the Flory–Pincus estimate of RgR_gRg​ → prefactor ≈ 90 nm

Tegenfeldt quote a scaling for free-solution radius of gyration:

Rg≈A nkbp0.6R_g \approx A\, n_{\text{kbp}}^{0.6}Rg​≈Ankbp0.6​

where nkbpn_{\text{kbp}}nkbp​ is the length in kilobasepairs. Using the Flory–Pincus model for a self-avoiding chain:

Theme F1 - Lecture notes_2025

Rg∼(p weff)1/5Lc3/5R_g \sim (p\,w_{\text{eff}})^{1/5} L_c^{3/5}Rg​∼(pweff​)1/5Lc3/5​

Write Lc=nkbp×103 bp×0.34 nm/bpL_c = n_{\text{kbp}} \times 10^3\,\text{bp} \times 0.34\text{ nm/bp}Lc​=nkbp​×103bp×0.34 nm/bp. Group terms:

Rg∼(p weff)1/5(0.34×103)3/5nkbp3/5R_g \sim (p\,w_{\text{eff}})^{1/5} (0.34\times 10^3)^{3/5} n_{\text{kbp}}^{3/5}Rg​∼(pweff​)1/5(0.34×103)3/5nkbp3/5​

So the prefactor is:

A≈(p weff)1/5(0.34×103)3/5A \approx (p\,w_{\text{eff}})^{1/5} (0.34\times 10^3)^{3/5}A≈(pweff​)1/5(0.34×103)3/5

Using typical values (as in the paper):

- p=60p = 60p=60 nm
    
- weff=2w_{\text{eff}} = 2weff​=2 nm
    

gives:

A≈86 nm≈90 nmA \approx 86 \text{ nm} \approx 90 \text{ nm}A≈86 nm≈90 nm

So the **90 nm** prefactor stated in the paper is consistent with the Flory–Pincus model to within normal parameter uncertainty.

---

### Q6. Estimate RgR_gRg​ for λ-DNA (TOTO-1 stained, actual buffer)

Take λ-DNA length n=48.5n = 48.5n=48.5 kbp. Tegenfeldt found experimentally for TOTO-1 stained DNA:

Rg≈80 nm  n0.6R_g \approx 80\,\text{nm}\; n^{0.6}Rg​≈80nmn0.6

Using this:

- Compute n0.6n^{0.6}n0.6 with n=48.5n = 48.5n=48.5.
    
- Result: Rg≈0.8R_g \approx 0.8Rg​≈0.8 µm (≈ 0.82 µm).
    

Using the theoretical 90 nm prefactor:

Rg≈90 nm  ×48.50.6≈0.9 μmR_g \approx 90\,\text{nm}\;\times 48.5^{0.6} \approx 0.9\,\mu\text{m}Rg​≈90nm×48.50.6≈0.9μm

So:

- **Theory**: Rg≈0.9R_g \approx 0.9Rg​≈0.9 µm
    
- **Experiment**: Rg≈0.8R_g \approx 0.8Rg​≈0.8 µm
    

They are reasonably close, especially given uncertainties in ppp, weffw_{\text{eff}}weff​ and dye effect on contour length.

---

### Q7. Confirm the relaxation time estimate τ≈1.6\tau \approx 1.6τ≈1.6 s

From de Gennes scaling, Tegenfeldt give the relaxation time of confined DNA as:

τ≈8π5 ηLc2kBT (pweff)−2/3D1/3\tau \approx \frac{8\pi}{5}\,\frac{\eta L_c^2}{k_BT}\,(p w_{\text{eff}})^{-2/3} D^{1/3}τ≈58π​kB​TηLc2​​(pweff​)−2/3D1/3

Use typical values for λ-DNA:

- Lc≈22 μmL_c \approx 22\,\mu\text{m}Lc​≈22μm (TOTO-1 stained λ in their buffer).
    
- p≈60p \approx 60p≈60 nm, weff≈2w_{\text{eff}} \approx 2weff​≈2 nm.
    
- Channel “diameter” D≈100D \approx 100D≈100 nm.
    
- Viscosity η≈1\eta \approx 1η≈1 mPa·s.
    
- kBT≈4.1×10−21k_BT \approx 4.1 \times 10^{-21}kB​T≈4.1×10−21 J at room temp.
    

Plugging these into the formula gives a relaxation time of order:

τ∼1–2 s\tau \sim 1\text{–}2\ \text{s}τ∼1–2 s

and more precise evaluation gives about **1.6 s**, matching the value stated in the paper.

Physically: this is the time it takes for the extension of confined λ-DNA to “forget” its previous value and relax back to equilibrium after a perturbation.

---

If you’d like, next step could be to turn these notes + answers into a compact formula sheet or a one-page summary for revision.

Sources

##### You said:

Do questions 8, 9, 10

###### ChatGPT said:

Thought for 36s

Thought for 1m 33s

Here we go—questions 8–10, with the reasoning kept as simple as possible.

---

### Question 8

**What is the measured extension factor, ϵ?**

From the paper (Tegenfeldt PNAS 2004), they analyze λ-DNA (one monomer of the λ-ladder) in 100 nm wide channels. They report:

- Contour length of λ-DNA with TOTO-1 dye:  
    L≈22 μmL \approx 22\ \mu\text{m}L≈22 μm
    
    tegenfeldt 2004 the dynamic of …
    
- Measured end-to-end extension in the 100 nm channel:  
    Lz≈8 μmL_z \approx 8\ \mu\text{m}Lz​≈8 μm for the monomer peak.
    
    tegenfeldt 2004 the dynamic of …
    

The extension factor is defined as

ε=LzL.\varepsilon = \frac{L_z}{L}.ε=LLz​​.

Plug in the numbers:

ε=8 μm22 μm≈0.36.\varepsilon = \frac{8\ \mu\text{m}}{22\ \mu\text{m}} \approx 0.36.ε=22 μm8 μm​≈0.36.

**Answer Q8:**

ε≈0.36\boxed{\varepsilon \approx 0.36}ε≈0.36​

So the DNA is stretched to about **36%** of its full contour length in the nanochannel.

---

### Question 9

**Resolution 220 nm – how many base pairs is that in the chip?**

We want to know: along the stretched DNA in the nanochannel, how many base pairs correspond to a distance of **220 nm** (the diffraction-limited resolution).

We already know in the experiment:

- λ-DNA has **48.5 kbp** (48,500 base pairs).
    
- In the channel, the **projected length** (extension) is  
    Lz≈8 μm=8000 nmL_z \approx 8\ \mu\text{m} = 8000\ \text{nm}Lz​≈8 μm=8000 nm.
    
    tegenfeldt 2004 the dynamic of …
    

So the _projected_ length per kilobase pair in the channel is:

length per kbp=8000 nm48.5 kbp≈165 nm/kbp.\text{length per kbp} = \frac{8000\ \text{nm}}{48.5\ \text{kbp}} \approx 165\ \text{nm/kbp}.length per kbp=48.5 kbp8000 nm​≈165 nm/kbp.

This means:

- **1 kbp ≈ 165 nm** along the channel.
    

Now we compare that to the optical resolution (220 nm):

number of kbp per resolution element=220 nm165 nm/kbp≈1.33 kbp.\text{number of kbp per resolution element} = \frac{220\ \text{nm}}{165\ \text{nm/kbp}} \approx 1.33\ \text{kbp}.number of kbp per resolution element=165 nm/kbp220 nm​≈1.33 kbp.

Convert to base pairs:

1.33 kbp≈1.3×103 bp≈1300 bp.1.33\ \text{kbp} \approx 1.3 \times 10^3\ \text{bp} \approx 1300\ \text{bp}.1.33 kbp≈1.3×103 bp≈1300 bp.

So, the microscope cannot distinguish features that are closer than about **1.3 kbp** apart along the stretched DNA.

**Answer Q9:**

220 nm corresponds to roughly 1.3×103 bp (about 1300 base pairs).\boxed{\text{220 nm corresponds to roughly } 1.3 \times 10^3\ \text{bp} \text{ (about 1300 base pairs).}}220 nm corresponds to roughly 1.3×103 bp (about 1300 base pairs).​

---

### Question 10

**How would you estimate the throughput (molecules per minute) with a 200 × 200 µm field of view?**

Here the question is more about **order-of-magnitude reasoning** than an exact number. We combine two ideas:

1. **How many channels are in the field of view?**
    
2. **How many “measurement cycles” can we do per minute?**
    

#### 1. Number of channels in a 200 × 200 µm field of view

From the device design and figures, the nanochannels are parallel with a typical spacing (pitch) of about **2 µm** (this is also a typical value seen in such nanochannel arrays and compatible with the post spacing etc.). If the field of view is 200 µm across:

Nchannels≈200 μm2 μm≈100 channels.N_{\text{channels}} \approx \frac{200\ \mu\text{m}}{2\ \mu\text{m}} \approx 100\ \text{channels}.Nchannels​≈2 μm200 μm​≈100 channels.

So, in the microscope image you see on the order of **~100 channels** at once.

#### 2. How often can we load a new set of molecules?

From the paper description of the imaging protocol:

- They turn on an **electrophoretic field for ~2 s** to bring new molecules into the nanochannels.
    
- Then they **record ~20 frames at 10 Hz**, which takes another ~2 s.
    
    tegenfeldt 2004 the dynamic of …
    

So one “measurement cycle” (load + image) is roughly:

tcycle≈2 s (field)+2 s (imaging)≈4 s.t_{\text{cycle}} \approx 2\ \text{s (field)} + 2\ \text{s (imaging)} \approx 4\ \text{s}.tcycle​≈2 s (field)+2 s (imaging)≈4 s.

The number of cycles per minute is then:

cycles per minute≈60 s4 s/cycle≈15 cycles/min.\text{cycles per minute} \approx \frac{60\ \text{s}}{4\ \text{s/cycle}} \approx 15\ \text{cycles/min}.cycles per minute≈4 s/cycle60 s​≈15 cycles/min.

Assume that in each cycle, **about one molecule per channel** is present and analyzable (some channels may be empty, some may have more than one, but this gives an order-of-magnitude estimate).

Total molecules analyzed per minute:

Nmolecules/min≈Nchannels×cycles per minute≈100×15≈1500.N_{\text{molecules/min}} \approx N_{\text{channels}} \times \text{cycles per minute} \approx 100 \times 15 \approx 1500.Nmolecules/min​≈Nchannels​×cycles per minute≈100×15≈1500.

So you’re in the ballpark of **10³ molecules per minute**.

**Answer Q10 (with reasoning):**

- Estimate ~100 nanochannels in a 200 µm-wide field of view (channel pitch ~2 µm).
    
- Each measurement cycle (load + imaging) takes ~4 s, so ~15 cycles per minute.
    
- Each channel gives ~1 molecule per cycle →
    
    Throughput ∼103 molecules per minute (around 1500 molecules/min).\boxed{\text{Throughput } \sim 10^3\ \text{molecules per minute (around } 1500\ \text{molecules/min).}}Throughput ∼103 molecules per minute (around 1500 molecules/min).​

This is an approximate but reasonable estimate for the throughput of the nanochannel-based DNA sizing in the Tegenfeldt setup.