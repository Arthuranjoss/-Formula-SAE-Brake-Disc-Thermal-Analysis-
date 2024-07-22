
## Formula-SAE-Brake-Disc-Thermal-Analysis

This repository provides MATLAB code for performing thermal analysis of brake discs used in Formula SAE race cars. It includes scripts for both lumped parameter and finite element models, allowing you to choose the approach that best suits your needs and computational resources.

### Features

* **Lumped Parameter Model:**
    * Calculates temperature distribution in key sections (disc core, air gap, pads).
    * Efficient for quick analysis and parameter sweeps.
* **Finite Element Model (FEM):**
    * Provides a more detailed temperature distribution across the entire disc.
    * Suitable for complex geometries or when high accuracy is essential.
* **Customizable:**
    * Modify material properties, braking force, and vehicle speed data based on your specific design and competition requirements.
* **Visualization:**
    * Generates plots to visualize the temperature distribution on the brake disc.
* **Documentation:**
    * Includes clear comments and this README file explaining the code structure, usage instructions, and references.

### Target Users

* Formula SAE teams and engineers interested in optimizing brake disc performance and preventing thermal fatigue.
* Students and researchers working on thermal analysis of automotive components.

### Dependencies

* This repository requires MATLAB. 
* Depending on the chosen model complexity, additional toolboxes might be necessary (e.g., `Thermal`, `HeatTransfer`).

### Getting Started

1. Clone this repository to your local machine.
2. Install any required MATLAB toolboxes.
3. Open the main script (e.g., `formula_sae_brake_thermal_analysis.m`).
4. Update the script parameters with your specific design data (refer to comments within the script).
5. Run the script to perform the thermal analysis.
6. The script will generate plots visualizing the temperature distribution.

### Contributing

We welcome contributions to improve this repository! Feel free to submit pull requests for:

* Bug fixes
* Code enhancements
* Additional features

Please ensure your code adheres to the existing code style and includes clear documentation.

### License

This repository is licensed under the [insert your preferred open-source license here] (e.g., MIT License). See the `LICENSE` file for details.
