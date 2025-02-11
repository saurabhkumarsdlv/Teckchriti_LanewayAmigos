# Line Follower Robot with PID Control & Node Detection

## About This Project

This project brings to life a **line-following robot** that uses **PID (Proportional-Integral-Derivative) control** for smooth and precise movement. It also includes **node detection**, allowing the robot to recognize intersections and make intelligent navigation decisions.

## What Makes It Special?

- **Smooth Movement with PID Control** – The robot dynamically adjusts its speed to follow the line accurately.
- **Node Detection** – Identifies intersections and makes smart decisions.
- **Arduino-Based** – Simple and easy to implement.
- **Real-Time Adjustments** – Reduces overshoot and improves performance.

## Project Files

- **line_follower_pid_overshot.ino** – Implements PID-based line following.
- **NODE_detection_stop.ino** – Handles node detection and stopping logic.
- **README.md** – This guide to help you get started.

## What You’ll Need

### Hardware:

- **Arduino Uno** (or a compatible board)
- **IR Sensor Array** (for detecting the line)
- **Motor Driver (L298N or similar)**
- **Motors & Wheels**
- **Battery Pack**

### Software:

- **Arduino IDE** (for coding and uploading)
- **PID Library** (if needed for tuning)

## How to Set It Up

1. **Clone the repository:**
   ```sh
   git clone https://github.com/saurabhkumarsdlv/Teckchriti_LanewayAmigos
   ```
2. **Open and upload the Arduino files:**
   - `line_follower_pid_overshot.ino` controls the line-following behavior.
   - `NODE_detection_stop.ino` enables node detection and stopping.
3. **Assemble your hardware** following the circuit diagram.
4. **Power it up!** Watch it follow the line and react at intersections.

## How It Works

### 1. **PID Control for Line Following**

The PID algorithm fine-tunes motor speed based on sensor input to keep the robot aligned. Adjusting **Kp, Ki, and Kd** helps optimize movement.

### 2. **Node Detection & Decision Making**

With IR sensors, the robot detects intersections and follows predefined rules to stop, turn, or continue.

## Fine-Tuning the PID Controller

- Increase **Kp** to make the robot more responsive.
- Adjust **Ki** to correct long-term drift.
- Modify **Kd** to reduce overshooting.

## What’s Next?

- **Adaptive PID control** for better response in different environments.
- **Bluetooth/Wi-Fi control** for remote operation.
- **Obstacle detection** to avoid crashes.

## Join the Project

This project is open-source! Feel free to fork, contribute, or suggest improvements.

## License

This project is released under the **MIT License**. See `LICENSE` for details.

---

Have questions or suggestions? Drop an issue on GitHub! 🚀
