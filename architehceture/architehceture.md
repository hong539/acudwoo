# architehceture

## resources

* Android
* Linux
* USB cable

```mermaid
sequenceDiagram
    camera->>+android: send streaming
    android->>+interface: send streaming
    interface->>+linux: send streaming
    linux-->>-client: send streaming
```