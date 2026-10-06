## com.apple.driver.AppleUSBLightningAdapter

> `com.apple.driver.AppleUSBLightningAdapter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1316` | `0x135b` | **`+0x45`** |
| `__TEXT_EXEC.__text` | `0x5d9c` | `0x5dd0` | **`+0x34`** |

### Other Changes

```diff

-91.0.0.0.0
+92.0.0.0.0

-  CStrings:  179
+  CStrings:  180
Functions:
~ __ZN24AppleUSBLightningAdapter11auxpBosInfoEPh : 1368 -> 1420
CStrings:
+ "[ERROR] %s::%s(): BOS wTotalLength changed mid-read: was %u, now %u\n"
```
