# 🚦 Adaptive Traffic Light RL
A simple reinforcement learning project for optimizing a traffic light at a single intersection using SUMO and Deep Q-Networks (DQN).

**This project was built to finish the MSIB program at AI Mastery in Orbit Future Academy and ended up being the second runner-up for best project. ✨✨**

<div align="center">
  <img src="https://github.com/user-attachments/assets/d05697e8-04cc-41c8-8c22-0a2dd6995681" alt="Demo" width="400"/>
</div>

# ✨ Features
- Trains a DQN agent to control traffic lights
- Traffic simulation via [SUMO](https://www.eclipse.org/sumo/)
- Easy configuration with `.ini` files
- Auto-generates performance plots


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
