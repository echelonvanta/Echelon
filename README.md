# Echelon Tool

**Echelon** is a multifunctional tool built for both **Termux** and **Kali Linux** environments. It offers a fast and user-friendly interface for automation, information gathering, and more—all from your terminal.

---

## Features

- Full support for **Termux** and **Kali Linux**
- Automatic installation and configuration
- Clean and intuitive menu interface
- Fast execution and multiple script modules
- Custom terminal utilities

---

## Languages Used

- **Bash**
- **Python**
- Utilities: `curl`, `wget`, `grep`, `awk`, etc.

---

## Installation

### For Termux

1. First, update and upgrade your system:

    ```bash
    pkg update && pkg upgrade
    ```

2. Install the necessary packages:

    ```bash
    pkg install git -y
    pkg install python -y
    ```

3. Clone the repository and navigate to the project folder:

    ```bash
    git clone https://github.com/echelonvanta/Echelon
    cd Echelon
    ```

4. Run the setup script:

    ```bash
    python setup.py install
    ```

---

### For Kali Linux

1. Update and upgrade your system:

    ```bash
    sudo apt update && sudo apt upgrade
    ```

2. Install the necessary packages:

    ```bash
    sudo apt install git -y
    sudo apt install python3 -y
    ```

3. Clone the repository and navigate to the project folder:

    ```bash
    git clone https://github.com/echelonvanta/Echelon
    cd Echelon
    ```

4. Run the setup script:

    ```bash
    python3 setup.py install
    ```

---

## Usage

Once installed, you can launch the tool by running:

```bash
python3 echelon.py
