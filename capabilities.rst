0. Package Capabilities
This package implements the methods of the paper:

JC Schindler, A Aguirre. Algorithms for the explicit computation of Penrose diagrams. Class Quantum Grav 35 105019 (2018). doi:10.1088/1361-6382/aabce2. [arxiv:1802.02263.]

Allowed metrics
It allows one to plot causal diagrams for 3+1 dimensional spacetimes in two classes:

Any metric of the form
ds^2 = -f(r) \, dt^2 + f(r)^{-1} \, dr^2 + r^2 \, d\Omega^2.
Metrics that are piecewise-of the above form, glued along radial null shell junctions. Arbitrarily many shells and piecewise regions can be included to approximate smooth dynamical evolution.
Nature of the diagrams
The diagrams are constructed by exactly constructing coordinate transformations from a defining coordinate system (e.g. Schwarzchild (t,r,\theta,\phi) or Eddington-Finklestein (u,v,\theta,\phi) coordinates) into a system of "diagram" coordinates (U,V,\theta,\phi) with the following properties:

The diagram is simultaneously a Penrose diagram and an exact coordinate diagram.

The coordinates (U,V) cover the entire spacetime in a global compact double-null coordinate patch, so causal cones are bounded by lines of unit slope, without losing conformal information.
Thus internal features such as matter content, observers, and arbitrary spherically symmetric functions, can be unambiguously plotted.
