# CryoSPARC OOD Application for PACE at Georgia Tech

An [Open OnDemand](https://openondemand.org/) 
application for [CryoSPARC](https://cryosparc.com/),
implemented by [PACE at Georgia Tech](https://pace.gatech.edu/).  
Many thanks to [SLAC at Stanford](https://www6.slac.stanford.edu/) 
for providing their implementation as a starting point.

* https://github.com/slaclab/slac-ood-cryosparc/tree/main
* https://github.com/slaclab/cryosparc-docker

This app runs CryoSPARC master and worker as services within a single Apptainer
instance.  The Apptainer image was built from
[`apptainer/cryosparc-latest.def`](apptainer/cryosparc-latest.def), which is
included here for reference.
