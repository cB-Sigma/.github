<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/cB-Sigma/.github/main/profile/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/cB-Sigma/.github/main/profile/banner-light.svg">
  <img alt="[cB]-Sigma: a sigma drawn as a network of nodes over faint protocol frames" src="https://raw.githubusercontent.com/cB-Sigma/.github/main/profile/banner-dark.svg" width="100%">
</picture>

<br>


<p align="center">
Meters, lights, trackers and sirens each speak their own language.<br>
We write down what they say, in Go, and keep a copy of each machine to talk back.
</p>

<br>

### Σ &nbsp;libraries

| library | dialect |
|---|---|
| [**dlms**](https://github.com/cB-Sigma/dlms) | DLMS/COSEM electricity meters, IEC 62056-21 and India's IS 15959 |
| [**dnp3**](https://github.com/cB-Sigma/dnp3) | DNP3 masters and outstations, Secure Authentication v5 |
| [**iec60870**](https://github.com/cB-Sigma/iec60870) | IEC 60870-5-104 and -101 telecontrol |
| [**trackers**](https://github.com/cB-Sigma/trackers) | GT06, Teltonika, TK103, Queclink, Meitrack, Ruptela, JT/T 808, H02, OsmAnd, AIS-140 |
| [**mdns**](https://github.com/cB-Sigma/mdns) | multicast DNS and DNS-SD that finds what answers in either voice |
| [**cap**](https://github.com/cB-Sigma/cap) | Common Alerting Protocol: alerts, signatures, areas, feeds |
| [**schc**](https://github.com/cB-Sigma/schc) | SCHC header compression and fragmentation for LPWAN, and V.44 |
| [**wiz**](https://github.com/cB-Sigma/wiz) | the local UDP API of WiZ lights |
| [**tlsx**](https://github.com/cB-Sigma/tlsx) | crypto/tls with pre-shared keys, raw public keys and the industrial edges |
| [**iotcrypto**](https://github.com/cB-Sigma/iotcrypto) | CCM, KMAC, AES-MMO, brainpool, Koblitz curves, ECQV, ECMQV, SCRAM |
| [**iotsec**](https://github.com/cB-Sigma/iotsec) | the seams through which a protocol reaches its security |
| [**lanbcast**](https://github.com/cB-Sigma/lanbcast) | a broadcast that still finds the LAN behind a VPN |
| [**xsd**](https://github.com/cB-Sigma/xsd) | W3C XML Schema 1.0 validation |
| [**jsonschema**](https://github.com/cB-Sigma/jsonschema) | JSON Schema sets, ordered failures, dialects |
| [**brokersim**](https://github.com/cB-Sigma/brokersim) | AMQP brokers that exist only inside a test |

### ∿ &nbsp;machines

Each library has a twin that pretends to be the device, for tests and for the bench.

[`dlms-sim`](https://github.com/cB-Sigma/dlms-sim) &nbsp;
[`dnp3-sim`](https://github.com/cB-Sigma/dnp3-sim) &nbsp;
[`iec60870-sim`](https://github.com/cB-Sigma/iec60870-sim) &nbsp;
[`trackers-sim`](https://github.com/cB-Sigma/trackers-sim) &nbsp;
[`mdns-sim`](https://github.com/cB-Sigma/mdns-sim) &nbsp;
[`cap-sim`](https://github.com/cB-Sigma/cap-sim) &nbsp;
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
