# MOM6_Pacific
Regional Pacific domain configuration for MOM6

Requires: xarray, matplotlib, numpy, netCDF4, jupyter, nco

```sh
cd preprocessing/input_data/om4_025
chmod +x wget.bash;./wget.bash
```


Best practice, use an environment rather than install in the base env, choose your own environment name like "mom6-env"
```sh
conda create -n mom6-env
conda activate mom6-env
```


# If you want to install from conda-forge
`conda config --env --add channels conda-forge`

# The actual install command
```sh
conda install numpy
conda install netCDF4
conda install matplotlib
conda install xarray
conda install jupyter
conda install nco
```

Does MIDAS need to be installed? (Located in open boundary code)

# Run notebook

Run notebook (follow instructions to open tab in your existing browser session)
```sh
jupyter lab --no-browser
```
