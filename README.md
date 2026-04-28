# Draw Digits with Turtles 🐢🐢🐢🐢✍️

### Concept: Swarm Coordination and Collaborative Trajectory Generation

This project implements a multi-agent system where a group of robots works together to visualize complex numbers. The primary showcase is the synchronized drawing of the specific digit sequence **"205"** using four coordinated TurtleBot3 Burger robots in a simulated environment.

---

### 🌐 Key Multi-Agent Features:
* **Multi-Robot Synchronization:** Developed a strategy to coordinate four TurtleBot3 Burger robots to draw sequential numbers without colliding.
* **Algorithm for Digit Mapping:** Implemented precise trajectory generation to ensure the collective output accurately visualizes **"205"**.
* **Precise Control:** Utilized P-controllers for each robot to maintain formation and timing accuracy.

---

### 🛠 Technical Deep Dive:
* **Kinematics:** Individual differential drive controllers.
* **Coordination Layer:** High-level algorithm to manage the "flow" and separation of the four robots.
* **Environment:** Tested using the ROS/TurtleSim/Gazebo environments to stresstest agent coordination.
