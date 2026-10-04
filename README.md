# Corn-LoRa
A not so basic electronic project... This is a LoRa Board which is great for meshtastic but not great for my sanity when routing! This has a SX1262 radio chip and uses a RP2040 for the microcontroller along with a crystal occulator for the RP2040 like any normal dev board. Corn LoRa also includes a *0900FM15D0039* as a IPD (integrated passive device) by Johanson which controlls the balun and filtering (868-915MHz, may be different footprint) To switch between TX and RX, it uses an RF switch, controlled by DIO2; along with a PE4259 for a 2 channel switcher (as mentioned above!).


![GitHub Repo stars](https://img.shields.io/github/stars/vms-hc/corn-series?style=flat&logo=github&logoColor=white) 

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

