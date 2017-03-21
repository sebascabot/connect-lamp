# connect-lamp

Cheap way to connect a lamp to the internet

# Hardware

- ESP module (Ex. NodeMCU)
- SolidState relay
  - ex. https://www.aliexpress.com/item/5V-1-Channel-OMRON-SSR-G3MB-202P-Solid-State-Relay-Module-240V-2A-Output-with-Resistive/32310604393.html
  - ex. https://www.aliexpress.com/item/25DD-SSR-input-3-32VDC-load-5-110VDC-DC-single-phase-DC-solid-state-relay/32267494300.html
- DC-DC stepdown (ex. Input 5-25, output 3.3)
- External power supply (ex. output 5v)

# Software

WiFi connection to owner AccessPoint.
Web Server, exposing an API to toggle on and off the lamp.

# Extra

Can we modulate the ON/OFF with a PWM frequency to simulate a dimmer ?
Can we use a triac.
