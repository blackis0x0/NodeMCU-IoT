Switch
===

## Required

- NodeMCU
- Relay 3.3V
- 802.11n (or earlier) WiFi AP and MQTT Broker

## Interface

```
Broadcast Topic : switch/{id}
Control Topic   : switch/{id}/set
```

On (Relay: NO)
```
1
```

Off (Relay: NC)
```
0
```

## Layout

<img alt="layout" src="https://user-images.githubusercontent.com/31122855/208235552-f58cf2cd-5457-450f-b16a-95c9d4f12cf9.svg" width="500">
