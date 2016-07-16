# SharePoint List Data Analysis
Whenever using a mutli-choice choice column in a SharePoint list, you will run into a lot of fun parsing data for analysis. Similar to HTML, all selected choices are stored as a single field with delimiters. In this case, SharePoint uses "#;".

In this example, we have a SharePoint list called Company Offices. Each company may have 1 or more global offices. There isn't an really easy way to achieve within SharePoint itself. Solutions like SQL Server Reporting Services (SSRS) and SQL Server Integration Services (SSIS) are pontentail candidates. 

What if the token requirement is "We needed this yesterday for an executive report"? It will take a little longer to spin up the above services!

Python comes into the picture beautifully.


# Objectives
* Bypass Excel, Reporting Services, SQL Server Integration Services to perform data analysis. 
* Parse data exported from a SharePoint list that contains one or more mutli-choice columns.
* Generate graphs to for better presentations.


# Game Plan
Import SharePoint list data into Pandas DataFrames.
Transform and cleanse data using techniques (Split, Join, Apply, Stack).
Visualize data using Seaborn package.


# Resources
<a href="http://pandas.pydata.org/">Pandas</a>
<a href="https://stanford.edu/~mwaskom/software/seaborn/">Seaborn</a>
