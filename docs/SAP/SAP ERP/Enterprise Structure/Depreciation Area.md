## Depreciation Area Overview
Higher Level(s): [[Chart of Depreciation]]
Lower Level(s): 

A depreciation area is an organisational structure object that defines the area for the valuation of fixed assets, based on specific sets or rules. Depreciation rules and the useful life of assets are maintained on the depreciation area level. 

### Portraying Valuation Frameworks
Each chart of depreciation represents a collection of depreciation areas, which define an asset valuation based on various requirements in the country. Usually, more than one depreciation area is needed because your organisation will probably need to comply with multiple valuation principles in several countries. For example, in the US, companies must valuate their assets based on US GAAP. Additionally, big international companies will need to valuate their assets according to IFRS. 

Prior to S/4HANA (i.e. ERP), maintaining all these parallel valuation frameworks was a cumbersome process that required running periodic programs that would post the differences between the non-leading and leading valuation in even further delta depreciation areas. 

https://dxc.percipio.com/books/072e4012-c992-4deb-ada6-de10b856461d

## Defining Depreciation Areas
Menu Path: Financial Accounting -> Asset Accounting -> General Valuation -> Depreciation Areas -> Define Depreciation Areas

![[Pasted image 20220419110409.png]]
![[Pasted image 20220419112921.png]]

**Configuration Fields**
Depreciation Area
- Number of the depreciation area. Typically, a two-digit code is used, except for the main book depreciation area, which normally is 1. 
- The numbering of your depreciation areas should be meaningful; for example, areas for local GAAP purposes could start with 2, while areas for local tax purposes could start with 3, and so on. 

Description
- Meaningful long and short descriptions of the depreciation area

Real Depreciation Area
- Determines whether the system will store the values of the depreciation area in the database. If so, the area is not a derived depreciation area.

Accounting Principle
- In this field, you link the depreciation area with an accounting principle, which is a method of valuation, such as IFRS or local GAAP. Based on the accounting principle, the system will automatically populate the target ledger group, which is linked to the accounting principle.

Cross-Syst. Depreciation Area
- A cross-system depreciation area is used to combine depreciation areas. This field consists of a key and a description without control parameters. 
- Note that, with S/4HANA, posting both APC (Acquisition and Production Costs) and depreciation in real time makes sense because then you won't need to run periodic programs to post adjustment entries to non-leading depreciation areas.

Posting in the General Ledger
- Area Does Not Post
	In this case, the depreciation area does not post to the general ledger; therefore, the depreciation area is for information purposes only.
- Area Posts in Real Time
	All postings in the depreciation are are posted to the general ledger
- Area Posts Depreciation Only
	Only the depreciation postings in the depreciation area are posted to the general ledger
- Area Posts APC Immediately, Depreciation Periodically
	Only the APC postings in the depreciation area are posted to the general ledger in real time. 

Value Maintenance
- In this section, you'll configure whether all, only positive, or only negative values are allowed for the various value categories, such as acquisition value, ordinary depreciation, net book value, and so on. 

Entries for Derived Depreciation Area
- These settings are applicable only for derived depreciation areas. In this section, you can set the depreciation area for reporting purposes only and define it as a derived depreciation area. In this case, you'll need to define how it derives its values by entering the depreciation areas from which it takes values with positive signs and areas from which it takes values with negative signs. For example, you can define an area that is equal to a specific area minus another area.