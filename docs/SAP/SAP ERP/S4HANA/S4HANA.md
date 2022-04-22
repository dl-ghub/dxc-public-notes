## S/4HANA
SAP's newest ERP product. A complete rewrite of SAP ECC, revolving around the use of [[HANA]] as the central in-memory database. Unlike all previous SAP ERP products, S/4HANA will only work with HANA as its database. 

It provides organisations with software that addresses their business requirements across 26 verticals (i.e. niche markets). 

SAP S/4HANA comprises the S/4HANA Enterprise Management Digital Core, the component closest in scope to the SAP ERP (ECC) solution, and various lines of business (LoB) solutions, which are generally cloud solutions that are SAP products gained through mergers and acquisitions. 

![[Pasted image 20220303115333.png]]


## Capabilities
**Procurement**
- Provides insight into purchasing operations, streamlines operational purchasing, automates contract management and sourcing, centralises procurement processes, reduces supply chain risk, manages commodity procurement, etc.

**Sales**
- Drive and manage sales performance, supports sales professionals and sales managers, maximises revenue with optimised sales processes for contract and order management, etc.

**Supply Chain**
- Provides more accurate commitment dates, achieves more streamlined warehouse management, optimises inventory processes for optimal inventory levels, integrates transportation management, etc.

**Manufacturing**
- Supports complex assembly execution, improves production planning, supports seamless manufacturing engineering, and accelerates manufacturing operations, including enhanced quality management

**R&D and Engineering**
- Improves product development and project control, as well as helping achieve effective management of enterprise-wide projects, better product lifecycle management, and improved efficiency through requirement-driven processes. 

**Finance and Asset Management**
- Simplifies accounting processes and financial close, enables improvements to the treasury and financial risk processes, provides support for collaborative financial operations, helps simplify real estate management, etc.

**Professional Services**
- Optimises engagement profitability, achieves better staffing levels, helps capture time sheets faster with simplified entry, streamlines quote-to-cash processes, reimagines bid management processes, etc.

**Cross-Functional Capabilities**
- Cross-functional capabilities are used in human resources, asset operations and maintenance, and more

**Industry Capabilities**
- Industry capabilities are used across 28 industries, such as automotive, consumer, retail, mill, chemicals, and oil and gas


![[Pasted image 20220308093632.png]]

## Benefits
**[[Universal Journal]]**
- ![[Pasted image 20220405142821.png]]
- While in SAP R/3, the various tasks in Management Accounting (CO) and Financial Accounting (FI) were handled by special modules with their respective data structures, the new general ledger in SAP ERP already provided a certain simplification and consolidation. SAP S/4HANA accounting is now taking the radical step of integrating all requirements into one application with a common data model. 


## Editions
See: [[Deployment Models]]

![[Pasted image 20220303115140.png]]

NOTE: Hybrid Deployments
- The hybrid operating model enables you to combine the characteristics of the on-premise and cloud operating models. For example, core areas of your enterprise, where you want a high degree of control and a high level of flexibility, can be operated on-premise, while other enterprise areas can be operated in the cloud as common industry standards are sufficient. 
- Especially useful if you have complex geographical structures or need distributed systems. 
	- For example, you can have on-premise systems for a central ERP for headquarters where the corporation consolidates and reports financial results, and a cloud system for smaller or dedicated units focusing on sales and exploration. 


## User Interfaces
See: [[S4HANA User Interfaces]]

SAP GUI
- For on-premise SAP S/4HANA, SAP continues to offer classic access via the SAP GUI, which must be installed locally on the computer. 
- From a company's perspective, the SAP GUI can also be advantageous because employees don't need access to the Internet and can work only in the company network. 

Web GUI
- An easier and more convenient alternative is to access via the web GUI. All you need is a browser, the URL, and access authorisation. This access is also possible via mobile devices.

SAP Fiori
- This replaces the traditional transaction codes of the SAP GUI with a web-based UI.
- Fiori allows the concrete role and working environment of the respective user to be taken into account. The user will be assigned to business roles, such as general ledger accountant. To the business roles, specific apps are assigned. Tiles for apps that are specific to your business role appear when you access the system. 


## App Classifications
Regarding the function of the apps, SAP offers the following three types:

**Transactional Apps**
- These apps perform business process transactions or maintain master data. 
- Example Apps: Post General Journal Entry, Manage Supplier Invoice, Manage Cost Centre, and Post Activity Allocation.
- The master data transactional apps are especially important because they provide a more user-friendly way for reviewing, creating, and changing master data by downloading and uploading. Many approval apps are personalised to the specific user and offer the ability to review, confirm, or reject documents when the user has the approver role (e.g., the time sheet approval in the project manager role).

**Analytical Apps**
- These apps are used to display real-time analytics on actual and plan data, including KPIs. There are numerous examples for these useful apps. These apps provide a drag and drop method for pulling in general ledger dimensions for reporting on line item or balance details. As mentioned, in principle, all Universal Journal fields are now available as reporting dimensions. 
- Report results can be downloaded to Excel and then converted to a graph for quick visual analysis. In addition, a report-to-report interface is available that allows further detail analysis with a different view.

**Fact Sheet Apps**
- These apps are used to display key facts about master data and to navigate directly to associated master data or business transactions. Fact sheet apps allow you to drill down to display or edit associated master data and relevant business transactions.
- A good example is the Customer 360° View app, which contains customer master data and provides a direct link to key contacts, quotations, sales orders, contracts, customer returns, and fulfilment issues. This dashboard is a powerful tool for users who need a quick overview of the customer's status.


### Accompanying Lines of Business (LoB) Solutions
- [[Ariba]]
- [[Concur]]
- [[SuccessFactors]]
- [[Fieldglass]]
- [[SAP Customer Experience]]
- 