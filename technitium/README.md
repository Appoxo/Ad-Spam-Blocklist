# Technitium list

This list contains entries for allowed and blocked services and endpoints

## Style guide

### Syntax

- block (incl. all subdomains) -> ||domain^
- allow (overrides blocks) -> @@||domain^

### Formatting

#### What to where

The list for domains is split in two sections.  

- Section A: big multi-national corporations like Google (Alphabet), Facebook (Meta) and so on.
- Section B: Anything else that is not as big.

Which entry belongs to which category may shift as I deem appropriate.

#### How and where to split the sections

Some stuff is very specific like services used for xbox belong (to my interpretation) to microsoft. Game specific domains belong to the main owning body (e.g. HQ or subsidiary).  
3rd party services used by a company (e.g. AWS-domains) should be added to the specific service rather than the actual one (e.g. `Amazon - AWS`)  
Every section has to be divided by: `! =============================`  

#### Commenting

|Level|Purpose|Example|
|-|-|-|
|`!`|Name of the company|`! Microsoft`|
|`!!`|Subsidiaries|`Microsoft - XBOX`|
|`!!`|Notes/Reasoning|`!! Notes: XYZ`<br>`!! Reasoning: Excessive telemetry`|
|`!!!`|Subsidiaries of subsidiaries or products|`!!! XBOX - Halo Infinite`|

##### Grouping

```txt
! Headquarter Company (e.g. Microsoft)
-> Entries for domains directly related to the owning company

!! HQ Company - Subsidiary (e.g. XBOX)
-> Entries that belong more to the subsidiary than to the HQ

!!! XBOX - Halo Infinite
-> Entries specific to the product or service

! =============================

! Headquarter Company (e.g. Alphabet)
-> Entries for domains directly related to the owning company

!! HQ Company - Subsidiary (e.g. Google)
-> Entries that belong more to the subsidiary than to the HQ

!!! Google - Adsense
-> Entries specific to the product or service

!! HQ Company - Subsidiary (e.g. Youtube)
-> Entries that belong more to the subsidiary than to the HQ
```

### Example

```txt
! Google (Alphabet)
!! Reasoning: Google search
@@||google.com^

!!! Google - AdSense
!! Reasoning: Fuck ads.
||adsense.google.com^

!! Google - Youtube
||youtube.com^

! =============================

! Meta
!! Notes: Fuck Meta
||meta.com^

!! Meta - Facebook
!! Reasoning: Fuck facebook even harder
||facebook.com^

! =============================

! Microsoft
!! Notes: Microslop
@@||microsoft.com^
!! Microsoft - XBOX
||xbox.com^
!!! XBOX - Halo Infinite
(...)

!!! XBOX - Minecraft
(...)
```
