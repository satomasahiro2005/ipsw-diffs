## PerfPowerServicesMetadata

> `/System/Library/PrivateFrameworks/PerfPowerServicesMetadata.framework/PerfPowerServicesMetadata`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ea94` | `0x3ec8c` | **`+0x1f8`** |
| `__AUTH_CONST.__cfstring` | `0x8c00` | `0x8c60` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x2d0` | `0x280` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x1130` | `0x1180` | **`+0x50`** |
| `__TEXT.__cstring` | `0x46e3` | `0x4705` | **`+0x22`** |
| `__TEXT.__objc_methlist` | `0x290c` | `0x291c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1328` | `0x1330` | **`+0x8`** |

### Other Changes

```diff

-3486.0.21.502.1
+3486.0.46.502.1

-  Functions: 1085
-  Symbols:   1730
-  CStrings:  1301
+  Functions: 1086
+  Symbols:   1731
+  CStrings:  1304
Symbols:
+ +[PPSXPCMetrics droppedXPCTrackingMetrics]
Functions:
~ +[PPSXPCMetrics allDeclMetrics] : 512 -> 548
+ +[PPSXPCMetrics droppedXPCTrackingMetrics]
CStrings:
+ "ClientDroppedEvents"
+ "Count"
+ "Process"
```
