 **SMART FIRE & GAS SAFETY SYSTEM**  
 **Project Title**  
       Smart Fire & Gas Safety System using Arduino and ESP-01  
 **Introduction**

* Fire and gas leakage can cause serious damage.  
* Early detection is important for safety.  
* This project detects fire, gas leakage/smoke and high temperature.  
* When danger is detected, it automatically turns ON a fan and buzzer.  
* ESP-01 is used to send an alert through Wi-Fi.

**Problem Statement**    
          Gas leakage and fire incidents may not be detected immediately, which can lead to safety hazards and property damage. A smart system is needed to continuously monitor gas and fire conditions, provide a local alarm, and send an instant alert to the user's mobile phone.  
**Objectives**

* To detect flame using a flame sensor.  
* To detect gas/smoke using MQ-2.  
* To monitor temperature using DHT11.  
* To activate a buzzer during danger.  
* To automatically control a fan using a relay.  
* To send an alert through ESP-01 Wi-Fi.

**Components Used**

* Arduino UNO  
* Main controller  
* MQ-2 Sensor  
* Gas/smoke detection  
* Flame Sensor  
* Fire/flame detection  
* DHT11  
* Temperature measurement  
* 16×2 I2C LCD  
* Display  
* Relay Module  
* Fan control  
* DC Fan  
* Ventilation  
* Buzzer  
* Alarm  
* ESP-01  
* Wi-Fi communication  
* 12V DC Fan  
* Cooling/ventilation

**Working Principle**  
      Sensors → Arduino → Decision → Alert

* MQ-2 continuously checks gas/smoke level.  
* Flame sensor checks for fire.  
* DHT11 measures temperature.  
* Arduino compares sensor values with preset limits.  
* If a dangerous condition is detected:  
* Buzzer turns ON.  
* Fan turns ON through relay.  
* Warning is shown on LCD.  
* ESP-01 sends an alert.  
* When the condition becomes normal, the buzzer and fan turn OFF.


**Advantages** 

* Automatic fire detection.  
* Gas leakage detection.  
* Temperature monitoring.  
* Automatic fan control.  
* Audible warning using buzzer.  
* Wi-Fi-based alert.  
* Low-cost prototype.

**Block Diagram**  
**![](block.jpg)**  
**Working ![](work.jpg)**
**Schematic Diagram![](ima.jpg)**

