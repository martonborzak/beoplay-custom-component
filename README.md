# beoplay-custom-component
Custom component for Beoplay speakers in Home Assistant

1. Create a folder in your custom_components directory called beoplay.
2. Copy the files there. It should look like this: custom_components/beoplay/
3. Add a configuration in the `configuration.yaml` file

Example configuration:
```
media_player:
  - platform: beoplay
    host: 192.168.100.20
    name: Beoplay M5
  - platform: beoplay
    host: 192.168.100.22
    name: Beoplay S8
```
