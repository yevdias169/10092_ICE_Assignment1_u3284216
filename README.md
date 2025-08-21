# Railway Crossing Gate Control System

## Project Overview
A logic-based safety system designed to control the operation of gates at a railway level crossing. This system ensures gates are lowered when a train is approaching and only raised when it is completely safe.

## Assignment Details
- **Course**: Introduction to Computer Engineering (8223/10096)
- **Assignment**: Assignment 1 - The Engineering Method
- **Institution**: University of Canberra

## Repository Structure
```
├── Step1_Analysis/          # Problem analysis and requirements
├── Step2_Alternatives/      # Solution alternatives and research
├── Step3_Evaluation/        # Solution evaluation and decision
├── Step4_Implementation/    # Sequence of tasks and flowchart
├── Step5_Testing/          # Test cases and results
├── Documentation/          # Additional project documentation
└── README.md              # This file
```

## System Components
**Inputs:**
- Arrival sensor (train detection)
- Departure sensor (train departure)
- Gate position sensors (closed/open verification)

**Outputs:**
- Gate control (open/close)
- Warning bells
- LED warning lights
- Crew notifications
- System status indicators

## Implementation Approach
The system uses a straightforward logic-based approach with:
- Memory bits for state tracking (%M0.0, %M0.1)
- Sequential task execution
- Safety verification at each step
- Fail-safe notifications for system anomalies

## Key Features
- ✅ Train arrival and departure detection
- ✅ Automated gate control
- ✅ Safety verification systems
- ✅ Crew notification for failures
- ✅ Fail-safe operation principles

## Testing
The system includes comprehensive test cases covering:
- Normal operation scenarios
- Edge cases and failure conditions
- Safety verification checks
- System recovery procedures

## Technologies Used
- Draw.io for flowchart creation
- GitHub for version control
- AI assistance for solution refinement

## How to Use This Repository
1. Review the problem analysis in `Step1_Analysis/`
2. Examine alternative solutions in `Step2_Alternatives/`
3. Check the implementation logic in `Step4_Implementation/`
4. View test results in `Step5_Testing/`

## Author
[Your Student ID] - University of Canberra

## License
This project is for educational purposes as part of coursework requirements.