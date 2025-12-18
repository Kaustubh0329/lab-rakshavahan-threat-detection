# RakshaVahan Virtual Lab - Implementation Guide

## Project Overview

RakshaVahan is a complete Virtual Lab solution for on-vehicle threat detection and sensor fusion. This implementation guide provides the structure, technical specifications, and deployment information for the lab.

## Quick Summary

**Project Created:** ✅ Complete V-Lab Framework
- Repository: `lab-rakshavahan-threat-detection`
- Lab Configuration: `lab-descriptor.json` 
- Documentation: Complete README with 8 experiments
- Status: Ready for experiment implementation

## 8 Core Experiments

### 1. Power Supply and Protection for On-Vehicle Electronics
**Folder:** `exp-power-protection/`
- Learn automotive power distribution
- Protection circuit design
- Voltage regulation techniques
- Proteus/Multisim circuit models included

### 2. Radar Sensor Interface and Signal Processing
**Folder:** `exp-radar-interface/`
- Radar principles and signal acquisition
- Doppler processing algorithms
- Range-Doppler computations
- MATLAB/Simulink models for signal processing

### 3. Camera Sensing and AI-Based Trigger Generation  
**Folder:** `exp-camera-sensing/`
- Image processing pipelines
- Threat classification using CNN
- Trigger generation logic
- Real-time performance analysis

### 4. LiDAR Range Measurement and Cross-Check
**Folder:** `exp-lidar-range/`
- 3D point cloud generation
- Range measurement techniques
- Multi-sensor validation
- Error handling strategies

### 5. Multi-Sensor Fusion and Threat Score Computation
**Folder:** `exp-sensor-fusion/`
- Kalman filtering fundamentals
- Multi-sensor data fusion
- Threat scoring algorithms
- Performance metrics

### 6. Embedded Controller State Machine
**Folder:** `exp-state-machine/`
- Real-time control logic
- State design patterns
- Embedded system constraints
- C/MATLAB implementation

### 7. Vehicle Interface via CAN and Driver Alerts
**Folder:** `exp-vehicle-can/`
- CAN protocol implementation
- Message scheduling
- Alert system design
- Safety compliance

### 8. End-to-End Virtual Mission Scenario
**Folder:** `exp-mission-scenario/`
- Complete system integration
- Realistic threat scenarios
- Performance evaluation
- End-to-end testing

## Technical Specifications

### Required Software
- MATLAB R2023a or later
- Simulink with Automated Driving Toolbox
- Proteus 8+ or Multisim for circuit simulation
- Git and GitHub account

### Supported Platforms
- Windows 10/11
- Linux (Ubuntu 20.04+)
- macOS (Big Sur+)

### Simulation Capabilities
- Real-time simulation: Up to 100 ms latency
- 3D visualization for sensor data
- Interactive parameter tuning
- Performance benchmarking

## File Structure

```
lab-rakshavahan-threat-detection/
├── README.md                           # Main documentation
├── IMPLEMENTATION_GUIDE.md             # This file
├── lab-descriptor.json                 # Lab metadata & experiments
├── .github/
│   └── workflows/                      # CI/CD automation
├── docs/
│   ├── theory/                         # Theory documentation for each experiment
│   ├── procedures/                     # Step-by-step procedures
│   └── diagrams/                       # System architecture diagrams
├── simulations/
│   ├── power-protection.slx            # Power system Simulink model
│   ├── radar-processing.slx            # Radar signal processing
│   ├── sensor-fusion.slx               # Multi-sensor fusion
│   └── mission-scenario.slx            # End-to-end scenario
├── circuits/
│   ├── power-protection.pdsproj        # Proteus design
│   ├── vehicle-interface.pdsproj       # CAN interface
│   └── signal-conditioning.pdsproj     # Sensor conditioning
├── code/
│   ├── matlab/                         # MATLAB functions
│   ├── c_embedded/                     # Embedded C code
│   └── python/                         # Support scripts
└── downloads/
    ├── lab-manual.pdf                  # Complete lab manual
    ├── student-guides/                 # Student worksheets
    └── resources/                      # Reference materials
```

## Experiment Access Flow

1. **Home Page**: Lab introduction and objectives
2. **Experiment List**: Browse all 8 experiments organized by category
3. **Theory Tab**: Understand concepts and background
4. **Procedure Tab**: Step-by-step simulation guide
5. **Simulator**: Run MATLAB/Simulink models
6. **Observations**: Record measurements and results
7. **Quiz**: Verify understanding
8. **Downloads**: Access models and resources

## Key Features

✅ **Phase 3 V-Lab Compliant**
- Follows IIT Virtual Labs standards
- Structured experiment format
- Automatic GitHub Actions deployment

✅ **Interactive Simulations**
- Real-time parameter adjustment
- Live visualization
- Data export capabilities

✅ **Comprehensive Documentation**
- Theory sections for each topic
- Practical procedures
- Expected results
- Common troubleshooting

✅ **Assessment Tools**
- Self-evaluation quizzes
- Performance metrics
- Assignment templates

## Deployment Pipeline

```
Local Development
        ↓
   Git Commit
        ↓
  GitHub Push
        ↓
GitHub Actions (CI/CD)
        ↓
Automatic Testing
        ↓
GitHub Pages Deployment
        ↓
Live Virtual Lab
```

## How to Use This Lab

### For Students
1. Navigate to experiment of interest
2. Read theory section
3. Follow procedure step-by-step
4. Run simulation and collect data
5. Document observations
6. Complete quiz
7. Download resources

### For Instructors
1. Customize experiments for your course
2. Set up assignments and deadlines
3. Monitor student progress
4. Grade assignments
5. Provide feedback

### For Developers
1. Clone the GitHub repository
2. Set up MATLAB environment
3. Modify Simulink models
4. Test locally
5. Push to GitHub
6. Automated deployment to VLabs

## Getting Started

```bash
# Clone the repository
git clone https://github.com/Kaustubh0329/lab-rakshavahan-threat-detection.git
cd lab-rakshavahan-threat-detection

# Open README for detailed instructions
cat README.md

# Access experiments
# Navigate to lab-descriptor.json to see experiment definitions

# Run simulations
matlab -r "open('simulations/power-protection.slx')"
```

## Support Resources

- **Documentation**: `/docs` folder
- **Example Models**: `/simulations` folder  
- **Circuit Files**: `/circuits` folder
- **Code Samples**: `/code` folder

## Contact & Support

- **Lab Issues**: Create GitHub Issue
- **Email**: rakshavahan.lab@gmail.com
- **VLabs Support**: support@vlab.co.in

## License

Creative Commons Attribution 4.0 International (CC BY 4.0)
For educational and research use only.

---

**Version**: 1.0.0
**Last Updated**: December 2025
**Maintained By**: Kaustubh (RakshaVahan Project)
