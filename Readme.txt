

The TSL directory contains the files use to generate the concrete inputs.

The analylis data directory contains the output from the oracle proccessing stage of ChemtTest. 
This output was then grouped to generate the tables in the paper. 

For each Abstract Test we evaluated, they are grouped by an identifier in the Property Column. 
For all the Abstract Tests, they are concretized with a value represented in the ID column.
 The combination ID and Property define a single concrete test. 
 Each conrete test is ran 100 times for each subject; 
 this results in the values in the table which range from 0 failures to 100 failures.

RQ1 Supplemental contains the full model checking study results, including smaller input sizes that were used.

RQ2 Supplemental contains the approximate majority graph.

RQ3 Supplemental contains the approximate majority graphs.

The Oracles Table.csv files contains the requirements used to evaluate the simulation traces for each subject. 
An english description of the property is also included next to each property.


Matlab Models contains the simbio project files for each correspnding subject. S10 is the 10th mutation of the subtraction CRN. Whereas S0 is the orignal subtraction model.
For the Hailstone subjects, they are named H# where # is the subject number.

Prism Models contain the .smbl files the matlab exports, and the converted .sm files that the smbl2prism command generated in Prism.
The reason for the number of .sm files is that one is needed for each input used whereas the matlab files are supplied the input values when they are simulated.





Acknowledgments:
This work is supported in part by NSF Grant CCF-1909688, CCF-1901543, and  FET-1900716. 
Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.