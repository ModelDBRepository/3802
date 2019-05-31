NEURON mod files for a Potassium current from the paper:
Beech DJ, Barnes S.
Characterization of a voltage-gated K+ channel that accelerates 
the rod response to dim light.
Neuron 3:573-81 (1989).

Running the kinetics.hoc simulation file will show 
the activation steady-state, the time constant, 
and a family of curves generated modeling the same protocol 
used for Fig.2A of the paper.

Under unix systems:
to compile the mod files use the command 
nrnivmodl 
and run the simulation hoc file with the command 
nrngui kinetics.hoc

Under Windows using NEURON 5.1:
to compile the mod files use the "mknrndll" command.
A double click on the simulation file
kinetics.hoc 
will open the simulation window.

Questions on the model parameters should be directed to the 
authors.

Questions on how to use this model with NEURON
should be directed to michele@pa.ibf.cnr.it
