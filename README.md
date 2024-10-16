# PLC-Based Control of Temperature and Humidity in a Greenhouse

**Objective:**

The project aims to design a smart greenhouse system using a Programmable Logic Controller (PLC) to automatically regulate the temperature and humidity within the greenhouse. The goal is to optimize plant growth by maintaining an ideal environment with minimal manual intervention.




**Key Components:**


1. Sensors:

    Temperature and humidity sensors (DHT series) are used to continuously monitor the environmental       conditions within the greenhouse.
    The system can use DHT11 or DHT22 sensors, which measure temperature and humidity and provide          digital outputs.


   
2. Actuators:

    Fan: Activates to circulate air and maintain a consistent temperature.
   
    Heater: Engages when the temperature drops below a defined threshold.
   
    Damper: Opens to release excess heat or closes to retain heat as necessary.
   
    Humidifier: Controls moisture levels by adding humidity when needed.



**System Features:**
   
  Automated Mode: In this mode, the system autonomously controls the greenhouse environment by           adjusting the fan, heater, damper, and humidifier based on sensor data.

  
  Manual Mode: Allows operators to manually control all aspects of the system, such as opening and       closing dampers or turning on/off the heater and humidifier.

  
  Remote Monitoring: The system supports remote access and control, allowing users to monitor       conditions and make adjustments from a distance.





**Control Logic:**

  The system uses a series of input and output signals, controlled by the PLC, to operate the       actuators. The PLC program is designed to:

  Adjust the fan, heater, and humidifier based on temperature and humidity thresholds.
    
  Provide alarms and fail-safes if conditions exceed pre-set limits (e.g., fire alarms, or sudden changes in temperature or humidity).



**Safety Features:**
    
  Alarms: Triggered when temperature or humidity exceeds defined safe limits.
  
  Fail-Safe Mechanism: Allows the system to continue operating safely even in the event of unforeseen issues like equipment failure.



Conclusion:
The report concludes that this automated PLC-based system provides an efficient, reliable method to control a greenhouse environment. It minimizes manual effort while ensuring optimal conditions for plant growth, with provisions for safety and remote monitoring.

