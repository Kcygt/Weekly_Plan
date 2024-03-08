# Weekly Plan
##  Date : 15/02/2024 - 22/02/2024
#### 1 - Brushing Task in MUJOCO  
  - Generate Straight line trajectory
  - Implement Inverse Kinematics using Bruno Block Diagram and Ozan's code
    
#### 2 - Viva Question
  - Singularity , Null space
  - Orginality for the thesis  
  - Explain

#### 3 - Outline 28 months plam for thesis

##  Date : 29/02/2024 - 07/03/2024
#### 1 - Mujoco coriolis and gravity plot
  - qfrc_bias plot ( Kf and gravity )
    
#### 2 - MUJOCO gravity cancelation
  - 
#### 3 - Mark Spong book
  - Feedforward Cancelation
  - Impedance control
#### 4 - Double Pendulum Impedance Control
  - Impedance control in joint space
#### 5 - KinovaGen3 Debugging for cartesian space impedance control in MUJOCO

##  Date : 08/03/2024 - 15/03/2024
#### Closed loop impedance control
  - generate cartesian trajectory to map joint space (Trajectory Following)
  - Apply force to the End-Effector in the End-effector frame( Note: Null Space issue )
  - Comparison of Force Mapping (Mujoco vs PyKinova)
      - Apply Force and read the joint torques (Mujoco)
      - Get Torques using Jacobian and Force (PyKinova)
      - Comparison Mujoco and PyKinova  (Note: Robot doesn't move)
  - Integrate the FORCE CONTROL to closed loop impedance control

#### Carignan Admittance Control
  - convert frequency domain to time domain( Inverse Laplace )

#### Siciliano Closed Loop Impedance Control





  
#### Brushing Test In Mujoco
  - Add brush as a sphere (Rigid or Soft)
  - Draw a brush in Fusion 360
