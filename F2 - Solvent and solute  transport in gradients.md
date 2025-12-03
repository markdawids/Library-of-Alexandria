
2025-11-23 17:33
Tags: [[Nanosystems]]

## Systems we study

We look at **solute–solvent systems** in micro- and nanochannels:
- **Solvent**: usually water (buffer).
- **Solutes**: ions (salts), small molecules, polymers (PEG, DNA), nanoparticles.    
- Often the solute is **fluorescently labelled** so we can track it with a microscope.

We focus on how **gradients** in **temperature** or **concentration** generate motion of:
- The **solute** (particles, DNA, etc.).
- The **solvent** (water flow in channels).

## Thermophoresis – transport in a temperature gradient

#### Basic idea

![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image.png|568x280]]

#### Why does thermophoresis happen?

![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-1.png]]
- ![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-6.png|531x305]]


#### Hot-spot experiments with DNA

**Setup**:
- Genomic DNA in buffer inside a microchannel.
- DNA is fluorescent; we image it.
- An IR laser creates a **local hot spot** in the channel.

**Observations**:
- DNA is depleted near the hot spot, i.e. it is pushed away → ($S_{T}>0$).
- Calibration with a temperature-sensitive fluorescent dye (ruthenium complex) allows conversion of intensity changes to **temperature maps**.
- The IR beam is a few µm wide, but the hot region grows to ~50 µm due to heat diffusion.

This directly visualizes thermophoresis: a temperature gradient changing **concentration profiles**.

![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-3.png|483x345]]
#### DNA in a nanochannel above a hot spot

![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-2.png]]
- ![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-5.png|404x288]]
- ![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-4.png|608x306]]

#### Thermoviscous flows from moving hot spots

Another experiment: a thin **water–glycerol film** (~20 µm thick) with tracer particles.
- An IR laser spot is scanned in a circle.
- Tracer particles move in circles **opposite** the laser motion.

This is not just thermophoresis of the particles; it is **bulk fluid flow** caused by:
- Temperature-dependent viscosity (hot → less viscous).
- Thermal expansion and asymmetric heating as the spot moves.

This produces **thermoviscous flows**: subtle fluid motion driven by temperature-dependent mechanical properties of the liquid.

![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-7.png|440x261]]![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-8.png|236x230]]


## Diffusio-osmosis and diffusio-phoresis – transport in concentration gradients

#### Core concepts

- **Diffusio-osmosis (DO)**: flow of **liquid along a surface** driven by a **solute concentration gradient**.
- **Diffusio-phoresis (DP)**: motion of a **particle** in a solute gradient.

Both come from interactions in a thin layer near surfaces:
- The solute feels a **surface potential** $\Phi\left(y\right)$.
- This makes the solute concentration near the surface differ from the bulk.
- If the bulk concentration varies along x, the **osmotic pressure** in the near-surface layer also varies along x.
- That pressure gradient drives a **tangential flow** (DO) or particle motion (DP).

#### Neutral solute at a wall

**Slip velocity** - Difference in speed between two phases (like a fluid and a solid particle) or between a fluid and a solid surface.

![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-9.png]]
- **KEY**: **Neutral solute** (not charged) “feels” a **surface potential** Φ(y) near the wall → it is slightly attracted or repelled close to the surface.
	- Tiny **pressure gradient parallel to the wall** pushes the liquid along the surface → that’s **diffusio-osmosis**.
	- ![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-17.png]]

#### Charged solute and the electric double layer

![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-10.png]]
- ![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-20.png]]
- ![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-16.png]]

#### From slip velocity to channel flow

![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-11.png|522x358]]

- ![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-21.png|563x218]]

#### Diffusio-phoresis

![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-12.png|498x131]]


## Lee et al. 2014 – Osmotic flow through nanochannels

#### Device and measurement method

![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-13.png]]

#### Results with salt gradients

![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-14.png]]

### 4.3 Neutral polymer gradients and sign change

![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-15.png]]

## Diffusiophoretic trapping application

- ![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-23.png|510x251]]

**Practical use** of diffusio-phoresis: using a salt gradient to **trap and analyse tiny vesicles** (liposomes and exosomes) in nanochannels.

