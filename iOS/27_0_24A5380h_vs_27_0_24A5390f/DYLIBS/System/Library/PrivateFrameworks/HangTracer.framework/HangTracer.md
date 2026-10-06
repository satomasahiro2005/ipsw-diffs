## HangTracer

> `/System/Library/PrivateFrameworks/HangTracer.framework/HangTracer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x5b80` | `0x5c60` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x4534` | `0x45aa` | **`+0x76`** |
| `__DATA_CONST.__const` | `0x17b8` | `0x17f8` | **`+0x40`** |
| `__TEXT.__text` | `0x174f0` | `0x17524` | **`+0x34`** |
| `__TEXT.__unwind_info` | `0x5c8` | `0x5d0` | **`+0x8`** |

### Other Changes

```diff

-421.0.0.0.0
+424.0.0.0.0

-  Functions: 588
-  Symbols:   1306
-  CStrings:  994
+  Functions: 589
+  Symbols:   1315
+  CStrings:  1001
Symbols:
+ _HTIsDeviceRestricted
+ _kHTExtendedAttributeHangEnd
+ _kHTExtendedAttributeHangStart
+ _kHTExtendedAttributeSampleEnd
+ _kHTExtendedAttributeSampleStart
+ _kHTLostPerfJSONKeyEndMATU
+ _kHTLostPerfJSONKeyIntervals
+ _kHTLostPerfJSONKeyReason
+ _kHTLostPerfJSONKeyStartMATU
Functions:
~ _HTHangEventCreateWithBundleID : 1360 -> 1368
~ _bundleIDFromPath : 180 -> 216
+ _HTIsDeviceRestricted
CStrings:
+ "end_matu"
+ "hangtracer.hang_end"
+ "hangtracer.hang_start"
+ "hangtracer.sample_end"
+ "hangtracer.sample_start"
+ "intervals"
+ "start_matu"
```
