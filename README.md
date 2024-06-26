# 3DS Description
This is for research and education purposes on how to get the most out of an outdated and currently unmaintained consumer product, Nintendo 3DS.


Follow this [link](https://3ds.hacks.guide/get-started.html) to get started.

https://3ds.hacks.guide/get-started.html


# Getting Started


## System Check
To make sure that your 3DS is up to date
1. Launch System Settings on your console.
2. Verify that the bottom right on the top screen is "Ver. 11.17.0-50U"

## I. Installing boot9strap (MSET9)
**Requirements:**
Make sure that Python 3 is installed on your computer.
Download the MSET9 file in this repo, if [MSET9](https://github.com/zoogie/MSET9/releases/tag/v1.2) no longer works.

1. Power on your console with SD card inserted
2. Open Mii Maker
3. Wait, until Mii Maker loads, if this was the first time opening it give it a little more time
4. Power off your console and insert your SD card into your computer
5. Copy all of the contents of the `MSET9` into the root/main part of the SD card

6. Run MSET9 (mset9.bat for windows)
7. Follow the instructions, depending on the model, (but you should only be using 1 or 2 if you are up to date)
8. Once you successfully, do that page press `1. Perform sanity checks`
9. If the message "Everything appears to be functional!", press enter and insert your SD card into your 3DS.

## II. MSET9
**Very SPECIFIC INSTRUCTIONS**
1. Power on your console.
2. Hover over the System Settings using the **D-Pad** (do not open it)
3. Press (A) to launch System Settings
4. Go to `Data Management -> Nintendo 3DS -> Extra Data`
5. With everything STILL ON, remove SD card with pressing any button or touching the screen
6. Insert your SD card into your computer
7. Run MSET9 again
8. Type in your console number again (same as section 1 number 7)
9. On the next page run `2` and press enter
10. Reinsert your SD card into the console

MSET9 should now be successfully installed

## III. Installing bott9strap (OS, not really)
1. First, follow the key combo on the bottom screen
2. Press (A) to reboot your console
3. Your console should have booted into Luma3DS custom firmware
4. Leave all of the configuration on default
5. Press (Start) to save and reboot

## IV. Removing MSET9
Removing MSET9 will prevent future crashes in the future.
1. Power off your console
2. Insert your SD card into your computer
3. Run MSET9, again
4. Type in your console number again (same as section 1 number 7)
5. On the next page run `3`


We will now be installing the big stuff

## V. Prep Work
1. Power off your console
2. Insert your SD card into your computer
3. Copy `finalize.romfs` to the root fo your SD card
4. Open the `luma` folder on your SD card and create a folder named `payloads` inside, if it does not already exist
5. Copy `finalize_helper.firm` to the `payloads` folder
6. Insert SD card into console

## VI. Updating the System
1. Update your console `System Settings -> Other Settings -> System Update`

## VII. RTC and DSP setup
1. Press (Left Shoulder) + (D-Pad Down) + (Select) combo to open the Rosalia menu
2. Select "Miscellaneous options"
3. Select "Dump DSP firmware"
4. Press (B) to continue
5. Select "Nullify user time offset"
6. Press (B) to continue
7. Press (B) to return to the Rosalina main menu
8. Press (B) to exit the Rosalina menu

## VI. Setup Script
1. Power off your console
2. Press and hold (Start), and power on your console. (This should launch the finalizing Setup Helper)
3. If the Helper was successful, your console will boot into GodMode9
4. If you are promoted to create an essential files backup, press (A) to do so, then set the date and time, then press (A) to continue
5. If you are prompted to fix the RTC date&time, press (A) to do so, then set the date and time, then press (A) to continue
6. Press (Home) to bring up the action menu
7. Select "Scripts..."
8. Select "finalize"
9. Follow the prompts in the script, answering any questions that you are asked
10. Once the scripts says "Setup complete!", press (A) to power off the device
11. Insert your SD card into your computer
12. Copy the `/gm9/backups/` folder to a safe location on your computer

You're Done! all of your custom firmware on configured on your console!
