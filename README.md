# Neuromorphic-LIF-Simulation

> **A Python implementation of the Leaky Integrate-and-Fire (LIF) neuron model for neuromorphic computing and spiking neural network research.**

---

## Table of Contents

- [Overview](#overview)
- [Objectives](#objectives)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Mathematical Model](#mathematical-model)
- [Expected Results](#expected-results)
- [Applications](#applications)
- [Future Improvements](#future-improvements)
- [License](#license)
- [Author](#author)

---

## Overview

The **Leaky Integrate-and-Fire (LIF)** neuron is one of the most widely used computational models in **Computational Neuroscience**, **Spiking Neural Networks (SNNs)**, and **Neuromorphic Computing**.

This project demonstrates the behavior of a biological neuron by simulating how it:

- Integrates input current
- Leaks membrane potential over time
- Generates spikes when a threshold is reached
- Resets after firing

The implementation is written in **Python** using **NumPy** and **Matplotlib**. It is designed to help students and enthusiasts understand the behavior of the LIF neuron model through simulation and visualization.

---

## Objectives

- Simulate the membrane potential dynamics of an LIF neuron.
- Visualize neuron firing behavior.
- Generate spike trains.
- Study the influence of input current on neuron activity.
- Provide an educational implementation of the LIF neuron model.
- Build a foundation for future Spiking Neural Network projects.

---

## Features

- Leaky Integrate-and-Fire neuron simulation
- Python implementation
- Membrane potential visualization
- Spike train generation
- Adjustable neuron parameters
- Firing rate analysis
- Well-documented notebook
- Google Colab compatible
- Modular project structure

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| Python 3 | Programming language |
| NumPy | Numerical computation |
| Matplotlib | Plotting and visualization |
| Jupyter Notebook | Interactive simulation |
| Git | Version control |
| GitHub | Repository hosting |

---

## Project Structure

```text
Neuromorphic-LIF-Simulation/
│
├── docs/                     # Documentation
├── examples/                 # Example programs
├── images/                   # README images and diagrams
├── notebooks/                # Jupyter notebooks
│   └── lif_simulation.ipynb
├── results/                  # Generated simulation figures
├── src/                      # Python source files
├── tests/                    # Test scripts
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## Prerequisites

Before running this project, install:

- Python 3.10 or later
- Git
- Jupyter Notebook or JupyterLab

Verify your Python installation:

```bash
python --version
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/akshajsaigandi-ux/Neuromorphic-LIF-Simulation.git
```

Navigate to the project directory:

```bash
cd Neuromorphic-LIF-Simulation
```

Install the required Python libraries:

```bash
pip install -r requirements.txt
```

---

## Usage

1. Open `notebooks/lif_simulation.ipynb`.
2. Run all notebook cells sequentially.
3. Observe the membrane potential plot.
4. Observe spike generation.
5. Modify neuron parameters and input current to study different firing behaviors.

---

## Mathematical Model

The membrane potential evolves according to the discrete-time LIF equation:

```text
V(t + Δt) = V(t) + (Δt / τ) [-(V(t) - Vrest) + R · I(t)]
```

where:

- **V** = Membrane potential
- **τ** = Membrane time constant
- **R** = Membrane resistance
- **I** = Input current
- **Vrest** = Resting membrane potential

Whenever

```text
V ≥ Vthreshold
```

the neuron generates a spike and the membrane potential is reset to **Vreset**.

---

## Expected Results

Running the notebook will generate:

- Membrane potential vs. time
- Spike train
- Neuron firing behavior
- Response under different input currents

> Simulation figures will be included after the implementation is completed.

---

## Applications

- Neuromorphic Computing
- Spiking Neural Networks (SNNs)
- Computational Neuroscience
- Brain-inspired Artificial Intelligence
- Academic teaching and demonstrations
- Neuromorphic hardware research

---

## Future Improvements

- Multiple interconnected neurons
- Adaptive LIF neuron model
- Implement the Izhikevich neuron model
- Implement the Hodgkin–Huxley neuron model
- Small Spiking Neural Network implementation

---



## License

This project is licensed under the MIT License.

---

## Author

**Akshaj Gandi**

B.Tech – Electronics and Communication Engineering

GitHub: [akshajsaigandi-ux](https://github.com/akshajsaigandi-ux)