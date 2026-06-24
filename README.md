# Text-Editor
# Text Editor Installation Guide (Ubuntu)

This guide explains how to install and use common text editors in Ubuntu.

## Option 1: Nano Text Editor

### Install Nano

```bash
sudo apt update
sudo apt install nano -y
```

### Verify Installation

```bash
nano --version
```

### Create and Edit a File

```bash
nano sample.txt
```

### Nano Shortcut Keys

| Action | Shortcut |
|----------|----------|
| Save File | Ctrl + O |
| Exit Editor | Ctrl + X |
| Cut Line | Ctrl + K |
| Paste Line | Ctrl + U |
| Search Text | Ctrl + W |

---

## Option 2: Vim Text Editor

### Install Vim

```bash
sudo apt update
sudo apt install vim -y
```

### Verify Installation

```bash
vim --version
```

### Open a File

```bash
vim sample.txt
```

### Basic Vim Commands

| Action | Command |
|----------|----------|
| Insert Mode | i |
| Save File | :w |
| Quit | :q |
| Save and Quit | :wq |
| Force Quit | :q! |

---

## Option 3: Gedit (GUI Text Editor)

### Install Gedit

```bash
sudo apt update
sudo apt install gedit -y
```

### Launch Gedit

```bash
gedit
```

### Open a File

```bash
gedit sample.txt
```

---

## Check Installed Editors

```bash
which nano
which vim
which gedit
```

Example Output:

```text
/usr/bin/nano
/usr/bin/vim
/usr/bin/gedit
```

---

## Installed Files Locations

| Editor | Location |
|----------|----------|
| Nano | /usr/bin/nano |
| Vim | /usr/bin/vim |
| Gedit | /usr/bin/gedit |

---

## Uninstall Editors

### Remove Nano

```bash
sudo apt remove nano -y
```

### Remove Vim

```bash
sudo apt remove vim -y
```

### Remove Gedit

```bash
sudo apt remove gedit -y
```

### Remove Unused Packages

```bash
sudo apt autoremove -y
```

---

## Recommended Editor

- **Nano** – Easy for beginners.
- **Vim** – Powerful for advanced users.
- **Gedit** – User-friendly graphical editor.

---

**Author:** Goutham 
**Purpose:** Text Editor Installation and Usage on Ubuntu
