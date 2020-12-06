# troubleshooting-OS-Virtualization
Contains notes on how to tackle every errors, problems that occurred related to virtualization any OS.
P stands for Problem, S stands for Solution.


## Installation

### PI1     : Unsuccessful EFI Network Process (case: installing windows 10 x64)
#### SI1    :
* Change Firmware Type in Advanced Options from edit virtual machine to BIOS (it was EFI)
* Make sure that the iso file is already assigned in vmware

## Operation


### PO1     : Innacurate mouse position
#### SO1    : 
* uncheck override high DPI scalling behavior.
    * It located in compatibility tab (vmware's properties) --> inside change high DPI settings