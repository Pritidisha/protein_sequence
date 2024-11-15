Requirements
 - Python 3.x
 - Numpy library for matrix operations
 - bash command
    pip install numpy
How to Use
 - Prepare the Input File: 
     Ensure disease.csv is in the same directory. 
 - Each row should contain:
     disease: Name of the disease
     sequence: Protein sequence associated with the disease
 - Run the Script:
     Enter the input protein sequence when prompted.
     The program will compare the input sequence to each disease sequence in the file and calculate similarity scores.
     It outputs diseases with similarity scores above 20%, sorted in descending order of similarity.
