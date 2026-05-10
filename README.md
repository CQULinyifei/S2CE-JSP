# S2CE-JSP

This repository provides the dataset for the S2E-JSP problem. Each instance text file contains odd columns (J) and even columns (T) for operations. J denotes the machine assigned to each operation, and T denotes the corresponding processing time.

The repository also includes two auxiliary input files:

- `P_i.xlsx` provides the rated power \(P_i\) of each machine. These values are used to calculate machine-level electricity consumption during operation processing intervals.

- `CE_t.xlsx` provides time-varying clean-electricity availability at a 3-minute resolution. It includes wind generation (`WIN_3min`) and photovoltaic generation (`SOL_3min`) profiles, which are used to evaluate how production electricity demand can be temporally matched with clean electricity supply.

## Repository structure

```text
S2CE-JSP/
├── Data/        # Job-shop instance text files
├── P_i.xlsx     # Rated power of machines
├── CE_t.xlsx    # Time-varying energy-side data
└── README.md
