---
title: "[Windows] Get Driver"
sidebar: katalon_studio_docs_sidebar
permalink: katalon-studio/docs/windows-kw-get-driver.html
---
> Starting from **Katalon Studio version 7.0.0**, Katalon Studio Enterprise users can run a test on a Windows desktop application.

## getDriver

* **Description**: Get the current Windows Driver.
* **Keyword name**: getDriver
* **Keyword syntax**: Windows.getDriver()
* **Return Value**
  * Description: The current Windows Driver
  * Parameter Type: WindowsDriver
* **Example**:

``` groovy
"Start the note pad application"
Windows.startApplication('C:\\Windows\\System32\\notepad.exe')

"Get the application title"
Windows.getDriver().getTitle()
```
