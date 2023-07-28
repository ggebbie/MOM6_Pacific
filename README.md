# MOM6_Pacific
Regional Pacific domain configuration for MOM6



Requires: xarray, matplotlib numpy and netCDF4


(cd preprocessing/input_data/om4_025;chmod +x wget.bash;./wget.bash)
jupyter lab --no-browser
(follow instructions to open tab in your existing browser session)

conda create -n mom6-env
conda activate mom6-env
 Best practice, use an environment rather than install in the base env
conda create -n my-env
conda activate my-env
# If you want to install from conda-forge
conda config --env --add channels conda-forge
# The actual install command
conda install numpy
conda install netCDF4
conda install matplotlib
conda install xarray
conda install jupyter
conda install nco
conda install midas
