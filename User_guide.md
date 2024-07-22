
### User Guide for Your Arduino DIY Meteo Station

#### Getting Started

**Power Supply:**
- Ensure you have a 5V, 2A power supply connected to your meteo station. Once connected, the station will start automatically.

**Internal Timer Module:**
- The station uses a DS3231 timer module with a CR2032 battery to keep time accurately.

#### Display Modes

Your meteo station has several modes to display various information such as time, date, and sensor data. Here’s a quick rundown of how to navigate these modes using the sensor button:

- **Mode '0':** Displays the current time, date, and all sensor readings.
- **Modes '1'-'6(8)':** Depending on the number of sensors, these modes show different diagrams (temperature, humidity, pressure, etc.).

#### Button Functions

**Single Click (Sensor Button):**
- Cycles through display modes in a loop from '0' to '6(8)'.

**Long Press (Sensor Button):**
- Resets the display to mode '0'.

**Double Click (Sensor Button):**
- Switches to clock settings mode ('101').

#### Clock Settings Mode ('101')

In this mode, you can set the time and date. Here’s how to do it:

**Single Click (Sensor Button):**
- Increases the value of the current parameter (hours, minutes, day, month, year).

**Long Press (Sensor Button):**
- Saves the current parameter and moves to the next one. If you are on the last parameter, it saves all changes and exits to mode '0'.

**Double Click (Sensor Button):**
- Discards all changes and exits to mode '0'.

#### CO2 Sensor Calibration

To calibrate the CO2 sensor, press the 'reset' button. The current air state will be considered as 'normal' (~400ppm).

---

### Example: How to Set Up the Time and Date

1. **Enter Clock Settings Mode:**
   - **Double click the sensor button** to switch to clock settings mode ('101').

2. **Set the Hour:**
   - **Single click the sensor button** to increase the hour. Repeat until the desired hour is displayed.
   - **Long press the sensor button** to save the hour and move to the minutes setting.

3. **Set the Minutes:**
   - **Single click the sensor button** to increase the minutes. Repeat until the desired minutes are displayed.
   - **Long press the sensor button** to save the minutes and move to the day setting.

4. **Set the Day:**
   - **Single click the sensor button** to increase the day. Repeat until the desired day is displayed.
   - **Long press the sensor button** to save the day and move to the month setting.

5. **Set the Month:**
   - **Single click the sensor button** to increase the month. Repeat until the desired month is displayed.
   - **Long press the sensor button** to save the month and move to the year setting.

6. **Set the Year:**
   - **Single click the sensor button** to increase the year. Repeat until the desired year is displayed.
   - **Long press the sensor button** to save the year and exit to mode '0'.

7. **Discard Changes (if needed):**
   - At any time during the clock setting mode, **double click the sensor button** to discard all changes and return to mode '0'.

---

This user guide should help you navigate and use your Arduino DIY meteo station effectively. If you have any more questions or need further assistance, feel free to ask!

