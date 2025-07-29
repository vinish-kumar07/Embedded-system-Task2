COMPANY :CODTECH IT SOLUTIONS PVT.LTD

NAME:VINISH KUMAR S

INTERN ID:CT04DH1830

DOMAIN NAME: embedded system

DURATION:4 WEEKS

MENTOR:NEELA SANTOSH

DESCRIOTION

The Home Automation with Bluetooth project is a beginner-friendly yet practical embedded systems project that allows control of home appliances using a Bluetooth interface. In this project, I used Tinkercad to simulate the basic functions of a Bluetooth-controlled home automation system, even though Tinkercad does not support Bluetooth modules directly in its simulation environment. To overcome this limitation, I used Serial Communication to simulate Bluetooth input. The primary concept behind the project is to turn devices like LEDs (representing home appliances such as lights or fans) ON or OFF based on commands sent from a mobile device or computer. In a real-world hardware setup, this would be done using a Bluetooth module like HC-05 connected to the Arduino UNO, allowing the system to receive commands wirelessly from a smartphone using apps like Bluetooth Terminal or Arduino Bluetooth Controller. However, since Bluetooth modules are not functional in Tinkercad simulations, I replaced the Bluetooth interface with serial input through the Serial Monitor. This means that instead of sending commands wirelessly, I typed them directly into the Serial Monitor to simulate how the Arduino would react to Bluetooth input. The components used in the Tinkercad circuit included an Arduino UNO, multiple LEDs (to represent home devices), resistors, and jumper wires connected on a breadboard. The logic of the system is that the Arduino continuously listens for incoming characters over the serial connection. When a specific character is received—for example, 'A' to turn on the light and 'a' to turn it off—the Arduino executes a digital output command to control the corresponding LED. Each device is assigned a unique command character to switch it ON or OFF. This kind of communication mimics what would happen if a Bluetooth module received data from a smartphone app. The project can be extended to include fans, door locks, or other household devices by using relays in place of LEDs. The Serial Monitor plays a crucial role in the simulation because it allows for manual testing of the logic and behavior of the Arduino sketch without needing wireless modules. It also helps understand how Serial Communication works between devices. In a real-world scenario, the same sketch would function identically with a Bluetooth module, since Bluetooth modules communicate with Arduino through serial pins (TX and RX). This project is very educational as it demonstrates real-life applications of home automation, introduces serial-based data processing, and teaches the basics of interfacing with external input systems like Bluetooth. It also improves understanding of condition checking, pin control, and how commands can be mapped to specific actions in an embedded system. In Tinkercad, using the Serial Monitor as a substitute is a smart workaround that lets learners simulate Bluetooth behavior even without native module support. Overall, this project is a strong foundation for creating fully functional smart home systems. It combines software and hardware logic, works well in a virtual simulation environment, and helps develop the skills required to build real automation projects using wireless technology in the future.

circuit:

<img width="528" height="307" alt="Image" src="https://github.com/user-attachments/assets/46cab9ba-1372-4616-8b06-0d26b392c69e" />



output:


<img width="825" height="368" alt="Image" src="https://github.com/user-attachments/assets/3445e1a3-a9af-4ff2-a7c7-04262f9b174d" />
