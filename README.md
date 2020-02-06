# Invoice2SAP
## Description
Invoice2SAP demos our machine learning document understanding solution to digitize invoices and enter them into SAP. It is based on a more comprehensive demo by Ludwig available to run from Studio in the **SSD-SAPSuperDemo_Stable** folder
1. Read invoices from Outlook
2. Digitize them using https://invoices.uipath.com
3. Export the data into Excel
4. Write the data to SAP

## Story
Finance receives an invoice as an e-mail attachment in a dedicated mailbox (represented by an Outlook folder). When a new e-mail is found in the mailbox, the robot downloads the attachment, digitizes it and enters the invoice into SAP. 