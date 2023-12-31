# Mp3ToWav Converter
## Status:
Working(ish). The batches for this program may only run on Windows 10 due to the different PowerShell launch commands required for various OS versions, that microsoft have bizarly chosen to use for each OS, and may cause endless launch loop on other systems.

## Description
Mp3ToWav Converter is a Python script that converts MP3 files to WAV format. This is particularly useful for script compatibility or for use in platforms like Second Life. The script not only converts the files but also normalizes the volume, converts them to mono, and sets the sample rate to 44.1 kHz and bit depth to 16-bit.

## Features
1. **Convert to WAV:** Converts MP3 files to WAV format.
2. **Volume Normalization:** Normalizes the volume of the audio files.
3. **Mono Conversion:** Converts stereo audio to mono.
4. **Sample Rate and Bit Depth:** Sets the sample rate to 44.1 kHz and bit depth to 16-bit.

## Usage (windows instruction only)
1. Run 'Install.bat" to install the requirements.
2. Go to "https://github.com/BtbN/FFmpeg-Builds/releases" download windows x64 zip, extract this to folder to "Program Files" or the likes and shorten the folder name, the "./bin" folder inside must then be  system's PATH (be careful editing PATH). 
3. Place your MP3 files in the `./INPUT` directory.
4. Run 'Mp3ToWav.bat'.
5. Converted WAV files will be saved in the `./OUTPUT` directory, you must manage the rest.

## Requirements
* FFmpeg
* Python 3.x
* Requirements in 'requirements.txt'.

## Disclaimer
Use at your own risk. This script modifies audio files. Always keep a backup of your original files. If you do not fully understand what the script does, do some research or do not use the script.
