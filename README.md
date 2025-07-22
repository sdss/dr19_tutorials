# Tutorials for SDSS DR19

This repo contains Jupyter Notebooks showing how to access various SDSS data products.

If you encounter any issues, e.g., you're on a brand new operating system, feel free to file an issue.

These Jupyter Notebook tutorials can be run remotely on [SciServer Compute](https://apps.sciserver.org/compute), with direct access to a file system hosting the DR 19 data volume.
If you prefer, you can also download DR 19 files from https://data.sdss.org/sas/dr19/ and run these notebooks locally in your own computer.

#### In [SciServer Compute](https://apps.sciserver.org/compute), you will need to:

- Choose the `SDSS` Docker image. This image contains the `sdss_access` python package, as well as `astropy`, `astroquery`, `specutils` and other useful libraries.

- Include the `SDSS SAS` data volume. It will be mounted in the Jupyter session under `/home/idies/workspace/sdss_sas/`.

- Once in a notebook, make sure the `py39` python kernel is selected.
