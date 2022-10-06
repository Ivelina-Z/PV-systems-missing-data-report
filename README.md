# NREL-API-interaction-and-report

Make request to the NREL's API to get information about PV systems metadata. After processing the metadata interact with 'Annual Data CSV for a System' of NREL API and extract data for the available systems for each year with records. For performance optimization synchronous and asynchronous are compared.

After extracting the systems annual data is processed and missing data percentage is calculated for each system per year. The final report is extracted to missing_data_report.csv. After further exploration of the report a conclusion about certain systems' data suitability for a data analysis, supervised or unsupervised application can be made based on the available features, years of records and the percentage missing data for each one of them.

For the asynchronous method the hpptx package needs to be installed. 
