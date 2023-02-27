"""
# Win10-calculator-python
Example script for Calculator on Windows 10

Requirements:
  - OS Windows 10
  - pywinauto 0.6.1+ (install it by typing in the terminal : pip install pywinauto)

Win10 version of Calculator is very specific. Few different processes (!)
own different windows and controls, so the full hierarchy can be accessed
through Desktop object only.

Minimized Calculator is a process in a "Suspended" state.
But it can be restored with some trick for invisible main window.
"""
