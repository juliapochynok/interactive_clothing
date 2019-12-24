# Interactive Clothing Project

## Description
A simple clothing supplemented with a frame of intelligent control LED tapes(WS2812B) that change colour of lights and the pattern depending on certain metrics taken by the sensor(in current state - range-finder HC-SR04)

## How it works:
### Getting data to process

Сurrently we are using the rangefinder as one of the sensors that produces the information. However, in the nearest future we are planning to use other sensors that will give more accurate information about factors closer to human`s ordinary life.

### Displaying patterns
Depending on data we get our interactive clothing displays different patterns with different combinations of colours.
*not implemented yet*

## Materials that we use

### STM32F4Discovery microcontroller
![](https://www.waveshare.com/img/devkit/STM32F4DISCOVERY/STM32F4DISCOVERY-5.jpg)

### WS2812B Intelligent control LED tapes
![](https://nettigo.eu/system/images/2203/original.JPG?1495546386)

### Sensor - ( temporarily range-finder HC-SR04)
![](https://uawest.com/image/cache/product_images/original_images/1829_0-700x700.jpg)

## Our progress
### Done:
- got acquainted with the principles of diodes operation
- used Motion Detector to illuminate the diode depending on the presence of motion
- worked with one Intelligent control LED (WS2812B)
- got acquainted with the features of the color transfer of the diode
- we work with a rangefinder to illuminate the diode(not WS2812B) depending on the distance at which the object is located.
- we learn how to light up a certain number of LED on the tape 

### Working with:
- We are trying to set a specific color to the Intelligent control LED tape
- We are trying to change LED tape lighting colour depending on distance

### Should be done:
- change the sensor we use to get data ( to make a wider and more convenient range of data we can get)
- in accordance with the results of done work develop the mechanism of operation of the LED strip
- make all components of our project "smaller size", to make usage of IC easier and more comfortable


## Documentation

## Team
Sophia Kravchuk, Julia Pochynok, Sophia Haletska, Anastasia Liatska
