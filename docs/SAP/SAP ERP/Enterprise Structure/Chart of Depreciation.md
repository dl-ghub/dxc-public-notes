## Chart of Depreciation Overview
Higher Level(s): [[Client]]
Lower Level(s): [[Company Code]], [[Depreciation Area]]

A chart of depreciation is an organisational object in S/4HANA that manages the depreciation and other valuation requirements in a system. This object contains one but usually multiple [[Depreciation Area|Depreciation Areas]], each providing different valuation options for fixed assets. 

Company codes are assigned to a chart of depreciation. In most cases, the company codes within a country are each assigned to the same chart of depreciation.

![[Pasted image 20220419104548.png]]

The chart of depreciation is positioned centrally because all asset processes are based on it. When asset master records are created for each company code, they inherit the chart of depreciation and related chart of accounts .


## Configuring the Chart of Depreciation
A new chart of depreciation should be created by copying an already existing chart of depreciation, such as the SAP-provided reference chart of depreciation, which contains predefined depreciation areas able to meet many local, country-specific requirements. 

Configuration Menu Path: Financial Accounting -> Asset Accounting -> Organisational Structures -> Copy Reference Chart of Depreciation/Depreciation Areas
- as
![[Pasted image 20220419104859.png]]
## Setting the Chart of Depreciation
Menu Path: Financial Accounting -> Asset Accounting -> General Valuation -> Set Chart of Depreciation

## Assigning a Chart of Depreciation to a Company Code
Menu Path: Financial Accounting -> Asset Accounting -> Organisational Structures -> Assign Chart of Depreciation to Company Code
![[Pasted image 20220419113422.png]]