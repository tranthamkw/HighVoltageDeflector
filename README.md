Schematic for high(er) voltage deflection circuit

Bill of materials is for FIVE sets of deflectors.

update 4/17/24
old design not reliable. texas instruments opamp died in prototype.

new design based on discrete component opamps.

update 4/30/24
schematic, Bill of Materials (BOM), and assembly diagram updated. 
With the present choice of Zener diodes D10 and D6, the maximum voltages are +/- 82V.  This can be increased to +/-100V by updating the zener.  Resistors R27 and R28 will need to be changed to ~1.8k.
Note, on the assembly document, that there are series 1k resistors for all out bias in/out connections.  These are intended to safegaurd in the event of a short.  The maximum current in/out any pin is 500mA, so these could be lowered to ~200Ohms.  If we are certain that no shorts will occur, remove these resistors.  Also, BNC jacks are drawn as the in/out connections.  The BNC sheild is drawn to ground (do not float the BNC shield).  Banana connectors, or any other choice of connector, may be used instead.
The maximum bias voltage is limited by the isolation transformer, N-68X, to 1500V.  That is to say, the largest common mode (lens float) voltage is 1500V. 

