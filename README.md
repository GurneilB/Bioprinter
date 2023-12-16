# Bioprinter
The workflow and software breakdown for Dr. Mohsen Akbari's Bioprinter.

Welcome to the BioPrinter's GitHub Page!

Attached is all of the software needed to complete your workflow for using the Bioprinter. 

The BioPrinter's Workflow is divided into 4 sections:
  1. Design  
  2. Slice
  3. Process
  4. Print 

Below goes more in-depth into the 4 sections and the software behind them:

# 1. Design

Any Computer-Aided Design (CAD) software will suffice. 

The goal is to save the file as a '.obj' or '.stl' file 

# 2. Slice

The slicing software used is RepetierHost.

  - First download the software from this site
  - Modify the Printer Config to the dimensions of your printer
  - Upload the Configuration file on this Github to slice correctly
  - Upload the '.obj' or '.stl' file
  - Slice the '.obj' or '.stl' file
  - Download slice file and save into the same folder as the post-processor file

# 3. Process
The Post-Processing Software is required to calculate the correct extrusion rates of the bioinks as all slicers are optimized for plastic filaments.

  - Download the file
  - Run it ad makesure that your sliced .gcode file is saved in the same folder as this executable. 
# 4. Print 
