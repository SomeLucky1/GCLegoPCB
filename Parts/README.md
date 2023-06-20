## Soldered Components

- ### JST-XH 2.54mm Male Headers
    - 3x 3P (Boiler SSR,Brew/Steam Switches,Pressure Transducer)
    - 1x 2P (12V LED)
    - 1x 4P (Display)
    - 1x 5P (Scales)
    
    <br>
- ### Male Pin Headers
    - 28x 11.5mm
    - 4x 15mm
    - (optional) 1x 2x2 right angle 3mm/6mm board/header

    <br>
- ### Female Pin Headers
    - 8x 2P (5V PSU,12V PSU,FR120N, QWIIC Shim)
    - 2x 20P (Blackpill)
    - 2x 3P (12V PSU,FR120N)
    - 1x 7P (ADS1115)
    - 1x 5P (MAX6675)
    - 3x 4P (Dimmer, I²C Shifter)

    <br>
- ### Screw Terminals
    - 1x 3P 5mm pitch - Bundled with most FR120N preassembled boards
    - (optional) 4x 10P 2.54mm pitch

    <br>
- ### Power/3WV/Pump Connections
    - 4x Male blade quick connect terminals
    - (optional) Molex 4P Mini Fit Jr. 90 degree mount -- for use with Molex Power design PCB

    <br>
- ### Resistors ¼W
    - 1x 1kΩ - for use with hardware scales
    - (optional) 1x 330Ω - If 3WV SSR requires

    <br>
- ### 3-Way Solenoid Valve SSR (choose one)
    - Omron G3MB-202P 5V - No input resistor requried (short R1 Bypass solder pad)
    - Panasonic AQG12105 - Input resistor required

    <br>

## Lego Part Modifications
Part|3D Model|Mod
---|---|---
![Dimmer](/Parts/Images/DIMMER.JPG "Dimmer")|[STL](/Parts/Images/STL/RDDimmer.stl "Dimmer") <br> [STEP](/Parts/Images/STEP/RDDimmer.step "Dimmer")|No modifications required
![12V PSU](/Parts/Images/12VPSU.JPG "12V PSU")|[STL](/Parts/Images/STL/12V1APSU.stl "12VPSU") <br> [STEP](/Parts/Images/STEP/12V1APSU.step "12VPSU")|Use 15mm male pin headers
![5V PSU](/Parts/Images/5VPSU.JPG "5V PSU")|[STL](/Parts/Images/STL/SY8205.stl "5VPSU") <br> [STEP](/Parts/Images/STEP/SY8205.step "5VPSU")|Use 11.5mm male pin headers
![MAX6675](/Parts/Images/MAX6675.JPG "MAX6675")|[STL](/Parts/Images/STL/MAX6675.stl "MAX6675") [STL](/Parts/Images/STL/KPlugPCBMount.stl "KPLUG")<br> [STEP](/Parts/Images/STEP/MAX6675BB.step "MAX6675") [STEP](/Parts/Images/STEP/KPlugPCBMount.step "KPLUG")|Straighten pins<br><br>(optional) Use PCB mountable female mini K-type plug
![TCM4](/Parts/Images/TCM4.JPG "TC Sensor - M4")||(optional) Use male mini K-type plug
![ADS1115](/Parts/Images/ADS1115.JPG "ADS1115")|[STL](/Parts/Images/STL/ADS1115.stl "ADS1115") <br> [STEP](/Parts/Images/STEP/ADS1115BB.step "ADS1115")|Use 11.5mm male pin headers
![FR120N](/Parts/Images/FR120N.JPG "FR120N")|[STL](/Parts/Images/STL/MosfetBoard.stl "FR120N") <br> [STEP](/Parts/Images/STEP/MosfetBoard.step "FR120N")|Use 11.5mm male pin headers<br><br>Bend 12V/Load pins to 2.54mm pitch width
![QWIIC SHIM](/Parts/Images/QWIIC_Shim_Module2.png "QWIIC SHIM")|[STL](/Parts/Images/STL/LevelConverter.stl "Level Shifter") [STL](/Parts/Images/STL/QWIICShim.stl "QWIIC Shim") <br> [STEP](/Parts/Images/STEP/LevelConverter.step "Level Shifter") [STEP](/Parts/Images/STEP/QWIIC%20SHIM.step "QWIIC Shim")|  Qwiic connector and I²C 3.3V regulation module.