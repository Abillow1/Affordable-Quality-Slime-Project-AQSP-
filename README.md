# Affordable Quality Slime Project (AQSP)

**Main Goal:** A slime tracker using a BMI270 sensor, 18650 battery, and including straps for at or under $7.50 each, with a goal of $5 each.

**Reason:** This would allow many users of VR to be able to get FBT (Full Body Tracking), letting people have better experiences in VR for a low cost.

# **Projected Specs**
- ~20 hours play time
- ~3 hour charge time (*projected*)
- 69mm long, 27mm wide (might change), ~27mm thick (TBD)
- Satisfying and easy rocker power switch
- USB-C charging


# Side Goals: (1/3 Achieved)

- Goal of 2 PCB's or less, integrating the sensor and charging chip onto the main PCB **[** Currently: 3 PCB's + 1 switch **]**
- Total manufacturing cost of $4 or less **[** Currently: ~$5 **]**
- Easy manufacturing and small size ***Partially Achieved***
  
# Possible Ideas:

- AA-style battery and battery charging dock for the 18650 battery, for reduced cost (Goal cost: $10/dock | Dock must have 5 ports, with a 10 port model for $17.50)
- Consider a more expensive LSM6DSV model
- Possibly sell accessories for a profit
- A Raspberry PI or similar based Plug and Play WIFI router for easy 2.4Ghz wifi, for LAN only. (Goal cost: $20 +WIFI dongle) ***HIGH PRIORITY***
  
^^ *Possibly important for many quest users who do not have networking knowlage* ^^

# TO-DO
- Update case design to mold around the battery
- Update BOM
- Get PCB prototype & test
- Design PnP LAN router
- Make this Readme file look nice
- Make open source

# Physical Development

**Currently, this project has no physical development. A initial prototype is projected by next month.**

# Digitial Development

    Functionality Test Requiered. PCB redesigned, now smaller and efficcent. Case Design in progress.
    
**Current PCB Prototype**

v![image](https://github.com/user-attachments/assets/e7a61292-d96a-4990-b391-18ee283f659a)


![image](https://github.com/user-attachments/assets/e2173e16-2dd3-44a4-b0cc-ac390330bdfd)


*Estimated prototype cost: $4.90 per tracker per batch, batch size of 500*

# BOM (NEEDS UPDATING)

Battery: YDL 18650 battery, $0.90 each for 500, 2000mAh 

^^ *Goal cost of $0.80 per tracker* ^^ 

Sensor: BMI270, $0.9663 each for 500

Battery Charging Chip: TP4056 Lithium Battery Charger Module, $18.61 per 100 

Microcontroler: D1 mini, $149 / 100 

^^ *Goal cost of $1 per tracker* ^^

Other: $100 per 500 trackers

(*https://ydlbattery.com/products/3-7v-18650-battery-pack*)

(*https://www.aliexpress.us/item/2251832779311798.html?spm=a2g0o.cart.0.0.40767a9dhPQyeY&mp=1&_gl=1*1yijdl2*_gcl_au*MTE0NTQ3NjQzOS4xNzMyODk4MzA2*_ga*MTM2ODQ5MDE3Mi4xNzMyODQxNzAw*_ga_VED1YSGNC7*MTczMzAwMTI5OC42LjEuMTczMzAwNzk0Ni42MC4wLjA.&gatewayAdapt=glo2usa*)

(*https://www.aliexpress.us/item/2251832779311798.html?spm=a2g0o.cart.0.0.40767a9dhPQyeY&mp=1&_gl=1*1yijdl2*_gcl_au*MTE0NTQ3NjQzOS4xNzMyODk4MzA2*_ga*MTM2ODQ5MDE3Mi4xNzMyODQxNzAw*_ga_VED1YSGNC7*MTczMzAwMTI5OC42LjEuMTczMzAwNzk0Ni42MC4wLjA.&gatewayAdapt=glo2usa*)

(https://www.lcsc.com/product-detail/Rocker-Switches_SHOU-HAN-KCD11-2P_C5884412.html)

(https://www.lcsc.com/product-detail/Schottky-Diodes_LGE-1N5817_C7544876.html)

# Copyright Notice

All Rights Reserved

THE CONTENTS OF THIS PROJECT ARE PROPRIETARY AND CONFIDENTIAL.
UNAUTHORIZED COPYING, TRANSFERRING OR REPRODUCTION OF THE CONTENTS OF THIS PROJECT, VIA ANY MEDIUM IS STRICTLY PROHIBITED.

The receipt or possession of the source code and/or any parts thereof does not convey or imply any right to use them
for any purpose other than the purpose for which they were provided to you. This project is being provided for INFORMAL PURPOSES ONLY.

The project is provided "AS IS", without warranty of any kind, express or implied, including but not limited to
the warranties of merchantability, fitness for a particular purpose and non infringement.
In no event shall the authors or copyright holders be liable for any claim, damages or other liability,
whether in an action of contract, tort or otherwise, arising from, out of or in connection with the project
or the use or other dealings in the project.

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the project.
