# 🚀 CPU Scheduling Simulator

A modern, interactive web application that visualizes and simulates various CPU scheduling algorithms in real-time. Experience the power of different scheduling algorithms through an intuitive and beautiful user interface.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-CPU%20Scheduler-blue?style=for-the-badge)](https://cpu-scheduler-vert.vercel.app/)

## ✨ Features

- **Multiple Scheduling Algorithms**
  - First Come First Serve (FCFS)
  - Shortest Job First (SJF)
  - Priority Scheduling
  - Round Robin (RR)

- **Interactive Visualization**
  - Real-time Gantt chart generation
  - Ready queue visualization
  - Step-by-step simulation control
  - Adjustable simulation speed
  - Dark/Light mode support

- **Detailed Metrics**
  - Completion Time
  - Turnaround Time
  - Waiting Time
  - CPU Utilization
  - Average metrics calculation

## 🎮 Live Demo

Check out the live demo: [CPU Scheduling Simulator](https://cpu-scheduler-vert.vercel.app/)

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- Vercel (Deployment)

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/swatiriya/cpu-scheduler.git
   ```

2. Navigate to the project directory:
   ```bash
   cd cpu-scheduler
   ```

3. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

## 📝 Usage

1. Select a scheduling algorithm from the available options
2. Add processes with their respective:
   - Arrival Time
   - Burst Time
   - Priority (for Priority algorithm)
3. Configure additional parameters:
   - Time Quantum (for Round Robin)
4. Click "Run Simulation" to start the visualization
5. Use the playback controls to:
   - Step through the simulation
   - Play/Pause the animation
   - Adjust simulation speed
   - Reset the visualization

## 📊 Metrics Explanation

- **Waiting Time (WT)** = Turnaround Time - Burst Time
- **Turnaround Time (TAT)** = Completion Time - Arrival Time
- **CPU Utilization** = (Total Burst Time / Completion Time of Last Process) × 100%
- **Average Waiting Time** = Sum of all Waiting Times / Number of Processes
- **Average Turnaround Time** = Sum of all Turnaround Times / Number of Processes

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- Swati Rai - Initial work
- [Aryan K](https://github.com/ba3a-g) - Guidance
