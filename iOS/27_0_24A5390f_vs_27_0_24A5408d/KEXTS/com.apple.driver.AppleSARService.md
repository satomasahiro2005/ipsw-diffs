## com.apple.driver.AppleSARService

> `com.apple.driver.AppleSARService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0xf2500` | `0xf34d4` | **`+0xfd4`** |
| `__TEXT.__cstring` | `0x1ecad` | `0x1edbf` | **`+0x112`** |
| `__TEXT.__os_log` | `0x23f39` | `0x24020` | **`+0xe7`** |

### Other Changes

```diff

-1580.0.0.0.0
-  Functions: 1823
+1585.0.0.0.0
+  Functions: 1826

-  CStrings:  2340
+  CStrings:  2347
CStrings:
+ "#D: %s::%s:%d: HSAR Metric: enum/state fields done, OBD_raw=%u (rfsensing=%u) OBD_ca=%u, BT_conn=%d, Cell_on=%d TxSusp=%d MmW_on=%d Stewie_on=%d TxActive=%d Cell_connected_ca=%u, WiFi_pwr=%d TimeAvgMode=%u, uplink_constraint_condition=%u"
+ "#D: %s::%s:%d: Max SAR Usage Ratio: %u, Total SAR Usage Ratio: %u, Total MPE Usage Ratio: %u"
+ "%s::%s:%d: %s: max: %u, min future: %u, margin: %u, duration: %u, residual: %u"
+ "BT SPLSR"
+ "Connectivity SPLSR"
+ "No Case"
+ "Ry60"
+ "Ry61"
+ "WiFi SPLSR"
- "#D: %s::%s:%d: HSAR Metric: enum/state fields done, OBD=%u, BT_conn=%d, Cell_on=%d, WiFi_pwr=%d, uplink_constraint_condition=%u"
- "%s::%s:%d: %s: max: %u, min future: %u, margin: %u, duration: %u"
```
