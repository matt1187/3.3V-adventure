# MSI MS-4138 Ver 1

![pictures](https://github.com/matt1187/3.3V-adventure/blob/main/Abit_AN4/Abit_AN4_REV1_0_MOD.jpg)


# Jumper setting
JP12 1-2 = 3.3V  
JP12 2-3 = 5V

# part should be removed
|Footprint|Count|Value|
|------|----|-----|
|JP9|1|wire|
|JP12|1|wire|


# Bill of material


|Footprint|Value|Size|Supplier|Order-number|
|--------------|-----|-----|-------|-----------------|
|R41| 220 ohm|THT 0207 1/4 w |Mouser||
|R42| 220 ohm|THT 0207 1/4 w |Mouser||
|MC1,2,3,5,6| 100nF 25V |RM 7.5 |Mouser||
|MC8,9,10,11,12,13,14,15| 100nf 25V |RM 7,5 |Mouser||
|TC12| 220-470µF 10V |RM 5,08 |Mouser||
|TC15| 10µF 10V tantalum |RM 2.54 |Mouser||
|Q4|LT1085-3.3|TO220|Mouser||
|for Q4|TO220 heatsink|TO220|Mouser||
|JP9|short 1-2|10mm  wire d = 0.5 |various||
|JP12|1x3 pinheader|RM 2.54|Mouser||
|JP40|short 2-3|10mm  wire d = 0.5 |various||


# Note

JP9 wire on 2-3 should moved to  1-2. 
JP40 should be wired on 2-3.
TC12 value 220-470µF, it is not critical value.


# Disclaim
Risk of modification is on your side.  It is not my fault, if your board or CPU dies.


# License
The project is free for non-commercial reproduction. Do not sell it on Ebay or other platforms for profit. Do not make a closed source derivative. Share your experiences and ideas with the community.

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
