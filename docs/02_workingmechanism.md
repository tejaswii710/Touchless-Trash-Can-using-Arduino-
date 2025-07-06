# 03_workingmechanism


1. The **ultrasonic sensor** emits pulses and measures the echo time.
2. Arduino calculates distance from the sensor readings.
3. If an object is detected within ~30 cm, **servo motor** rotates to open the lid.
4. Lid stays open for 3 seconds, then closes.
5. Cycle repeats when the sensor detects again.
