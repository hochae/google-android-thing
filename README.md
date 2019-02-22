# AI-speaker

## Google Andoid Things 
- ### [i.MX7D](https://developer.android.com/things/hardware/imx7d)
  - Low-power requirements with a high degree of functional integration.
  - ARM®Cortex®-A7 2 cores, operating at speeds of up to 1.2 GHz
  - ARM® Cortex®-M4 core
  - The [Pico variant of GApps](https://opengapps.org/) is pin-compatible with the [Intel® Edison](https://en.wikipedia.org/wiki/Intel_Edison) for sensors and low-speed I/O
  - also adds additional expansion possibilities for multimedia and connectivity
  - can easily be expanded and implemented for IoT designs.
  - #### [Flashing Image](https://developer.android.com/things/hardware/imx7d#flashing_the_image)
- ### [Raspberry Pi3](https://developer.android.com/things/hardware/raspberrypi)


## NXP I.MAX 7D Image burning sequence
- Image file
  - android-things-setup-utility.zip
- Operation procedure
  1. Unzip Android thing setup utility
  2. Excute android-things-setup-utility-windows.exe
     1. Select opetion 1 for the first installation 
     2. Select NXP Pico i.MX7D
     3. Select custome image (Subsequent TechNexion Diana wants us to choose 1.Default image For Android Things 1.0)
        - start image zip file burning process
        - the system will be automatically detected and starts burning
        - After successful burning, the wifi setup window will be pop up
        - Debug port is Micro USB type, Baud rate 115200, 8 bits, no pariy check, stop bit 1
  3. Install Android USB driver for Android studio
     - SDK manager tool
     - Google USB driver
  4. Jumper setup for Boot mode
     - 
     
