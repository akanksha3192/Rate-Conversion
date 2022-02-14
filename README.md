# Rate-Conversion
The project tests the multiple converison rates on a website

1.Introduction : 

This code has acceptance test automated to tests the conversion rates for multiple currency on website http://www.xe.com/currencyconverter/.
The tests has to be iterated over 5 sets of input data.

2.Resources
The program has been developed using Eclipse Java EE IDE for Web Developers version Neon.1a Release (4.6.1) and Selenium WebDriver Language Binding 3.0.1 for Java on windows 8.1. and TestNG framework.

3.Approach
There is only 1 test case:TestCurrencyConversion()

Test steps :
Go to http://www.xe.com/currencyconverter/.
Input the base(from) currency.
Input the counter(to)  currency.
Click on submit button and verify teh results on next page.


Test Solution :
Tests  build using maven build tool.
TestNG framework used for unit testing and test reporting.
Assertions are used to verify the test steps.


