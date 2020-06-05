# Samsung PM851 order in chaos

Samsung MZ7TE drives run EXT0x  
Samsung MZNTE drives run EXT2x  
Samsung MZMTE drives run EXT4x  

My drive: EXT23D0Q

Lenovo 128GB and 512GB run the same firmware, but 256GB runs different firmware.  
You can see this in drive id, last two characters.

| | |
| - | - |
| MZ7TE512HMHP-000L1 | EXT07L0Q | L1 drive becomes L0 firmware |
| MZ7TE128HMGR-000L1 | EXT07L0Q | |
| MZ7TE256HMHP-000L7 | EXT0BL6Q | L7 drive becomes L6 firmware |


Timestamps:

| | | |
| - | - | - | 
| | EXT06L0Q | 2014041821:25    |
| | EXT07L0Q | 2016084 19:37    |
| | EXT09L6Q | 2014041821:34    |
| | EXT0AL6Q | 2015082211:55    |
| | EXT0BL6Q | 2016084 17:59    |
| | EXT27L0Q | 2016085 9:51     |
| | EXT29L6Q | 2016085 10:30    |
| | |
| | EXT26S0Q | 2014053010:58    |
| | |
| | EXT08D0Q | 2015062416:50    |
| MZNTE128HMGR-000D1 | EXT23D0Q | | 
| MZNTE256HMHP-000D1 | EXT25D0Q | |
| **MZNTE512HMJH-000D1** | **EXT23D0Q** | |


| PM851_Performance_Restoration v1.0_RC2 | | |
| - | - | - |
| MZMTE128HMGR-000MV | EXT42M0Q | 2014117 14:33 |
| MZMTE256HMHP-000MV | EXT42M0Q | 2014117 14:33 |
| MZMTE512HMHP-000MV | EXT42M0Q | 2014117 14:33 |
| MZMTE1T0HMJH-000MV | EXT42M1Q | 2014111421:50 |


```
Sony:
2014053010:58
Samsung MZNTE256HMHP-000SO
Update:https://www.sony.nl/electronics/support/downloads/Z0001398

<CURFW>EXT25S0Q</CURFW>
<NEWFW>EXT26S0Q</NEWFW>
```

```
Dell:
Update: https://www.dell.com/support/home/nl-nl/drivers/driversdetails?driverid=rymd3
<CURFW>EXT06D0Q</CURFW>
<NEWFW>EXT08D0Q</NEWFW>
```

```
Lenovo updates: (Source: fwsd48/fwwinsd.pro)
"SAMSUNG MZ7TE128HMGR-000L1","EXT05L0Q","EXT06L0Q","EXT06L0Q.enc","fwwinupdater.exe","","S","Samsung"
"SAMSUNG MZ7TE128HMGR-000L1","EXT06L0Q","EXT07L0Q","EXT07L0Q_DL.ENC","fwwinupdater_v11.exe","","S","Samsung"
"SAMSUNG MZ7TE512HMHP-000L1","EXT05L0Q","EXT06L0Q","EXT06L0Q.enc","fwwinupdater.exe","","S","Samsung"
"SAMSUNG MZ7TE512HMHP-000L1","EXT06L0Q","EXT07L0Q","EXT07L0Q_DL.ENC","fwwinupdater_v11.exe","","S","Samsung"

"SAMSUNG MZ7TE256HMHP-000L7","EXT07L6Q","EXT0AL6Q","EXT0AL6Q_DOWNLOADONLY.ENC","fwwinupdater_v11.exe","edrivechk","S","Samsung"
"SAMSUNG MZ7TE256HMHP-000L7","EXT08L6Q","EXT0AL6Q","EXT0AL6Q_DOWNLOADONLY.ENC","fwwinupdater_v11.exe","edrivechk","S","Samsung"
"SAMSUNG MZ7TE256HMHP-000L7","EXT09L6Q","EXT0AL6Q","EXT0AL6Q_DOWNLOADONLY.ENC","fwwinupdater_v11.exe","edrivechk","S","Samsung"
"SAMSUNG MZ7TE256HMHP-000L7","EXT0AL6Q","EXT0BL6Q","EXT0BL6Q_DL.ENC","fwwinupdater_v11.exe","edrivechk","S","Samsung"

"SAMSUNG MZNTE128HMGR-000L1","EXT26L0Q","EXT27L0Q","EXT27L0Q_DL.ENC","fwwinupdater_v11.exe","","S","Samsung"
"SAMSUNG MZNTE256HMHP-000L7","EXT28L6Q","EXT29L6Q","EXT29L6Q_DL.ENC","fwwinupdater_v11.exe","edrivechk","S","Samsung"
"SAMSUNG MZNTE512HMJH-000L1","EXT26L0Q","EXT27L0Q","EXT27L0Q_DL.ENC","fwwinupdater_v11.exe","","S","Samsung"```



