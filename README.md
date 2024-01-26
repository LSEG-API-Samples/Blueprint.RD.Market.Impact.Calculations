# Market Impact Calculations


## <a id="overview"></a>Overview
In this article series, we implement a theoretical system that aims to shed some light on one of the stochastic constituents of Transaction Cost Analysis (TCA) that of the market impact. We will start by presenting some of the theory behind TCA and then move on to the implementation and analysis of the market impact calculations.

With regards to the dataset, we will be using LSEG D&A libraries to ingest historical pricing data and use used to calculate the important components of market impact.

Details and concepts are further explained in the [Market Impact Calculations]() Blueprint published on the [LSEG Developer Community portal](https://developers.lseg.com/en).

## <a id="disclaimer"></a>Disclaimer
The source code presented in this project has been written by LSEG D&A only for the purpose of illustrating the concepts of creating example scenarios using the LSEG D&A Data Library for Python.

***Note:** To [ask questions](https://community.developers.refinitiv.com/index.html) and benefit from the learning material, we recommend registering on the [LSEG Developer Community](https://developers.lseg.com/en)*

## <a name="prerequisites"></a>Prerequisites

To execute any workbook, refer to the following:

- A LSEG D&A Desktop license (LSEG D&A Workspace) that has API access 
- Tested with Python 3.10.12
- Packages: [pandas](https://pypi.org/project/pandas/), [refinitiv.data](https://pypi.org/project/refinitiv-data/)
- RD Library for Python installation:  '**pip install refinitiv-data**'

 
## <a id="authors"></a>Authors
* **Marios Skevofylakas**

