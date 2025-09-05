# PRR-Manipulator-Kinematics-Simulators
Interactive Python-based simulators for the PRR (Prismatic–Revolute–Revolute) manipulator, featuring forward kinematics with slider control, forward kinematics driven by inverse kinematics solutions, and an inverse kinematics simulator.




This repository provides interactive simulators for the PRR (Prismatic–Revolute–Revolute) Manipulator, implemented in Python with `matplotlib`.  
It includes both forward and inverse kinematics tools designed for learning, visualization, and research in robotics.



🚀 Features
- Forward Kinematics (Slider-Controlled)
  Adjust the prismatic displacement and joint angles using sliders to visualize the manipulator configuration.

![image alt](https://github.com/aAfeworki/PRR-Manipulator-Kinematics-Simulators/blob/main/FK_Simulator_for_PRR_manipulator_with_Slider.png?raw=true)

- Forward Kinematics (IK-Driven) 
  Use joint angles and link length generated from the inverse kinematics solver to control the manipulator.

![image alt](https://github.com/aAfeworki/PRR-Manipulator-Kinematics-Simulators/blob/main/FK_Simulator_for_PRR_Industrial_Robot.png?raw=true)

- Inverse Kinematics Simulator 
  Enter the equation of a curve on the User Interface to generate joint angles that position the manipulator’s end-effector.

![image alt](https://github.com/aAfeworki/PRR-Manipulator-Kinematics-Simulators/blob/main/IK_Generator_for_PRR_manipulator_with_Simulator.png?raw=true)

![image alt](https://github.com/aAfeworki/PRR-Manipulator-Kinematics-Simulators/blob/main/IK_Generator_for_PRR_manipulator_with_Simulator%20User%20Interface.png?raw=true)

📂 Project Structure

PRR-Manipulator-Kinematics-Simulators
     
      FK_Simulator_for_PRR_manipulator_with_Slider.py
      FK_Simulator_for_PRR_Industrial_Robot.py
      IK_Generator_for_PRR_manipulator_with_Simulator.py
      README.md



🛠 Requirements
- `Python 3.12`
- `numpy`
- `matplotlib`
- `tkinter`



▶️ Usage
Run any simulator with:
      
      FK_Simulator_for_PRR_manipulator_with_Slider.py

      FK_Simulator_for_PRR_Industrial_Robot.py

      IK_Generator_for_PRR_manipulator_with_Simulator.py


🎯 Applications

      Educational tool for understanding PRR manipulator kinematics.


      Useful for robotics students, educators, and researchers.


      Foundation for advanced extensions: dynamics, control, and trajectory planning.



📜 License
This project is licensed under the MIT License.

👨‍💻 Developed by Afework Alemu
