---
title: "OOMMF"
collection: coding
type: "oommf"
permalink: /coding/oommf
venue: " University of Naples &quotFederico II&quot, Department of Physics"
date: 2021-03-25
location: "Napoli, Italy"
---

Installation

```
conda activate oommftools
conda deactivate

cd OOMMFTools
conda env create -f environment.yml
cd oommftools
python -m oommftools
```

conda activate oommftools

```
x tclsh oommf.tcl avf2ppm -config test.config -format b24 colorwheel.ovf​tclsh oommf.tcl avf2ppm -config colorbarZ.config -format b24 colorbarZ.ovf
```

3D figures

```
conda create -n discretisedfield python=3.8
conda activate discretisedfield
conda install --channel conda-forge discretisedfield

python3 -m discretisedfield.ovf2vtk -i Disk_77.omf

```
