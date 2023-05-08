# Magisk GPIO Tools
Magisk GPIO Tools is a Magisk module that adds various GPIO tools to your Android device. These tools include gpioinfo, gpiomon, gpioset, gpiodetect, gpiofind, and gpioget binaries.

These binaries are compiled as aarch64-android33-clang and are independent and not linked like libgpiod.

### Installation
1. Download the Magisk GPIO Tools module zip file.
2. Open the Magisk Manager app.
3. Click on the menu icon in the top left corner and select "Modules".
4. Click on the "Install from storage" button.
5. Select the Magisk GPIO Tools module zip file and click on "Install".
6. Wait for the installation to complete and then reboot your device.

### Usage
Once you have installed the Magisk GPIO Tools module, you can use the various GPIO tools via the command line.

Here are some examples:

- `gpioinfo`: displays information about GPIO chips and lines
- `gpiomon`: monitors GPIO lines and prints changes
- `gpioset`: sets the value of a GPIO line
- `gpiodetect`: detects the number of GPIO chips and lines on your device
- `gpiofind`: searches for GPIO chips and lines
- `gpioget`: gets the value of a GPIO line

For more information on how to use these tools, please refer to the documentation of each tool.

### Disclaimer
Use this module at your own risk. The developer is not responsible for any damage that may occur to your device.

### Credits
- [libgpiod](https://git.kernel.org/pub/scm/libs/libgpiod/libgpiod.git).
- The Android Community and everyone who has helped me learn through the years.
- John Wu (@topjohnwu) for all things Magisk.