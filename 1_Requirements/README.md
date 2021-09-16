# Requirements
## Objective
The purpose of this project/activity is to develop a user-friendly heating system for vehicle seats and control the heating area of ​​individual seats.
## Introduction
Vehicle seat heating or seat heating monitoring systems can generate mild heat in the seat. When the passenger is seated, the passenger needs to set the temperature of accordingly (this tells us that the passenger has turned on the heater). Based on these factors, our controller generates heating power for the seat. 
Then the LCD display should display the seat heating value provided by the passenger via the knob. Our project usually prefers European countries, 
,where the temperature is too low.
## Feature

+ The system uses Sensors to access the information about the paasenger is seated or not.
+ Each seat should have a nobe to control/monitor the range of heat.
+ A LCD display shows the temperature of Seat heater.
+ Low cost
# SWOT analysis - Strength, Weakness, Opportunities and Threats
## Strengths

+  Seats with individual heating systems.
+  The temperature range can easily be changed.
+  Easy to use. 
+  Low cost and robust system.
## weakness

+  Usually recommended for countries with extreme cold temperatures.
+  During this process, the engine needs to be on.
+  The vehicle must have a greater number of sensors if it has a greater number of seats.
## Threats

+  In high temperatures, there are fewer opportunities to use.
+  The seat can't be turned on before there is someone sitting on it.
# 4W's AND 1H
## What
+ This project deals with providing mild heating facility to passengers via their seats.
## Where
+ An interest in automobiles and the automotive industry is preferred
## Why
+ To maintain HEALTH in normal/stable state.
## When
+ At low temperature regions
## How
+ By generating a variable heat
# High level and low level Requirement

# High level Requirement 
|ID	  |Description                                                                                               |	 Category|	  Status   |
|-----|----------------------------------------------------------------------------------------------------------|-----------|-------------|
|HR01	|Sensor should give output(LED Turn on or Off)whether the person is seated or not in the vehicle           |  Automatic|	IMPLEMENTED|
|HR02	|Temperature sensor should toggle the temperature	                                                         |  Automatic|	IMPLEMENTED|
|HR03	|Temperature is beyond threshold then turn Off or on AC                                                    |  Manual	 |  IMPLEMENTED|  
|HR04	|display Temperature Value on LCD Screen                                                                   |  Automatic|	IMPLEMENTED|
|HR05	|Exit from the system when Vehicle is not moving	                                                         |  Automatic|	IMPLEMENTED|

# Low level Requirement
|ID  |Description		                                                            |Status      |
|----|--------------------------------------------------------------------------|------------|
|LR01|	Sensor output(LED Turn on or Off) will be in boolean form either 0 or 1	| IMPLEMENTED|
|LR02|	System will tell user that temperature is switching		                  | IMPLEMENTED|
|LR03|  user have to turn on or off the vehicle AC		                          | IMPLEMENTED|
|LR04|	System will display the temperature value inside the vehicle		        | IMPLEMENTED|
|LR05|	System will stopped working once vehicle is Stopped		Not               | IMPLEMENTED|
