# dvlab

Notes

We will use Jupyter Notebooks and Tipboard Dashboard to demostrate the analysis work on the virtualize tables. The jupyter notebook contains sample SQL queries that access and combine data from across the virtualized data enterprise in this environment.

Play

1. Demonstrate Analysis using Jupyter Notebooks
2. Goto to Jupyter URL - Look for ‘Jupyter:’ link in your welcome email from techzone. If asked for password, use CTP.cp4data!
3. From the list Click and Open CP4D - Stock Queries Notebook
4. Run each cell in turn to see the kind of queries you can build using virtualized data. 
5. Demonstrate analysis using dashboard application
6. Goto to Stocks application URL - Look for ‘Stocks Application:’ link in your welcome email from techzone
7. Click the CP4D_Dashboard_Continuous Jupyter notebook in the Jupyter Notebook Environment. The Python code in this Jupyter notebook runs SQL that retrieves data from each of the available data sources. It combines the data and pushes it out the Tipboard open source dashboard.  
8. Select Restart and Run All from the Kernel menu in the Jupyter notebook.
9. Wait until you see the last cell in the notebook start running. It will list three new stocks every few seconds. It will keep running until you Interrupt the Kernel. 
10. Revisit the dashboard URL. You will notice dashboard is getting live feed via notebook
The dashboard is rendered by the Tipboard (allegro.github.io)open source project code and is an example of using an application outside of Cloud Pak for Data to user virtualized data. 



Test Data Protection - Using External application


Test using external Jupyter Notebooks


Play

1. Download file CP4D-Masking-Customer-CC.ipynb Link
2. Goto to Jupyter URL - Look for ‘Jupyter:’ link in your welcome email from techzone. If asked for password, use CTP.cp4data!
3. On Jupyter page, Click Upload to upload the downloaded file (step 1)
4. Click CP4D-Masking-Customer-CC.ipynb
5. Click cells -> Run All
6. Review output when logged in as DATAENGINEER0. Notice that the credit card data is redacted with X.
7. Review output when logged in as ADMIN. Notice that the credit card data is visible

Notes

We saw that the data protection rule implement on Cp4D using WKC is fully protected both on the platform and also when accessed from outside the platform using Jupyter Notebooks
