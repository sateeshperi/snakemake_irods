# snakemake_irods


1. Login to CyVerse [Atmosphere](https://atmo.cyverse.org/)
2. Launch tiny1 instance with [Snakemake 2019](https://atmo.cyverse.org/application/images/1687) image
3. Initiate irods with `iinit` (This will generate `.irodsA` authentication file required by Snakemake)
4. git clone this repo 
5. Replace paths with files in your data-store in Snakefile
6. `snakemake`
