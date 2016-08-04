# 3DS-Dev-unit-Signing-Tools
A set of tools used to Re-sign and convert .CCI/.CSU/.3ds Retail Roms to Dev Signed .Cia files for CTR and Snake Development Units. The RSF included in this package allows for a signed .3ds/.csu Header, which is required when converting to a cia for dev.

# Quick Guide
Note : If you have a decrypted .3ds rom directly from Decrypt9 then skip to step 4!

1. Grab a .cia or a .3ds file. Make sure it's already decrypted!
2. Extract its contents with the tools in the extraction folder or use your own favorite tool. BE SURE TO DECOMPRESS THE .CODE
3. Repack it using Makerom.exe. Be sure to set the Target Type as -d instead of -p and DO NOT FORGET THE .RSF included in this package as it is required and to set the RSF's MediaCard Size when editing!
4. Rename the Name.3ds/Name.CCI file you generated to Name.csu. (THIS IS VERY IMPORTANT)
5. Finally Drag your Name.csu file onto RetailToDev.exe and your done.
