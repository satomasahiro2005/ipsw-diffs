## safetyalertsAwUI

> `/System/Library/PrivateFrameworks/SafetyAlerts.framework/PlugIns/safetyalertsAwUI.appex/safetyalertsAwUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x402c` | `0x41b4` | **`+0x188`** |
| `__TEXT.__gcc_except_tab` | `0x938` | `0x984` | **`+0x4c`** |
| `__TEXT.__objc_methname` | `0xd8d` | `0xdce` | **`+0x41`** |
| `__TEXT.__objc_stubs` | `0xf20` | `0xf60` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0xb15` | `0xb38` | **`+0x23`** |
| `__DATA_CONST.__cfstring` | `0x5a0` | `0x5c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3b6` | `0x3c9` | **`+0x13`** |
| `__DATA.__objc_selrefs` | `0x528` | `0x538` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x460` | `0x450` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x240` | `0x238` | **`-0x8`** |
| `__TEXT.__objc_methtype` | `0x3e8` | `0x3eb` | **`+0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-70.0.15.0.0
+70.0.17.0.0

-  Symbols:   126
-  CStrings:  331
+  Symbols:   125
+  CStrings:  334
Symbols:
- _objc_retain_x24
Functions:
~ sub_1000014c0 : 640 -> 720
~ sub_100001c84 -> sub_100001cd4 : 2416 -> 2412
~ sub_10000395c -> sub_1000039a8 : 252 -> 256
~ sub_100003bb0 -> sub_100003c00 : 120 -> 212
~ sub_100003f08 -> sub_100003fb4 : 1440 -> 1660
CStrings:
+ "SAFETY_ALERTS_EARTHQUAKE_AREA_POSSIBLE_SHAKING"
+ "mapletLoadingStatus"
+ "numberWithInteger:"
+ "onUserTappedWithUid:action:"
+ "submitMetricsInfoToDaemonForUid:tapTimestampSeconds:snapshotTimestampSeconds:mapletLoadSuccess:"
+ "v44@0:8r*16d24d32B40"
+ "{\"msg%{public}.0s\":\"#saNotificationExtension,sentMetricsToDaemon\", \"uid\":%{private, location:escape_only}s, \"tapTimestampSeconds\":\"%{private}.1f\", \"snapshotTimestampSeconds\":\"%{private}.1f\", \"mapletLoadSuccess\":%{private}hhd}"
- "SAFETY_ALERTS_EARTHQUAKE_AREA_POTENTIAL_SHAKING"
- "submitMetricsInfoToDaemonForUid:tapTimestampSeconds:snapshotTimestampSeconds:"
- "v40@0:8r*16d24d32"
- "{\"msg%{public}.0s\":\"#saNotificationExtension,sentMetricsToDaemon\", \"uid\":%{private, location:escape_only}s, \"tapTimestampSeconds\":\"%{private}.1f\", \"snapshotTimestampSeconds\":\"%{private}.1f\"}"
```
