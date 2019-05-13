# City Light from Windmills

City Light from Windmills is a interactive and visual art that displays how our city turns up the lights with electricity generated by windmills. The user can light up city building by blowing windmills and change its color/brightness. Each windmill is equipped with a photo interrupter to estimate the rotational speed of axis. Arduino interprets the rotational speeds of windmills and map them to back-light LED strips to illuminate city buildings. The colors and brightness of LEDs are adjusted according to the rotational speeds of each windmill.

![alt tag](https://raw.githubusercontent.com/ppp9494/CMSC838_MP2_CityLightfromWindmills/master/parts_desc.png)

Source Code
-----
  Main.ino  -> Arduino Main source code
  
  Adafruit_NeoPixel.cpp -> Neopixel LED API Wrapper
  
  Adafruit_NeoPixel.h -> Neopixel LED API Wrapper

Hardware Component
-----
  [Adafruit Neopixel LED Strip] (http://www.adafruit.com/category/168?gclid=CjwKEAiAmuCnBRCLj4D7nMWqp1USJABcT4dfRb3MFvUZVDyFr7Tg5PLFnIpEN-a3gsF8bBOPL3o8ohoCdofw_wcB)
  
  [Sparkfun Photo Interrupter] (https://www.sparkfun.com/products/9299)
  
  [Arduino Board] (http://Arduino.cc)


Running Environment
-----
  General Arduino Board
  
Test
-----
  Build on Windows8/64bit
  Tested on Arduino Leonardo Rev.3
  

  
  


