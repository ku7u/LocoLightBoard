# LocoLightBoard
Design data for building two different PCBs for connecting lighting circuits in model railroad locomotives are included.

One design expects to use only decoder powered outputs, with or without a current limiting resistor at the source. The other, with 'amped' in its name
 expects to use up to four logic level outputs from the decoder. This board will amplify those outputs using transistors on the board.
 The other two outputs on the amped board are expected to be the powered headlight and rearlight outputs (white and yellow wires). Transistors
 to be used on the amped board will be BC847B type (NOTE: this type has not been tested) or equivalent. Driver resistor values have not been determined.
 
 Both designs allow for including current limiting resistors on the board. If such a resistor is already resident in the decoder 
 then a zero ohm resistor (or a simple wire jumper) must be soldered onto the board. The boards are designed to take 0805 size SMD components.
 
 The gerber files can be submitted as is to a pcb fabrication source such as Oshpark or JLCPCB.
