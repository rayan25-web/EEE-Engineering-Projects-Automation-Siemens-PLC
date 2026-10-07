# Engineering & Industrial Automation Projects

This repository contains my engineering projects, practical implementations, technical experiments, and project documentation developed during my Electrical and Electronics Engineering studies.

My primary area of focus is **PLC programming and industrial automation**, with hands-on work involving Siemens PLC hardware, TIA Portal, Ladder Logic, HMI, SCADA, sensors, actuators, motor control, and industrial control systems.

The repository also includes projects in battery health monitoring, impedance analysis, machine learning, MATLAB/Simulink, embedded systems, electrical and control engineering, AutoCAD, and SolidWorks CAD.

# Table of Contents

| No. | Section |
|---|---|
| 1 | Primary Focus |
| 1.1 | PLC and Industrial Automation |
| 1.1.1 | Siemens Software |
| 1.1.2 | Siemens Hardware |
| 1.1.3 | Industrial Automation |
| 2 | Projects |
| 2.1 | Ongoing Final-Year Project |
| 2.1.1 | PLC-Based Automated Storage and Retrieval System |
| 3 | Other Engineering Projects |
| 3.1 | Advance Battery Health Monitoring and Prognostics Research |
| 3.2 | Rainfall Prediction Using Machine Learning |
| 4 | Electrical and Control Engineering |
| 5 | MATLAB and Simulink |
| 6 | Embedded Systems and Electronics |
| 7 | Engineering Design and CAD |
| 7.1 | AutoCAD |
| 7.2 | SolidWorks |
| 8 | Technical Skills |

# 1. Primary Focus

## 1.1 PLC and Industrial Automation

My main technical focus is industrial automation and PLC-based control systems.

### 1.1.1 Siemens Software

- Siemens TIA Portal V20
- Siemens PLCSIM V20
- Siemens WinCC Advanced
- PLC hardware configuration
- Ladder Logic programming
- HMI development
- SCADA development
- PLC simulation

### 1.1.2 Siemens Hardware

- Siemens S7-1200 PLC
- CPU 1214C DC/DC/DC
- Digital Inputs and Outputs
- 24V DC control systems
- Push buttons
- Proximity sensors
- Limit switches
- Relays
- Actuators
- Motor control interfaces

### 1.1.3 Industrial Automation

- PLC Programming
- Ladder Logic
- Industrial Control Systems
- HMI and SCADA
- Sensors and Feedback Systems
- Actuators
- Motor Control
- Variable Frequency Drives
- Digital I/O
- Electrical Control Circuits
- Automation Simulation
- Hardware Integration
- System Testing and Troubleshooting

# 2. Projects

The actual project files, source code, PLC programs, documentation, and supporting material are organized separately under the `Projects` directory.

## 2.1 Ongoing Final-Year Project

### 2.1.1 PLC-Based Automated Storage and Retrieval System

**Status: Ongoing**

A miniature PLC-based Automated Storage and Retrieval System developed as my final-year engineering project.

The system uses a Siemens S7-1200 PLC for automated movement, position detection, storage, and retrieval operations.

#### Technologies and Hardware

- Siemens S7-1200 PLC
- CPU 1214C DC/DC/DC
- Siemens TIA Portal V20
- Ladder Logic
- HMI
- Proximity Sensors
- Limit Switches
- Motors and Motor Drives
- Actuator
- 24V DC Control System
- Digital I/O
- Position Sensing

#### Development Areas

- PLC program development
- Sensor integration
- Actuator control
- X-axis and Y-axis movement
- Position detection
- Storage and retrieval sequence control
- Motor and drive interfacing
- HMI integration
- Electrical wiring
- Hardware testing
- Troubleshooting

# 3. Other Engineering Projects

## 3.1 Advance Battery Health Monitoring and Prognostics Research

**Status: Completed Mini-Project**

A simulation-based battery health monitoring project focused on analysing battery behaviour using an equivalent electrical circuit and impedance characteristics.

