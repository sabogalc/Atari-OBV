# Atari-OBV
Project to create OpenBoardView files for the Atari line of computers to aid repair and restoration.

## OpenBoardView
Excellent open source board view software.
http://openboardview.org

## KiCad to BoardView Exporter
Python plugin to convert PCB file to OBV BRD.
https://github.com/whitequark/kicad-boardview

## Issues
Active low signals. KiCad needs to have the Pin/Net name enclosed in the tilde ~ character for it to display properly in KiCad. Those nets appear as ~BR~ in OBV. Easy enough to RegEx into /BR.
