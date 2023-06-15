# simpleswitch-pack
Thanks for checking out my pack, I really just want to simplify the process even further as far as speed of start to finish for inexperienced/non-tech-saavy users.

## what is this pack
This pack is an easy way to grab one file with everything needed to:
- Make an emummc with proper protections from nintendo (exo+dns), also proper system config for cheats
- Boot that emummc directly into a ready to use & functional atmosphere
- Tinfoil was also added for convenience
- nothing more as far as plugins/customizations

## actual files
- <a href="https://github.com/Atmosphere-NX/Atmosphere">Atmosphere</a>
- <a href="https://github.com/CTCaer/hekate">Hekate</a>
- <a href="https://tinfoil.io">Tinfoil</a>
- <a href="https://github.com/rashevskyv/dbi">DBI Installer</a>
- exosphere.ini configured to block both sysmmc/emummc access to serial if on cfw
- system settings changed for edizon to function properly
- default.txt/hosts blocking file/dnsmitm
- And the final ingredient was love, a kind of love that doesnt check for proper certificates

## How to quickly mod your switch if you are not that new to all this
- Copy all files to SD (hekate.bin and fusee.bin can stay on the computer, but they can be on the SD too, it is fine to just copy all)
- Extract from the ZIP to PC "fusee.bin" and "hekate.bin"
- Put switch into RCM via an RCM jig, metal pins facing down, into the RIGHT HAND joycon port
- After jig is in correctly, Press and HOLD VOL+, and then press power while still holding. VOL+ HAS TO BE PRESSED FIRST
- Plug the switch into PC via USBC cable
- Download <a href="https://github.com/developersu/ns-usbloader/releases/tag/v7.0">nsusbloader</a>, the installer.exe or get .jar for mac/linux
- Install it, open nsusbloader, press gear icon on left, install drivers
- Press RCM button on left, Press blue folder icon, find hekate.bin, inject
- Set time in hekate, Go to Tools->Partition SD Card->Drag the RED BAR to 29FULL, press next step, follow prompts to format
- Go back to Home from top menu
- Press emuMMC->Create emuMMC->SD Partition->First Button->At 100% Press Close In Corner
- Go to Hekate Home, Press on bottom part of home menu, Reboot->RCM
- Load fusee.bin into RCM section on nsusbloader
- Inject fusee.bin
- Wait for boot, Press ALBUM button, Open DBI Installer
- Install Tinfoil NSP from SD with DBI
- Be on WiFi and open tinfoil, it will update, press B to exit, it is now installed to home menu
- Find tinfoil shops to add
