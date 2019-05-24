# Selenium C Sharp Example

This is a basic example of using Selenium in Visual Studio with C# DotNetCore and MSTest.

This uses the following Nuget packages:

* DotNetSeleniumExtras.WaitHelpers Version="3.11.0"
* Microsoft.NET.Test.Sdk Version="16.1.0"
* MSTest.TestAdapter Version="1.4.0"
* MSTest.TestFramework Version="1.4.0"
* Selenium.Chrome.WebDriver Version="74.0.0"
* Selenium.WebDriver Version="3.141.0"

GoogleSearchExample.cs contains code for starting a Chrome browser, 
navigating to google.com, executing a search for 'Selenium HQ'
& asserting some values from the results page (see comments).

For more information please see my blog post here: https://blankstechblog.com/2019/05/23/cross-platform-selenium-with-dotnet-core/
