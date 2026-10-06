## com.apple.driver.AppleSmartIO2

> `com.apple.driver.AppleSmartIO2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0xb488` | `0xb498` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-146.0.0.0.0
+149.0.0.0.0
Functions:
~ __ZN19AppleSmartIOControl14setupMapRangesEv : 708 -> 716
~ __ZN19AppleSmartIOControl31populateShimPowerGatePropertiesEv : 508 -> 504
~ __ZN19AppleSmartIOControl10setupShimsEv : 772 -> 776
~ __ZN19AppleSmartIOControl12setupDevicesEv : 624 -> 632
CStrings:
+ "20:59:00"
+ "Jun 30 2026"
- "19:32:47"
- "Jun 18 2026"
```
