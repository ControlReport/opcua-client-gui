# Nexcon OPCUA

![Nexcon OPCUA Logo](nexcon-logo.png)

**Nexcon OPC UA – Your Bridge to Industry 4.0.**

[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/FreeOpcUa/opcua-client-gui/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/FreeOpcUa/opcua-client-gui/?branch=master)
[![Build Status](https://travis-ci.org/FreeOpcUa/opcua-client-gui.svg?branch=master)](https://travis-ci.org/FreeOpcUa/opcua-client-gui)
[![Build Status](https://travis-ci.org/FreeOpcUa/opcua-widgets.svg?branch=master)](https://travis-ci.org/FreeOpcUa/opcua-widgets)

**Nexcon OPCUA** is a modern, user-friendly OPC-UA GUI client for seamless industrial connectivity.

Written using the freeopcua Python API and PyQt, Nexcon OPCUA provides essential functionalities for OPC UA server interaction: subscribe to data changes and events, write variable values, list attributes and references, and more.

![Screenshot](/screenshot.png?raw=true "Screenshot")

## Key Features

- Connect and disconnect with ease
- Browse nodes with icons per type
- View attributes and references
- Subscribe to variable changes and events
- Write variable node values
- GUI for certificates and encryption
- Method calls and value plotting
- Connection history and session restoration

## Installation

*Note: PyQT 5 is required.*

### Linux

1. Make sure python and python-pip is installed  
2. `pip3 install opcua-client`  
3. Run with: `opcua-client`  

### Windows

1. Install winpython https://winpython.github.io/ , install the version including pyqt5!
2. Use pip to install opcua-client: `pip install opcua-client`  
3. Run via the script pip created: `YOUR_INSTALL_PATH\Python\Python35\Scripts\opcua-client.exe`  

To update to the latest release run: `pip install opcua-client --upgrade`

### MacOS

1. Make sure python, python-pip and homebrew is installed
2. `brew install pyqt@5`
3. `pip3 install opcua-client pyqtgraph cryptography numpy`
4. Run with `opcua-client`

## License

This project is licensed under the MIT License.

---

*For more information, see the documentation or reach out to the Nexcon team!*