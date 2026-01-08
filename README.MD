## 🔐 *Password-Based Door Lock System (Embedded C / Arduino)*
📌 Overview

This project is a Password-Based Door Lock System developed using Embedded C with the Arduino framework.
It uses a keypad for password input, an LCD for displaying messages, and a servo motor to control the door locking and unlocking mechanism.

The system improves security by allowing access only when the correct password is entered. It also includes alert mechanisms for wrong password attempts.

## 🎯 Project Objective

To design a secure electronic door locking system

To replace traditional keys with password-based authentication

To gain hands-on experience in embedded programming and hardware interfacing

## ⚙️ How the System Works

The user enters a password using a 4×4 keypad

The system compares the entered password with a stored master password

If the password is correct:

The door unlocks using a servo motor

A success message is displayed on the LCD

After a few seconds, the door locks automatically

If the password is incorrect:

An error message is displayed on the LCD

A buzzer sounds and an LED turns ON

If the password is entered incorrectly multiple times:

A security alarm is activated

The LED blinks to indicate unauthorized access

## ✨ Features

Password-based access control

Servo motor controlled door lock

LCD display for user interaction

Buzzer and LED alerts for wrong attempts

Alarm activation for multiple wrong password entries

Automatic door locking after access

🛠 Components & Technologies Used
Hardware

Arduino board

4×4 Keypad

16×2 LCD Display

Servo Motor

Buzzer

LED

Connecting wires

Software

Embedded C (Arduino C++)

Arduino IDE

Libraries Used

Keypad.h

LiquidCrystal.h

Servo.h

📁 Project Structure
```
Password-Based-Door-Lock-System/
│
├── door_lock.ino
├── README.md
└── circuit_diagram.png (optional)
```

 ## 🚀 Applications

Home security systems

Office access control

Lockers

Restricted areas

Educational embedded system projects

## 📸 Demo

(Add a photo or short video of the working project here)

## 📚 What I Learned

Embedded C programming

Arduino programming fundamentals

Hardware interfacing (keypad, LCD, servo)

Implementing security logic in embedded systems

Debugging and testing embedded applications

## 🤝 Future Improvements

Password change feature

EEPROM-based password storage

Keypad lock after multiple failures

GSM / IoT-based alert system

Mobile app integration

## 📬 Contact

If you have suggestions or questions, feel free to reach out.

⭐ If you like this project, give it a star on GitHub!