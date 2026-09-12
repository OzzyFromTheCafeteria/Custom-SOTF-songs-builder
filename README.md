# SOTF Custom Music Builder

A simple tool for replacing **Sons of the Forest** radio music with your own songs.

## Demo

https://github.com/user-attachments/assets/52fcb0b9-db09-47f1-b66f-f25963cfff3e

## How to use

1. Put your `.wav` music files into:

   ```
   input\
   ```

2. Make sure the WAV files are:

   * **48 kHz**
   * **Mono**
   * **16-bit PCM WAV**

   or import
   ```
   prepare for SOTF.txt
   ```
   as macro in Audacity to quickly and easily convert 1 or many sound files to .wav and add correct formatting

4. Run:

   ```
   release\SOTF_Custom_Music_Builder.exe
   ```
5. The builder will automatically:

   * Find your Sons of the Forest installation
   * Copy the required music banks
   * Extract the banks
   * Replace the configured music slots with your songs
   * Rebuild the banks
   * Install the modified banks into the game

6. Launch Sons of the Forest and your custom music should play.

## Customising replacement slots

The replacement slots are controlled by:

```
config\replacements.json
```

Edit this file if you want to change which vanilla songs are replaced.

## Notes

* Your original `.wav` files in `input\` are not modified.
* If you have fewer songs than replacement slots, the songs will automatically cycle through the slots.
* **Back up your game files if you want an easy way to restore the original music.**
