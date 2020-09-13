# WorkScripts
Scripts used at work to save time and eliminate human error.

# Any input/output data is hidden due to privacy and legal concerns.

Canada_MonReturns.ipynb
Our current process is when we receive the monthly return files from various companies,
we manually check to make sure it is in a specific format our system can read.
The tought part is that each company has their own format. The script is used to get rid 
of the manual checking and confirming each excel file is sent in the specified format.

HoldingsEmail.ipynb
We send out emails regarding different in pricing off of an export from our internal software.
The software exports the data in a strange way making it very manual to cut, copy, and select
columns that we only want clients to see. This script requires me to export the data for each fund
and apply it to the path in the script.

HoldingsEmail_LessManual.ipynb
Similiar to the one above, however it asks the user to ask the name, id and date of 
the fund we are reaching out for. Less manual work up front, kind of cool to fill out.
Both this script and the one above produce the same kind of file.

