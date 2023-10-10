# opencodi
Open source software for the Pillar Codi Robot

Coming up with a new firmware for this device is worth the time for a few reasons:

  1. These devices are cheap and readily available on ebay
  2. They look like a Reddit avatar
  3. They have all the right peripherals to make a cool IoT device
  4. The company is unresponsive and maybe out of business

Here's what I've got so far:

I have disassembled the toy and found what hardware it is using:

  * Main processor: XR871ET
    
  * Audio processor: A101
    
  * Bluetooth(?): JL AS20AP24150
    
  * Storage: GD25Q64C

Ignored files/folders:

SDK: This is where I clone the XRadio sdk into my project https://github.com/XradioTech/XR871SDK
SD_Contents: This is where I put the files off of the SD card in the Codi in case I need them later
