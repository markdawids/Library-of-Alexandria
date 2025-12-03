
2025-12-03 15:23
Tags: [[Nanosystems]]

## Part 1: Nucleation

### 1. Introduction to Synthesis Strategies

Creating nanomaterials usually follows one of two main strategies:

- **Top-Down:** This is the "physical" way. You start with a bulk material (a large piece) and sculpt or cut away material to get the size you want.
- **Bottom-Up:** This is the "chemical" way. You build the material atom-by-atom or molecule-by-molecule.

Solution phase synthesis (doing chemistry in liquids) is a "bottom-up" approach. It is popular because:

- Generally lower cost.
- Consumes less energy (often under 200°C).
- Easier to scale up than physical methods.

![[2 - Source Material/Images/F4 - Synthesis Mechanisms/image.png]]

### 2. What is Nucleation?

Nucleation is the very first step of creating a solid crystal from a liquid solution. It involves atoms or molecules in the liquid rearranging themselves into a small cluster that is stable enough to keep growing.

There are two main types of nucleation:

1. **Homogeneous Nucleation:** Occurs in a pure solution with no foreign particles.
2. **Heterogeneous Nucleation:** Occurs in the presence of foreign surfaces (impurities, walls, bubbles).
- ![[2 - Source Material/Images/F4 - Synthesis Mechanisms/image-8.png|360x197]]

### 3. Homogeneous Nucleation (The Energy Battle)

In a pure solution, forming a solid nucleus is difficult. It involves a battle between two types of energy:

- **Volume Free Energy (Good Energy):** When atoms bond together to form a solid, they release energy. This is a "negative" energy change, which is favorable. The more volume the particle has, the more stable it becomes.
- **Surface Energy (Bad Energy):** Creating a new surface between the solid and the liquid costs energy. This is a "positive" energy change, which is unfavourable.

**The Critical Radius ($r^*$)**

- When a nucleus is very small, it has a lot of surface area compared to its volume. The "bad" surface energy wins, making the tiny particle unstable. It will likely dissolve back into the liquid.
- However, if the particle manages to grow past a specific size, called the critical radius ($r^*$), the "good" volume energy takes over. At this point, the particle becomes stable and will continue to grow rather than dissolve.
- ![[2 - Source Material/Images/F4 - Synthesis Mechanisms/image-5.png]]

**The Barrier:**

- There is an energy barrier ($\Delta G^*$) that must be overcome to form a stable nucleus. This barrier represents the maximum energy cost required to create a particle of the critical size. High temperature or high supersaturation (concentration) helps overcome this barrier.
- ![[2 - Source Material/Images/F4 - Synthesis Mechanisms/image-4.png|610x345]]
	- ![[2 - Source Material/Images/F4 - Synthesis Mechanisms/image-6.png|153x216]]![[2 - Source Material/Images/F4 - Synthesis Mechanisms/image-7.png|481x178]]

### 4. Heterogeneous Nucleation (The Easier Path)

In the real world, solutions often contain impurities, container walls, or dust. Nucleation happens much faster and easier on these surfaces. This is **heterogeneous nucleation**.

- ![[2 - Source Material/Images/F4 - Synthesis Mechanisms/image-3.png]]

Why is it easier?

- Because a surface already exists, the new nucleus does not have to create a full spherical surface; it creates a "cap" shape on the existing surface. This reduces the amount of new surface energy required.

The Contact Angle ($\theta$):

- The shape of the nucleus on the surface depends on the contact angle ($\theta$), which describes how well the liquid "wets" the solid surface:

- **High Wetting (Low $\theta$):** The energy barrier is lowered significantly. If $\theta = 0$ (perfect wetting), there is no barrier at all.
- **No Wetting (High $\theta$):** If $\theta = 180$, the surface doesn't help at all, and it acts just like homogeneous nucleation.

- ![[2 - Source Material/Images/F4 - Synthesis Mechanisms/image-10.png|505x403]]
- ![[2 - Source Material/Images/F4 - Synthesis Mechanisms/image-11.png|532x332]]

**Key Takeaway:** The critical radius ($r^*$) stays the same for both types, but the _energy barrier_ is much lower for heterogeneous nucleation, making it the dominant process in most real-world situations.

- ![[2 - Source Material/Images/F4 - Synthesis Mechanisms/image-12.png|569x327]]

### 5. Multi-Step Nucleation

Classical theory assumes a single step where atoms form a cluster. 
- ![[2 - Source Material/Images/F4 - Synthesis Mechanisms/image-13.png|613x313]]

However, modern Liquid Phase Electron Microscopy (LPEM) has revealed that nucleation can happen in complex steps.

- Example: Gold Nanocrystals.

Instead of turning directly into crystals, gold atoms in solution might follow this path:

