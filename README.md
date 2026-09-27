# NexaLink

NexaLink is the open-source Paper plugin that exposes local Minecraft status to NexaAgent. It is designed for NexaCloud-managed Paper networks and does not contain control-plane credentials.

## Compatibility

- Paper 1.21.4+
- Java 21+
- NexaAgent on the same host

## Build

```bash
mvn clean verify
```

Install `target/nexalink-1.0.0.jar` in the server `plugins/` directory and restart Paper. Use `/nexalink` with the `nexalink.status` permission to verify the bridge.

## Security

Please report vulnerabilities privately as described in [SECURITY.md](SECURITY.md).

## License

MIT
