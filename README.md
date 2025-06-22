# Amstrad-CPC-Drive-AB-Switch
 
Some Amstrad CPC software will not run on an external drive, Drive B, as it expects to run on the internal drive, Drive A.

This can be rectfied by adding a header to the floppy ribbon cable and inserting a small switch to pull Drive Select 1 low.

<img src="https://github.com/user-attachments/assets/3f278486-c8bc-49df-9346-88eff15258df" width="400" height="400"/>

Information regarding this can be found at [CPCWiki Guide on how to connect a 3.5" drive to a CPC 6128](https://www.cpcwiki.eu/index.php?title=Guide_on_how_to_connect_a_3.5%22_drive_to_a_CPC6128/664)

This CPCWiki guide discusses an option to make the external drive the Primary Drive by connecting pin 11 to 12 on the cable where pin 12 is the Shugart standard numbering system for Drive Select 1, see [CPCWkiki Guide for the 2nd disc drive connector](https://www.cpcwiki.eu/index.php/Connector:2nd_disc_drive_(CPC664,_CPC6128,_CPC6128%2B)). Pin 11 is GND.

However, adding a header and switch is not always an option for a user.

This small PCB effectively acts as the switch in the ribbon cable, pulling Drive Select 1 low and allowing software which expects to run on Drive A, to run on Drive B.

<img src="https://github.com/user-attachments/assets/3120dffd-dbe2-4441-ba2c-a1241a7e4073" width="400" height="400"/> 

The PCB then sits between the second floppy drive edge connector and the floppy drive ribbon cable.

<img src="https://github.com/user-attachments/assets/6b773aa4-a92a-407d-a65e-02a400f9a7c2" width="400" height="400"/> 
