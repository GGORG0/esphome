# GGORG's ESPHome configs

## Secrets

Secrets are encrypted using sops.

```
sops decrypt secrets.sops.yaml > secrets.yaml
```

## Devices

### S60

[Sonoff S60](https://devices.esphome.io/devices/sonoff-s60tpf/) smart plug

### TauronPlug

Cheap smart plug from Tauron, modified with an ESP8266

### MatrixClock

A [Hack Club Neon](https://github.com/hackclub/neon/tree/main/pcb) (ESP32-S3) with a HUB75-based 64x32 LED matrix