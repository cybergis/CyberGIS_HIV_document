Data Summary
==================================================================

When choosing an optimal number of variables, it is important to avoid both over-fitting, i.e., low predictive power due to the inclusion of too many variables without statistical justification at the model identification stage, and under-fitting, i.e., poor performance in modeling both the training and test data due to the inclusion of too few variables. We fit the two model parts discussed above separately. Both model parts use stepwise regression, selecting from the explanatory variables described above. The binary part of the model, classifying positive-versus-zero outcomes, selects 40 significant variables and the positive part of the model, predicting diagnosis rates for counties classified as positive, selects 37 significant variables. While the two model parts are allowed to select different variables, a few of the variables are found significant for both model parts. For example, the number of opioid prescriptions, percentage of people participating in food stamp, percentage of population in juvenile facilities, the number of federally qualified health centers, knowledge of HIV status, the rate of HIV testing, HCV death, the rate of PrEP use, percentage of households receiving social security income, rate of illicit drug use, and linkage to HIV care are significant in classifying both positive-versus-zero outcomes and predicting the positive diagnosis rates.

To model new HIV diagnosis rates, we consider a variety of explanatory variables. For the full list of data and descriptions, see the following table.

.. csv-table:: 
   :file: data/data.csv
   :widths: 15 20 30 15 15
   :header-rows: 1
   

Abbrevations in the Source column and their associated links. 

| * AHRF: https://data.hrsa.gov/topics/health-workforce/ahrf
| * AIDSVu: https://aidsvu.org/
| * BRFSS
| * Census TIGER: https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html
| * CDC NCHHSTP AtlasPlus: https://www.cdc.gov/nchhstp/atlas/index.htm
| * CDC Opioid data: https://www.cdc.gov/opioids/data/index.html
| * Hepvu: https://hepvu.org/hepatitis-c-related-mortality-in-the-u-s-at-the-county-level/
| * NSDUH (National Survey on Drug Use and Health): https://nsduhweb.rti.org/respweb/homepage.cfm
| * Jones et al. (2018): https://doi.org/10.1093/ofid/ofy124

