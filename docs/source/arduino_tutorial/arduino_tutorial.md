# Arduino_tutorial  
------------------
This tutorial is based on Arduino UNO R3 and Nano!    


**Arduino basics  (Important):**  
If you don't have Arduino basics, you can follow the link to learn the basics:         
1. Learn about [UNO R3](https://docs.mosiwi.com/en/latest/arduino/A1D0000_uno_r3/A1D0000_uno_r3.html) briefly.     
2. Install the [Arduino IDE](https://docs.mosiwi.com/en/latest/arduino/resources/arduino_ide/arduino_ide.html).   
3. [Upload a blink code to UNO R3](https://docs.mosiwi.com/en/latest/arduino/A1D0000_uno_r3/A1D0000_uno_r3.html#programming-platform).   

```{tip}
The Nano is used in a similar way to the UNO R3, but select "Arduino Nano" when selecting the board type.   
```
![img](../_static/arduino/img/4img.jpg)      

## Wiring diagram
----------------- 
|  UNO or nano  |   Cube   |  
|      :--:     |   :--:   |  
|   5V or 3V3   |   VCC    |  
|      GND      |   GND    |  
|      13       |   SH_C   |  
|      10       |   ST_C   |  
|      11       |   DIN    |  

## Install the Arduino library file
-----------------------------------     
```{tip}   
The library files are downloaded in the "[Previous_tutorial](https://docs.mosiwi.com/projects/c1k0001/en/latest/previous_tutorial/previous_tutorial.html#download-library-file)" section!
```

Load the "Mosiwi-4x4x4cube.zip" file downloaded above into the arduino IDE:          
![Img](../_static/arduino/img/1img.png)       
Select the compressed library file to load:       
![Img](../_static/arduino/img/2img.png)

For other methods, see (Option): <https://www.arduino.cc/en/Guide/Libraries>      

## Use the example code in the library file
-------------------------------------------    
If you have successfully loaded the library file, you can open the example code in the library file in the arduino IDE as follows.   
![Img](../_static/arduino/img/3img.png)   

After opening the example, select the "Arduino UNO" or "Arduino nano" development board, then select the COMx port, and then upload the code to the development board.  

| 1 | 2 |    
| :--: | :--: |    
| ![img](../_static/arduino/img/5img.jpg) | ![img](../_static/arduino/img/6img.jpg) |     
| 3 | 4 |    
| ![img](../_static/arduino/img/7img.jpg) | ![img](../_static/arduino/img/8img.jpg) |   

------------
More arduino learning Resources: [Click me](https://docs.mosiwi.com/projects/c1k0000/en/latest/arduino_tutorial/basic_tutorial.html)

**End!** 
