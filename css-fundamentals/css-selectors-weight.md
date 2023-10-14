# CSS Selectors Weight/Power/Importance/Specificity - Written by Ahsan Mahmood - Zaions Youtube Channel - @ZaionsOfficial

## Here i have Explained what weigth each CSS selector gets and how we can properly calculate and confirm which CSS rule is going to apply to our html element

### Please do add comments to video if you see any mistake in this sheet

### Your will be able to get this reference sheet from (zaions.com/css-selectors-weight-sheet)[https://zaions.com/css-selectors-weight-sheet]

#### I have also created a short url for the sheet for you guys which is (zaions.com/css-sws)[https://zaions.com/css-sws] - sws = selectors-weight-sheet

## Okay Now Let's Get Started

- inline-css
  - Weight: 1000
  - e.g: <h1 style="font-size: 30px;"></h1>
- Tag Name
  - Weight: 1
  - e.g: h1
- ID
  - Weight: 100
  - e.g: #h1
- class
  - Weight: 10
  - e.g: .h1
- [attributeName] | [attributeName=attributeValue]
  - Weight: 10
  - e.g: [type] | [type='email']
- combinator selector
  - Weight: 10
  - e.g: ul > li
- pseudo-class
  - Weight: 10
  - e.g: p:first-child
- pseudo-element
  - Weight: 1
  - e.g: div::before
- "\*" (wild card | universal) selector
  - Weight: 0
  - e.g: \* { ...css-rules... }