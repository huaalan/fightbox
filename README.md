# Fightbox
All button fightbox with 11 buttons

# Firmware
Use https://gp2040-ce.info/ to flash firmware
1. Download firmware. It is recommended to get the one for flatbox 5.
2. Flash the firmware, connect the board to a computer with a USB cable, then press the RESET button while holding the BOOT button on the RP2040-Zero. A drive named "RPI-RP2" should appear. Copy the UF2 file you downloaded to that drive.
3. Now that firmware has been flashed, use the built in web configurator to map buttons and configure controller (instructions at gp2040-ce.info)

# Troubleshooting
Start button bind missing?
If you used a firmware other than flatbox 5, try using the flatbox 5 since the pinouts for other firmware could be different.

Missing start button to get into web config after rebinding.
If you can't get the start bind back from flashing firmware, you will want to do a nuke flash and reflash the flatbox firmware so you will have the default buttons. The nuke flash will wipe all configurations.
