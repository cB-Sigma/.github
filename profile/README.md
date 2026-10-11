<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/cB-Sigma/.github/main/profile/sigma-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/cB-Sigma/.github/main/profile/sigma-light.svg">
  <img alt="[cB]-Sigma: a sigma drawn as a network of nodes over faint protocol frames" src="https://raw.githubusercontent.com/cB-Sigma/.github/main/profile/sigma-dark.svg" width="100%">
</picture>

<br>

### Σ &nbsp;libraries

| library | dialect |
|---|---|
| [**dlms**](https://github.com/cB-Sigma/dlms) | DLMS/COSEM electricity meters, IEC 62056-21 and India's IS 15959 |
| [**mbus**](https://github.com/cB-Sigma/mbus) | wired and wireless M-Bus, OMS, heat, water and gas meters |
| [**lwm2m**](https://github.com/cB-Sigma/lwm2m) | LightweightM2M content formats and object model |
| [**ocpp**](https://github.com/cB-Sigma/ocpp) | EV chargers, OCPP 1.6, 2.0.1 and 2.1 |
| [**openadr**](https://github.com/cB-Sigma/openadr) | demand response, OpenADR 2.0b, 2.0a and 3 |
| [**sunspec**](https://github.com/cB-Sigma/sunspec) | solar inverters and DER controls over Modbus |
| [**dnp3**](https://github.com/cB-Sigma/dnp3) | DNP3 masters and outstations, Secure Authentication v5 |
| [**iec60870**](https://github.com/cB-Sigma/iec60870) | IEC 60870-5-104 and -101 telecontrol |
| [**trackers**](https://github.com/cB-Sigma/trackers) | GT06, Teltonika, TK103, Queclink, Meitrack, Ruptela, JT/T 808, H02, OsmAnd, AIS-140 |
| [**mdns**](https://github.com/cB-Sigma/mdns) | multicast DNS and DNS-SD that finds what answers in either voice |
| [**cap**](https://github.com/cB-Sigma/cap) | Common Alerting Protocol: alerts, signatures, areas, feeds |
| [**schc**](https://github.com/cB-Sigma/schc) | SCHC header compression and fragmentation for LPWAN, and V.44 |
| [**knx**](https://github.com/cB-Sigma/knx) | KNX buildings over IP, KNX IP Secure, ETS projects and keyrings |
| [**mqttsn**](https://github.com/cB-Sigma/mqttsn) | MQTT-SN 1.2 and 2.0 for sensors that sleep |
| [**shelly**](https://github.com/cB-Sigma/shelly) | Shelly relays, dimmers and sensors, Gen1 and Gen2+ |
| [**hue**](https://github.com/cB-Sigma/hue) | Hue bridges, CLIP v2 and the event stream |
| [**tplink**](https://github.com/cB-Sigma/tplink) | TP-Link Kasa and Tapo on the LAN |
| [**miio**](https://github.com/cB-Sigma/miio) | Xiaomi miIO and MIoT on the LAN |
| [**tuyalan**](https://github.com/cB-Sigma/tuyalan) | Tuya devices on the LAN, protocol 3.1 to 3.5 |
| [**wiz**](https://github.com/cB-Sigma/wiz) | the local UDP API of WiZ lights |
| [**tlsx**](https://github.com/cB-Sigma/tlsx) | crypto/tls with pre-shared keys, raw public keys and the industrial edges |
| [**iotcrypto**](https://github.com/cB-Sigma/iotcrypto) | CCM, KMAC, AES-MMO, brainpool, Koblitz curves, ECQV, ECMQV, SCRAM |
| [**iotsec**](https://github.com/cB-Sigma/iotsec) | the seams through which a protocol reaches its security |
| [**lanbcast**](https://github.com/cB-Sigma/lanbcast) | a broadcast that still finds the LAN behind a VPN |
| [**xsd**](https://github.com/cB-Sigma/xsd) | W3C XML Schema 1.0 validation |
| [**jsonschema**](https://github.com/cB-Sigma/jsonschema) | JSON Schema sets, ordered failures, dialects |
| [**jscodec**](https://github.com/cB-Sigma/jscodec) | LoRaWAN payload codecs in JavaScript, run in a Go sandbox |
| [**brokersim**](https://github.com/cB-Sigma/brokersim) | AMQP brokers that exist only inside a test |

### ∿ &nbsp;machines

Each library has a twin that pretends to be the device, for tests and for the bench.

[`dlms-sim`](https://github.com/cB-Sigma/dlms-sim) &nbsp;
[`mbus-sim`](https://github.com/cB-Sigma/mbus-sim) &nbsp;
[`lwm2m-sim`](https://github.com/cB-Sigma/lwm2m-sim) &nbsp;
[`ocpp-sim`](https://github.com/cB-Sigma/ocpp-sim) &nbsp;
[`openadr-sim`](https://github.com/cB-Sigma/openadr-sim) &nbsp;
[`sunspec-sim`](https://github.com/cB-Sigma/sunspec-sim) &nbsp;
[`dnp3-sim`](https://github.com/cB-Sigma/dnp3-sim) &nbsp;
[`iec60870-sim`](https://github.com/cB-Sigma/iec60870-sim) &nbsp;
[`trackers-sim`](https://github.com/cB-Sigma/trackers-sim) &nbsp;
[`mdns-sim`](https://github.com/cB-Sigma/mdns-sim) &nbsp;
[`cap-sim`](https://github.com/cB-Sigma/cap-sim) &nbsp;
[`knx-sim`](https://github.com/cB-Sigma/knx-sim) &nbsp;
[`mqttsn-sim`](https://github.com/cB-Sigma/mqttsn-sim) &nbsp;
[`shelly-sim`](https://github.com/cB-Sigma/shelly-sim) &nbsp;
[`hue-sim`](https://github.com/cB-Sigma/hue-sim) &nbsp;
[`tplink-sim`](https://github.com/cB-Sigma/tplink-sim) &nbsp;
[`miio-sim`](https://github.com/cB-Sigma/miio-sim) &nbsp;
[`tuyalan-sim`](https://github.com/cB-Sigma/tuyalan-sim) &nbsp;
[`wiz-sim`](https://github.com/cB-Sigma/wiz-sim)

### ⌁ &nbsp;terms

```
pure Go          no cgo, one static binary
checked          against what others built: their code, their vectors, real devices
honest           every README says what is missing, and who does it better
apache-2.0       take it
```

<br>

<p align="center"><sub>more arrive as they pass.</sub></p>
