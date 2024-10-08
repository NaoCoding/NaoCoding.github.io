---
title: "TPTRS-MQTT"
date: 2024-08-15
draft: false   
tags: ["Side Project", "MQTT", "GUI", "PyQt"]
---
# TPTRS-MQTT

[TPTRS-MQTT](https://github.com/NaoCoding/TPTRS-MQTT) is a project written with **PyQt5** and **MQTT** server, <br> the final project of [Data Science &amp; Communication 2024](https://web.ntnu.edu.tw/~cw/icoil/) NTNU. <br><br>

The default setting of the MQTT broker located at **NTNU**(National Taiwan Normal University), <br>however we can't assume that the MQTT broker will keep working after the course ended.<br><br>

To run the server with your own MQTT broker, edit the IP address in **server.py** and **client_mqtt.py**.

---
### How to run the project

Execute **client.py** and **server.py** in **./src/** <br>
You can modify IP address to your own broker.

---

### Functions

- [x] Check current (**real-time**) **UBike** parking space and available bikes.
- [x] Calculate nearest **UBike/Bus/MRT** stations in crow-flight distance.
- [x] Interactive Map for searching stations in **Taipei City** and **New Taipei City**
- [x] User-Friendly GUI 

---

### PyQt5

- [x] **Web Engine** for interacting Folium Map
- [x] Graphic User Interface for better experience
- [x] Select Language options for different language users ( **English** , **Traditional Chinese** , **Japanese**(partial) )

 ### Folium

 - [x] Support **OpenStreetMap** and other tiles.
 - [x] automatically generate markers from real-time api data
 - [x] MarkerCluster and markers for **MRT**, **bus**, and **Ubike** stations

### MQTT

- [x] MQTT server for clients to interact data
- [x] Support localhost and MQTT brokers


---

## Screenshots

![image](overview.png)
![image](map.png)
![image](result.png)





