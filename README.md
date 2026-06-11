## Dataset Preparation

The original datasets are not included in this repository due to file size limitations and repository management considerations.

Before running the project, please manually create the following directory structure:

```text
project/
│
├── data/
│   ├── normal/
│   │   ├── MG_Normal_V_abc.csv
│   │   ├── MG_Normal_I_abc.csv
│   │   ├── MG_Normal_P_total.csv
│   │   └── MG_Normal_Q_total.csv
│   │
│   └── test/
│       ├── Loadstep/
│       ├── PhaseToPhase_NoGround/
│       ├── SinglePhaseOpenCircuit/
│       ├── SinglePhaseToGround/
│       ├── ThreePhaseShortCircuit/
│       └── ThreePhaseUnbalance/
```

The `normal` directory contains the healthy operating-condition data used for PINN training.

The `test` directory contains all fault and disturbance scenarios used for model evaluation, including load-step changes, grounding faults, open-circuit faults, phase-to-phase faults, three-phase short circuits, and three-phase unbalance conditions.

Due to repository size limitations, the datasets are not included in this repository. Users should create the directories above and place the corresponding CSV files into each folder before running the project.

Once the datasets are prepared, the training and detection scripts can be executed directly without modifying the source code.
