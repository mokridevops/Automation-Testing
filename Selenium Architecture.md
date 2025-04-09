
#Selenium Architecture


![image](https://github.com/user-attachments/assets/803e39f1-aff1-4e60-8ffa-e822fd7a3a10)


JSONWireProtocol

All implementations of webdriver communicating with the browser is through a common wire protocol - defines a Restful Web Service - using JSON over HTTP.

So, what ever you do on Selenium - lets say - driver.findElement - it is making an API call over HTTP.

