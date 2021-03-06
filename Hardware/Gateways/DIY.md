# Do-It-Yourself Gateways

There are two options for the communication chip:
* SX1272/SX1276: Only supports one simultaneous connection (not LoRaWAN compliant)
* SX1301/SX1257: Supports 8 simultaneous connections (LoRaWAN compliant)

## Full LoRaWAN-compliant gateways (SX1301 + SX1257)
* [Based on Multitech mCard-LoRa](https://github.com/mirakonta/lora_gateway/wiki)
* [Based on IMST iC880a](https://github.com/ttn-zh/ic880a-gateway/wiki)
* [Outdoor setup](http://www.meiland.nl/2015/12/outdoor-lora-gateway/)

## Single-channel forwarders (SX127x)
* [semi-LoRaWAN @tftelkamp](https://github.com/tftelkamp/single_chan_pkt_fwd) (not LoRaWAN compliant, but works partly on TTN)
* [DIY lora forwarder](http://cpham.perso.univ-pau.fr/LORA/RPIgateway.html) (not LoRaWAN compliant)
* [http://www.daveakerman.com/?p=1719](http://www.daveakerman.com/?p=1719) (not LoRaWAN compliant)
* [TTN-compatible ESP8266 Single Channel Gateway](https://github.com/JaapBraam/LoRaWanGateway) (not LoRaWAN compliant, but listens on all SF, has support for up&downlink, works on TTN)