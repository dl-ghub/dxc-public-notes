## Universal Journal
The Universal Journal can undoubtedly be described as the heart of SAP S/4HANA—at least from an accountant's point of view. It offers the potential for a drastic simplification of processes in financial accounting and management accounting while simultaneously increasing the reporting functionality.

![[Pasted image 20220405142909.png]]

While in SAP R/3, the various tasks in Management Accounting (CO) and Financial Accounting (FI) were handled by special modules with their respective data structures, the new general ledger in SAP ERP already provided a certain simplification and consolidation. SAP S/4HANA accounting is now taking the radical step of integrating all requirements into one application with a common data model.

![[Pasted image 20220405143303.png]]

## Single Source of Truth
In the past, the various data structures and applications required a great deal of reconciliation work, for example, to show identical sales revenues and operating results in CO and FI in SAP ERP. The goal was to achieve a single point of truth, which could only be accomplished through hard work. With the Universal Journal in SAP S/4HANA, this goal is already reached at the starting point, so that you actually have a single source of truth that makes the reconciliation work obsolete.


## Benefits
Some benefits of the Universal Journal are summarised as follows:
- Data is presented in a common structure to make comparisons easier.
- All required currencies are provided
- A 360-degree view on objects of interest is presented (P&L + balance sheet + key performance indicators (KPIs))
- Ad hoc group reporting is possible with views of unconsolidated and consolidated figures
- With real-time reporting, up-to-date figures are available at every point in time
- A full audit trail is provided
- Legal requirements from a local and a group perspective are fulfilled
- The basis for management reporting at every needed granularity is given and can be easily enhanced via extension fields and extension ledgers.

## One Data Base and One Data Model for Accounting
The previous data sets for the general ledger, CO-PA, management accounting, asset accounting, and the material ledger are now integrated into one data model.
![[Pasted image 20220405143602.png]]

Benefits:
- One journal entry line item is used with full details for all applications
- Instant insight and easy extensibility are provided.
- Data is stored only once, reducing memory footprint and resulting in no redundancy
- No data transfer (e.g. settlement) between applications is required at period end
