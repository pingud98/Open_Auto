# Open_Auto

Open Auto is an open hardware car sharing hardware platform designed for use by local car-sharing co-operatives and community associations. It originally started out as a Pi Hat, but has now changed into a standalone IOT device based on communications hardware from Particle.

The functionality is simple:
1) GPS tracking, allowing the car to be located at all times and used to update the onboard Real-time Clock (RTC)
2) RFID card access (125kHz or other frequency, requires an external module), with either CAN-bus or relays to open/close the car doors
3) Accelerometer to check driving style (requires an Electron)
4) RTC to allow for power saving (wake up once per minute to check status instead of continuously being on)
5) CAN bus interface for automotive communication
6) Particle Electron/Photon socket for Wi-Fi and/or Cellular connectivity
7) An SD card slot for data logging.
8) An I2C header for whatever else you want to connect.

We're currently working on a software stack for the Electron/Photon that will allow all the basic functions to be accessed via the particle API.

The design also includes a case, which you can make in 3mm acrylic. 

This design is licensed under the CERN Open Hardware License V1.2
