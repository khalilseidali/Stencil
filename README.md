# Stencil
Accurate method to solder components&lt;0603
there is always problems such as cold solders or incorrect connection of components to its own pads and etc. while soldering manually. soldering 0805 or bigger components are usually manual but with this system if the PCB has mostly STM components it would be more accurate and fast to use stencil for soldering.

for this method you will need

1. Frameless thin foil : it should be etched exactly like solder-paste of STM pads on PCB.
2. soldering paste
3. Stainless metal plate ( in this case I use nickel )
4. functional system to set a circular temperature period
5. monitoring system

The first two cases are very clear and there is no need to discuss about them. my plate is ( 30x35x1 CM ) because I have 3 elements to hit up that so I can size it big enough to put more PCBs at a time. remember, the plate most be stainless.

### function
This system can adjust temperature between (20°C to 500°C)
first when operator starts the system, it needs a maximum and minimum temperature to set by. maximum most be at least the tins melt temperature and minimum most be where operator can pick the PCBs from plate and put the new ones. For this cycle, I used a PT100 sensor that is most common type of platinum resistance thermometer and is really accurate to sense the plates temperature. for processing unit I use ATmega8 and for the monitoring unit a graphical LCD is completely satisfying.

This file includes :

Codes
Two layer Altium library files ( sch - pcb - gerber - libraries )
Simulation ( proteus and an excel file :‌ resistance - voltage and temperature characteristic)
Datasheets
Stencil
View 1

