# ASUS VL/I 486SVGO Rev 1.5

![pictures](https://github.com/matt1187/3.3V-adventure/blob/main/asus_SVGO/SVGO_rev1_5.jpg)


# Jumper setting
autodetection of CPU voltage  (5v or low voltage)

JP23 1-2 forced to low voltage.
JP nc = 3.3V
JP34 1-2 = 3.45V  
JP34 2-3 = 3.6V

# part should be removed
|Footprint|Count|Value|
|------|----|-----|
|wire on U20|1|wire|
|wire on U19|1|wire|
And you can peel off a white sticker near "VL/I-486SVGO". -> You got  "VL/I-486SVGOX4"

# Bill of material


|Footprint|Value|Size|Supplier|Order-number|
|--------------|-----|-----|-------|-----------------|
|C35| 330µF 10 or 16V |RM 3.5 |Mouser||
|C51| 10µF 10V tantalum |RM 2.54 |Mouser||
|C52| 1µF 10V tantalum |RM 2.54 |Mouser||
|C53| 10µF 10V tantalum |RM 2.54 |Mouser||
|C54| 1µF 10V tantalum |RM 2.54 |Mouser||
|U19|NDB604BL or IRF530|TO-220|Mouser||
|U20|LT1085-ADJ|TO-220|Mouser||
|U21|7407|SOIC-14|Mouser||
|for U20 and 19|bolt and nuts|M3 |various||
|JP33|10mm  wire |d = 0.5 |various||
|JP34|1x3 pinheader|RM 2.54|Mouser||


# Notes
bill of material is for VL/I 486SVGO Rev 1.5 .
Some  older Revision has other footprint as like DIP-14 for U21

<img width="438" height="660" alt="image" src="https://github.com/user-attachments/assets/af6e6742-1853-42c9-8b0f-95d2a273839a" />



# Disclaim
Risk of modification is on your side.  It is not my fault, if your board or CPU dies.


# License
The project is free for non-commercial reproduction. Do not sell it on Ebay or other platforms for profit. Do not make a closed source derivative. Share your experiences and ideas with the community.

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png


