𝗦𝗺𝗮𝗿𝘁 𝗣𝗮𝗿𝗸𝗶𝗻𝗴 𝗦𝘆𝘀𝘁𝗲𝗺 𝘂𝘀𝗶𝗻𝗴 𝗔𝗿𝗱𝘂𝗶𝗻𝗼

A fully functional, automated 𝗦𝗺𝗮𝗿𝘁 𝗣𝗮𝗿𝗸𝗶𝗻𝗴 𝗦𝘆𝘀𝘁𝗲𝗺 built with Arduino. This system optimizes parking management by tracking space availability in real time, controlling entry/exit gates, and providing visual feedback to drivers.

𝗙𝗲𝗮𝘁𝘂𝗿𝗲𝘀
𝐑𝐞𝐚𝐥-𝐓𝐢𝐦𝐞 𝐒𝐩𝐚𝐜𝐞 𝐓𝐫𝐚𝐜𝐤𝐢𝐧𝐠: Uses sensors to detect the presence of vehicles in parking slots.
𝐀𝐮𝐭𝐨𝐦𝐚𝐭𝐞𝐝 𝐆𝐚𝐭𝐞 𝐂𝐨𝐧𝐭𝐫𝐨𝐥: Opens and closes entry/exit barriers automatically when a vehicle approaches.
𝐋𝐢𝐯𝐞 𝐒𝐭𝐚𝐭𝐮𝐬 𝐃𝐢𝐬𝐩𝐥𝐚𝐲: Shows available parking slots using an LCD screen / LEDs.
𝐂𝐨𝐦𝐩𝐥𝐞𝐭𝐞𝐝 𝐏𝐫𝐨𝐣𝐞𝐜𝐭: The physical hardware and core logic are fully built, tested, and operational.

𝗛𝗮𝗿𝗱𝘄𝗮𝗿𝗲 𝗖𝗼𝗺𝗽𝗼𝗻𝗲𝗻𝘁𝘀 𝗨𝘀𝗲𝗱
𝐌𝐢𝐜𝐫𝐨𝐜𝐨𝐧𝐭𝐫𝐨𝐥𝐥𝐞𝐫: Arduino Uno / Nano / Mega
𝐒𝐞𝐧𝐬𝐨𝐫𝐬: Ultrasonic sensors (HC-SR04) or Infrared (IR) sensors
𝐀𝐜𝐭𝐮𝐚𝐭𝐨𝐫𝐬: Servo motor (for the gate barrier)
𝐃𝐢𝐬𝐩𝐥𝐚𝐲: 16x2 I2C LCD screen / LEDs (Red/Green for space availability)
𝐎𝐭𝐡𝐞𝐫: Breadboard, jumper wires, and a external power supply / USB cable

𝗥𝗲𝗽𝗼𝘀𝗶𝘁𝗼𝗿𝘆 𝗦𝘁𝗿𝘂𝗰𝘁𝘂𝗿𝗲
* `/code` — Contains the final `.ino` Arduino sketches.
* `/schematics` — Circuit diagrams, pinout connections, and wiring guides.
* `/media` — Photos and videos of the working, completed system.

𝗛𝗼𝘄 𝗜𝘁 𝗪𝗼𝗿𝗸𝘀
1. A vehicle approaches the entry gate, triggering the sensor.
2. The Arduino checks if there are empty parking spaces available.
3. If a space is open, the servo motor lifts the gate barrier and the LCD updates the count.
4. Once parked, slot sensors update the system that a spot is taken.
