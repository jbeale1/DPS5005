Based on https://github.com/TheHWcave/DPS5005-control/tree/master/update-1

6-26-2024 JPB:
Modified to take input from an additional, separate external serial device working as a sensor, in addition to the DPS5005 device serial connection, and include that external sensor's 1-line output string along with the DPS5005 data in the recorded file. The sensor is presumed to frequently emit measurements, without prompts, so it is an output-only device in this usage.
