# SPaMD
Scalable Parallel Molecular Dynamics Studio

Updated in Ver.1.3: Add several high-throughput implementations for Simulation module, e.g. AELAS, ADAIS, ASURF, AEDOS, ABAND; Add the analyses modules for VASP results, e.g. VASPDV for density of state (DOS) and band structure, VASPVV for charge density difference and electron localization function; fix the bugs for modelling, Simulation and visulization modules. 

Updated in Ver.1.2: Add Surfkit for Modelling module; Add support for GUI to VASP for automatically including more functionals by other developer or users; fix the bugs for Simulation and visualization module. 

Updated in Ver.1.1: Add Cryskit for Modelling module; fix the bugs for Simulation module, support submit task to current terminal. 

SPaMD, which includes the following features: 1) a user-friendly GUI for operation and visualization; 2) a robust rendering system designed for several million atoms or more, supporting color-coding, camera control, atom pickup, and anti-aliasing rendering; 3) a modular modeling system that supports the direct construction of nanoparticles, nanowires, nanosheets, polycrystals with different axial ratios, bilayers and multilayers, as well as dislocation and crack insertion; 4) a custom modeling system called atomkit, which provides geometrical selection (e.g., slice, cubic, sphere, prism, polyhedron), multilevel region adjustment (e.g., move, deform, rotate) with boolean selection (e.g., and, or, not), and basic operations (e.g., add, delete, random displace, duplicate, deform); 5) workflow templates that can be defined with preconfigured operations for quick access and used to perform the same operations with the same settings in different simulations; 6) adaptive real-time analysis that supports the topological methods of CNA, BAA, CSP, CNP, OIM, and LCO that were previously implemented in our AACSD code; 7) a post-analysis system that is packaged for vector and tensor analysis methods, i.e., DVA, STA, DDA, SVA, IDA, and NTA, which were recently released in our AADIS code; 8) an automatic task management system for high-throughput simulation, e.g., dynamic tension/compression, shock loading, and fracture toughness calculation via the internal SPaMD Simulator or other external simulators e.g., LAMMPS; and 9) an internal robust SPaMD simulator that supports molecular dynamics simulations through various ensembles such as NVE, NVT, and NPT, as well as molecular statics methods via CG and FIRE.
