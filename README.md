# NetCDF and `xarray` tutorial

This is a small introduction to NetCDF and `xarray` for the EPIC Orientation seminar.

### Instructions:

Rerun this code:

1. Ask @atrisovic for data 

2. Run the following commands:

```
git clone <this repository>
cd xarray-notebooks
mkdir data
# put data into the folder data
```

3. Create a virtual environment:
```
pip install virtualenv
virtualenv env
source env/bin/activate
pip install -r requirements.txt
```

4. Run a notebook server:
```
jupyter notebook
```

### References:

These notebooks are based on:

    - http://xarray.pydata.org/en/stable/plotting.html
    - https://geohackweek.github.io/nDarrays/05-aggregation/
    - https://daac.ornl.gov/resources/tutorials/NetCDF_webinar_08302017.html
    