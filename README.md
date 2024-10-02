# Presence+
### Multi-Person Tracking
ESPHome-powered presence sensor designed to track the position of up to three individuals.

## Features
* **Multi-Person Detection**
  * Tracks up to three individuals simultaneously.
* **Integration with Home Assistant**
  * Easily integrate with Home Assistant and add your own automations based on where individuals are located and how many individuals are visible (moving and standing still).
* **Real-Time Updates**
  * Receive real-time status updates on the presence of individuals.

## Requirements
* ESP32
* LD2450 mmWave sensor
* esphome-cli (or the dashboard)

## Installation
**1. Clone the Repository:**
```bash
$ git clone https://github.com/svenar-iot/esphome-presence-plus.git
$ cd esphome-presence-plus
```

**2. Upload to Your ESP Device:**

Use the ESPHome dashboard to upload the configuration to your ESP device.

or using the CLI:

```bash
$ esphome compile presence.yaml && esphome upload presence.yaml
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/svenar-iot/esphome-presence-plus/blob/main/LICENSE) file for details.
