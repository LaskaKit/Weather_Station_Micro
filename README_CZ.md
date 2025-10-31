# Návod na stavbu venkovní Wi-Fi meteostanice s Meteo Mini v3

Přemýšlíš o výrobě své vlastní domácí meteostanice?  
Nachystali jsme pro tebe kompletní kit obsahující radiační Solární panel, krabičku, senzory, spojovací materiál a naši vývojovou desku Meteo Mini, kterou jednoduše naprogramuješ pomocí Arduino IDE.

![LaskaKit Meteo Micro Weatherstation](https://github.com/LaskaKit/Weather_Station_Mini/blob/main/img/LaskaKit-meteo-micro-meteostanice-0.jpg)

Obsahuje modul ESP32-C3-mimi založený na Wi-Fi čipu ESP32-C3, je osazen konektorem pro připojení I²C, SPI, a IO čidel.  
Meteostanice je napájena z LiPol akumulátoru, který je připojen pomocí JST-PH-2 konektoru na základní desce.  
  
Deska má také integrovanou nabíječku Li-Pol akumulátoru, takže může být akumulátor nabíjen z USB-C konektoru nebo solárního panelu se jmenovitým napětím 5–10V, pro který je na základní desce rovněž osazen konektor JST-PH-2. Na desce je též osazený dělič napětí, který je připojen k akumulátoru a jeho výstup je připojen na ADC vstup mikrokontroléru. Stav akumulátoru tak bude neustále pod dohledem.  

---

## Součásti kitu

![LaskaKit Meteo Mini](https://github.com/LaskaKit/Weather_Station_Mini/blob/main/img/LaskaKit-meteo-micro-meteostanice-4.jpg)

- 1 ks – Základní deska LaskaKit Meteo Mini V4 IPEX  
- 1 ks – Anténa 3.0dBi 11.5cm 2.4G  
- 1 ks – Pigtail MHF3/IPEX3 - SMA Female, kabel 15cm  
- 1 ks – GeB LiPol Baterie 603048 900mAh 3.7V JST-PH 2.0
- 1 ks – Solární panel 6V 0.6W  
- 1 ks – Lepidlo silikonové
- 1 ks – JST-PH-2 2mm 2pin konektor s 20cm vodiči
- 1 ks – μŠup-SP13-IO 3pin 5cm kabel
- 1 ks – μŠup-SP13-I2C 4pin 5cm kabel
- 1 ks – Senzor s kabelem DS18B20+ nebo SHT40 (podle varianty kitu)  
- 2 ks – Matice přesná M3
- 2 ks – Šroub M3×12  
- 4 ks – Šroub do plastu 2,2×5 BN 82428  
- 2 ks – Šroub do plastu 2,2×8 BN 82428  

---

## Návod k použití

V našem detailním návodu na stavbu micro meteostanice s Meteo Mini najdeš vše od sestavení, přes naprogramování až po nastavení.  
V ukázkovém kódu používáme **WiFi Manager**, který slouží pro prvotní konfiguraci celé meteostanice.  

Stačí připojit akumulátor k Meteo Mini, vyhledat WiFi síť, kterou Meteo Mini vytvoří, přihlásit se (AP: `LaskaKitMeteo`) a nastavit tvou domácí Wi-Fi síť.  

---

🔗 Odkaz na stavebnici: https://www.laskakit.cz/laskakit-meteo-micro-meteostanice/
