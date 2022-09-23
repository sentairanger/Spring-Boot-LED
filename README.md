# Spring-Boot-LED

## Introduction

This is a Spring Boot Application that uses Diozero to blink an LED. Click [here](https://www.diozero.com/) for more info. When you press the button the LED blinks four times. To run this application make sure to have Maven installed. Click [here](https://maven.apache.org/install.html) to learn more. After that you can build the application with `mvn package`. Change to the target directory and then run `java -jar -DPIGPIOD_HOST=<ip-address-of-pi> demo-0.0.1-SNAPSHOT.jar`. Then go to `localhost:8080/home` and then press the button. This will work with any Pi.

![app](https://github.com/sentairanger/Spring-Boot-LED/blob/main/led.png)
