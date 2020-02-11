# View Public Telemetry

You can take a look at the overall network using the telemetry website:

[https://telemetry.polkadot.io/#list/Denver Testnet](https://telemetry.polkadot.io/#list/Denver%20Testnet)

Your node will connect to the telemetry server because of the `spec.json`:

```json
"telemetryEndpoints": [
    ["ws://telemetry.polkadot.io:1024", 0]
],
```

## Discussion

* Peer Discovery
* Network Topology

<!-- slide:break -->

![Polkadot Telemetry](./assets/telemetry.png)
