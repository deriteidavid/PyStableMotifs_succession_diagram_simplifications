# PyStableMotifs_succession_diagram_simplifications
A simple notebook containing some simplification steps to PyStableMotifs succession diagrams.

The explanations in the notebook assume a basic understanding of stable motif succession diagrams and the PyStableMotif library by Rozum et al.:
https://github.com/jcrozum/PyStableMotifs <br>
<br>
Both kinds of succession diagrams (SD) -- the reduction based (RBSD) and the motif-based (MBSD) succession diagrams generate different pathways for different combinations of motif stabilization. The RBSD is more efficient in doing this but the end result can still be quite difficult to interpret, if the system is large and/or has a lot of motifs. This notebook aims to introduce a few simple methods to further simplify the succession diagrams and help with their interpretation. 
<br> This nodebook goes trough some of the steps of the PyStableMotif tutorial notebook, from generating the attractor repertoire to saving the succession diagrams, then introduces a few methods of simplifying these and generates two additional succession diagrams, the Simplified MBSD and the Bipartite MBSD.
