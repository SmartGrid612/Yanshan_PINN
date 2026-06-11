## Dataset Availability

Due to GitHub file size limitations, the complete microgrid datasets used in this project are not included in this repository.

To reproduce the experiments, please create the following directory structure before running the code:

project/

├── data/

│   ├── normal/

│   └── faults/

The `normal` folder should contain the normal operating condition datasets used for PINN training, while the `faults` folder should contain the fault and anomaly datasets used for evaluation and testing.

Users may place their own datasets following the same file naming convention and format described in this repository. The code will automatically load the corresponding files from these directories.

For research collaboration or academic purposes, the original datasets can be provided upon reasonable request.
