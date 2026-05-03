# Software-Defined Networking

Software-Defined Networking (SDN) is a network architecture approach that decouples the network control plane from the data forwarding plane, enabling dynamic, programmatically efficient network configuration. SDN controllers expose northbound REST APIs for network applications to define routing, load balancing, and security policies, while southbound APIs communicate with switches and routers via OpenFlow, NETCONF, and RESTCONF protocols.

**URL:** [https://raw.githubusercontent.com/api-evangelist/software-defined-networking/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/software-defined-networking/refs/heads/main/apis.yml)

## Tags

- Cloud Infrastructure
- Network Architecture
- Networking
- Virtualization
- SDN
- OpenDaylight
- ONOS

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### OpenDaylight RESTCONF API

OpenDaylight is an open-source SDN controller platform hosted at the Linux Foundation that exposes RESTCONF APIs for managing network devices, topology, flows, and configuration.

**Base URL:** `http://localhost:8181/restconf`
**Tags:** SDN, OpenDaylight, RESTCONF, Network Management, Networking

#### Properties

- [Documentation](https://docs.opendaylight.org/en/latest/user-guide/opendaylight-controller-overview.html)
- [Website](https://www.opendaylight.org/)
- [JSON Schema](json-schema/sdn-network-topology-schema.json)
- [JSON Structure](json-structure/sdn-topology-structure.json)

### ONOS SDN Controller REST API

ONOS (Open Network Operating System) is an open-source SDN controller providing REST APIs for network management including topology discovery, flow rule management, host tracking, and device management.

**Base URL:** `http://localhost:8181/onos/v1`
**Tags:** SDN, ONOS, Network Management, Topology, Flow Rules

#### Properties

- [Documentation](https://wiki.onosproject.org/display/ONOS/REST+API)
- [Website](https://onosproject.org/)

## JSON Schema

| Schema | Description |
|---|---|
| [sdn-network-topology-schema.json](json-schema/sdn-network-topology-schema.json) | JSON Schema for SDN network topology, nodes, links, and flow rules |

## JSON Structure

| Structure | Description |
|---|---|
| [sdn-topology-structure.json](json-structure/sdn-topology-structure.json) | Structure documentation for Topology, Node, Link, and FlowRule resources |

## JSON-LD

| Context | Description |
|---|---|
| [software-defined-networking-context.jsonld](json-ld/software-defined-networking-context.jsonld) | Linked data context mapping SDN concepts to NML (Network Markup Language) ontology |

## Examples

| Example | Description |
|---|---|
| [sdn-topology-example.json](examples/sdn-topology-example.json) | OpenDaylight RESTCONF network topology response with nodes and links |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [software-defined-networking-vocabulary.yml](vocabulary/software-defined-networking-vocabulary.yml) | SDN vocabulary covering architecture, protocols (OpenFlow, RESTCONF, NETCONF), topology, and controllers |

## Common Properties

- [Open Networking Foundation](https://opennetworking.org/)
- [Wikipedia: Software-Defined Networking](https://en.wikipedia.org/wiki/Software-defined_networking)
- [RFC 7426: SDN Layers and Architecture](https://datatracker.ietf.org/doc/html/rfc7426)
- [GitHub: OpenDaylight](https://github.com/opendaylight)
- [GitHub: Open Networking Lab](https://github.com/opennetworkinglab)
