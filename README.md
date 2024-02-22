# TrackStatus
Track Status is a generic app used to track stages of a process. This app tracks the stages for ordering and receiving IT equipment. Created using MS PowerApps and MS Power Automate and with backend using Sharepoint lists, it gives the user a cleaner, easier to use interface that can be used to forward application for new IT equipment within your department.

It makes use of two sharepoint lists :  ParentRequest and LineItems table.

Parent Request :  Keeps account of all pending or in progress order requests for new IT equipment.

<img width="1325" alt="image" src="https://github.com/mrudulabapat/TrackStatus/assets/35365848/9eb69bc7-c588-492e-8930-3b0d470aafcc">



LineItems:  It is a child for the above table and keeps track of all the individual items in an order.

<img width="1499" alt="image" src="https://github.com/mrudulabapat/TrackStatus/assets/35365848/ca40205b-47dd-492d-a0e9-697361a3483e">



**PowerApp:**
Home Page: 

<img width="1027" alt="image" src="https://github.com/mrudulabapat/TrackStatus/assets/35365848/3a20faef-2f1f-4460-9b54-49d8256385d1">



Items page:

When a particular item from home page is selected, it takes us to the items page and displays the parent order and also all the child items within the order on this page.

It also displays the stage in which the order is currently in if there are actions required by the user.

<img width="1028" alt="image" src="https://github.com/mrudulabapat/TrackStatus/assets/35365848/e11af2fb-33db-4fd5-b4bc-605dd822c44f">









