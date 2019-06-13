# SmartHome
I have been creating a smart home slowly, adding bits and pieces from various manufacturers along the way. As I do, I'm integrating into a home Dashboard and extra automation to help me manage the house. 

This is the overall architecture: 
![Architecture Diagram](https://github.com/gwgorman/SmartHome/blob/master/GGHouse.png)

# Major functions: 
- Show MQTT Server Status
- Show Garage Door status (Open/Closed) and flash all LifX lights ORANGE when open
- Track and Show IBM Stock Price, display trend on a LifX light. Future: Only show color when asked by Alexa, otherwise leave light alone.
- Track and Show Upstairs temp, humidiy, baro from SenseHAT Pi. 
- Snoop on 433Mhz and display a few things I've found
- Show status from all my SmartThings devices
- Automatically turn on my office lamp when motion is detected in the office
- Track and Display Lewisville Lake, TX information
- Future: display next hour's forecast as a color on LifX when asked by Alexa (old function stopped working when WeatherUnderground killed their API. 
- Display my PiAware FlightAware screen
- Command a Pi with a camera to take a picture, run thru IBM Watson Image Recognition and display the results
- Future: Display select Blink cameras (I have 2 systems) and allow snapshots to be triggerd
- Future: Secure the dashboard, connect to a Domain Name and expose to the Internet
- whatever else I can think of
