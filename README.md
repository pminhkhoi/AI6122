In this assignment we use packages which can be downloaded from the following links:
- Whoosh: https://pypi.org/project/Whoosh/
- PySimpleGUI: https://pypi.org/project/PySimpleGUI/
- NLTK: https://www.nltk.org/install.html
- PyPDF2: https://pypi.org/project/PyPDF2/

Our source code is built using .ipynb files so in order open the files:
- Open CMD then type in "jupyter notebook" to activate jupyter notebook
- Download Jupyter notebook extension on Visual Studio Code or following the guidance to download Jupyter Notebook for other IDEs

Our source code contains of 5 files:

- 3.1 Domain Specific Dataset Analysis.ipynb: this file is the source code for analysing dataset from 3 different domains. To run this file follows these steps:
	+ Download the required packages and open files using jupyter notebook.
	+ Run all cells in file. (need data file to run)

- indexing.ipynb: this file is the source code for indexing the dataset. To run this file follows these steps:
	+ Download the required packages and open files using jupyter notebook.
	+ Downloadthe dblp.xml.gz and dblp.dtd from https://dblp.org/xml/ and extract dblp.xml.gz to the same directory of this file.
	+ Run all cells in file.

- querying.ipynb: this file is the source for perform the querying on the indexed dataset. To run this file follows these steps:
	+ Download the required packages and open files using jupyter notebook.
	+ Config the fields variables that you want to search for.
	+ Change the search_string variable to you desired query and run the file.

- 3.3 Development of a Research Trend Explorer: this file is the source code for analysing the trend of publications from the Web Search and Data Mining (WSDM) conference over the past 16 conferences.
	+ Download the required packages and open files using jupyter notebook.
	+ Run all cells in file.

- application.ipynb: this file is the source code of a small pop up window for the user to type in the query of the corresponding search fields and retrieval the corresponding documents based on the indexed dataset. To run this file follows these step:
	+ Download the required packages and open files using jupyter notebook.
	+ Run the file and a window will pop-up
	+ Input the string you want to search for each corresponding fields (You can leave some fields blank but at least 1 field must
	be filled)
	+ Specify how many results to display
	+ Press OK and the results will appear in a new pop-up window