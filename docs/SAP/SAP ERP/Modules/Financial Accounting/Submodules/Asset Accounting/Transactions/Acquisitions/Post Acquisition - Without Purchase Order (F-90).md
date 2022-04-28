Post Acquisition - Without Purchase Order (F-90)
---
# Details
Business Role(s) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:  [[Asset Accountant]]<br />
App Launcher Title(s) &nbsp;&nbsp;&nbsp;:  Post Acquisition (Integrated AP)<br />
Application Type &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:  SAP GUI <br />
T-code &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:  F-90  <br />
Scope Item &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:  [[Asset Accounting (J62)]]

# Usage
You want to post an asset acquisition from a vendor (integrated with [[Accounts Payable (J60)]])) without a Purchase Order. You need to first make sure the asset master exists (if not, [[Create Asset (AS01)]]), and then you can post the vendor invoice for its acquisition. 

# Notes
Fields:  
- Type: For standard vendor invoices, you would enter "KR"  
- Document Number: This number is the document number under which the invoice will be stored in the system. Usually, you'll leave this field blank, and the system will assign a document number from the predefined number range assigned to the document type. For some document types, you may configure an external number assignment; in this case, the field would be mandatory. But vendor invoices are usually automatically numbered.

https://dxc.percipio.com/books/072e4012-c992-4deb-ada6-de10b856461d


---
# Links
Fiori Apps Library: https://fioriappslibrary.hana.ondemand.com/sap/fix/externalViewer/#/detail/Apps('F-90')/S22OP