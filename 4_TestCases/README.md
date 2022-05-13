# TEST PLAN AND OUTPUT

## High Level Requirements
| TEST ID | Description | Expected I/P | Expected O/P | Actual output | Status
|--|--|--|--|--|--|
| HR01 |Switch on the Engine| Button pressed for 2s | Red LED ON |Red LED turned ON | **SUCCESS** |
| HR02 | Switch on wiper | Three button press three modes | Sequential glow of three LEDs | Three LEDs Glown sequentially | **SUCCESS**
| HR03 | Switch off the wiper | 5th button press | Switch of the wiper|wiper switched off |**SUCCESS**
| HR04 | Turn OFF the Engine |  6th button press | Turn OFF Red LED |Red LED turned OFF |**SUCCESS**


## Low Level Requirements 

| TEST ID | Description | Expected I/P | Expected O/P | Actual output | Status
|--|--|--|--|--|--|
| LR01 |Button press  | If button not pressed for 2s | Engine not turn ON | Engine didn't turned on | **SUCCESS**
| LR02 |Button press |Second Button press |LEDs glow at 1Hz speed |LEDs glown sequentially for 1Hz|**SUCCESS**
| LR03 |Button press |Third Button press |LEDs glow at 4Hz speed |LEDs glown sequentially for 4Hz|**SUCCESS**
| LR04 |Button press |Fourth Button press |LEDs glow at 8Hz speed |LEDs glown sequentially for 8Hz|**SUCCESS**
| LR05 |Button press |Fifth Button press |Wiper system turn off |Wiper system turned off|**SUCCESS**
| LR06 |Button press |Sixth Button press |Engine turn off (Red LED turn off) |Red LED turned off|**SUCCESS**
