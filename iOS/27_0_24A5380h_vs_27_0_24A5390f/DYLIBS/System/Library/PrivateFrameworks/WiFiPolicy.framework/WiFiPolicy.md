## WiFiPolicy

> `/System/Library/PrivateFrameworks/WiFiPolicy.framework/WiFiPolicy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe2b64` | `0xe2d0c` | **`+0x1a8`** |
| `__DATA_CONST.__const` | `0x2790` | `0x27b8` | **`+0x28`** |
| `__TEXT.__cstring` | `0x25ceb` | `0x25d0b` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x29e0` | `0x29e8` | **`+0x8`** |

### Other Changes

```diff

-1070.59.0.0.0
+1070.61.0.0.0

-  Functions: 7205
-  Symbols:   11983
-  CStrings:  5319
+  Functions: 7206
+  Symbols:   11985
+  CStrings:  5320
Symbols:
+ ___48-[WiFiScanCacheVendor getProcessedCachedBeacons]_block_invoke
+ ___block_descriptor_40_e8_32s_e30_B32?0"CWFScanResult"8Q16^B24ls32l8
Functions:
~ -[WiFiScanCacheVendor getProcessedCachedBeacons] : 508 -> 740
+ ___48-[WiFiScanCacheVendor getProcessedCachedBeacons]_block_invoke
CStrings:
+ "B32@?0@\"CWFScanResult\"8Q16^B24"
```
