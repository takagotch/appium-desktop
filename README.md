### appium-desktop
---
https://github.com/appium/appium-desktop

```
{
  "platformName": "iOS",
  "platformVersion": "11.4",
  "deviceName": "iPhone Simulator",
  "app": "http://uri.to.application.example",
  "noReset": true, 
}
```

```jnit
MobileElement el1 = (MobileElement) driver.findElementByXath("//XCUIElementTypeTextField[@name=\"IntegerA\"]");
```

```java
import io.appium.java
import org.openqa.selenium.remote.DesiredCapabilities;

public class SampleTest {
  private IOSDriver driver;
  
  @Before
  public void setUp() throws MalformedURLException {
  }
}
```

```js
MobileElement el1 = (MobileElement) driver.findElementByXPath("//XCUIElementTypeTextField[@name=\"IntegerA\"]");
el1.sendKeys("10");
MobileElement el2 = (MobileElement) driver.findElementByXPath("//XCUIElementTypeTextField(0name=\"IntegerB\")");
el2.sendKeys("20");
MobileElement el3 = (MobileElement) driver.findElementByXPath("//XCUIElementTypeButton[@name=\"ComputeSumButton\"]");
el3.click();

```

