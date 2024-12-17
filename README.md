# MATLAB Vehicle Dynamics and Control Simulations

This repository contains MATLAB scripts and live scripts (MLX files) for simulating and analyzing vehicle dynamics, control strategies, and path tracking models. These simulations serve as educational tools for understanding concepts in autonomous vehicle systems, control theory, and vehicle kinematics.

## **Files Overview**

1. **car_path_simulation_w_sigma_points.mlx**
   - **Purpose**: Simulates vehicle path tracking using sigma points.
   - **Key Features**:
     - Incorporates sigma points for uncertainty propagation.
     - Models vehicle path dynamics in a simulated environment.
   - **Applications**: State estimation and Kalman filtering approaches in vehicle systems.

2. **Dynamic_Bicycle_Model_Simulation_in_Vehicle_Dynamics.mlx**
   - **Purpose**: Implements a dynamic bicycle model to simulate vehicle dynamics.
   - **Key Features**:
     - Models lateral dynamics of a vehicle using the bicycle model approximation.
     - Analyzes yaw rate, slip angle, and stability.
   - **Applications**: Vehicle dynamics analysis and controller design.

3. **Pure_pursuit_vs_stanley_control_sim.mlx**
   - **Purpose**: Compares Pure Pursuit and Stanley controllers for vehicle path tracking.
   - **Key Features**:
     - Simulation of two common path-tracking algorithms.
     - Visual comparisons of performance metrics like tracking accuracy and trajectory adherence.
   - **Applications**: Control strategy selection for autonomous navigation.

4. **Vehicle_tracking_w_kinectic_model.mlx**
   - **Purpose**: Simulates vehicle path tracking using a kinematic model.
   - **Key Features**:
     - Implements a kinematic bicycle model for vehicle motion.
     - Tracks vehicle position and orientation over time.
   - **Applications**: Path planning and motion analysis for autonomous vehicles.

5. **Vehicle_Tracking_w_SMC.m**
   - **Purpose**: Simulates vehicle path tracking using Sliding Mode Control (SMC).
   - **Key Features**:
     - Tracks a sinusoidal reference path defined as $ y = A \cdot \sin(k \cdot x) + \cos(x) $.
     - Implements SMC control to minimize lateral error and stabilize vehicle trajectory.
     - Visualizes vehicle trajectory compared to the reference path.
   - **Parameters**:
     - Vehicle speed: $ v = 5 $ m/s.
     - SMC gain: $ K = 10 $, smoothing parameter: $ \theta = 0.1 $.
     - Sliding surface parameter: $ \lambda = 2 $.
     - Sinusoidal reference path: $ A = 2.5 $, $ k = 0.1 $.
   - **Applications**: Robust control design and advanced vehicle path tracking.

## **Requirements**

- MATLAB R2020b or later.
- Vehicle Dynamics Toolbox (recommended for detailed visualization).
- Basic understanding of control theory, kinematics, and vehicle dynamics.

## **Usage**

1. Clone or download the repository:
   ```bash
   git clone https://github.com/yourusername/vehicle-dynamics-simulations.git
   ```
2. Open MATLAB and navigate to the project folder.
3. Run the desired script (`.mlx` or `.m`) in MATLAB to visualize results and plots.
4. Modify parameters as needed to explore different scenarios.

## **Potential Applications**

- Academic projects on vehicle dynamics and control.
- Research in autonomous vehicle systems.
- Comparative analysis of control strategies for path tracking.

## **License**

This project is licensed under the MIT License. Feel free to use and modify the scripts.

## **Author**

Jonathan Mendez and Jose Baranda
