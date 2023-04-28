# Additional notes

Installed with institutional conda:

```
./src/conda/conda_env_setup.sh --all --conda_root /home/oar.gfdl.mdtf/miniconda3 --env_dir /home/oar.gfdl.mdtf/miniconda3/envs
```

Instead using my own conda install:
```
./src/conda/conda_env_setup.sh --all --conda_root /nbhome/Enrico.Zorzetto/software/miniconda3 --env_dir /nbhome/Enrico.Zorzetto/software/miniconda3/envs
```

To run the example:
```
cd <CODE ROOT>
./mdtf -f mytests2.jsonc
```

To run the msp snow multi case experiment
```
cd <CODE ROOT>
./mdtf -f diagnostics/map_snow_multicase/runfile.jsonc
```