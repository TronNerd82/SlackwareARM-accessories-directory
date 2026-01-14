# SlackwareARM accessories directory
A user-contributed directory of links to purchase accessory hardware required by or otherwise benefiting the user experience of Slackware ARM

The creation of this GitHub repo was inspired by a suggestion from Stuart Winter, the lead maintainer of Slackware ARM, seen in this thread on the LinuxQuestions forum ( https://www.linuxquestions.org/questions/slackware-arm-108/user-contributed-links-to-accessory-hardware-required-recommended-by-slackware-arm-4175757312/ ). Links posted on this thread will also be included here, with credit given to the LQ user who posted it.

## The bare minimum recommended hardware:
* Your single-board computer of choice and its according power supply
* A USB multi-card reader ( EXAMPLE: https://www.amazon.com/UGREEN-Adapter-Windows-Surface-Chromebook/dp/B01EFPX9XA )
* A USB-to-serial adapter ( ideally must use a PL2303 chip; others may work, but the Slackware ARM project has only tested this one )
* A USB-to-SATA cable of some kind ( EXAMPLE: https://www.amazon.com/StarTech-External-Converter-Transfer-OS-Independent/dp/B00HJZJI84/ )
* A 2.5" SATA SSD; your choice of size and brand ( a HDD can also work, but must use external power in most cases )
* A real-time clock setup for your machine, if necessary ( some devices like the Raspberry Pi don't include a RTC, so time doesn't stay synced - follow the Slackware ARM install guides to deal with this issue )

Other items can be used, such as NVMe drives if the hardware supports it, and some devices like the USB-to-serial adapter are unnecessary if they don't fit your needs. Just know that such setups are TECHNICALLY unsupported by the Slackware ARM project, though many users will have little to no issue using such varied setups. Your mileage may vary.

## How to contribute
  Start a pull request with your edits of the README.md file. Include (on a new line below the bottom link) one or more links to the accessories you'd like added to the directory.
  You must give the name of the product, followed by the link itself enclosed in parentheses ( like this ). Then add a section in brackets [ like this ] with the phrase "contributed by 'your GitHub username'" so proper credit can be given.
  I don't check GitHub as often as I should, so your contributions, valued as they are, may not be added right away, but I'll certainly try to add them in a timely fashion.

## User-contributed links directory
Here reside the links to any and all hardware that users of Slackware ARM contribute to this page. Hardware is grouped by the release of Slackware ARM the user is running/targeting, and subgrouped into additional categories based on hardware device type, such as USB, networking, PCI, etc. If a category you'd like to see does not exist, feel free to open an issue suggesting a new category; in most cases, I'd be more than happy to add it if it seems necessary.

### Releases
Currently, the only two supported releases of Slackware ARM are: Slackware ARM 15.0, the 32-bit stable release, and Slackware AArch64 -current, the 64-bit development/rolling branch. Once Slackware ARM 15.1 comes out, 32-bit ARM support will be gone. Releases before 15.0 that are EOL (End-Of-Life) may also have links contributed via a separate .md file. Once a currently-supported release becomes EOL, it will be moved to the file for EOL releases.

#### Slackware ARM 15.0 (32-bit)
##### USB devices
To be populated
##### Networking
To be populated
##### Storage
To be populated
##### Miscellaneous
To be populated

----------

#### Slackware AArch64 -current (64-bit)
##### USB devices
To be populated
##### Networking
To be populated
##### Storage
To be populated
##### PCI devices
To be populated
##### Pi hats
To be populated
##### Miscellaneous
To be populated
