# metiostation


# AVR Temperature Monitoring & Bluetooth Data Transmission


> A simple AVR project for temperature monitoring, Bluetooth data transmission, and battery management using pure C programming.

---

## Table of Contents

- [Description](#description)
- [Components Used](#components-used)
- [Project Functionality](#project-functionality)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Description

In this project, we explore the world of electronics and programming by creating a temperature monitoring system using a thermal resistor. What sets this project apart is our decision to code it entirely in pure C with `avr-gcc`, bypassing the Arduino framework. Additionally, we've incorporated a TP4056 charger and a lithium battery to ensure a self-sustained power source, making it practical for various applications. The system can also send temperature data wirelessly using Bluetooth communication.

### Components Used

- **Thermal Resistor:** To measure temperature accurately.
- **TP4056 Charger:** For battery charging and management.
- **Lithium Battery (3.7V):** To power the system.
- **Bluetooth Module:** For wireless data transmission.

### Project Functionality

- **Temperature Monitoring:** Measures ambient temperature using the thermal resistor.
- **Battery Management:** Safely charges and manages the lithium battery.
- **Pure C Programming:** The entire code is written in pure C with `avr-gcc` for deeper embedded programming understanding.
- **Bluetooth Data Transmission:** Establishes a Bluetooth connection to send real-time temperature data to a paired device.
- **Battery-Powered:** Operates independently on the lithium battery, making it suitable for portable applications.

### Learning Opportunities

- Gain proficiency in embedded C programming with `avr-gcc`.
- Understand sensor integration for reading data from thermal resistors.
- Learn about lithium battery charging and maintenance.
- Establish Bluetooth connections for wireless data transmission.
- Create a user-friendly interface for displaying temperature data.

---

## Getting Started

### Prerequisites

- AVR toolchain with `avr-gcc` and `avrdude` (for compiling and uploading code to the AVR microcontroller).
- Bluetooth terminal app on your smartphone or computer for receiving data.
- Required libraries (if any) mentioned in the project code.

### Installation

1. Install avr-gcc ( configure scripts can help)
2. Compile the code using `avr-gcc`.
3. Upload the compiled code to your AVR microcontroller using `avrdude`.
4. Connect the components following the wiring diagram (provided in the repository).

---

## Usage

1. Power on the system using the lithium battery.
2. Pair your Bluetooth device with the AVR Bluetooth module.
3. Open the Bluetooth terminal app on your device.
4. Receive and display real-time temperature data transmitted by the AVR microcontroller.

---

## Contributing

Contributions are welcome! If you have improvements or feature suggestions, please open an issue or create a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments

- Mention any acknowledgments or resources you found helpful during the project.

---

## Contact

- Your Name - [Your Email] - [Your Website] (if applicable)

- Project Link: [GitHub Repository](https://github.com/your-username/avr-temperature-monitor)