The battery is represented using an RC-based equivalent circuit in LTspice. Different internal resistance and capacitance values are used to represent healthy, medium, weak, and faulty battery conditions.

An AC frequency sweep from **1 kHz to 50 kHz** is performed in LTspice. The resulting data is exported as CSV files and analysed using MATLAB Online for comparison and visualization.

### Technologies

- LTspice
- MATLAB Online
- Battery Equivalent Circuit Modelling
- RC Circuit Modelling
- AC Frequency Analysis
- Impedance Analysis
- CSV Data Analysis
- Battery State-of-Health Analysis

The current project is simulation-based and provides a foundation for future hardware implementation using sensors, embedded controllers, and real-time data acquisition.

## 3.2 Rainfall Prediction Using Machine Learning

**Status: Completed Course Project**

A machine-learning project focused on rainfall prediction for **Bandar Seri Begawan, Brunei**, using historical weather data from the NASA/POWER dataset.

The project involved data preprocessing, feature engineering, chronological data splitting, feature ranking, PCA, machine-learning model development, model evaluation, and rainfall prediction.

### Dataset and Processing

- NASA/POWER weather data
- Historical rainfall data
- Data preprocessing
- Missing-value handling
- Feature engineering
- StandardScaler
- Pearson correlation analysis
- Principal Component Analysis

The target variable was daily rainfall (`PRECTOTCORR`). The dataset was divided into a 1995–2020 development period and an unseen 2021–2025 testing period.

### Machine Learning Models

- Decision Tree
- Random Forest
- XGBoost
- Linear Regression
- Ridge Regression
- Gradient Boosting
- MLP Regressor

XGBoost was selected as the project's best-performing model and was evaluated on the unseen 2021–2025 dataset.

### Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- PCA
- StandardScaler
- Matplotlib
- Seaborn
- Pickle

The final model and scaler were serialized into `.pkl` files, and a predictor interface was developed to accept meteorological parameters and generate rainfall predictions.

# 4. Electrical and Control Engineering

Additional engineering work covers areas related to Electrical and Electronics Engineering, including:

- Electrical Systems
- Electrical Machines
- Control Systems
- Electrical Control Circuits
- Power Electronics
- Sensors and Instrumentation
- Motor Control
- Embedded Systems
- Microcontrollers
- Engineering Simulation

# 5. MATLAB and Simulink

MATLAB and Simulink are used for engineering modelling, simulation, data analysis, and system studies.

Areas of use include:

- Mathematical Modelling
- System Simulation
- Control-System Modelling
- Electrical System Simulation
- Battery Analysis
- Data Analysis
- Engineering Calculations
- Experimental Analysis

# 6. Embedded Systems and Electronics

Technical work involving:

- Microcontrollers
- Sensors
- Digital and Analog Systems
- Electronic Circuits
- Motor Interfaces
- Embedded Control
- Hardware Interfacing

# 7. Engineering Design and CAD

Engineering design work includes both electrical and mechanical CAD.

## 7.1 AutoCAD

- Electrical Drawings
- Technical Diagrams
- Engineering Layouts
- System Documentation
- Project Drawings

## 7.2 SolidWorks

- 3D Mechanical Modelling
- Component Design
- Mechanical Assemblies
- Engineering Parts
- Product and System Modelling

# 8. Technical Skills

| Area | Technologies and Tools |
|---|---|
| PLC | Siemens S7-1200 |
| PLC Programming | Ladder Logic, TIA Portal |
| HMI / SCADA | Siemens WinCC Advanced |
| PLC Simulation | Siemens PLCSIM |
| Industrial Automation | Sensors, Actuators, Motors, Drives |
| Motor Control | Motor Drivers, VFDs |
| Engineering Simulation | MATLAB, Simulink |
| Electrical CAD | AutoCAD |
| Mechanical CAD | SolidWorks |
| Battery Analysis | LTspice, MATLAB, Impedance Analysis |
| Machine Learning | Python, Scikit-learn, XGBoost |
| Data Analysis | Pandas, NumPy, PCA |
| Embedded Systems | Microcontrollers, Sensors, Hardware Interfacing |
