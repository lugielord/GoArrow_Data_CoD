# GoArrow_Data_CoD
Decal Plugin GoArrow Locations Database

For whatever reason just putting the link below in the GoArrow Update the Locations Database / URL Box does not work and gives an error.

Instead download the file using the link, save to somewhere like C:\data_cod.xml, the add that to the GoArrow Update the Locations Database / URL Box, Hit the Update Locations Database button, Let it finish, then hit the button again.

Current number of locations in database should read: 5607 (as of 05.21.2024)


lugielord's Location Database:

https://raw.githubusercontent.com/lugielord/GoArrow_Data_CoD/master/data_cod.xml - Last File Update / Upload 05.18.2024
(insync with ACE Emulator database v0.9.280)

--

# GoArrow Dungeon Maps
How I got the Dungeon Maps to work

1.Modify your hosts file in Windows 10

    Open Notepad with administrator privileges.
    Browse to C:\Windows\System32\drivers\etc\hosts (Or paste this into the address bar)
    Open the file.
    Add:
    #Asherons Call ACMAPS for Go Arrow
    127.0.0.1 www.acmaps.com
    127.0.0.1 ac.lastalias.com
    Save File
    
2. Download GoArrow VVS Edition
https://github.com/Darktorizo/GoArrow_Data_CoD/blob/master/GoArrow_2.5.0.0.VVS_WDM.zip

3. Install GoArrowVVS in C:\Games\VirindiPlugins\GoArrowVVSEdition}

4. rename old DLL C:\Games\VirindiPlugins\GoArrowVVSEdition\GoArrow.dll to C:\Games\VirindiPlugins\GoArrowVVSEdition\GoArrow.dll.old

5. Download Go Arrow Update (fixes access to dungeon maps)
https://github.com/lugielord/GoArrow_Data_CoD/blob/master/GoArrow_Update.zip

6. Unzip new GoArrow.dll into C:\Games\VirindiPlugins\GoArrowVVSEdition

7. load client, clear GoArrow cache on HUD's/ Dungeon tab

8. Download Dungeon Maps Cache
https://github.com/lugielord/GoArrow_Data_CoD/blob/master/Dungeon_Map_Cache.zip
 (2018 Baseline maps) 

9. Unzip dungeon maps cache files into C:\Games\VirindiPlugins\GoArrowVVSEdition\Dungeon Map Cache

10. Download Dungeon Maps Cache updates
https://github.com/lugielord/GoArrow_Data_CoD/blob/master/Dungeon%20Map%20Cache%20Updates.rar 
 (All updates since 2018)

11. Unzip dungeon maps cache UPDATE files into C:\Games\VirindiPlugins\GoArrowVVSEdition\Dungeon Map Cache
  (Overwriting anything that is there)

12. restart client

