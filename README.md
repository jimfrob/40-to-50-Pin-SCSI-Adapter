I had a spare PowerBook version of a BlueSCSI v2 and wanted to make use of it, so I designed a PCB to adapt the 40-pin connector of the PowerBook to the standard 50-pin connector. I then designed a mount for installing it in a computer. The BlueSCSI is intended to be soldered on top of the board with the 40-pin header between. The power connector may be extranneous since the BlueSCSI should be able to take termination power.

40-pin header: Digikey part number [62004021121](https://www.digikey.com/en/products/detail/würth-elektronik/62004021121/15672211?s=N4IgTCBcDaIGxgAyICyLARg5kBdAvkA)

50-pin header: Digikey part number [SBH11-PBPC-D25-ST-BK](https://www.digikey.com/en/products/detail/sullins-connector-solutions/SBH11-PBPC-D25-ST-BK/1990069?s=N4IgTCBcDaIMoCEASBGFBaACgzBhdAImAKzpwAq6CA0iALoC%2BQA)

Any 4-pin header should work for power for use with a floppy drive berg connector.

The board was designed with KiCad 8.


![alt text](https://github.com/jimfrob/40-to-50-Pin-SCSI-Adapter/blob/main/top.svg?raw=true)
