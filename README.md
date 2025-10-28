# UDON V2 | Rivals Robotics Competition
UDON V2 ISO Picture:
![UDON ISO render](Pictures/UdonISOImage.png)

Onshape Link:
https://cad.onshape.com/documents/64d3a7b3a5a997c633685ba5/w/7495e428fcc4a5cb4c65dc9c/e/3e5da57740d178980547a374 

Feel free to make a copy and use it as a base for your robot!

## Rival Robotics
RIVAL Robotics Competition is a robotics competition for all ages targeted at advanced builders. There are multiple events with a different challange each year. For more information, visit https://www.rivalrobotics.co/

## Highlights
- 12x12 Mecanum Drive Base
- Compliant Shuttlecock Intake
- L1, L2 Shooter
- EDF Blower
- Silo Dumper

## Overview
UDON V2 is a shooter robot meant to compete in the Rival Robotics Competition. Its main goal is to shoot missiles (badminton shuttlecock) onto platforms on the goal post.

<table>
  <tr>
    <td valign="top" width="80%">
      <img src="Pictures/RivalFieldImage.png" width="100%" alt="Field ISO Render">
    </td>
    <td valign="top">
        Image of the Rival Robotics "DOOMSDAY" Field
    </td>
  </tr>
</table>

This robot intakes the missiles off the ground to shoot it up into the L2 platforms. It also has the ability to "silo dump" or drop all the missiles out of the tube. The EDF on the back of the robot allows for large area "acquisition" of the missiles and blow it to the other side.

### Why?
UDON V2 was created in order to explore further levels of advanced robotics. Coming from an FRC and Robotics background, UDON acts as a way to build and learn skills as well as grow the RIVAL community. Tonkotsu Tech, the overarching group overseeing UDON, has made contributions to RIVALS and wishes to continue that through UDON.

## Pictures:
![UDON Front View](Pictures/UdonFrontImage.png)
![UDON Top View](Pictures/UdonTopImage.png)

## Control System
UDON V2 is based off the moteus control system (https://mjbots.com/) which is a high precision control system with the Raspberry Pi 4 at its core. 

- Raspberry Pi 4
- pi3Hat r4.5
- moteus-r4 Motor Controller
    - Controls 6 5010 Brushles Motors
- mjpower-ss

## Bill of Materials List:

You can download the full CSV here: [UDON BOM - TEST Purchase.csv](UDON%20BOM%20-%20TEST%20Purchase.csv)
<table>
  <colgroup>
    <col width="8%" />
    <col width="60%" />
    <col width="12%" />
    <col width="8%" />
    <col width="6%" />
    <col width="6%" />
  </colgroup>
  <thead>
    <tr>
      <th align="left">Vendor</th>
      <th align="left">Item</th>
      <th align="right">SKU</th>
      <th align="right">Cost</th>
      <th align="right">Amount</th>
      <th align="right">Total</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>WCP</td>
      <td>1.625" OD x 1/2" Wide Straight Flex Wheel (1/2" Hex Stretch, 30A)</td>
      <td align="right">WCP-1281</td>
      <td align="right">$2.99</td>
      <td align="right">4</td>
      <td align="right">$11.96</td>
    </tr>
    <tr>
      <td>WCP</td>
      <td>1.625" OD x 1/2" Wide Straight Flex Wheel (1/2" Hex Stretch, 45A)</td>
      <td align="right">WCP-1282</td>
      <td align="right">$2.99</td>
      <td align="right">10</td>
      <td align="right">$29.90</td>
    </tr>
    <tr>
      <td>WCP</td>
      <td>.375" OD x .159" ID Rounded Hex Stock (36")</td>
      <td align="right">WCP-0911</td>
      <td align="right">$19.99</td>
      <td align="right">1</td>
      <td align="right">$19.99</td>
    </tr>
    <tr>
      <td>Fabworks</td>
      <td>Mecanum Frame Plates</td>
      <td align="right">25-10-5300</td>
      <td align="right">$142.10</td>
      <td align="right">1</td>
      <td align="right">$142.10</td>
    </tr>
    <tr>
      <td>Amazon</td>
      <td>4010 Fans 12V - 8500RPM</td>
      <td align="right"></td>
      <td align="right">$8.99</td>
      <td align="right">2</td>
      <td align="right">$17.98</td>
    </tr>
    <tr>
      <td>Amazon</td>
      <td>CNHL 2200mAh 4S Lipo Battery 40C</td>
      <td align="right"></td>
      <td align="right">$44.99</td>
      <td align="right">1</td>
      <td align="right">$44.99</td>
    </tr>
    <tr>
      <td>Amazon</td>
      <td>EDF 70mm 11 Blades Ducted Fan</td>
      <td align="right"></td>
      <td align="right">$76.99</td>
      <td align="right">1</td>
      <td align="right">$76.99</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td align="right">20</td>
      <td align="right">$343.91</td>
    </tr>
  </tbody>
</table>
*BOM is missing hardware, need to CAD and add hardware
BOM Google Sheet: https://docs.google.com/spreadsheets/d/1sjlqb2LRXWe4DsiQw7wpXGaVzfJAuZjR17yt-ZodIWk/edit?usp=sharing