1. **Spinodal Decomposition:** The liquid separates into "gold-rich" and "gold-poor" liquid blobs.
2. **Amorphous Clusters:** The gold-rich liquid forms unstructured (amorphous) solid clumps.
3. **Crystallization:** Finally, these amorphous clumps rearrange into organized crystals.

- ![[2 - Source Material/Images/F4 - Synthesis Mechanisms/image-15.png]]

---

# Part 2: Growth Mechanisms

Once a stable nucleus is formed (nucleation), the particle begins to increase in size. This is called **growth**. There are several models describing how this happens in solution and on substrates.

### 1. Growth Models in Solution

![[2 - Source Material/Images/F4 - Synthesis Mechanisms/image-16.png|569x385]]

##### A. The LaMer Mechanism

This is a classic model that describes synthesis in three distinct stages:

1. **Concentration Increase:** The amount of "monomers" (building blocks) in the solution rises rapidly.
2. **Burst Nucleation:** Once the concentration gets high enough, many nuclei form all at once (a "burst"). This uses up a lot of monomers, causing the concentration to drop quickly below the level needed for new nuclei to form.
3. **Diffusion-Controlled Growth:** No new nuclei are formed. The remaining monomers simply diffuse (swim) through the liquid and attach to the existing particles, making them grow.

- ![[2 - Source Material/Images/F4 - Synthesis Mechanisms/image-17.png|637x275]]
##### B. Ostwald Ripening

This process explains why larger particles tend to eat smaller particles.

- **The Concept:** Small particles have a very high surface energy and are less stable. They tend to dissolve back into the liquid. The dissolved atoms then attach to larger, more stable particles.
- **Result:** The average particle size increases, but the _number_ of particles decreases.
- **Everyday Example:** This is why old ice cream gets "crunchy." The tiny ice crystals dissolve and redeposit onto larger ice crystals, creating large, gritty chunks.

##### C. Coalescence

This is a growth mechanism where two or more particles collide and merge into a single larger particle.

- **Random Coalescence:** The particles merge with random crystal orientations.

##### D. Oriented Attachment

This is a special type of coalescence. Before the particles merge, they rotate and align their crystal lattices (atomic grids) so they match perfectly.

- **Observation:** Researchers have used LPEM to watch particles "jump" to contact each other and rotate continuously until they lock into a perfect fit.

- ![[2 - Source Material/Images/F4 - Synthesis Mechanisms/image-20.png|497x390]]
	- Surfaces of particles A and B make contact at many points and orientations before finally attaching and growing together at specific orientation.
### 2. Growth Models on Substrates

When growing material onto a flat surface (a substrate), the interaction between the new atoms and the surface determines the shape of the growth. There are three main classical models:

![[2 - Source Material/Images/F4 - Synthesis Mechanisms/image-18.png|499x218]]

##### A. Frank-Van der Merwe (Layer-by-Layer)

- **Mechanism:** The atoms like the substrate more than they like each other. They form a complete smooth layer across the surface before starting the next layer.
- **Structure:** Flat, smooth films.

##### B. Volmer-Weber (Island Growth)

- **Mechanism:** The atoms like each other more than they like the substrate. Instead of spreading out, they clump together to form isolated "islands" or clusters on the surface.    
- **Structure:** Bumpy, isolated clusters.

##### C. Stranski-Krastanov (Layer-plus-Island)

- **Mechanism:** A mix of the two. It starts growing as a flat layer (like Frank-Van der Merwe), but after a certain thickness, the strain energy builds up, and it switches to forming islands (like Volmer-Weber).
- **Structure:** A thin flat "wetting layer" topped with islands.

##### D. Dendritic Growth

This occurs when the growth is limited by how fast material can be transported to the surface (mass transport limited) or instabilities in the growth front.

- **Appearance:** The material grows in tree-like, branching structures called dendrites.
- **Implication:** In batteries (like Lithium-ion), dendrites are dangerous. They can grow sharp spikes that pierce the separator between the anode and cathode, causing short circuits and fires.

- ![[2 - Source Material/Images/F4 - Synthesis Mechanisms/image-19.png]]
- ![[2 - Source Material/Images/F4 - Synthesis Mechanisms/image-21.png|562x365]]

### Summary of Key Differences

- **Nucleation** is the "birth" of a particle. It requires overcoming an energy barrier ($r^*$). Heterogeneous nucleation (on a surface) is easier than homogeneous (in pure liquid) because the surface lowers the energy cost.
- **Growth** is the "aging" of the particle. It can happen by adding atoms one by one (LaMer), by eating smaller neighbours (Ostwald Ripening), or by merging with others (Coalescence/Oriented Attachment). When growing on a floor (substrate), the "stickiness" of the floor determines if it grows flat or in clumps.