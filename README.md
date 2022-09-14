---

## Sample Data Plotting (earth science)

---

#### Prerequisites

1. Install VSCode.
2. Go to Extensions in VSCode and install Jupyter Notebook and Python (newest versions).
3. Now go to the menu header "Terminal" and open up a new Terminal.
4. Run the following commands in the terminal:
  - pip install --upgrade pandas
  - pip install --upgrade numpy
  - pip install --upgrade matplotlib

---

#### Files

- "runnable.ipynb" contains all the runnable code.
- "config" contains all config files.
- "sample" is where the sample is stored.
- "plots" is where the plots are saved to after running the code.

---

#### Important

- Always run the codeblocks in the right order (first to last), alternatively you can use "Run All".

- When making changes to the code or plotting, read the code comments carefully before proceeding.

---

#### Description

1. The first codeblock is used solely for data import and is necessary for the rest of the codeblocks.

2. The second codeblock is used to create a config file **placeholder** in .csv format. 
To make use of this placeholder file, convert it into .xlsx format (using Excel) and
save it from "parameter_hier_einstellen.csv" to "eingestellte_parameter.csv".
Now you can set the parameters (columns) for each plot (rows) by inserting a "1"
to activate the config setting at the desired place.

3. The third codeblock is used to process the given data and create a scatter plot based on data and config settings.

---
