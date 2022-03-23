# lab-protocols
A collection of scripts to help with working in a microbiology lab including randomizing well plates, parsing the outputs from plate readers and other machines used for analyzing and measuring microbial populations and their growth. 

# Plate Randomization
An important consideration for microbiology includes (pseudo)randomizing treatments in either a structured way or with complete randomness. Letting a computer decide which wells have which strains and treatments also helps to remove individual bias. Here I am providing the tools to randomize aany number of plates given a few inputs, plate type (eg 96 well,48 well etc), number of strains, number of treatments, number of replicates per treatment and strain. 

Your output will include a .csv file of the plates and a .csv file for data entry, and you will also have two pdfs as printouts with a color coding for your strain * treatment combination.
