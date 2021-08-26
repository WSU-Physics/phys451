# Phys 451 - Quantum Mechanics

Useful codes to supplement Physics 451 at Winona State University.

## Set up an environment
You can use the included yaml file to create a conda environment that can run the notebooks.

```
conda env create --file=phys451_env.yml
conda activate phys451
python -m ipykernel install --user --name phys451 --display-name phys451
