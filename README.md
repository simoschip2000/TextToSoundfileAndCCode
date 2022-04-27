# TextToSoundfileAndCCode
Converts text to "SOMENUMBER.wav". C code is generated to easily identify the right soundfiles.

# Background
Microcontroller have limited programming memory. Saving a string for each soundfile would require a lot of memory.

# Prerequisites
Install the pyttsx3 Library:
```
pip install pyttsx3
```

# Usage
Modify the "listOfStrings" in the "Generator.py" file for your needs. Also set the right voice according to your language and your preferences.

# Output
The output files are located in the "output" folder. Include the "voiceOutputNumbers.h" in your C project and easily access the right ".wav" file.
Note that ".wav" files are generated for numerals and letters aswell according to ASCII.
