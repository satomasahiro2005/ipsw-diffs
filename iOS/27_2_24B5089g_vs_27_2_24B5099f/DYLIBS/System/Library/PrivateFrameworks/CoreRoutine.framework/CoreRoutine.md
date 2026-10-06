## CoreRoutine

> `/System/Library/PrivateFrameworks/CoreRoutine.framework/CoreRoutine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x70c9c` | `0x70a54` | **`-0x248`** |
| `__AUTH.__objc_data` | `0x14f0` | `0x12c0` | **`-0x230`** |
| `__DATA_DIRTY.__objc_data` | `0x1b80` | `0x1db0` | **`+0x230`** |
| `__TEXT.__unwind_info` | `0x2140` | `0x2128` | **`-0x18`** |
| `__TEXT.__cstring` | `0x7748` | `0x7735` | **`-0x13`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c10` | `0x2c08` | **`-0x8`** |
| `__TEXT.__const` | `0x2c8` | `0x2c0` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x8c70` | `0x8c68` | **`-0x8`** |

### Other Changes

```diff

-1123.0.0.0.0
+1123.0.3.0.0

-  Functions: 3114
-  Symbols:   5503
-  CStrings:  1219
+  Functions: 3113
+  Symbols:   5501
+  CStrings:  1218
Symbols:
+ _kRTFamiliarityIndexOptionsUnspecifiedLookbackInterval
- -[RTAddress initWithGeoDictionary:language:country:phoneticLocale:]
- __os_feature_enabled_impl
- _objc_retain_x5
Functions:
- -[RTAddress initWithGeoDictionary:language:country:phoneticLocale:]
~ -[RTFamiliarityIndexOptions init] : 116 -> 28
~ -[RTFamiliarityIndexOptions initWithDateInterval:spatialGranularity:] : 136 -> 20
~ -[RTFamiliarityIndexOptions initWithDateInterval:lookbackInterval:spatialGranularity:referenceLocation:referenceLocationSummary:distance:] : 328 -> 272
CStrings:
- "ExtendedTimeToLive"
```
