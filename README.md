# EatonAPR48
[SweetScape 010Editor's](https://www.sweetscape.com/010editor/repository/templates/file_info.php?file=EatonAPR48.bt&type=0&sort=) script for exploring and modifying Eaton APR48 power supply's EEPROM structure (in order to be able to change the output voltage). 

Note that Eaton APR48 is an older version of Eaton APR48-3G power supply.

You need to have 010Editor installed to use this script. Then follow the steps 
1. File|Open File... -> EatonAPR48_EEPROM_145294054_copy.bin
2. Template|Open Template... -> EatonAPR48.bt
3. Template|Run Template
4. Expand **the first** _struct EatonEEPROMParams_ and change the _outputVoltage_.
5. File|Save As... -> EatonAPR48_EEPROM_145294054_modified.bin

![010Editor Workspace](./SweetScape_010Editor.PNG "010Editor Workspace")
