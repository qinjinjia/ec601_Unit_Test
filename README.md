# EC601_Assignment 5 Unit Test:thumbsup::thumbsup::thumbsup:
## Brief Introduction :sunglasses:
  Hello Everyone! :trollface::trollface::trollface::trollface:
  
  This is the page for **EC601(Fall 2017) A1 Assignment 5 Unit Test** 
  [@github/qinjinjia/ec601_unit_test](https://github.com/qinjinjia/ec601_Unit_Test)
  
  The Author: :boy: **Qinjin Jia** qjia@bu.edu   :point_right:[@github/qinjinjia](https://github.com/qinjinjia)
  
  **The Unit Test Assignment is based on [EC601 HW2 Mini Project](https://github.com/qinjinjia/ec601_miniproject)**
      
  **Link:link:[https://ec601-hw2-task1-publish.firebaseapp.com](https://ec601-hw2-task1-publish.firebaseapp.com)** 
  
  **Link:link:[https://ec601-hw2-chat.firebaseapp.com](https://ec601-hw2-chat.firebaseapp.com)**
     
  :mailbox_closed:Please feel free to contact me, if you have any suggestions or concerns.
  
  
## :sun_with_face: **Task 1 - Test Cases**
   
**1) Generate your own test cases.**

**2) Run your own black box testing.**
  
  **Test Case Sheet Link:point_right: [Qinjin Jia's Resume Test Case Sheet.xlsx:link:](https://github.com/qinjinjia/ec601_Unit_Test/blob/master/Qinjin%20Jia's%20Resume%20Test%20Case%20Sheet.xlsx)** 
  
  Screenshot of the Test Case Sheet:
  
  <img src="https://github.com/qinjinjia/ec601_Unit_Test/blob/master/Unit%20Test%20Screenshot.png" width="400" height="200">

## :full_moon_with_face: **Task 2 - Automated Test**
  
**1) Run an automated test, e.g., AWS test farm and monkey test.**

**2) Interpret the results.**

**Due to the APP developed in HW2 is the Resume Website**
**[CrossBrowserTesting](https://app.crossbrowsertesting.com/test-center) is used for the automated test**

The automated test tests the website on two differnt platforms: **Mac Safair(version 11) and Window 10 Chrome**

[Script for Web automated Test on Mac Safari](https://github.com/qinjinjia/ec601_Unit_Test/blob/master/webunittest_chrome.py)

```#python
        caps['name'] = 'Qinjin Jia's Resume'
        caps['build'] = '1.0'
        caps['browserName'] = 'Safari'
        caps['version'] = '11'
        caps['platform'] = ''
        caps['screenResolution'] = '1366x768'
```

[Script for Web automated Test on Window 10 Chrome](https://github.com/qinjinjia/ec601_Unit_Test/blob/master/webunittest_safair.py)

``` #python
        caps['name'] = 'Qinjin Jia's Resume'
        caps['build'] = '1.0'
        caps['browserName'] = 'Chrome'
        caps['version'] = '61x64'
        caps['platform'] = 'Windows 10'
        caps['screenResolution'] = '1366x768'
```
