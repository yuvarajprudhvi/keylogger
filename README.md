# Keylogger Project

This is a simple keylogger built using Python, utilizing the **pynput** library for key event monitoring and **Tkinter** for the graphical user interface (GUI). The keylogger captures keypress and release events and stores them in both text and JSON formats for educational purposes.

## 🚀 Features

- **Keylogging**: Captures all keypress and release events.
- **Text Logging**: Logs keys pressed into a text file (`key_log.txt`).
- **JSON Logging**: Stores key events (Pressed, Held, Released) in a structured JSON file (`key_log.json`).
- **Start and Stop**: Control the keylogger using the Start and Stop buttons.
- **Simple GUI**: Built using Tkinter, displaying the status of the keylogger.

## 🛠️ Technologies Used

- Python
- Tkinter (for GUI)
- Pynput (for key event monitoring)
- JSON (for structured data storage)


## 🚀 Getting Started

To get started with the keylogger, follow these steps:
1. **Clone the repository**
   ```bash
   git clone https://github.com/yuvarajprudhvi/keylogger.git
   ```

2. **Install dependencies**
   ```bash
   pip install pynput
   ```
3. **Run the keylogger**
   ```bash
   python3 keylogger.py
   ```

4. **Start/Stop the keylogger**
  ```bash
- Press the **Start** button to begin keylogging.
- Press the **Stop** button to stop the keylogger.
  ```


## 📱 Responsiveness

- The application is designed for desktop use and operates in a basic window with controls for starting and stopping the keylogger.

## 🔑 Key Components

- **`keylogger.py`**: The main script that runs the keylogger and handles key press/release events.
- **`key_log.txt`**: The text file that stores the pressed keys.
- **`key_log.json`**: The JSON file that stores the key events (Pressed, Held, Released).

## 📝 License

This project is licensed under the **Educational Use License** - see the LICENSE file for details.

## 🤝 Contributing

If you wish to contribute to this project:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## 🙏 Acknowledgments

This project was built for educational purposes, to learn about keylogging mechanisms and security principles.

**Disclaimer**: This keylogger is for educational purposes only. Misuse of this software is prohibited and could result in legal consequences.


