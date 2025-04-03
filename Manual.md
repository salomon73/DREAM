To run the code, use some generated input generally in the form settings.h5. 
The input has been generated in a python script from the class DREAMSettings. 

To run a input, either give the generated DREAMSettings instance inside the python script to the function runiface as 
do = runiface(ds, nthreads=N) where N is the number of threads desired. ds is the instance of the class DREAMSettings. 

Or, from the command line, fetch the dreami executable as 
./Path/to/Dreami/dreami settings.h5

This will run DREAM with the input configuration specified by the file settings.h5. The output will be saved into a file output.h5. 
Note: even if DREAM crashes, it saves the output in a file output.h5, overwriting any prevously existing output file, and saves all the data produced until the code crashed. 

[last update on 04/03/2025]
