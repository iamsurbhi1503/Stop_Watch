# Stop_Watch - https://iamsurbhi1503.github.io/Stop_Watch/

This JavaScript code implements a simple timer. It displays hours, minutes, seconds, and milliseconds. The timer includes functionality to start, pause, and reset.

#Usage

1. Start Timer: Click the "Start Timer" button to begin the timer. If the timer is already running, clicking this button will reset it and start from 0.
2. Pause Timer: Click the "Pause Timer" button to halt the timer. This will freeze the timer at its current value.
3. Reset Timer: Click the "Reset Timer" button to stop the timer and set all values back to zero.

#Implementation

1. The timer values (milliseconds, seconds, minutes, hours) are initialized to zero.
2. The displayTimer function is responsible for updating the timer values and displaying them in the specified format (HH : MM : SS : MS).
3. The setInterval function is used to repeatedly call the displayTimer function at intervals of 10 milliseconds, creating the timer effect.
4. The "Start Timer" button starts or resets the timer, and the "Pause Timer" button halts the timer.
5. The "Reset Timer" button stops the timer and resets all values to zero.

   Feel free to customize and integrate this timer into your projects as needed.
