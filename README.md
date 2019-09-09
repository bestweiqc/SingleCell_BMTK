# SingleCell_BMTK

1.Download VM from https://www.virtualbox.org/wiki/Downloads

2.Download the CompNeuro Virtual Appliance provided by the Mizzou Neural Engineering Lab: https://drive.google.com/uc?id=1-9tUHcFvi5LpnII8Zdzsfv8ZObdEwAUl This file is 8.6GB and will take some time to download. The file may also be available via USB.

3.download model from allen Database http://celltypes.brain-map.org, replace the morphology(.swc), modfiles and parameter_fit.json to the source floder.

4.compile the modfiles in sources floder, use the command nrnivmodl modfiles and generate the x86_64, move x86_64 to the sources floder

5.run the notebook, you can change any conductances values or injeted current current amplitude，delay time and duration time.

6.If you want to test another sets of inputs or conductances, just click the kernel button and select restart l& run all.
