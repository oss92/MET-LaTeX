The German University in Cairo - GUC
www.guc.edu.eg

Faculty for Media Engineering and Technology - MET
met.guc.edu.eg

LaTeX templates for coursework documents
Repository started on August 25th, 2011
Repository restarted on September 18th, 2012


----

newcsen.cls              - new class file to compile course documents
config.tex               - example file to test the class
PracticeAssignment01.tex - example file to test the class
GUC-logo.pdf      	 - PDF vectorized version of the GUC logo (gets loaded with option "logo" unless other file is specified)
GeorgJung-thumb.png	 - PNG file for testing purposes (can be specified as alternative logo)
FExtinguish.pdf          - Another logo to test the scaling

Implemented so far:
- Automatic result table
- Automatic search for global config file in current and parent and parent of parent directory
- Automatic setting of image search path according to location of config file
- options: all
- commands: \Institute{} \Department{} \Class{} \Title{} \Lecturer[]{} \Email{} \Logo{} \Topic{} \Date{} and more
- exercise environment
- bonusexercise environment
- options practice (default) and assignment usable now
- scratch paper generator
- cover pages
- spacing

To do:
- testing
- cleanup (consistently prefix variable names and booleans, tighten code)
- Redo formula sheet (and maybe solutions) by using the environ package with \detokenize{\BODY} (possible loss of backward compatibility!)
  (check http://tex.stackexchange.com/questions/67550/write-content-of-box-to-a-file)
- nicer subproblem handling
- provide scratchpaper command to put scratchpaper at other place than last pages
