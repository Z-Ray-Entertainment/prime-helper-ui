# Prime Helper
This is a collection of shell scripts and *.desktop Files to be used with prime-select.  
Aka: suse-prime, prime-manager, optimus manager you name it.  

## Requirements
- prime-select / suse-prime / Optimus-Manager
- X11: Sorry no Wayland as prime-select does flip around X-Configfiles to to it's thing.
- bbswitch: for power managnement on older systems with out the GSP co-processor. (Pascal and older)

## Explanation
### prime-test
Test if prime-select is installed into the current system.

### prime-toggle
Switches the driver from intel to nvidia or vise versa

### prime-boot
Set's the gpu driver to be used at boot. This can be intel, nvidia or offload

#### prime-i18n
Helper script to display localized messages.