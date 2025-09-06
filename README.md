# Lenovo Thinkpad T480s
Lenovo ThinkPad T480s OpenCore Configuation for macOS Ventura.

## GenSMBIOS
We need a script, called GenSMBIOS, to create fake serial number, UUID and MLB numbers. This step is essential to have working iMessage, so do not skip it!

The process is the following:

- Download [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS).
- Start GenSMBIOS.bat and use option 1 to download MacSerial.
- Choose option 2, to select the path of the config.plist file. It will be located in EFI -> OC folder.
- Choose option 3, and enter MacBookPro15,2 as the machine type.
- Press Q to quit. Your config now should contain the requied serials.
