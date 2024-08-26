# Simple Calculator Project*

**The calculator app** is a simple calculator that can perform operations such as addition, subtraction, multiplication and division.

Submitted by: **Iman**

Time spent: **7** hours spent in total

## User Stories

The following **required** functionality is complete:

* [ ] User can enter any values with any operations (+, -, * or /) and the calculator will show the outcome of the input.

The following **optional** features are implemented:

* [ ] Decimal numbers can be used for calculations

## Notes

I identified a bug where the decimal place, when used after clicking an operator, was mistakenly appended to the first operand instead of the second. I resolved this by modifying the inputDecimal function to ensure additional digits are added to the second operand.