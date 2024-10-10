# Beehive Sensor Data

This repository contains weekly data collected from a beehive monitoring system. The data is gathered from a beehive sensor device that sends a message every 10 minutes. Each message includes environmental and audio data, such as temperature, humidity, light intensity, and frequency analysis of the hive sounds. This data is valuable for monitoring the health and activity of the bees within the hive.

## Data Description

Below is an explanation of the columns included in the data files:

- **DEVICE_ID**: Unique identifier for the device collecting the data (e.g., v001/c00001/d001).
- **SENSOR_DATETIME**: The full timestamp when the data was collected, in the format DD/MM/YYYY HH:MM.
- **TEMP_DEVICE**: Temperature of the device itself in degrees Celsius.
- **TEMP_INSIDE**: Temperature inside the beehive in degrees Celsius.
- **TEMP_OUTSIDE**: Temperature outside the beehive in degrees Celsius.
- **LIGHT_INTENSITY**: Light intensity near the beehive in arbitrary units.
- **VOLTAGE**: Voltage level of the device's power supply.
- **HUMIDITY_INSIDE**: Humidity inside the beehive, measured in percentage.
- **PRESSURE**: Atmospheric pressure around the beehive in Pascals.
- **100-150 Hz** to **550-600 Hz**: Audio frequency bins capturing sound intensity in specific frequency ranges (e.g., 100-150 Hz) within the hive. Each value represents the intensity level of the sounds recorded in the respective frequency range.
- **MESSAGE_ID**: Unique identifier for each message sent by the device.
- **PROCESSED_DTTM**: The timestamp when the data was processed.

## Additional Information

The data is collected using sensors specifically designed for monitoring the environment inside and outside the beehive. Audio frequencies are captured to analyze the sounds produced by the bees, which can give insights into the hive's activity and health.

Feel free to explore the data and contribute to the analysis by opening issues or submitting pull requests!
