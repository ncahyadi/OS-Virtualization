# troubleshooting-OS-Virtualization
Contains notes on how to tackle every errors, problems that occurred related to virtualization any OS.

## Code Terms
P          = Problem  
S          = Solution  
vm-version = using VMware


## Installation

### PI1-vm16     : Unsuccessful EFI Network Process  (case: installing windows 10 x64)
#### SI1-vm16    :
* Change Firmware Type in Advanced Options from edit virtual machine to BIOS (it was EFI)
* Make sure that the iso file is already assigned in vmware

## Operation

### PO1-vm16     : Innacurate mouse position
#### SO1-vm16    : 
* uncheck override high DPI scalling behavior.
    * It located in compatibility tab (vmware's properties) --> inside change high DPI settings
### PO2-vm16     : Setting connection between several machines
#### SO1-vm16    :
