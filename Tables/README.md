## Getting Started <a name = "getting_started"></a>
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
1. MS PowerApps
2. MS SharePoint

### Installing
1. Download the above data sheets for tables - ParentRequest, LineItems
2. Download the msapp from the repository [ Link ] https://github.com/mrudulabapat/TrackStatus/tree/main
3. Export both the tables in Sharepoint - please check if the 'purchased date' column is of type single line of text [Note] . Also please check if the 'Approved','Waiting','Declined' columns from LineItems are of type 'Yes/No' in Sharepoint.
4. Export the msapp app.
5. Establish data connections with the SharePoint lists.
6. Check the app and Run

## Usage <a name = "usage"></a>
1. Tracking status for a process-based application.
   Example usage: Tracking new IT equipment for the department.
   

*Note:
1. While importing and exporting SharePoint lists I faced an issue where the date columns were not imported with the correct type of Date Time and hence I used Single line of text type for this example. 
Please feel free to use the type Date Time for Date columns.
2. SharePoint lists also doesnot correctly import/export Person column. For which I used Single line of text, please feel free to use Person column.
3. 
