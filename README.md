# CodeTest
Demo Project
ASP.Net MVC application.
The application should let the user pick widgets from a given list, enter quantity and state.
When the user clicks calculate button, it should display discount, sales tax and total price.
All Widgets should have a name, base price, and discount indicator (true/false).
Widgets are given a discount of 10% if the discount indicator is true.
The total price of a widget should be determined by adding the base price - discount (if applicable) + tax.
Tax is calculated based on the currently selected state.
All states have a 5% flat tax rate except for TX and FL (which have no  tax rate of 0%).
Store the data in memory or use Microsoft SQL Server Compact 4.0 which can be downloaded from https://www.microsoft.com/en-us/download/details.aspx?id=17876.
Visual Studio, Community Edition from here: https://www.visualstudio.com/vs/community/
Use dependency injection and layered/hexagonal architecture.
Use dependency injection library you are familiar with.
Unit tests requied.
MSTest or any xUnit testing framework.
Provide some examples of mocking in your unit tests. Choose any mocking library.
