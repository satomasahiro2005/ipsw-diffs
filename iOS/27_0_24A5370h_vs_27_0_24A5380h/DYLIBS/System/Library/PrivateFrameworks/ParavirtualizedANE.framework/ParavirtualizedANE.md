## ParavirtualizedANE

> `/System/Library/PrivateFrameworks/ParavirtualizedANE.framework/ParavirtualizedANE`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f970` | `0x1fa8c` | **`+0x11c`** |
| `__TEXT.__oslogstring` | `0x6427` | `0x645e` | **`+0x37`** |
| `__TEXT.__gcc_except_tab` | `0x3b0c` | `0x3b3c` | **`+0x30`** |

### Other Changes

```diff

-382.9.0.0.0
+382.11.0.0.0

-  Functions: 537
+  Functions: 538

-  CStrings:  557
+  CStrings:  558
Functions:
~ -[_ANEVirtualPlatformClient loadModelNewInstance:] : 5380 -> 5600
~ -[_ANEVirtualPlatformClient doCreateModelFile:aneModelKey:] : 5468 -> 5464
~ -[_ANEVirtualPlatformClient doCreateModelFile:aneModelKey:].cold.19 : 60 -> 68
+ -[_ANEVirtualPlatformClient doCreateModelFile:aneModelKey:].cold.20
CStrings:
+ "%@: srcHashDirectory rejected (empty or traversal): %@"
```
