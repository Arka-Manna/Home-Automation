# Home Automation System with Theme Switching

The Home Automation System with Theme Switching is a web-based interface designed to control up to four electrical devices using an ESP8266 or ESP32 microcontroller. By connecting to a local WiFi network, users can remotely turn devices on or off via a web browser, providing convenience and modern control over household or office appliances.

## Key Features

### Remote Device Control
- Users can control up to four devices (e.g., lights, fans) from any web browser.
- Each device can be independently turned on or off.

### Responsive Web Interface
- The interface is accessible on desktops, tablets, and smartphones.
- It features a clean and user-friendly design.

### Theme Switching
- Users can toggle between light and dark themes for better visual comfort.
- The interface updates instantly to reflect the current theme.

### Real-Time Feedback
- The web interface displays the current state (on/off) of each device.
- The display updates immediately upon any state change.

### WiFi Connectivity
- The system connects to a local WiFi network for remote access.
- Users can control devices from anywhere within the WiFi coverage area.

## Technical Details
- **Microcontroller**: ESP8266 or ESP32, known for low cost and built-in WiFi capabilities.
- **Web Server**: The microcontroller runs a web server on port 80 to serve the control interface.
- **HTML/CSS/JavaScript**: The interface uses these technologies for structure, styling, and interactivity.
- **Relay Control**: GPIO pins on the microcontroller control relays that switch the electrical devices.

## Benefits
- **Ease of Installation**: Simple setup with basic wiring and WiFi configuration.
- **User-Friendly Interface**: Intuitive design suitable for users of all ages.
- **Customization**: Easily modifiable code to accommodate more devices or different controls.
- **Cost-Effective**: Utilizes inexpensive components for robust functionality.

## Applications
- **Home Automation**: Remotely control household appliances for convenience and energy efficiency.
- **Office Automation**: Manage office equipment efficiently.
- **Accessibility**: Facilitate easier control of devices for individuals with mobility issues.

This project provides a solid foundation for building a home automation system, offering flexibility, ease of use, and efficient control over electrical devices.

## License
This project is licensed under the Apache License 2.0. See the (LICENSE) file for details.

## Author
[ARKA MANNA]
