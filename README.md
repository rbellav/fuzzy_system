This project implements Particle Swarm Optimization (PSO) using the educational library softpy.
The implementation extends the MetaHeuristicsAlgorithm and FloatVectorCandidate classes provided by softpy to define a custom ParticleCandidate and ParticleSwarmOptimizer.

Features:
- PSO Implementation: particles with position, velocity, inertia and neighborhood-based updates.
- Fitness Function: Sphere function (minimization of the sum of squares).
- Visualization: fitness trend plotted across iterations.
- Softpy Integration: fully consistent with the library interface and design principles.

Structure
- ParticleCandidate: represents a single particle in the swarm.
- ParticleSwarmOptimizer: manages the swarm, updates velocities and positions, and tracks the best solutions.
- Notebook cells: setup, algorithm definition, run, and results visualization.



PSO.ipynb: Notebook with PSO implementation and execution.

softpy: a Python library for soft computing (@AndreaCampagner)

