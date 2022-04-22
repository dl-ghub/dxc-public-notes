## Company Code
Higher Level(s): [[Company]]
Lower Level(s): [[Profit Centre]], [[Cost Centre]], [[Functional Area]], [[Credit Control Area]]

The company code is the central organisational element of financial accounting in SAP S/4HANA. Each posting must be assigned to a company code. The company code can also be regarded as a building block in SAP S/4HANA. With this entity, accounting is connected to other applications. 

The company code organisational element is not equal to and doesn't have a 1:1 relationship with the company element. **Rather, different company codes can be created within a single company** (for example, if they are operating abroad with external reporting requirements). 

The purpose is to maintain a closed accounting system for each company code, with the option of generating a balance sheet and income statement for each company code. Therefore, all company codes within a company must use the same chart of accounts and fiscal year. 

You can use company codes for a location, factory, business area, branch or functional area, such as a development department, if you want a pro forma financial statement for these organisational elements. 

You can have different currencies in use to maintain a cross-national corporation. 

The advantage of the company code in, for example, comparison to a profit centre, is that these units provide not only a result per unit but also a hard financial statement that includes all period-end closing steps and a legal company balance sheet. 

For every company code, you need to control the financial postings, which is done mainly in the company code parameters. 


## Create a Company Code
Menu Path: Enterprise Structure -> Definition -> Financial Accounting -> Edit, Copy, Delete, Check Company Code -> Edit Company Code Data. 
![[Pasted image 20220407133629.png]]

## View/Maintain Company Code Parameters
Menu Path (IMG): Financial Accounting -> Financial Accounting Global Settings -> Global Parameters for Company Code -> Enter Global Parameters (or use Transaction OBY6) to get a list of company codes. Double-click on a line to arrive at the following screen. 

![[Pasted image 20220407134135.png]]