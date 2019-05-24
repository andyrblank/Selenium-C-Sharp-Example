# Selenium C# Example

This is a basic example of using Selenium in Visual Studio with C# DotNetCore and MSTest.

This uses the following Nuget packages:

* [DotNetSeleniumExtras.WaitHelpers Version="3.11.0"](https://www.nuget.org/packages/DotNetSeleniumExtras.WaitHelpers/3.11.0)
* [Microsoft.NET.Test.Sdk Version="16.1.0"](https://www.nuget.org/packages/Microsoft.NET.Test.Sdk/16.1.0)
* [MSTest.TestAdapter Version="1.4.0"](https://www.nuget.org/packages/MSTest.TestAdapter/1.4.0)
* [MSTest.TestFramework Version="1.4.0"](https://www.nuget.org/packages/MSTest.TestFramework/1.4.0)
* [Selenium.WebDriver.ChromeDriver Version="74.0.3729.6"](https://www.nuget.org/packages/Selenium.WebDriver.ChromeDriver/74.0.3729.6)
* [Selenium.WebDriver Version="3.141.0"](https://www.nuget.org/packages/Selenium.WebDriver/3.141.0)

[GoogleSearchExample.cs](https://github.com/andyrblank/Selenium-C-Sharp-Example/blob/master/SeleniumExample/GoogleSearchExample.cs) contains code for starting a Chrome browser, 
navigating to google.com, executing a search for 'Selenium HQ'
& asserting some values from the results page (see comments).

For more information please see my blog post here: https://blankstechblog.com/2019/05/23/cross-platform-selenium-with-dotnet-core/
