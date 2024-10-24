
# Minimalistic Detection Tool

This is a simple Python-based tool to detect promiscuous mode and ARP poisoning using `Tkinter` for the user interface and `Scapy` for network interaction. The tool provides a minimalistic interface for network monitoring.

## Features
- Detect network interfaces and select the desired one.
- Detect promiscuous mode on selected interfaces.
- Detect ARP poisoning attacks on the network.

## Requirements

To run this project, you'll need to install the required dependencies. The following Python libraries are used:

- Tkinter (for GUI)
- PIL (Python Imaging Library)
- Scapy (for network interaction)
- Psutil (for retrieving system and network information)

Install the required dependencies using pip:

```bash
pip install -r requirements.txt
```

## Instructions to Run

1. Clone the repository or download the project files.

2. Ensure you have Python installed on your system (preferably Python 3.7 or higher).

3. Install the necessary libraries:

```bash
pip install scapy psutil Pillow
```

4. Run the project:

```bash
python project.py
```

## Project Structure

- **project.py**: Main script that contains the logic for the tool's functionality and interface.
- **imagess.jfif**: Image used for displaying in the GUI.

## Notes
- This tool is designed for educational and monitoring purposes only.
- Requires root/administrator permissions for some network operations.

## GitHub Repository

You can access the project repository at: https://github.com/Sidharthc606/ARPDetectionAndPromiscuousMode
