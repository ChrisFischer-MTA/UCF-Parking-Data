# UCF-Parking-Data

This data is scraped data from UCF Parking Services showcasing the parking utilization. This is taken approximately every two minutes. The data is stored in the following format (comma delemitited)

Date-Time (UTC), garage a utilization, garage b utilization, garage c utilization, garage d utilization, garage h utilization, garage i utilization, garage l utilization.

The code for data retrieval is stored: https://github.com/ChrisFischer-MTA/UCFGrg/tree/master/src/io/github/chrisfischerdashmta

If you'd like the data to be updated, create an issue request. I'm more then happy to update this for you. I'd also like to say that on multiple occasions the data appears to be incorrect - but in production I have error checking that notifies me. Multiple times I have verified by hand that the data being logged matches what is on the website - so you're best off taking that discussion to UCF Parking Services. 
