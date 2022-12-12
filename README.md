# The Nightmare Before Christmas(R) Version 1.0 2022/12/11 

### General Usage Notes 
------------------------
- The Nightmare Before Christmas reads the *student-mat.csv* file provided to evalute multiple examples of sorting and evaluating data. 
  1. The data is loaded into a data structure. From text processing a dictionare is created filled with the information from *student-mat.csv*. The dicitonary contains five different dictionary keys *School, Age, Health, Failures and Average Grade*(**Average Grade is calculated through the use of the 'G_Avg' that has been developed**). 
  2. The 'Load Data' module created above is then used to perform unit testing while reading from the *student-mat.csv* file. The dictionary is 'split' into separate dictionaries for easier manipulation of the data.
  3. Various sorting methods are developed for the user to sort as necessary. Selection sort and bubble sort take the different attributes then return the sorted data. Regression curve fitting is used to find the polynomial that best fits the data. 
  4. The sorted data is then formatted into multiple different histograms directly related to the attribute of the given information. The 'Sort Plot' module functions to devise a visual representation of the information of the *student-mat.csv* file. 
  5. The polynomail found in the regression module is then utilized to optimize the provided data by locating the Minimum and Maximums' of the information set, based on the attributes. 
  6. Two user inerfaces (*UIs*) are compiled to call and execute selected functions from above based on the needs of the user. The firts UI directly obtains input from the terminal. The second UI is a batch interface; a non-interactive interfaces where the details are specified and then returns upon completion, the required information. 
  
 ### Installing the Required Programs
  ------------------------------------
- When installing *The Nightmare Before Christmas*, it is recommended that the user installs multiple programs. 
  1. The first required program is **pip**
  - This needs to be downloaded to collect the rest of the required modules. **Download the run the latest version.** 
  - [Installation can be found at:] (https://bootstrap.pypa.io/get-pip.py)
    -(*Ensure to download to same directory as python*)
  2. **matplotlib.pyplot** 
  -Use pip to intall matplotlib.pyplot in the python interface. 
  3. **scipy.optimize**
  -Use pip to intall scipy.optimize in the python interface.
  
  
