# Asset Setup

It allows the user to create an asset hierarchy structure and configure the individual asset by configuring sensors and KPIs at the asset and component level.

## Recommendations

Following are the recommendations to create an asset hierarchy

- From the Enterprise level, the user can create a Product, Region, or Site. Note that defining the structure from Enterprise to Asset, once defined, the user needs to repeat for the rest of the hierarchy. Additional flexibility is planned for future releases. If the user decides to use Enterprise > Site1 > Asset1, then every other asset needs to follow the same structure (Enterprise > Site1 > Asset2 or Enterprise > Site2 > Asset3) would work without issue. If the user follows other structures (Enterprise > Region > Site3 > Asset4), it does not work.
- Under Product, the user can define Region (If not defined before) or Site.
- Under Region, the user can define Product (If not defined before) or Site.
- Under Site, the user can define Area or Asset.
- Under Area, the user can define Sub-Area or Asset.
- Under Asset, the user can define Component.


