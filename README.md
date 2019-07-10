# LoRa Gateway Bridge

[![Build Status](https://travis-ci.org/brocaar/lora-gateway-bridge.svg?branch=master)](https://travis-ci.org/brocaar/lora-gateway-bridge)

LoRa Gateway Bridge is a service which converts LoRa packet-forwarder protocols
into a LoRa Server [common protocol](https://github.com/brocaar/loraserver/blob/master/api/gw/gw.proto) (JSON and Protobuf).
This project is part of the [LoRa Server](https://github.com/brocaar/loraserver)
project.

## Backends

The following packet-forwarder backends are provided:

* [Semtech UDP packet-forwarder](https://github.com/Lora-net/packet_forwarder)
* [Basic Station packet-forwarder](https://github.com/lorabasics/basicstation)

## Integrations

The following integrations are provided:

* Generic MQTT broker
* [GCP Cloud IoT Core MQTT Bridge](https://cloud.google.com/iot-core/)

## Architecture

![architecture](https://docs.loraserver.io/img/architecture.png)

### Component links

* [LoRa Gateway Bridge](https://www.loraserver.io/lora-gateway-bridge)
* [LoRa Gateway Config](https://www.loraserver.io/lora-gateway-bridge/install/config)
* [LoRa Server](https://www.loraserver.io/loraserver)
* [LoRa App Server](https://www.loraserver.io/lora-app-server)

## Links
****
* [Downloads](https://www.loraserver.io/lora-gateway-bridge/overview/downloads/)
* [Docker image](https://hub.docker.com/r/loraserver/lora-gateway-bridge/)
* [Documentation](https://www.loraserver.io/lora-gateway-bridge/)
* [Building from source](https://www.loraserver.io/lora-gateway-bridge/community/source/)
* [Contributing](https://www.loraserver.io/lora-gateway-bridge/community/contribute/)
* Support
  * [Support forum](https://forum.loraserver.io)
  * [Bug or feature requests](https://github.com/brocaar/lora-gateway-bridge/issues)

## License

LoRa Gateway Bridge is distributed under the MIT license. See 
[LICENSE](https://github.com/brocaar/lora-gateway-bridge/blob/master/LICENSE).
