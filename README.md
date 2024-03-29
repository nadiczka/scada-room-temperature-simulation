# SCADA-room-temperature-simulation

### Project created during studies on University of Science and Technologies in Krakow.

## Description:
Scada application to supervise and simulate running of the heating room the whole year.	The built assures a set of automatically operated two heaters and one air-conditioner during all seasons. Alarm should is defined as power supply failure.

Project was made in the AVEVA InTouch HMI application. This is the world’s most popular HMI/SCADA system for visualization and control of production processes.

## Description

![Sample visualisation](https://github.com/nadiczka/SCADA-room-temperature-simulation/blob/main/readme_files/Sample%20visualisation.png?raw=true)

Outside Temperature can be chosen by four buttons . Each button is labelled with a different season and changes temperature to the mean temperature in this season and is:
-	17°C in spring
-	28°C in summer
-	12°C in autumn
-	2°C in winter

![Season simulation](https://github.com/nadiczka/SCADA-room-temperature-simulation/blob/main/readme_files/Season%20simulation.png?raw=true)

Set Temperature can be changed by slidebar. The possible set temperature range in the room is from 10°C to 30°C. When inside temperature differs from set temperature by offset ( +/- 0.5°C)  

![Set temperature slider](https://github.com/nadiczka/SCADA-room-temperature-simulation/blob/main/readme_files/Set%20temperature%20slider.png?raw=true)

Inside temperature - actual temperature inside the room. Calculating the inside temperature also includes the impact of outside temperature.

Inside temperature is shown in the left upper corner of the room:

![Inside temperature](https://github.com/nadiczka/SCADA-room-temperature-simulation/blob/main/readme_files/Inside%20temperature.png?raw=true)

Outside temperature impact visualisation:

![Outside temperature impact](https://github.com/nadiczka/SCADA-room-temperature-simulation/blob/main/readme_files/Outside%20temperature%20impact.png?raw=true)

Power supply can be turned off and on by the switcher. Turning on the power supply has an additional security system. When the user wants to switch on the power supply, he is prompted to login. Only after successful login he is able to turn on the power supply.

![Power supply](https://github.com/nadiczka/SCADA-room-temperature-simulation/blob/main/readme_files/Power%20supply.png?raw=true)

Alarm is triggered when the difference between temperature inside the room and the set temperature is greater than 2°C and the power supply is off.

![Alarm](https://github.com/nadiczka/SCADA-room-temperature-simulation/blob/main/readme_files/Alarm.png?raw=true)

Plots present changes of inside temperature, outside temperature and set temperature over time. 

![Plots](https://github.com/nadiczka/SCADA-room-temperature-simulation/blob/main/readme_files/Plots.png?raw=true)
