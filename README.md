# IoTMeter Integration for Home Assistant

The IoTMeter integration allows you to monitor and manage your IoTMeter within Home Assistant. This integration provides real-time data and control over your connected devices.

## Features

- Real-time monitoring of IoTMeter
- Historical data tracking
- Easy configuration and setup

## Installation

### Manual Installation

1. Download the `iotmeter` directory from the [GitHub repository](https://github.com/Vilmio/home_assistent).
2. Copy the `iotmeter` directory to your Home Assistant custom components directory:
   ```sh
   cp -r iotmeter /config/custom_components/
3. Restart Home Assistant.

## HACS Installation
1. Open HACS in your Home Assistant.
2. Go to "Integrations" and click the "+" button.
3. Search for "IoTMeter" and follow the prompts to install the integration.

## Sensors

The integration adds the following sensors:
- Total power
- Total consumption energy
- Total generation energy
- EVSE status

## Number
The integration adds the following number entities:
- Max charging current (Only for SmartModule)


## Support
If you encounter any issues or have questions, please open an issue on the GitHub repository.

## Contributing
We welcome contributions to improve this integration! To contribute, please fork the repository, make your changes, and submit a pull request.
