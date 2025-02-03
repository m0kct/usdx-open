# Modifications made by Alex M0KCT to his "white buttons" uSDX (v3 PCB):

1. Ground the case by connecting the ground of the BNC connector to the two
case screws near it using a piece of aluminium tape.

2. Solder 100K resistor to the R23 pad.

3. Remove C24 and C27 (10nF capacitors) and replace them with 10nF ceramic
capacitors between MOSI and GND and between MISO and GND on a plug that
attaches to the ISP header.  The plug can then be removed for programming and
put back once finished.

References:
* https://lipkowski.com/2024/11/28/usdx-simple-modifications/
* https://www.vk4sn.com/Radios/USDX
* https://www.youtube.com/watch?v=oPDza8W7pGQ
* https://github.com/TekMaker/uSDX-QRP-Transceiver/blob/main/uSDR%20Manual_V1.0.pdf

