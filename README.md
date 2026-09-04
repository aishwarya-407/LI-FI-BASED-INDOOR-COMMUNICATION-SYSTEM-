# LI-FI-BASED-INDOOR-COMMUNICATION-SYSTEM

The Li-Fi Based Indoor Communication System is an optical wireless communication project that demonstrates the transmission of digital information using visible light instead of traditional radio-frequency signals. The system is designed for short-range indoor communication and uses an LED to transmit information and a solar panel to detect the transmitted light.

In this project, an Arduino UNO is used on the transmitter side to process and generate the data signal. The data is used to control the LED at a high switching rate. The LED acts as the optical transmitter, converting the electrical data signal into variations in visible light.

At the receiver side, a solar panel is used as the optical detector. It detects the variations in light produced by the transmitting LED and converts them back into an electrical signal. An Arduino Nano receives and processes this signal to recover the transmitted information.

The decoded information is then displayed on a 16×2 LCD, allowing the received data to be viewed by the user. This demonstrates the basic working principle of Light Fidelity (Li-Fi), where light intensity variations are used to carry information.

Working Principle

- The input data is generated and processed using the Arduino UNO.
- The Arduino UNO controls the LED according to the transmitted data.
- The LED rapidly switches its light intensity to represent the digital information.
- The solar panel placed at the receiver detects the variations in the transmitted light.
- The solar panel converts the received optical signal into an electrical signal.
- The Arduino Nano processes and decodes the received signal.
-The recovered information is displayed on the 16×2 LCD.

Hardware Components

- Arduino UNO – Transmitter/controller
- Arduino Nano – Receiver/controller
- LED – Optical transmitter
- Solar panel – Optical receiver/detector
- 16×2 LCD – Received-data display
- Connecting wires and supporting components

Key Features

- Uses visible light for wireless data transmission.
- emonstrates the basic concept of Li-Fi technology.
- Provides a short-range indoor optical communication prototype.
- Uses a solar panel for optical signal detection.
- Uses Arduino-based digital signal processing.
- Provides real-time display of the received information.
- Low-cost and suitable for educational and prototype applications.

Technologies Used

Arduino UNO | Arduino Nano | Embedded C | LED Communication | Solar Panel Detection | Visible Light Communication (VLC) | 16×2 LCD
