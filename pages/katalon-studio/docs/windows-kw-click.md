---
title: "[Windows] Click"
sidebar: katalon_studio_docs_sidebar
permalink: katalon-studio/docs/windows-kw-click.html
---
> Starting from **Katalon Studio version 7.0.0**, Katalon Studio Enterprise users can run a test on a Windows desktop application.

## click

* **Description**: Perform a left-clicking action on the  Web element found by using the locator value of the given Windows object.
* **Keyword name**: click
* **Keyword syntax**: Windows.click(windowsObject)
* **Parameter**: windowsObject
  * Description: An object describing the locator and locator strategy to find a Windows element.
  * Parameter Type: WindowsTestObject
  * Mandatory: Required
* **Example**:

``` groovy
 "Click on the Close button"
 Windows.click(findWindowsObject("Object Repository/CloseButton"))
```
