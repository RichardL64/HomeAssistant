# Home Assistant related

## Tuya Local interface definition: herschel-t-mt_thermostat.yaml
[Tuya Local](https://github.com/make-all/tuya-local) integration interface deinfition for the [Herschel IR Heater Thermostate T_MT](https://www.herschel-infrared.co.uk/product/t-mt-wifi-thermostat/?srsltid=AfmBOoogAK3X89Li8mPwR83tkUp4cToMckao-AZdy6TuE4WAn8qOhCBE)

![Thermostat](https://github.com/RichardL64/HomeAssistant/blob/main/Herschel%20T-MT.jpg)


At the time of writing this thermostat was correctly identified by Tuya Local as a Tuya object but no matching config file was available.
I developed this interface and shared with the the Tuya integration project July 2025.

### Store the YAML in folder:

/homeassistant/custom_components/tuya_local/devices/**herschel_t_mt_thermostat.yaml**

### Functionality
Appears as a thermometer type.

All configuration, except programming functioning via Home Assistant:
![Config](https://github.com/RichardL64/HomeAssistant/blob/main/Herschel%20Config.jpg)


