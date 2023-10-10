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

Road-map:

  1. Acquire USB to Serial converter and create custom USB plug for reading/writing firmware to XR871 chip.
  2. Determine if existing firmware image can be de-compiled and edited or if a new FW will need to be written from scratch.
  3. Trace out all connections and create a detailed schematic of the motherboard.
  4. Create custom firmware. Can I make this thing run Linux?
  5. Use Codi as a control hub for smart devices similar to Siri or Alexa... Mycroft or Rhasspy?

Ignored files/folders:

  * SDK: This is where I clone the XRadio sdk into my project https://github.com/XradioTech/XR871SDK

  * SD_Contents: This is where I put the files off of the SD card in the Codi in case I need them later
