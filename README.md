# Splat Transform GUI

A simple Python GUI wrapper for [@playcanvas/splat-transform](https://github.com/playcanvas/splat-transform), allowing you to convert point cloud files with ease on Windows.  

This GUI allows you to:  
- Select a point cloud file (e.g., `.ply`).  
- Choose the output format (`ply`, `sog`, `meta.json`, `compressed.ply`).  
- Automatically handle overwriting existing files with user confirmation.  
- View live logs of the conversion process.  

---

## Features

- Detects if `@playcanvas/splat-transform` is installed and installs it if missing.  
- Uses the correct CLI syntax for the latest version (v0.13.1).  
- Keeps the original file intact and creates a new output file in the same folder.  
- Displays live conversion logs in the GUI.  

---

## Requirements

- Python 3.x  
- Tkinter (usually comes with Python)  
- Node.js + npm installed globally  
- `@playcanvas/splat-transform` (installed automatically if missing)  

---

## Usage

1. Run the exe
