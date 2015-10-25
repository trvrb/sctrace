<script src="processing.min.js"></script>
<canvas datasrc="sctrace.pjs" width="600" height="450">`Can't load canvas`</canvas>	

This is a simulation of a demographic / genealogical process that includes migration between demes.  Within each deme, individuals are born and individuals die, causing lineages to branch and to disappear. In addition to birth and death, individuals may migration between deme 1 and deme 2. This process is described by the structured coalescent.
		
Individuals are represented as circles. Layout is taken care of through simple physics. Each individual is given a charge and Coulomb's law is used to for repulsion. Each individual is attracted to its deme's origin, causing individuals to fly towards their new deme when migration events occur.
		
Press **H** to bring up a listing of commands.
