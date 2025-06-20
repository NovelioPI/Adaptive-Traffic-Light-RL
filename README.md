

# 🚦 Adaptive Traffic Light RL
A simple reinforcement learning project for optimizing a traffic light at a single intersection using SUMO and Deep Q-Networks (DQN).

<div align="center">
  <img src="https://github.com/user-attachments/assets/d715ec92-4d2d-4d9d-b009-fcbbdf53f3c1" alt="Demo"/>
</div>

**This project was built to finish the MSIB program at AI Mastery in Orbit Future Academy and ended up being the second runner-up for best project. ✨✨**

<div align="center">
  <img src="https://github.com/user-attachments/assets/d05697e8-04cc-41c8-8c22-0a2dd6995681" alt="Demo" width="400"/>
</div>

# ✨ Features
- Trains a DQN agent to control traffic lights
- Traffic simulation via [SUMO](https://www.eclipse.org/sumo/)
- Easy configuration with `.ini` files
- Auto-generates performance plots

![image](https://github.com/user-attachments/assets/807ec4a9-f38f-4d26-813e-371aef496cb5)
<div align="center">
  <img src="https://github.com/user-attachments/assets/b0122982-7726-43b5-a156-6bfa3829e32f" alt="Demo" width="600"/>
</div>

# 🚀 Quick Start
### 1. Prerequisites
  - Python 3.7+
  - SUMO (Simulated Urban Mobility) – installation instructions [here](https://sumo.dlr.de/docs/Downloads.php)
  - Python dependencies:
    ```bash
    pip install numpy tensorflow matplotlib
    ```
### 2. SUMO Setup
  - Download & install SUMO
  - Set the `SUMO_HOME` environment variable
  - Add SUMO’s `tools` folder to your `PYTHONPATH`
### 3. Clone This Repo
  ```bash
  git clone https://github.com/NovelioPI/Adaptive-Traffic-Light-RL.git
  cd Adaptive-Traffic-Light-RL
  ```


# 🏃‍♂️ Usage
### Trained the Agent
  1. (Optional) Edit `training_settings.ini` for your own setup
  2. Run:
     ```bash
     python training_main.py
     ```
     - Progress and results in console
     - Trained models & plots saved to `models/`
### Test the Trained Agent
  1. Set the model in `testing_settings.ini`
  2. Run:
     ```bash
     python testing_main.py
     ```
     - Test results/plots in `models/<model_x>/test/`


# 📁 Project Structure
- `intersection/` — SUMO network & config files
- `training_main.py`, testing_main.py — main scripts
- `*.ini` — configuration files
- `models/` — saved models & results
