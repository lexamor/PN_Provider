PushService

- [WIP] Common interface
- [DONE] Plugable push providers

APNS

- [DONE] Basic APNS connection
- [DONE] Pool of APNS connections
- [DONE] APNS message wrapper (creates JSON)
- [DONE] Callback system for message delivery. both success and failure.
- [DONE] Connection restart on error
- Handle shutdown message properly
- Support for custom field types in APNS message wrapper (not only string but also arrays, objects, etc.)


GCM (WIP)

- [DONE] Basic connection for GCM
- [WIP] Basic HTTP GCM message wrapper