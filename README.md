# VLDDR-Data-Collection-and-Analysis
Github repository containing all code relevant to Gijs Vermeulen's AI bachelors thesis on the VLDDR measure

The folder "Data preperation and calculation" holds 3 python notebooks. They are shown in order (1, 2, 3) and produce three files dataframes saved in csv files, the last of which is called "FinalData.csv".

The folder "Data analysis" holds 4 python notebooks and a copy of "FinalData.csv" which can be produced by the earlier mentioned 3 notebooks. The notebooks in "Data analysis" import "FinalData.csv" to calculate results and create plots using matplotlib and seaborn. These notebooks can be run in any order.

The calculation and collection in this python notebook has been done using Python 3.12.1 and uses packages:
- NumPy 1.26.3
- Matplotlib 3.8.2
- Seaborn 0.13.2
- SciPy 1.13.1
- Pandas 2.1.4
- SpaCy 3.8.14
- MLstatkit 0.1.8
