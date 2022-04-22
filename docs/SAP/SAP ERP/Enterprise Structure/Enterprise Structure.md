## Client
see [[Client]].

The client describes the technical framework of the system and is therefore the highest organisational element. All other levels of enterprise structure are located within a client. 


## Company (Trading Partner)
Intended by SAP in the system for a legal entity. It therefore describes a business organisation for which accounting must be performed and a balance sheet must be drawn up for legal reasons. 

**Similar to the client as a technical framework, the company conceptually represents a framework within which various organisational elements relevant to accounting can be defined. Therefore, basic elements for accounting, such as the chart of accounts, aren't defined on a company level.** 



## Company Code
The company code is the central organisational element of financial accounting in SAP S/4HANA. Each posting must be assigned to a company code. The company code can also be regarded as a building block in SAP S/4HANA. With this entity, accounting is connected to other applications. 



## Controlling Area
Roof of Umbrella. 

The controlling area identifies a self-contained organisational structure for which costs and revenues can be managed and allocated. It represents a separate unit of cost accounting. One or more company codes can be assigned to a controlling area, which enables you to carry out cross-company code cost accounting between the assigned company codes. however, this is only possible if the assigned company codes and the controlling area all use the same operating chart of accounts. 



## Credit Control Area
The credit control area serves as the main hub where decisions on customer credit are made. It specifies and checks the limit for each individual customer in both accounts receivable and sales and distribution. 

This can be done in one of two ways: a *decentralised* approach or a *central management* approach. In the former, a separate area is assigned to each company code. This allows credit to be awarded within a singular relationship.

But sometimes a customer will be involved with multiple company codes. This is where the central management approach comes into play. This combines all the different iterations of the same customer within different company codes into one control area, streamlining the credit checking and assigning process. 



## Profit Centre
While segments are used for external reporting, profit centres are internal units. They allow better controlling because you can follow the money in each unit and assign responsibility in accordance with results. Likewise, profit centres that are doing poorly are easier to identify and correct because their inefficiencies aren't easily masked by the surplus of a well-performing group. 



## Segment
Segments are divisions of a company that create revenue. Per GAAP and IFRS, you must be able to provide a balance sheet at the segment level. by identifying segments in SAP FI, you can easily create the necessary financial statements for external reporting requirements. 



## Functional Area
Functional areas allow you to assign costs to specific areas within the business - things like administration, sales, production, and so on. From there, it's easy to create profit and loss statements for each aspect of the business, allowing you to dig in and figure out where costs are bleeding and where you can make more. 



