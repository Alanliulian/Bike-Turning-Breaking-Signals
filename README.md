# Bike-Turning-Breaking-Signals
A DIY project to create a bike signal system with turn signals and brake lights. The system uses an Arduino to control LED lights based on inputs from handlebar-mounted switches and brake sensors.

## Features

- Brake light activation using brake sensors
- Left and right turn signals
- High-intensity LEDs for visibility
- Rechargeable battery pack

## Components

- Push-button switches
- High-intensity LEDs
- Arduino Uno
- Transistors/Relays
- Rechargeable battery pack

## Getting Started

### Prerequisites

- Arduino IDE
- Basic soldering and wiring tools

### Installation

Follow the instructions in [docs/installation.md](docs/installation.md) to set up the project.

## Usage

Detailed usage instructions are available in [docs/usage.md](docs/usage.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


# Installation Guide

## Components

1. Push-Button Switches for Brake Sensors
2. Handlebar Mounted Push Button Switches for Turn Signals
3. High-Intensity LED Lights
4. Arduino Uno
5. Transistors/Relays
6. Rechargeable Battery Pack
7. Battery Level Indicator
8. Wiring and Connectors

## Assembly Instructions

### Mounting the Brake Sensors

1. Mount the push-button switches on the brake levers.
2. Wire the switches to the Arduino (pins 2 and 3).

### Installing the Turn Signal Switches

1. Mount the handlebar switches on the left and right handlebars.
2. Wire the switches to the Arduino (pins 4 and 5).

### Connecting the LEDs

1. Mount the LED strips on the back of the bike.
2. Wire the LEDs to the Arduino through transistors (pins 6, 7, and 8).

### Power Supply and Battery Level Indicator

1. Connect the battery pack to power the Arduino and LEDs.
2. Install the battery voltage indicator.

## Programming the Arduino

1. Upload the `bike_signal.ino` file from the `src` directory to the Arduino.

### Final Testing

1. Test each component.
2. Secure all components and weatherproof the connections.
