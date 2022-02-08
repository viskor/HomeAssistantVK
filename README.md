# HomeAssistantVK

Home Assistant Automation Blueprints

This is going to be a collection of Home Assistant Blueprints that I made for my own home.

Improvements, comments, and feedback are more than welcome!

My first bp is un upgrade of the officiel blueprint of HA :
- [Motion light for use with switch](https://github.com/viskor/HomeAssistantVK/blob/main/VKMotion-switch.yaml)

For an integration with Start and stop hour (like 20h00 > 8h00 or 18h> 23h) 
- [VK Motion & Time Switch Version](https://github.com/viskor/HomeAssistantVK/blob/main/VKMotion-time-power.yaml)
- [VK Motion & Time Light Version](https://github.com/viskor/HomeAssistantVK/blob/main/VKMotion-time-light.yaml)


For Heating systeme, i have a NETATMO and he work with the "Window open, climate off" ( https://community.home-assistant.io/t/window-open-climate-off/257293 ) 


But no notification was send so i adapt a script (of Home OIT) for use google assistant chromecast:

- [VK Reminder to close windows-speaker mono window sensor](https://github.com/viskor/HomeAssistantVK/blob/main/VK-Reminder_googlespeak-mono.yaml)
- [VK Reminder to close windows-speaker duo window sensor](https://github.com/viskor/HomeAssistantVK/blob/main/VK-Reminder_googlespeak-duo.yaml)


Next upgrade for blueprint: 
- VKMotionTime : Auto off light at time2 or time 1, Multiple sensor selection, selection of day of week   
- VKReminder : Create a repeat mode with 1 timer
