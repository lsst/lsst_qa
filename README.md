# lsst_qa - A build target for LSST DM Quality Assurance

Run validation quality assurance on data sets from the supported cameras: 
`CFHT`, `DECam`, `HSC`, `SDSS`, and `lsstSim`.

```
obs_cfht
obs_decam
obs_subaru
obs_lsstSim
obs_sdss

validation_data_cfht
validation_data_decam
validation_data_hsc

validate_drp
ci_hsc
```

Intended for "daily-scale" quality-assurance testing.

Notes:
* There are explicitly `validation_data_*` data sets  for CFHT, DECam, and HSC
* Sims does not have such a package and will likely run its own self-generated data.
* SDSS has a bit of example data in `obs_sdss` 
