# Python Backdoor & Server Lab

An educational Python project demonstrating client-server communication in a controlled cybersecurity lab environment.

## Project Structure

```text
python-backdoor-lab/
├── backdoor.py
├── server.py
├── requirements.txt
└── README.md
```

## Description

This project is designed for cybersecurity education and controlled laboratory testing.

* `server.py` — Server-side component used to communicate with the client.
* `backdoor.py` — Client-side component used to establish communication with the server.

> **Disclaimer:** This project is intended only for authorized testing, cybersecurity labs, and systems owned or controlled by the user. Do not use it to access or control systems without explicit permission.

## Requirements

* Python 3.10 or newer
* A controlled testing environment
* Network access between the lab machines, if the project uses multiple machines

Install the Python dependencies with:


pip install -r requirements.txt

## Running the Project

Start the server first:


python server.py

Then, from the authorized lab environment, run:

python backdoor.py

Make sure the server address and port configured in the client match the server configuration.

## Educational Purpose

This project can be used to study:

* Python networking
* Client-server architecture
* TCP communication
* Basic cybersecurity concepts
* Detection and analysis of suspicious network behavior

## Legal & Ethical Notice

Use this software only on systems you own or have explicit permission to test.

The author is not responsible for unauthorized use of this project.
