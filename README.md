# **pythonic_monopoly**
## **Summary**
Here I will be creating a dashboard that provides charts, maps, and interactive visualizations that help customers explore data and determine if they want to invest in rental properties in San Francisco.
## **Workflow**
1. All necessary files are located within the repository. There should be two CSV files: neighborhoods_coordinates.csv and sfo_neighborhoods_census_data.csv.
2. The rental_analysis.ipynb file basically consists of all of the code work. One can disregard unless he/she would like to see my full coding process.
3. The dashboard.ipynb file is the finished product. One can see the completed functions that create the panes that then create the structures that constitute the dashboard.
4. In the dashboard.ipynb file the last line of actual code is dashboard_tabs.servable(). This is the servable function through panel. This function will allow one to serve the dashboard to the web.
5. One can then see a live version of the dashboard through his/her own computer as a local host by going to the folder that the respository is in and running code in the terminal.
6. - Pull the repository or at least the CSV data and dashboard.ipynb file.
   - Access the folder where all of this information has been pulled to via your command line.
   - Run: panel serve dashboard.ipynb --log-level debug --show
   - Enjoy!
 
