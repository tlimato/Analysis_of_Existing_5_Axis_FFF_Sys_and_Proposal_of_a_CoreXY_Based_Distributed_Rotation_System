# Kinematic Analysis of Existing 5-Axis FFF Architectures and Proposal of a CoreXY-Based Distributed-Rotation System

**Tyson Limato** · University of Wyoming, Department of Electrical Engineering and Computer Science, WY, United States of America · 2026

onventional fused filament fabrication (FFF) systems are typically limited to three translational degrees of freedom,
constraining deposition to planar layers and thereby introducing well-known limitations in support generation, surface finish, and
direction-dependent mechanical properties. Multi-axis extrusion systems have been developed to address these limitations by adding
rotational degrees of freedom, but existing 5-axis architectures exhibit important tradeoffs in kinematic complexity, structural stiffness,
calibration sensitivity, and reachable deposition orientation for larger build plate sizes. This paper first examines existing 5-axis FFF
system architectures from a robotics perspective, with particular emphasis on the previously proposed 3-axis gantry + 2-axis rotary-stage
configuration. Using a spatial kinematic framework, the analysis considers the relative nozzle–part pose, the role of coordinate-frame
assignment, and the implications of this head–table architecture for workspace, singularity behavior, and geometric error propagation. This
review highlights the strengths of rotary-stage systems, including mechanical simplicity and translational stiffness, while also identifying
limitations associated with stage-centered orientation, collision constraints, and amplified sensitivity to rotary misalignment. Motivated by
these observations, the paper then introduces a new 5-axis FFF architecture based on a Cartesian CoreXY platform with two distributed
rotary degrees of freedom: one rotational axis associated with the build-frame plane and a second rotational axis located at the toolhead.
In contrast to conventional rotary-stage systems that place both additional degrees of freedom on the workpiece, the proposed design
distributes orientation capability across the machine structure and deposition subsystem. This arrangement is intended to preserve the
accessibility and rigidity of a Cartesian mechanism while expanding local nozzle orientation control. A preliminary kinematic formulation
of the proposed system is presented to establish the basis for future analysis of workspace, singularities, calibration, and process-feasible
toolpath generation. More broadly, the work positions the proposed architecture as a candidate middle ground between conventional
Cartesian printers, head–table 5-axis systems, and fully articulated robotic additive manufacturing platforms.

**[Read the paper](https://tlimato.github.io/Analysis_of_Existing_5_Axis_FFF_Sys_and_Proposal_of_a_CoreXY_Based_Distributed_Rotation_System/)**
