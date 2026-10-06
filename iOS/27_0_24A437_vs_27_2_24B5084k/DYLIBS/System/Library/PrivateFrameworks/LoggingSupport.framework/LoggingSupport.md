## LoggingSupport

> `/System/Library/PrivateFrameworks/LoggingSupport.framework/LoggingSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x63890` | `0x63548` | **`-0x348`** |
| `__TEXT.__cstring` | `0x75d4` | `0x7650` | **`+0x7c`** |
| `__AUTH_CONST.__cfstring` | `0x3900` | `0x3940` | **`+0x40`** |
| `__TEXT.__const` | `0x57a` | `0x59a` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1360` | `0x1370` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xbb0` | `0xbb8` | **`+0x8`** |

### Other Changes

```diff

-1966.2.1.0.0
+1966.40.15.502.2

-  Functions: 1825
-  Symbols:   3597
-  CStrings:  1274
+  Functions: 1828
+  Symbols:   3601
+  CStrings:  1281
Symbols:
+ ___assert_rtn
+ _ctf_copy_membnames
+ _ehdr_to_gelf
+ _shdr_to_gelf
CStrings:
+ ".SUNW_ctf"
+ "_os_metric_get_bin_count"
+ "binIntervals"
+ "custom"
+ "md->bins > 0"
+ "md->type == _OS_METRIC_TYPE_HISTOGRAM"
+ "metric_internal.h"
```
