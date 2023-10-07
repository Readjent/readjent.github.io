# Tax Policy Across the US
![](https://taxfoundation.org/wp-content/uploads/2022/04/TaxEDU-Three-Basic-Tax-Types-Video-Thumbnail.png)

As anyone who has filed their taxes knows, navigating tax policy can be quite a tricky prospect. Not only are there several different types of taxes, but also each geographical jurisdiction--
from state to county to city, can set their own differing tax rates that all compound on each other. This project endeavors to create a helpful tool to determine where in the U.S. a person's
total tax cost would be lowest, factoring their yearly income, expenditures, and any property they own.

## How it Works
For this project, the user will be presented with a map of the U.S., as well as a console with multiple fields to be filled out. The user would need to enter 
data about their yearly income, yearly expenditures, as well as the value of any real estate they own. Since housing prices can vary wildly by geographical region,
there will also be an option to set the real estate value to match the median housing cost of the area. Afterwards, a heatmap would be displayed to indicate which
parts of the U.S. would have the highest tax cost for the user; as well as displaying the gross annual tax cost. Filters could also be applied to only display sales, 
income, or property data.

## Integrating Tax Data
Using geocoding, data regarding the tax rates set by the state, county, and municipality of a given region would be integrated into the map. An additional calculation for 
federal income tax would also be added on for the purposes of the gross annual tax cost display.
### Income Tax Brackets
*Since several jurisdictions implement an income tax that varies by the bracket an individual's income falls into, an additional step would have to be implemented
to calculate the tax bracket of the user.**
### Property Tax and Median House Cost
Since a user would likely look at property tax for the sake of planning to buy future property, it would be pertinent to display the median housing cost
for a given geographical region; which would thus require an additional layer of data to be encoded.*

## Possible Additional Features
**If the scope of the project allows it, additional features could be added into the console:**
1. Additional tax types, such as gas taxes and tpp taxes
2. Checkboxes for tax credits and deductions
3. Functionality for calculating tax cost before and after marriage in a given jurisdiction

## See also
- [Three Basic Tax Types](https://taxfoundation.org/taxedu/educational-resources/primer-the-three-basic-tax-types/)
- [State Tax Levels in the US](https://en.wikipedia.org/wiki/State_tax_levels_in_the_United_States#)
- [Tax Credits and Deductions](https://www.irs.gov/credits-deductions-for-individuals)