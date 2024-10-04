# Smart Irrigation System

This project is a **Smart Irrigation System** designed to reduce water waste by up to 50% through automated watering based on real-time data. The system integrates soil moisture sensors and weather condition monitoring to ensure optimal water usage, making it suitable for both agricultural and residential applications.

## Features
- **Automated Irrigation**: The system activates irrigation only when necessary, based on real-time soil moisture readings and weather conditions.
- **Efficient Water Usage**: Reduces water consumption by up to 50%, ensuring sustainability and conservation.
- **Real-Time Monitoring**: Displays current soil moisture, temperature, and humidity on an LCD screen for easy monitoring.
- **Weather Adaptive**: Adjusts watering schedules based on humidity and temperature levels.

## Components Used
- **Arduino Uno**: Microcontroller used for processing sensor data and controlling the relay.
- **Soil Moisture Sensor**: Detects the moisture levels in the soil to determine when to water.
- **DHT11 Sensor**: Measures temperature and humidity to help adjust irrigation patterns.
- **Relay Module**: Controls the water pump based on the moisture levels.
- **LCD Display (16x2)**: Shows real-time data like soil moisture, temperature, and humidity.

## How It Works
1. The soil moisture sensor monitors the soil's water level.
2. The DHT11 sensor collects environmental data such as temperature and humidity.
3. If the soil is too dry, the relay activates the water pump to irrigate the area.
4. The system turns off the water pump when optimal moisture levels are detected, preventing water waste.
5. Real-time data is displayed on the LCD for easy tracking.

## Benefits
- Reduces manual effort in watering plants.
- Conserves water by irrigating only when necessary.
- Suitable for both small-scale gardens and large agricultural fields.
- Easily scalable and customizable for different environmental conditions.

## Future Improvements
- Integration with weather APIs for more precise weather predictions.
- Mobile app control for remote monitoring and adjustments.
- Solar power integration for energy efficiency.

