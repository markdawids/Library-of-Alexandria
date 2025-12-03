
2025-11-27 13:56
Tags: [[Nanosystems]]

### Part 1: Course Introduction and Motivation

#### Why Electron Microscopy?

While optical microscopy is a standard tool, it is limited by the physics of light waves. The resolution of a microscope is determined by the **Abbe diffraction limit**, which states that the smallest distance ($d$) one can resolve is roughly half the wavelength ($\lambda$) of the light used ($d=\frac{\lambda}{n\sin\left(\alpha\right)}$). For visible light, this limit is about 200 nm. To see structures at the atomic scale (Angstrom level), we need a much shorter wavelength.
- **Abbe diffraction limit** is given by the minimal distance between two points that can create constructive interference to form an image.

Electrons are used because they have extremely short wavelengths compared to light. However, unlike X-rays or neutrons which also have short wavelengths, electrons interact very strongly with matter. (Additionally, electrons give the lowest damage to the sample). The scattering cross-section of electrons (the probability of hitting an atom) is about a billion times larger than that of X-rays or neutrons. This allows electrons to generate strong signals from very small, thin samples, making atomic-scale imaging possible.

#### The Need for Liquid Phase Electron Microscopy (LPEM)

Traditional Electron Microscopy (EM) requires a high vacuum, which usually means samples must be dry and static. However, many of the most important scientific and industrial processes—such as biological activity, battery function, and chemical synthesis—occur in liquids.

LPEM is a technique developed to observe these processes "in situ" (live, as they happen). By encapsulating a very thin layer of liquid between electron-transparent membranes (like a sandwich), we can use the electron beam to view dynamic processes, such as the growth of nanoparticles or the movement of biological structures, with nanometre or even atomic resolution.


![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image.png|215x294]]![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-1.png|398x326]]
![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-3.png|659x358]]

---

### Part 2: Transmission Electron Microscopy (TEM) Fundamentals

#### The Microscope Components

An electron microscope consists of an electron gun, a system of electromagnetic lenses, and a vacuum chamber.

**The Electron**

- The gun generates the beam of electrons. There are two main types:
	- **Thermionic Gun:** Uses a heated filament (like tungsten) to boil electrons off the surface. It is cheap but produces a beam with a large energy spread (1–2 eV), which reduces image quality due to chromatic aberration.
		- ![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-7.png]]
	- **Field Emission Gun (FEG):** Uses a very sharp needle and a high electric field to pull electrons out via tunnelling. This "cold" source provides a much brighter, more coherent beam with a very narrow energy spread, making it ideal for high-resolution imaging.
		- ![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-8.png]]
	- ![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-6.png|522x263]]

**Electromagnetic Lenses**

- Glass lenses cannot focus electrons; instead, electromagnets are used to generate magnetic fields that exert a Lorentz force ($F = qv \times B$) on the electrons to focus them. However, these lenses are optically poor compared to glass lenses and suffer from defects called aberrations:
	- **Astigmatism:** The lens focuses differently in different directions (e.g., x-axis vs. y-axis).
		- ![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-10.png]]
	- **Spherical Aberration:** The edges of the lens focus light more strongly than the centre, blurring the image. Modern "aberration-corrected" microscopes use complex corrector coils to fix this, achieving sub-angstrom resolution (0.4 Å).
		- ![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-11.png]]
	- **Chromatic Aberration:** Electrons of different energies focus at different distances. This is a major issue in liquid microscopy because the liquid causes energy loss in the electrons.
		- ![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-12.png|600x386]]

![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-9.png]]

#### Electron-Matter Interactions

When the high-energy electron beam hits a solid sample, it does not just pass through; it interacts with the atoms, generating various signals used for analysis:

- **Transmitted Electrons:** Electrons that pass through the sample (used for TEM imaging).
- **Scattered Electrons:** Electrons deflected by atoms.
- **Secondary Electrons (SE):** Low-energy electrons knocked out of the sample surface (used for topography in SEM).
- **Backscattered Electrons (BSE):** High-energy electrons that bounce back (used to detect atomic number contrast in SEM).
- **X-rays:** Generated when electrons change shells, allowing for chemical analysis (EDS).

- ![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-2.png|308x245]]
#### Imaging Modes: TEM vs. STEM vs. SEM

- **SEM (Scanning Electron Microscope):** Scans a focused beam over a bulk sample surface. It detects backscattered or secondary electrons. It has lower resolution (~3 nm) but allows for large samples.
- **TEM (Transmission Electron Microscope):** Shoots a broad beam through an ultra-thin sample (10–200 nm). It offers the highest resolution (down to atoms).
- **STEM (Scanning Transmission Electron Microscope):** Focuses the beam into a tiny spot and scans it across the thin sample, detecting electrons that pass through. This is often preferred for thick liquid samples because the detector can distinguish scattered electrons better than standard TEM

![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-4.png|503x355]]
- ![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-13.png|552x271]]


