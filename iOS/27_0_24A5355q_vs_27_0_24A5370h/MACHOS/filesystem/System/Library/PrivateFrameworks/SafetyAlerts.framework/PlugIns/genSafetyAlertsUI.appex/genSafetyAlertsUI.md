## genSafetyAlertsUI

> `/System/Library/PrivateFrameworks/SafetyAlerts.framework/PlugIns/genSafetyAlertsUI.appex/genSafetyAlertsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9260` | `0x92c0` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x1b00` | `0x1ac0` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0x1f67` | `0x1f8a` | **`+0x23`** |
| `__DATA_CONST.__cfstring` | `0x680` | `0x660` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x221b` | `0x21fb` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x1c0` | `0x1a8` | **`-0x18`** |
| `__TEXT.__gcc_except_tab` | `0x1154` | `0x116c` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xa60` | `0xa50` | **`-0x10`** |
| `__TEXT.__const` | `0x130` | `0x138` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x9b7` | `0x9ba` | **`+0x3`** |
| `__TEXT.__cstring` | `0x4e4` | `0x4e5` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-70.0.15.0.0
+70.0.17.0.0

-  Symbols:   154
-  CStrings:  664
+  Symbols:   151
+  CStrings:  661
Symbols:
- _NSTextCheckingCityKey
- _NSTextCheckingStateKey
- _NSTextCheckingStreetKey
Functions:
~ sub_1000019f8 : 640 -> 720
~ sub_100001fec -> sub_10000203c : 1448 -> 1912
~ sub_1000026d0 -> sub_1000028f0 : 4080 -> 4060
~ sub_100003864 -> sub_100003a70 : 252 -> 256
~ sub_100003ab8 -> sub_100003cc8 : 120 -> 212
~ sub_100003d38 -> sub_100003fa4 : 2008 -> 2004
~ sub_100004f04 -> sub_10000516c : 840 -> 344
~ sub_100005cac -> sub_100005d24 : 348 -> 344
~ sub_100005e08 -> sub_100005e7c : 508 -> 504
~ sub_100006004 -> sub_100006074 : 516 -> 512
~ __ZN10SAGeometryC1EP12NSDictionary : 6248 -> 6240
~ __ZNK10SAGeometry11getCentroidEv : 1344 -> 1340
CStrings:
+ "mapletLoadingStatus"
+ "numberWithInteger:"
+ "onUserTappedWithUid:action:"
+ "submitMetricsInfoToDaemonForUid:tapTimestampSeconds:snapshotTimestampSeconds:mapletLoadSuccess:"
+ "v44@0:8r*16d24d32B40"
+ "{\"msg%{public}.0s\":\"#saNotificationExtension,sentMetricsToDaemon\", \"uid\":%{private, location:escape_only}s, \"tapTimestampSeconds\":\"%{private}.1f\", \"snapshotTimestampSeconds\":\"%{private}.1f\", \"mapletLoadSuccess\":%{private}hhd}"
- ","
- "URLQueryAllowedCharacterSet"
- "addressComponents"
- "componentsJoinedByString:"
- "maps://?address="
- "stringByAppendingString:"
- "submitMetricsInfoToDaemonForUid:tapTimestampSeconds:snapshotTimestampSeconds:"
- "v40@0:8r*16d24d32"
- "{\"msg%{public}.0s\":\"#saNotificationExtension,sentMetricsToDaemon\", \"uid\":%{private, location:escape_only}s, \"tapTimestampSeconds\":\"%{private}.1f\", \"snapshotTimestampSeconds\":\"%{private}.1f\"}"
```
