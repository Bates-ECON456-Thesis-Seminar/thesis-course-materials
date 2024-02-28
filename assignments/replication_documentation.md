# Replication Documentation
This assignment entails completing one “thesis assignment”:

1. Thesis: Replication Documentation due 2/29 at midnight 
This component of the project entails the completion and submission of several data and
replication documentation components, including:
- Data processing command files (processing.do) [Code] or [Code/Build].
- Data construction command files (construction.do) [Code] or [Code/Build].
- Analysis code files in (analysis.do) [Code] or [Code/Analysis].
    

1. Processing Your Data: Building your Base Data File
The processing phase of a project consists of all the steps involved in transforming your original
data files (or the importable versions) into the fully cleaned and processed base data files that
you use to generate your analysis data.
All of the commands necessary for processing your data must be written in your processing.do
command file, or in a series of processing .do files. When you have finished writing this .do
file(s), executing it will automatically conduct all the procedures necessary to transform your
original (or importable) data files into your base data file.
Writing, experimenting with, and editing this command file (Processing.do) until it can
successfully carry out the necessary steps of processing is the focal point of the work you do
with your data. This usually entails:
• importing original or importable data files;
• combining several original or importable data files (appending and merging);
• making any necessary adjustments to facilitate these combinations (renaming, recoding,
reshaping);
• cleaning the data to resolve any errors or discrepancies;
• saving a cleaned version of your data under a new file name.
For full credit your processing.do should:
• have a header that includes your name and date created
• be free of errors
• be free of extraneous (unnecessary) commands
• include detailed comments explaining all commands (or series of commands)
• utilize spacing and delimiting to make it easily readable
You should avoid making any additional changes to the data at this phase (such as creating new
variables, transforming existing variables, or deleting variables or observations). These changes
should occur in the next phase, Data Construction, and be documented in the Construction.do
command file.

2. Data Construction. Transform your base data file into analysis data files. In one or more
command files (Construction.do), write code that transforms your base data file into your
analysis data files. Data construction can include many tasks, for example:
• opening your based data file;
• removing variables or observations that you do not need;
• generating new variables;
• transforming variables;
• saving intermediate and analysis data files.
Note that any variables remaining in your analysis data will need to be described in detail in
your Data Appendix and included in your Methods & Data section (both are part of a future
assignment). Remember, for full credit all command files should be fully commented and
easily readable.

3. Save your Construction.do command files in the Command Files folder and your
analysis data file in the Analysis Data folder.