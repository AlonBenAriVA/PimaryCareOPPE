# PimaryCareOPPE
A python application that returns an OPPE report for Primary care.
The application goes to the CDW and gets data relevant for primary care such as  panel size, female patient, PAP exam offered, Lipid Management,Tobacco Screen offered Retinal exam for diabetics, mammograms offered etc.
needs to be run from a linux machine with python 2 or above and latex and pdflatex for report generation.
To run from /src
run  getsql.py
run GetReport.py
from the CLI  run from /src/tex_files
$ find -name "*.tex" -exec pdflatex -output-directory=pdfReport '{}'\;

report will be under /src/text_files/pdfReport

