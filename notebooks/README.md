# Python notebooks

Computational exercises will be introduced only after the relevant biological concepts are taught.

## Planned notebooks

1. `01_inheritance_simulator.ipynb` — enumerate possible offspring genotypes from fictional parental genotypes.
2. `02_str_allele_tables.ipynb` — read and validate fictional STR genotype tables.
3. `03_profile_comparison.ipynb` — compare fictional mother/child/alleged-father profiles.
4. `04_paternity_index.ipynb` — calculate simplified likelihood ratios from a fully specified fictional frequency table and explicit propositions.
5. `05_capstone_analysis.ipynb` — reproducible analysis of the complete fictional case.

## Suggested software

- Python 3.11 or later
- JupyterLab
- pandas
- NumPy
- matplotlib

Install the basic educational environment in a virtual environment:

```bash
python -m venv .venv
```

Activate it:

**macOS/Linux**
```bash
source .venv/bin/activate
```

**Windows PowerShell**
```powershell
.venv\Scripts\Activate.ps1
```

Install packages:

```bash
python -m pip install --upgrade pip
python -m pip install jupyterlab pandas numpy matplotlib
```

Start JupyterLab:

```bash
jupyter lab
```

These packages support educational data handling and visualization. They do not constitute validated forensic software and must not be used to issue real paternity results.
