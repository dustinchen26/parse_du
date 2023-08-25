# Parse the du_stats_XXX.txt DL/UL Tput, BLER, MCS
online calculate: https://dustinchen26.github.io/parse_du

## Example
Please paste the whole du_stats_XXX.txt content below
```
【Input】
Total Number of UEs  : 1
	 EGTP DL Tpt : 473.91  UL Tpt 0.26
	 X2 EGTP DL Tpt : 0.00  UL Tpt 0.00
	 SCH  DL Tpt : 475.50  UL Tpt 0.26
	 
---------------------------------------------------------------------------------------------
                       UE MAC-Scheduler Instantaneous Statistics
---------------------------------------------------------------------------------------------
UE-ID   CELL-ID   ON-SUL   DL-TX   DL-RETX   ACK-TB[0] NACK-TB[0]  BLER-TB[0]  DTX-TB[0] ACK-TB[1] NACK-TB[1]  BLER-TB[1]  DTX-TB[1] DL-MCS  DL-RI-PER   DL-CQI-PER     UL-RX   UL-RETX  UL-CRC-SUCC   UL-CRC-FAIL   UL-CRC-DTX   UL-CQI  UL-MCS  UL-RI   NUM-BSR   SHR-BSR ST-BSR  LNG-BSR LT-BSR  NUM-CSI   NUM-SRS   
17017   1         0        25488   57        25474     58          0           0         0         0           0           0         23      1           8              6913    0        6909          0             0            11      21      0       6909      6218    0       691     0       0         0         

【Output】	 
SCH  DL Tpt:  475.50  UL Tpt:    0.26  DL-TX=  25488  DL-RETX=     57  DL-BLER= 0.0022  DL-MCS=     23  UL-CRC-SUCC=   6909  UL-CRC-FAIL=      0  UL-BLER= 0.0000  UL-MCS=     21

```