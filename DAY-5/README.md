# Python Alarm Clock ⏰

This Python script is a simple and customizable alarm clock. It allows you to set an alarm for a specific date and time, with the option to play either a music file or a beep sound as the alarm tone.

## Features
- **Set Alarm Date and Time**  
  Input the date and time in a user-friendly `HH:MM AM/PM` format for accurate scheduling.
- **Customizable Alarm Sound**  
  - Play a music file (`audio.wav`) for the alarm tone.  
  - Generate a beep sound with user-defined frequency and duration (Windows only).
- **Real-Time Monitoring**  
  The script continuously checks the current date and time to ensure precise alarm triggering.

## Requirements
- Python 3.x
- Required Python libraries:
  - `datetime` (standard library)
  - `playsound` (for playing music)
  - `winsound` (for beep sound; Windows only)
