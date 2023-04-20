Query a list of CITY and STATE from the STATION table.

---
The STATION table is described as follows:

| Field      | Type |
| ----------- | ----------- |
| ID      | NUMBER       |
| CITY   | VARCHAR2(21)        |
| STATE   | VARCHAR2 (2)        |
| LAT_N   | NUMBER        |
| LAT_W   | NUMBER        |

---
**Solution**
```sql
SELECT city, state FROM STATION;
```
