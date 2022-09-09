# Starting up, shutting down, and firmware updates

We recommend switching the X32 on before any active sound reinforcement system is connected. The function called "Safe Main Levels", located in the Setup/General Preferences screen, automatically turns down the main LRC bus levels when booting the console, and also prevents any scene loading actions from affecting (specifically turning up) the main levels.

Synchronization and Sample Rate settings can also be adjusted on the Setup/Config page, but please note that changing the sample rate will require a console reboot.

**Please Note**: Settings under ‘Link Preferences’, ‘Panning Mode’, and ‘DCA groups’ are stored with the Scene data while all other settings made on the Setup/Config page are not stored in any preset and will not be initialized either. Please verify before using the X32 that the sample rate is set correctly and if the synchronization source is selected appropriately. If set to external synchronization via one of the two AES50 ports, while no clock source is actually connected or switched on, then the corresponding small square icon in the main display’s top row would be red rather than green. In normal state you should only see 1-4 green squares in the top section depending on the units connected.

Note that if the X32 console has previously been in use by somebody else, and you feel unsure about its actual status, you can reset it to default settings in either of two convenient ways:

1. While the console is booting up and the "X32" logo appears on the screen, press and hold the "Scenes / UNDO" button, keeping it depressed until the console is fully operational and the Home screen is displayed. The console will now be in the exact same state as it was when first shipped from the factory. However, you can immediately revert back to the status the console was in before being switched off by pressing the Scenes/UNDO button.

2. You can also reset the console any time after booting by pressing "Setup/Config" -> "Initialize". The X32 regularly stores the console’s status to its onboard flash memory, so there is usually nothing wrong with switching it off, and you do not have to explicitly save the current status. However, when a large number of parameters have been recently changed, storing all of them to flash can take up to 1 minute, in a "worst-case" scenario. In order to prevent any errors by losing power during this type of storage operation, we recommend using the "Safe Shutdown" function from the Setup/Global page, an operation similar to un-mounting a USB thumb-drive from your PC.

## Updates

The X32 firmware can easily be updated by performing the following steps:

- Download the new console firmware from the X32 product page onto the root level of a USB thumb drive

- Plug the USB thumb drive into the front panel USB connector while the console is turned off

- Hold the USB View button depressed while switching the console on. While booting, the X32 will run a fully automatic firmware update, which will take 2-3 minutes longer than the regular boot sequence

When no update file is available on the USB drive, or when it is corrupted, the update mode will remain active, preventing the X32 from booting regularly. Switch the console off and back on without holding the USB View button to boot the console with the existing firmware.

The USB socket is not suitable for other non-memory USB devices like keyboards, mice, lamps, etc.