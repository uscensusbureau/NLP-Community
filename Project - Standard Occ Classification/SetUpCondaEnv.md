## NLP python env  
1) Open Anaconda PowerShell Prompt.
2) Run the following commands:

	- conda create -n NLPy python>3 # where NLPy is your name for a new environment  
	- conda activate NLPy  
	- conda install ipykernel pandas nltk spacy  
	- python -m ipykernel install --user --name NLPy --display-name "NLPy (Python 3)"  
	- conda deactivate  

Note: if you see a message saying "conda needs to be updated", this is normal and okay to ignore for now.  

Now, if you use Jupyter or Visual Studio, you can choose this kernel in the upper right corner when you open a Python notebook file. Otherwise, run the lines below to open jupyter notebook in your new environment.

conda activate NLPy
jupyter-notebook

