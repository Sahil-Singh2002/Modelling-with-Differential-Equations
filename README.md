# Unsteady Flow Visualization

This repository contains Python code that demonstrates how to model and visualize the behavior of an unsteady flow described by the function `u = u0*x^ + kty^`.

## Code Description

The provided code performs the following tasks:

1. **Streamlines Generation:**

    The code generates streamlines for the given unsteady flow function. It calculates the streamlines passing through an arbitrary point `(x0, y0)` by solving the streamline equation derived from the given flow function. The streamlines are represented as straight lines.

2. **Streamline Sketching:**

    The code sketches the streamlines at different times `t = 0, 1, 2` using `matplotlib` plotting functions. Each streamline is plotted as a straight line on the plot.

3. **Parabolic Pathline:**

    The code calculates and visualizes the path followed by a fluid particle released from `(x0, y0)` at `t = 0`. The pathline is derived from the relationship between streamlines and pathlines for unsteady flows.

4. **Streakline Generation:**

    The code simulates the movement of dye injected into the fluid from the fixed location `(x0, y0)` for times `0 ≤ t ≤ 1`. It calculates the streakline at time `t = 1`, representing the shape of the dye streak formed over time.

## How to Use

1. Make sure you have Python and the required libraries (`numpy`, `matplotlib`) installed.
2. Copy and paste the provided code into a Python environment, such as a script or a Jupyter Notebook.
3. Run the code to visualize streamlines, pathlines, and streaklines for the given unsteady flow.

## Example Output

The code generates plots that showcase the streamlines passing through an arbitrary point, the path followed by a fluid particle, and the streakline formed by injected dye. The plot titles provide information about the specific visualization, and the plots help in understanding the dynamics of the unsteady flow.

## Contributions

Feel free to contribute by suggesting improvements, providing explanations, or enhancing the visualization techniques used in the code.

## License

This code is licensed under the [MIT License](LICENSE).
