# XMOS XU(F)208 Breakout Board

XMOS XU208/XUF208 series minimal system board with USB Type-C port, full XSYS debug port, all pin already breakout to edge of the board.

## Image

<img src="image/top_view.png" height="340" width="200">

## About fabrication files

Folder Gerber include **gerber files** and **NC drill files**. If your manufacturer using other format or setting for fabrication files, you should not be use those files.

Gerber files are exported using the following settings:
* Unit: Inches
* Format: 2:5
* Output Layout: Plot all layers, except:
    * Mechanical 13
    * Mechanical 15
    * Mechanical 16
    * Top Pad Master
    * Buttom Pad Master
* Plot all used drill pairs
* Use software arcs
* other setting use default

`[Mechanical 1](Gerber/XUF208_Breakout.GM1) used to define board shape, [Mechanical 17](XUF208_Breakout.GM17) for describe impedance detail.`

NC drill files are exported using the following settings:
* default

## Last
Have fun with it :)