# Data analysis project

Our project is titled a Analyzis of the Danish stock market and is foucusing on the OMXC 20 cap and the stock indexes concerning the financial, industrial and IT sectors. This clarifies the development of each sector, compared to the OMCX 20 and their volatility.

The **results** of the project can be seen from running [dataproject.ipynb](dataproject.ipynb). The data is downloaded from the API pydst.Dst, which accesses Statistic Denmark's data.

The code loads the following data sets:

1. INDKP101.xlsx downloaded from statistikbanekn.dk/INDKP101
2. RAS200.xlsx downloaded from statistikbanekn.dk/RAS200

Which are cleaned and transformed to explore the sector performances relative to the benchmark OMXC20.

**Dependencies:** Apart from a standard Anaconda Python 3 installation, the project requires the following installations:

``pip install matplotlib-venn``
