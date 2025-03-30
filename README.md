# Vitis Scripts  

A collection of scripts to simplify and automate your Vitis workflow.  

You can find my suggested Vitis workflow here:  [Vitis Workflow](https://github.com/everythingFPGA/vitis_workflow.git)  

## Installation  

You can add this repository as a Git submodule in your Vitis project with:  

``` sh
git submodule add https://github.com/everythingFPGA/vitis_scripts.git
```

## Requirements
- Vitis Unified IDE (full version)
- Python 3

## create_platform.py
A Python script to recreate the platform environment for Vitis Unified IDE starting from the **.xsa** and **.spfm** files

It currently supports:
- single platform projects
- multiple domains
- Zynq Series 7000, Ultrascale+, Versal

Run the script using:

```sh
vitis -s create_platform.py
```

Additional Requirements:
- **tkinter** (optional, for Windows GUI-based features)

Tested on: Windows 11 with Vitis Unified IDE 2024.2

