## RegulatoryDomain

> `/System/Library/PrivateFrameworks/RegulatoryDomain.framework/RegulatoryDomain`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11164` | `0x11530` | **`+0x3cc`** |
| `__TEXT.__oslogstring` | `0x259c` | `0x2657` | **`+0xbb`** |
| `__DATA_CONST.__objc_selrefs` | `0x4d8` | `0x500` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x604` | `0x62c` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0xa4` | `0x8c` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x540` | `0x538` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x3e8` | `0x3f0` | **`+0x8`** |

### Other Changes

```diff

-73.0.0.0.0
+74.0.0.0.0

-  Functions: 267
-  Symbols:   210
-  CStrings:  190
+  Functions: 270
+  Symbols:   209
+  CStrings:  192
Symbols:
- _objc_retain_x25
CStrings:
+ "estimate with nil countryCode when posting to os_eligibility"
+ "{\"msg%{public}.0s\":\"estimate with nil countryCode when posting to os_eligibility\", \"estimates\":%{public, location:escape_only}@}"
+ "{\"msg%{public}.0s\":\"os_eligibility will receive 'unknown'\"}"
+ "{\"msg%{public}.0s\":\"update for os_eligibility\", \"update\":%{public, location:escape_only}s, \"atLeastWifi?\":%{public}hhd, \"atLeastServingCell?\":%{public}hhd, \"atLeastNearbyCell?\":%{public}hhd, \"atLeastSingleLoc?\":%{public}hhd}"
- "{\"msg%{public}.0s\":\"posting unknown to os_eligibility\"}"
- "{\"msg%{public}.0s\":\"posting update to os_eligibility\", \"update\":%{public, location:escape_only}s, \"atLeastWifi?\":%{public}hhd, \"atLeastServingCell?\":%{public}hhd, \"atLeastNearbyCell?\":%{public}hhd, \"atLeastSingleLoc?\":%{public}hhd}"
```
