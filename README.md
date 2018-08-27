# singularity-mriqc
Singularity recipes for building mriqc container
* Uses the official docker image of mriqc as base: https://hub.docker.com/r/poldracklab/mriqc/
* Recipes purge and reinstall libgsl2, since there were issues with it when just using the base container.
