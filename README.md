# Guide to Building an Outdoor Wi-Fi Weather Station with Meteo Mini v3

Thinking about building your own home weather station?  
We’ve prepared a complete kit that includes a **solar panel**, **enclosure**, **sensors**, **mounting hardware**, and our **Meteo Mini** development board, which you can easily program using **Arduino IDE**.

![LaskaKit Meteo Micro Weatherstation](https://github.com/LaskaKit/Weather_Station_Mini/blob/main/img/LaskaKit-meteo-micro-meteostanice-0.jpg)

It features an **ESP32-C3-mimi module** based on the **ESP32-C3 Wi-Fi chip**, equipped with connectors for **I²C**, **SPI**, and **IO** sensors.  
The weather station is powered by a **Li-Pol battery**, connected via a **JST-PH-2 connector** on the main board.  
  
The board also includes an **integrated Li-Pol charger**, allowing the battery to be charged either via a **USB-C connector** or a **solar panel** with a nominal voltage of **5–10V**, for which a **JST-PH-2 connector** is also provided on the main board. The board is equipped with a **voltage divider** connected to the battery, with its output linked to the **ADC input** of the microcontroller. This way, the battery status is constantly monitored.  

---

## Kit Contents

![LaskaKit Meteo Mini](https://github.com/LaskaKit/Weather_Station_Mini/blob/main/img/LaskaKit-meteo-micro-meteostanice-4.jpg)

- 1 pc – LaskaKit Meteo Mini V4 IPEX Main Board  
- 1 pc – 3.0dBi 11.5cm 2.4G Antenna  
- 1 pc – Pigtail MHF3/IPEX3 - SMA Female, 15cm Cable  
- 1 pc – GeB Li-Pol Battery 603048 900mAh 3.7V JST-PH 2.0  
- 1 pc – Solar Panel 6V 0.6W  
- 1 pc – Silicone Adhesive  
- 1 pc – JST-PH-2 2mm 2-pin Connector with 20cm Wires  
- 1 pc – μŠup-SP13-IO 3-pin 5cm Cable  
- 1 pc – μŠup-SP13-I2C 4-pin 5cm Cable  
- 1 pc – DS18B20+ or SHT40 Sensor with Cable (depending on kit version)  
- 2 pcs – Precision Nut M3  
- 2 pcs – Screw M3×12  
- 4 pcs – Plastic Screw 2.2×5 BN 82428  
- 2 pcs – Plastic Screw 2.2×8 BN 82428  

---

## Instructions for Use

In our detailed guide to building a **micro weather station with Meteo Mini**, you’ll find everything from assembly and programming to setup.  
The sample code uses **WiFi Manager**, which is responsible for the initial configuration of the entire station.  

Simply connect the battery to the **Meteo Mini**, search for the **Wi-Fi network** created by the board, connect to it (AP: `LaskaKitMeteo`), and configure your home Wi-Fi network.  

---

🔗 **Kit link:** [https://www.laskakit.cz/laskakit-meteo-micro-meteostanice/](https://www.laskakit.cz/laskakit-meteo-micro-meteostanice/)