1. **Device**  
	- They make **nanofluidic funnels**: shallow nanochannels that are wide at one end and narrow at the other, moulded in plastic and sealed with a thin lid. The channels are only a few hundred nanometres deep.
    
2. **Salt gradient = “force field”**  
    - They create a **salt concentration gradient** along the channel (high salt at one side, low at the other). Because the vesicles are charged, this gradient makes them move by **diffusio-phoresis**.
    
3. **Trapping mechanism**  
    - Inside the funnel, three effects balance:
		- Diffusio-phoretic drift in the salt gradient,
		- Ordinary diffusion,
		- Sometimes a small pressure-driven flow.

![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-22.png|547x295]]

For a given vesicle type (size + surface charge), these balance at a particular **position** in the funnel, so particles **accumulate there** → a “Diffusiophoretic trap”.

![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image 1.png|568x280]]

4. **Why it’s useful**  
    - Different vesicles stop at **different positions**, so they can:
		- **Separate and concentrate** specific liposomes or exosomes,
		- Measure **size and zeta potential** from one experiment,		    
		- Study **fusion/interaction kinetics** of trapped vesicles.

In short: the salt gradient plus nanochannel geometry turns into a tunable nano-trap and characterization tool for biological nanoparticles.

![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-24.png|439x305]]

![[2 - Source Material/Images/F2 - Solvent and solute  transport in gradients/image-25.png|438x204]]

## Big-picture summary

- **Thermophoresis**: temperature gradients move solutes; balance with diffusion is captured by ($S_{T}$). Rooted in entropy changes of water and ions around the solute.
- **Thermoviscous flows**: a moving hot spot in a thin film can drive fluid motion due to temperature-dependent viscosity and thermal expansion.
- **Diffusio-osmosis**: solute gradients along surfaces cause flow within a thin interfacial layer, controlled by surface potentials and solute properties.
- **Diffusio-phoresis**: the same effect but viewed as particle motion.
- **Nanochannel experiments (Lee 2014)**: directly measure tiny flows driven by concentration gradients in fully permeable channels, and show how flow direction and magnitude depend on whether the solute is a salt (charged) or a neutral polymer.









## Questions

## Q1 – Compute (K L^*) for the hard-wall potential

We have the “hard wall” potential

[  
\Phi(y)=  
\begin{cases}  
\infty, & y<a \  
0, & y>a  
\end{cases}  
]

In Eq. (22) of the notes, for a neutral solute:

[  
v_s = -\frac{k_B T}{\eta}\frac{dC}{dx} K L^*  
]

with

[  
K = \int_0^\infty!\big(e^{-\Phi(y)/k_BT}-1\big),dy,  
\qquad  
L^* = \frac{\int_0^\infty y\big(e^{-\Phi(y)/k_BT}-1\big),dy}{K}  
]

For the hard wall:

- For (y<a): (\Phi=\infty\Rightarrow e^{-\Phi/k_BT}=0\Rightarrow e^{-\Phi/k_BT}-1=-1)
    
- For (y>a): (\Phi=0\Rightarrow e^{-\Phi/k_BT}-1 = 0)
    

So the integrals only run from (0) to (a).

**Compute (K):**

[  
K = \int_0^a (-1),dy= -a  
]

**Compute numerator of (L^*):**

[  
\int_0^\infty y(e^{-\Phi/k_BT}-1),dy = \int_0^a y(-1),dy = -\frac{a^2}{2}  
]

So

[  
L^* = \frac{-a^2/2}{K}=\frac{-a^2/2}{-a}=\frac{a}{2}  
]

Finally

[  
K L^* = (-a)\cdot \frac{a}{2} = -\frac{a^2}{2}  
]

**Answer Q1:**

[  
K L^* = -\frac{a^2}{2}  
]

---

## Q2 – Slip velocity (v_s) far from the wall

From Eq. (22):

[  
v_s = -\frac{k_B T}{\eta}\frac{dC}{dx} K L^*  
]

Insert (K L^* = -a^2/2):