![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-16.png]]
- Electrons are scattered by atomic nuclei based on their charge. -> Heavier atoms scatter electrons more than lighter ones.
	- STEM can be more sensitive to atomic number, making it more powerful at distinguishing different elements.

![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-17.png]]
- Allows imaging of samples in a gaseous environment (up to ~10 mbar), unlike standard TEM which requires high vacuum.
- Used for studying catalysis and high-temperature processes in gases.

![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-19.png]]
- Cryo-EM has reached atomic resolution, enabling scientists to locate individual atoms within proteins. This is crucial for structural biology.
#### The Beer-Lambert Law and Mean Free Path

Electrons cannot penetrate deep into matter. The beam intensity drops exponentially as it travels through a material, described by the Beer-Lambert law: ![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-5.png|191x46]].

- Here, $\lambda_{mfp}$ is the Mean Free Path, representing the average distance an electron travels before scattering. For solid materials, this is only a few nanometres to micrometres. Therefore, samples must be extremely thin to let the beam through.
	- ![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-14.png|256x230]]
	- ![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-15.png]]
		- Essentially, you want a very high energy, so that the IMFP is larger, increasing the probability of electrons passing through -> Clear transmission image.

---

### Part 3: Liquid Phase Electron Microscopy (LPEM)

#### The Liquid Cell: A Nano-Laboratory

To put liquid in the high vacuum of a TEM, it must be encapsulated. The modern approach uses microchips.

![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-20.png|670x384]]


- **Sandwich Chips:** Two silicon chips with thin "windows" (membranes) made of Silicon Nitride ($SiN_x$) are clamped together. The liquid sits between the windows.
- **Bulging Issue:** A major challenge is that the vacuum causes the thin windows to bulge outward, making the liquid layer in the centre very thick (up to 2 µm). This drastically reduces resolution because the electron beam scatters too much in the thick liquid.
	- ![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-23.png|485x187]]
- **Graphene Cells:** To solve the thickness problem, researchers use graphene sheets to trap liquid droplets. Graphene is atomically thin and strong, allowing for the thinnest possible "windows" and enabling atomic resolution imaging of liquids.
	- ![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-24.png|478x358]]

![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-21.png|700x342]]

![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-22.png]]
![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-26.png|513x357]]
![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-27.png]]


![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-28.png]]

#### Resolution in Liquid

The resolution in LPEM is usually limited by **chromatic aberration**. As electrons pass through the liquid and the windows, they scatter inelastically (losing energy). This increases the energy spread ($\Delta E$) of the beam. Because magnetic lenses focus electrons with different energies at different points (chromatic aberration), the image becomes blurry.

The resolution ($d_{TEM}$) is roughly proportional to the thickness ($T$) of the liquid layer:

$$d_{TEM} \approx \frac{\Delta E}{E}$$

To get better resolution, you must reduce the liquid thickness ($T$) or increase the electron energy ($E$).

![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-25.png]]
- Thin liquid layers are essential for high resolution! 
- STEM generally better then TEM. 
- Both better than SEM for nanoscale imaging.
#### The Problem of Radiolysis

A critical issue in LPEM is **radiolysis**. The high-energy electron beam chemically alters the water/liquid it passes through. Radiolysis is very complex.

- **Dose Rate:** The beam deposits energy into the sample. In a focused TEM beam, the dose rate can be Gigagrays per second (far higher than a nuclear reactor), (10 Gy is a deadly dose used for tumours).
- **Chemical Changes:** This radiation breaks water molecules, creating reactive radicals like hydrated electrons ($e^-_{aq}$), hydrogen radicals ($H^\bullet$), and hydrogen peroxide ($H_2O_2$).
- **Artefacts:** These radicals can cause artificial reactions. For example, hydrated electrons are strong reducing agents and can cause metal ions to precipitate into nanoparticles even without a real chemical trigger. Additionally, bubbles of hydrogen gas often form, disrupting the image.

![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-29.png]]

![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-30.png]]

![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-31.png]]
- Higher dose rate = More radicals.
	- Radicals like hydrated electrons can cause beam-induced deposition (Donation of electrons to gold ions, turning them in to solid gold).
	- Radicals like $OH^{\cdot}$ and hydrogen peroxide can etch materials.

	- ![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-32.png|564x299]]

![[2 - Source Material/Images/F3 - Analysing Nanosystems using  Liquid phase transmission electron microscopy/image-33.png]]
- Another reason why working with high energy electrons is better.
	- A longer path means electrons pass through the water with _fewer_ collisions. Fewer collisions mean less energy is deposited into the liquid, which means less heating and less radiolysis (chemical damage).

#### Summary of Challenges

When designing an LPEM experiment, one must balance three factors:

1. **Resolution:** Requires a very thin liquid layer.
2. **Dynamics:** Requires a liquid layer thick enough for particles to move and flow.
3. **Beam Damage:** Requires keeping the electron dose low to avoid boiling the liquid or chemically altering the sample with radiolysis.