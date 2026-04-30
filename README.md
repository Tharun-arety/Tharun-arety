## Tharun Arety

M.Sc. Materials Science and Engineering graduate at the University of Augsburg.
My work sits at the intersection of computational
structural mechanics, composite materials, and gradient-based optimization.

I build frameworks that make optimization problems differentiable end-to-end —
turning fiber orientations, patch positions, and geometry parameters into
learnable variables that a PyTorch optimizer can update directly through a
finite element solver. The goal is always the same: find structurally optimal
designs that can actually be manufactured.

**Background:** B.Tech. Mechanical Engineering (NIT Agartala) → hands-on CFRP
fabrication at DRDO → structural FEM at IIST → industrial manufacturing and
NDT at L&T Construction → computational composites research at Uni Augsburg.

---

### What I work on

- Gradient-based structural optimization via differentiable FEM (torch-FEM, PyTorch autograd)
- Fiber Patch Placement and Automated Fiber Placement path planning
- Multi-objective loss formulations with manufacturing constraints (ply continuity,
  thickness gradients, strength knock-downs at patch boundaries)
- Multiphysics simulation: EM-thermal-fluid coupling (COMSOL), structural FEA (ANSYS, Abaqus)
- CAD-to-CAE workflows: CATIA V5, SolidWorks

---

### Pinned repositories

**[Fiber_Patch_Placement](https://github.com/Tharun-arety/Fiber_Patch_Placement)**
Master's thesis implementation. Optimizes position and orientation of N CFRP fiber
patches on a plate with an elliptical hole using differentiable FEM in PyTorch.
Full pipeline: pygmsh geometry → FEM assembly → Adam optimizer → manufacturability
constraints. 1,921-element mesh, 500-iteration convergence, strength and thickness
gradient penalties.

**[Coil-shape-optimizer](https://github.com/Tharun-arety/Coil-shape-optimizer)**
Differentiable Fourier cross-section optimizer for stellarator coil winding packs.
PyTorch autograd through parametric geometry, curvature energy, and soft-min
clearance constraints.

---

### Open to

Simulation engineer, composites design engineer, or computational R&D roles in
aerospace, space, or advanced manufacturing — anywhere in Europe.

`Python` `PyTorch` `ANSYS` `Abaqus` `COMSOL` `CATIA V5` `SolidWorks` `torch-FEM`
