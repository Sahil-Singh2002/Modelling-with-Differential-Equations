# Unsteady Flow, Vector Field, and Plotting direction fields

## Unsteady_Flow Project

This project focuses on visualizing unsteady flow phenomena using Python libraries such as `NumPy`, `Matplotlib`, and `SciPy`. It includes the following components:

$$\textbf{Streamline Equation}$$

The provided code performs the following tasks:

The first part displays streamlines for a given velocity field defined by the functions `velocity_components(x,y)` using the `ax.streamplot()` function.

$$\textbf{Sketch Streamlines for Different Times}$$

The second part illustrates how streamlines evolve over time by plotting them for various time instances. This is achieved by adjusting the coordinates based on time and recalculating the velocity components.

$$\textbf{Pathlines (Parabolic Paths)}$$

The third part plots pathlines that represent trajectories of fluid particles over time. The pathline equations are calculated using initial positions and the velocity field functions.

$$\textbf{Streakline at t = 1}$$

The final part visualizes a streakline at a specific time *t = 1* along with the corresponding pathline and the release point. It uses the velocity field and adjusts positions based on time.

## Vector_Field Project

This project deals with visualizing phase portraits and dynamics of a 2D dynamical system using Python libraries such as `NumPy`, `Matplotlib`, `SciPy` and `SymPy`. The main components are:

$$\textbf{Phase Portrait}$$

This section generates a phase portrait by plotting vector arrows based on the given dynamical system `system(u, v)` and calculates the normalized direction vectors for visualization.

Equilibrium Points
The project identifies equilibrium points by solving the differential equations `du_dt = 0` and `dv_dt = 0` symbolically using `SymPy`. It then plots these equilibrium points on the phase portrait.

$$\textbf{Dynamics in Time}$$

This part computes the temporal dynamics of the system by solving the ODEs numerically using the `odeint()` function and visualizes how the variables `u` and `v` change over time.

## Plotting_direction_fields Project

This project is about plotting direction fields and solution curves for a given first-order ordinary differential equation (ODE). It uses libraries such as `Matplotlib`, `NumPy` and `SciPy`. The main components are:

$$\textbf{ Direction Field and Solution Curves}$$

This section generates a direction field for the ODE and overlays solution curves on it. Solution curves are obtained by numerically solving the ODE for different initial conditions and plotting them over a specified time range.

$$\textbf{Symbolic Solution}$$

Lastly, the symbolic solution of the differential equation is obtained using SymPy's `dsolve()` function. The solution is printed for reference.

## Conclusion

In these three projects: Unsteady_Flow, Vector_Field, and Plotting_direction_fields. We have explored diverse aspects of dynamical systems and fluid flow phenomena using Python. Each project leverages a combination of libraries like `NumPy`, `Matplotlib` and `SymPy` to provide insightful visualizations and analyses.

The *Unsteady_Flow* project delves into unsteady fluid flow behaviour. It covers streamlines, pathlines, and streaklines, showcasing how fluid particles move through time. By using the power of numerical computation and visualization, we gain a deeper understanding of fluid dynamics.

The *Vector_Field* project concentrates on the study of phase portraits and temporal dynamics. It illuminates equilibrium points, direction fields, and solution curves, enabling us to visualize the behaviour of a dynamic system and how it evolves over time.

The *Plotting_direction_fields* project demonstrates the process of creating direction fields and overlaying solution curves for a first-order ordinary differential equation. It's a powerful approach to understanding the behaviour of various real-world systems governed by differential equations.

These projects serve as valuable resources for learning, experimentation, and implementation in the fields of fluid dynamics, physics, mathematics, and engineering. By combining mathematical concepts with programming and visualization, we gain insights that can aid in problem-solving and decision-making.



