# Echelon Tool

![Echelon Banner](https://i.imgur.com/z1zF1QZ.png) <!-- (İsteğe bağlı olarak banner URL'sini kendi görselinle değiştir) -->

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

### Termux

```bash
pkg update && pkg upgrade
pkg install git -y
pkg install python -y
git clone https://github.com/echelonvanta/Echelon
cd Echelon
bash install.sh
