# Book-Indexing
The Scans are done using an android app, all the data from the scans are exported to a Google Sheets Document.
From the Sheets Document, the necessary data are imported into the Jupyter Notebook which is running locally and which processes
the data to create some meaningful information.
This information includes metadata from the ISBN tag that is looked up from various sites.
GoogleBooks,Openlib,ISBNsearch.org,Amazon.com and isbns.net are the few services I am trying to use.

Once this information is gathered, the data is stored into a Pandas Dataframe which is then exported as a .csv file and also into another sheet of the same Google Sheets Worksheet.