[  
v_s = -\frac{k_B T}{\eta}\frac{dC}{dx}\left(-\frac{a^2}{2}\right)  
= \frac{k_B T}{\eta},\frac{a^2}{2},\frac{dC}{dx}  
]

**Answer Q2:**

[  
\boxed{v_s = \frac{k_B T}{2\eta} a^2 \frac{dC}{dx}}  
]

---

## Q3 – Direction of the diffusio-osmotic flow

Take (x) increasing to the right. Suppose the solute concentration increases to the right, so

[  
\frac{dC}{dx} > 0.  
]

From Q2, (v_s>0), so the fluid velocity is **positive**, i.e. the liquid moves **to the right**, from the **low concentration side to the high concentration side**.

Physical picture in simple words:

- Because of the hard wall, the solute “centers” cannot come closer than a distance (a) from the wall, so close to the wall there is a thin layer that is slightly solute-poor.
    
- If the bulk concentration is higher on the right, the osmotic pressure in the bulk on the right is higher than in the depleted layer near the wall.
    
- This pressure imbalance pushes the liquid along the wall from the low-concentration side toward the high-concentration side.
    

So **for a depleted neutral solute layer, diffusio-osmosis drives the liquid from low to high bulk concentration**.

---

## Q4 (optional) – Velocity profile (v_x(y))

We start from Eq. (19) in the notes:

[  
v_x(y)  
= -\frac{k_B T}{\eta}\frac{dC}{dx},  
\left[  
y\int_{\infty}^{y}\big(e^{-\Phi(y')/k_BT}-1\big),dy'

- \int_0^y y' \big(e^{-\Phi(y')/k_BT}-1\big),dy'  
    \right]  
    ]
    

Rewrite the first integral with swapped limits so a plus sign appears:

[  
v_x(y)  
= \frac{k_B T}{\eta}\frac{dC}{dx}  
\left[  
y\int_{y}^{\infty}\big(e^{-\Phi}-1\big),dy'

- \int_0^y y' \big(e^{-\Phi}-1\big),dy'  
    \right]  
    ]
    

Using the hard-wall values:

- (e^{-\Phi}-1=-1) for (0<y'<a)
    
- (e^{-\Phi}-1=0) for (y'>a)
    

### Case 1: (0<y<a)

[  
\int_{y}^{\infty}(e^{-\Phi}-1),dy' = \int_y^a (-1) dy' = -(a-y)  
]

[  
\int_0^{y}y'(e^{-\Phi}-1),dy' = \int_0^{y}y'(-1) dy' = -\frac{y^2}{2}  
]

So

[  
v_x(y) = \frac{k_B T}{\eta}\frac{dC}{dx}  
\left[ y\cdot(-(a-y)) -\left(-\frac{y^2}{2}\right)\right]  
= \frac{k_B T}{\eta}\frac{dC}{dx}\left(-ay + \frac{3}{2}y^2\right)  
]

You can check:

- at (y=0): (v_x(0)=0) (no-slip)
    
- at (y=a): (v_x(a)=\frac{k_B T}{\eta}\frac{a^2}{2}\frac{dC}{dx}=v_s).
    

### Case 2: (y\ge a)

Then the first integral is zero (no interaction region above (a)):

[  
\int_{y}^{\infty}(e^{-\Phi}-1),dy' = 0  
]

The second integral only has support from 0 to (a):

[  
\int_0^{y}y'(e^{-\Phi}-1),dy' = \int_0^a y'(-1)dy' = -\frac{a^2}{2}  
]

Thus

[  
v_x(y) = \frac{k_B T}{\eta}\frac{dC}{dx}\left[0 - \left(-\frac{a^2}{2}\right)\right]  
= \frac{k_B T}{\eta}\frac{a^2}{2}\frac{dC}{dx} = v_s  
]

So:

- Between the wall and (y=a), (v_x(y)) rises from 0 to (v_s) with a quadratic profile.
    
- For (y>a), the flow is **plug-like**: uniform velocity (v_s).
    

---

## Q5 – Expression for (R_g) of double-stranded DNA and salt-dependence of mobility

Double-stranded DNA (dsDNA) is a **semi-flexible polymer**. A good model is the **worm-like chain** with:

- contour length (L_c)
    
- persistence length (l_p) (how stiff the polymer is).
    

For a long chain ((L_c \gg l_p)), a common approximation is

[  
R_g \approx \sqrt{\frac{L_c,l_p}{3}}  
]

where

- (L_c = N_{\text{bp}}\times 0.34\ \text{nm}) (0.34 nm per base pair),
    
- (l_p \approx 50\ \text{nm}) for dsDNA in typical buffer.
    

This gives us an expression for dsDNA’s radius of gyration:

[  
R_g \simeq \sqrt{\frac{(N_{\text{bp}}\cdot 0.34\ \text{nm})(50\ \text{nm})}{3}}  
]

**Does mobility depend on salt?**

The polymer DO mobility for a neutral polymer is approximated in the exercise as

[  
\mu_{DO} \approx -\frac{k_B T}{\eta}R_g^2.  
]

So if (R_g) changes, (|\mu_{DO}|) changes.

DNA is **charged**, so its stiffness (l_p) depends on salt:

- At **low salt**, the charges repel more strongly → DNA is stiffer → larger (l_p) → larger coil ((R_g) increases).
    
- At **high salt**, screening reduces electrostatic repulsion → DNA is more flexible → (R_g) shrinks.
    

Because (R_g^2 \propto l_p), the **mobility (|\mu_{DO}|) decreases as salt concentration increases**.

---

## Q6 – (R_g) for λ-DNA (48 kbp)

λ-DNA length:

[  
L_c = 48,000 \times 0.34\ \text{nm} \approx 16,320\ \text{nm} = 16.32\ \mu\text{m}  
]

Take (l_p \approx 50\ \text{nm} = 0.05\ \mu\text{m}).

Use (R_g \approx \sqrt{L_c l_p /3}):

[  
R_g \approx \sqrt{\frac{16.32\ \mu\text{m} \times 0.05\ \mu\text{m}}{3}}  
= \sqrt{\frac{0.816\ \mu\text{m}^2}{3}}  
\approx \sqrt{0.272\ \mu\text{m}^2}  
\approx 0.52\ \mu\text{m}  
]

**Answer Q6:** (R_g(\lambda\text{-DNA}) \approx 0.5\ \mu\text{m}).

---

## Q7 – DO mobility and flow rate for a 1 µM λ-DNA gradient

We use

[  
\mu_{DO} \approx -\frac{k_B T}{\eta}R_g^2.  
]

Take:

- (k_B T \approx 4.1\times10^{-21}\ \text{J}),
    
- (\eta \approx 10^{-3}\ \text{Pa·s}),
    
- (R_g \approx 0.52\ \mu\text{m} = 5.2\times10^{-7}\ \text{m}).
    

Then

[  
R_g^2 \approx (5.2\times10^{-7})^2 \approx 2.7\times10^{-13}\ \text{m}^2  
]

[  
\frac{k_B T}{\eta} \approx 4.1\times10^{-18}\ \text{m}^3/\text{s}  
]

[  
\mu_{DO} \approx -(4.1\times10^{-18})(2.7\times10^{-13})  
\approx -1.1\times10^{-30}\ \text{m}^5/\text{s}  
]

Now use Eq. (9) from Lee’s paper for a neutral solute:

[  
Q = \frac{w h}{L},\mu_{DO}(n_L-n_R)  
]

Channel dimensions (Lee 2014):

- (h = 163\ \text{nm} = 1.63\times10^{-7}\ \text{m})
    
- (w = 5\ \mu\text{m} = 5\times10^{-6}\ \text{m})
    
- (L = 150\ \mu\text{m} = 1.5\times10^{-4}\ \text{m})
    

Gradient: ((n_L-n_R) = 1\ \mu\text{M}).

Convert 1 µM to **number density**:

- 1 µM = (10^{-6}\ \text{mol}/\text{L} = 10^{-3}\ \text{mol}/\text{m}^3)
    
- Number density difference
    

[  
\Delta n = 10^{-3}\ \text{mol/m}^3 \times N_A  
\approx 6.0\times10^{20}\ \text{m}^{-3}  
]

Plug into (Q):

1. First get the slip velocity scale:
    

[  
v_s \approx \mu_{DO},\frac{\Delta n}{L}  
\approx (-1.1\times10^{-30})\frac{6.0\times10^{20}}{1.5\times10^{-4}}  
\approx -4.5\times10^{-6}\ \text{m/s}  
= -4.5\ \mu\text{m/s}  
]

2. Flow rate (Q = v_s \times (w h)):
    

[  
A = w h \approx (5\times10^{-6})(1.63\times10^{-7})  
\approx 8.15\times10^{-13}\ \text{m}^2  
]

[  
Q \approx (-4.5\times10^{-6})\times(8.15\times10^{-13})  
\approx -3.6\times10^{-18}\ \text{m}^3/\text{s}  
]

Convert to fL/min:

- (1\ \text{fL} = 10^{-18}\ \text{m}^3)
    
- So (Q \approx -3.6\ \text{fL/s} \approx -220\ \text{fL/min}).
    

The minus sign just tells us the flow direction (toward the higher DNA concentration, since polymers are depleted at the wall).

**Answer Q7:**

- (\mu_{DO} \approx -1\times10^{-30}\ \text{m}^5/\text{s}).
    
- For a 1 µM λ-DNA gradient in this nanochannel, the predicted flow rate is of order  
    (|Q| \sim 2\times10^{2}\ \text{fL/min}).
    

---

## Q8 – Solution (C(x)) of the diffusion–advection equation

The 1D steady equation is

[  
v,\frac{dC}{dx} = D,\frac{d^2C}{dx^2},  
]

with (v = Q/(wh)) and boundary conditions (C(0)=C_L), (C(L)=0).

Solving this ODE gives

[  
C(x) = C_L,\frac{e^{vL/D} - e^{vx/D}}{e^{vL/D}-1}.  
]

This is equivalent to the expression printed on the sheet (just algebraically rearranged).

- For **(v=0)**, the exponentials can be expanded (see Q9) and you get a straight line: (C(x)=C_L(1-x/L)).
    
- For **(v>0)**, the profile becomes **curved**: advection carries the tracer along, so the concentration drops more sharply near the downstream end.
    
- The bigger (v) is (e.g. 8 µm/s vs 1 µm/s), the more bent the curve becomes.
    

---

## Q9 – Small-velocity limit gives a linear profile

Take the exact solution:

[  
C(x) = C_L,\frac{e^{vL/D} - e^{vx/D}}{e^{vL/D}-1}.  
]

Assume (vL/D \ll 1) (“Pe number” small). Then we can expand the exponentials:

[  
e^{vL/D} \approx 1 + \frac{vL}{D},\quad  
e^{vx/D} \approx 1 + \frac{vx}{D}.  
]

Plug in:

- Numerator: (e^{vL/D}-e^{vx/D} \approx \big(1+\frac{vL}{D}\big) - \big(1+\frac{vx}{D}\big) = \frac{v}{D}(L-x))
    
- Denominator: (e^{vL/D}-1 \approx \frac{vL}{D})
    

So

[  
C(x) \approx C_L,\frac{(v/D)(L-x)}{(v/D)L}  
= C_L\left(1-\frac{x}{L}\right),  
]

which is exactly the **linear** purely diffusive profile.

---

## Q10 – Is the salt gradient essentially linear?

We use the same solution but for the salt, with (D) the salt diffusivity (D_{\text{salt}}\approx1.6\times10^{-9}\ \text{m}^2/\text{s}) for NaCl.

The key parameter is the Péclet number

[  
\text{Pe} = \frac{vL}{D_{\text{salt}}}.  
]

From the experiment, even for fairly large flow rates, the average velocities are of order a few to (\sim 10\ \mu\text{m/s}). With (L=150\ \mu\text{m}):

- For (v = 1\ \mu\text{m/s}): (\text{Pe} \approx 0.09)
    
- For (v = 8\ \mu\text{m/s}): (\text{Pe} \approx 0.75)
    

When Pe ≪1, we just showed the profile is almost linear (Q9). Even for Pe ~ 0.7, the deviation from a straight line is moderate (on the order of 10–15%). So, **to a good approximation, the salt gradient is close to linear**, and the assumption made in the paper is reasonable.

---

## Q11 – Linear salt concentration profile

If we assume a linear gradient between (x=0) and (x=L):

[  
C_s(0) = C_{s,L},\quad C_s(L)=C_{s,R},  
]

then

[  
C_s(x) = C_{s,L} + \frac{C_{s,R} - C_{s,L}}{L},x.  
]

Equivalently:

[  
C_s(x) = C_{s,L}\left(1-\frac{x}{L}\right) + C_{s,R}\frac{x}{L}.  
]

---

## Q12 – Calculate (D_{DO}) for the salt (NaCl)

We use Eq. (78–79) from the notes / Eq. (4) in Lee:

[  
v_s = -D_{DO},\frac{d\ln C_s}{dx},  
]  
[  
D_{DO} = \frac{\varepsilon}{\eta}\frac{k_BT}{Ze}  
\left[  
\beta\zeta - \frac{2k_BT}{Ze}\ln(1-\gamma^2)  
\right],  
]  
with

- (\varepsilon = \varepsilon_0 \varepsilon_r \approx 6.95\times10^{-10}\ \text{F/m}) for water,
    
- (\eta = 10^{-3}\ \text{Pa·s}),
    
- (Z=1),
    
- (e=1.602\times10^{-19}\ \text{C}),
    
- (\zeta = -55\ \text{mV} = -0.055\ \text{V}) (given),
    
- (\beta = (D_+ - D_-)/(D_+ + D_-) \approx -0.20) for NaCl,
    
- (\gamma = \tanh\left(\frac{Ze\zeta}{4k_BT}\right)).
    

Numerically this gives

[  
\gamma \approx -0.49,  
\qquad  
\ln(1-\gamma^2) < 0,  
]

and plugging all numbers in yields roughly

[  
D_{DO} \approx 4\text{–}5\times10^{-10}\ \text{m}^2/\text{s}.  
]

Sign: for a negatively charged wall ((\zeta<0)), this (D_{DO}>0) means, via (v_s=-D_{DO}d\ln C_s/dx), that the liquid flows from **high salt to low salt**, in agreement with the experiment.

---

## Q13 – Slip velocity (v_s(x)), flow rate, and what goes wrong

If we combine:

[  
v_s(x) = -D_{DO}\frac{d\ln C_s(x)}{dx},  
]

and assume a **linear** salt profile (Q11):

[  
C_s(x) = C_{s,L} + \frac{C_{s,R}-C_{s,L}}{L}x,  
]

then

[  
\frac{dC_s}{dx} = \frac{C_{s,R}-C_{s,L}}{L} = \text{const},  
]

but

[  
\frac{d\ln C_s}{dx} = \frac{1}{C_s(x)}\frac{dC_s}{dx}  
]

**depends on (x)**, because (C_s(x)) is changing along the channel.

So (v_s(x)) varies like (1/C_s(x)):

- Where the salt concentration is **low**, (|v_s|) is **larger**.
    
- Where the salt is **high**, (|v_s|) is **smaller**.
    

If we now naively convert slip into a local flow rate

[  
Q_{\text{slip}}(x) = w h, v_s(x),  
]

we get a **different (Q_{\text{slip}}) at different positions (x)**.

But the channel has:

- constant cross-section,
    
- incompressible liquid,
    
- steady state.
    

In such a situation, **mass conservation (continuity) requires the flow rate (Q) to be the same everywhere** along the channel.

So this simple “local slip everywhere” picture plus a strictly linear salt profile **appears to violate mass conservation** (a fundamental law).

What’s going on?

- Eq. (78) is derived for an **infinite flat surface** with a local salt gradient and doesn’t enforce global conservation in a finite channel.
    
- In a real channel, the coupled salt profile and flow profile adjust together so that the total (Q) is constant—i.e. the actual (C_s(x)) is not exactly the simple linear profile if you fully solve the problem self-consistently.
    

So the “problem” you should notice is: **if you plug a strictly linear (C_s(x)) into the slip formula everywhere, you predict a position-dependent flow rate, breaking continuity / mass conservation.**
