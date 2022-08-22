# ILI9341 2.8" SPI TFT LCD Display Touch Panel 240X320

#Links
# Amazon Link Display https://www.amazon.com/dp/B094N26Q1L?psc=1&ref=ppx_yo2ov_dt_b_product_details
# Amazon Link ESP32 https://www.amazon.com/dp/B08PNWB81Z?psc=1&ref=ppx_yo2ov_dt_b_product_details
THIS WILL ONLY WORK ON AN WEMOS D1 MINI32

Enter your own informaiton for your devices.

substitutions:
  $esp_name: "bedroom-temp-controller"
### PAGE 1 ###
  $thermostat: "climate.bedroom_thermostat"
### PAGE 3 ###
  $alarm_name: "alarm_control_panel.alarmo"
  $alarmcode: "!secret alarm_code"   
### PAGE 2 ###
  $device_1: "cover.bedroom_blinds_1"  
  $device_1_name: "North"
  $device_1_call_service_up: "cover.open_cover"  
  $device_1_call_service_down: "cover.close_cover"    
  $device_2: "cover.bedroom_blinds_2"
  $device_2_call_service_up: "cover.open_cover"  
  $device_2_call_service_down: "cover.close_cover"     
  $device_2_name: "East"  
### PAGE 4 ###
  $media_player: "media_player.sonos"    
### PAGE 5 ###  
  $sound_device_1_call_service: "switch.toggle"  
  $sound_device_1: "switch.sonos_sub " 
  $sound_device_1_name: "Bass "   
  $sound_device_2_call_service: "switch.toggle"  
  $sound_device_2: "switch.sonos_sonosf_surround_enabled" 
  $sound_device_2_name: "urrond Sound "     
  $sound_device_3_call_service: "switch.toggle"  
  $sound_device_3: "switch.livingroom_projector "   
  $sound_device_3_name: "Projector "     


![Page 1](https://user-images.githubusercontent.com/23288746/185841792-6305a630-70eb-4cd7-b8f3-338195abdad5.JPG)
![Page 2](https://user-images.githubusercontent.com/23288746/185841812-53952414-9894-4e98-819f-8541263fe14a.JPG)
![Page 3](https://user-images.githubusercontent.com/23288746/185841833-52bda7e2-830a-454b-aded-5f6bb7c85cae.JPG)
![Page 4](https://user-images.githubusercontent.com/23288746/185841881-3549b342-13cd-485c-8f23-b541200ebe17.JPG)
![Page 5](https://user-images.githubusercontent.com/23288746/185841869-2df35801-fb35-4cf2-82bc-4d98607d19c1.JPG)


