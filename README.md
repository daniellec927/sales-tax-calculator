# Sales Tax Calculator (C++)

An interactive C++ program that computes the total price of a purchase including
sales tax. It prompts for a U.S. state, a purchase amount, and a date, then
applies that state's base rate, average local rate, and any special levy —
accounting for state sales-tax-holiday dates (when tax is waived).

## Build & Run
```bash
g++ -std=c++17 SalesTaxPaymentCalculator.cpp -o salestax
./salestax
```
Follow the prompts (state name, purchase amount, month, day, year). Invalid
input — an unknown state, a non-positive amount, or a bad date — is reported.
