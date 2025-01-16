# Countdown Timer ⏳

This Python program implements a simple countdown timer. It allows the user to input a duration in seconds and counts down to zero, displaying the remaining time each second. When the countdown ends, it displays a "Time's up!" message.

---

## Features
- **User Input**: Prompts the user to input the countdown duration in seconds.
- **Dynamic Countdown**: Displays the remaining time for each second until the timer reaches zero.
- **Error Handling**: Handles invalid input (e.g., non-numeric values) gracefully, prompting the user to enter a valid number.
- **Time Management**: Uses `time.sleep()` to create real-time delays for a smooth countdown experience.

---

## How It Works
1. The user is prompted to enter the countdown time in seconds.
2. The program validates the input:
   - If the input is numeric, the countdown begins.
   - If the input is invalid, an error message is displayed.
3. During the countdown:
   - The program prints the remaining time for each second.
   - It pauses for 1 second between updates using the `time.sleep()` function.
4. Once the countdown reaches zero, the program prints a final message: **"Time's up!"**

---

## Code Walkthrough
### 1. **Importing the `time` Module**
```python
import time
