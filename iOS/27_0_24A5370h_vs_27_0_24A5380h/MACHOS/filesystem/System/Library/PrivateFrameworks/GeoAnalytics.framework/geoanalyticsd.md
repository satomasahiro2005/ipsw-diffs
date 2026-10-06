## geoanalyticsd

> `/System/Library/PrivateFrameworks/GeoAnalytics.framework/geoanalyticsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x12540` | `0x12560` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1080` | `0x1090` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2a8` | `0x2b8` | **`+0x10`** |
| `__TEXT.__text` | `0x20138` | `0x20148` | **`+0x10`** |
| `__TEXT.__cstring` | `0xd8fa` | `0xd906` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2073.30.6.5.1
+2075.30.6.12.3

-  Symbols:   240
-  CStrings:  3312
+  Symbols:   241
+  CStrings:  3313
Symbols:
+ _GeoAnalyticsSessionConfig_GEOAPAnalyticSessionType_ACSN_FINDER_holddownDurationInSec
Functions:
~ sub_1000045b8 : 1460 -> 1448
~ sub_100005714 -> sub_100005708 : 26572 -> 26584
~ sub_10000bee0 : 84 -> 88
~ sub_1000109ec -> sub_1000109f0 : 76 -> 80
~ sub_10001e1f4 -> sub_10001e1fc : 260 -> 268
CStrings:
+ "ACSN_FINDER"
```
