## AppleCVA

> `/System/Library/PrivateFrameworks/AppleCVA.framework/AppleCVA`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb3cdc` | `0xb3a5c` | **`-0x280`** |
| `__TEXT.__oslogstring` | `0x95a0` | `0x95ee` | **`+0x4e`** |
| `__TEXT.__gcc_except_tab` | `0x416c` | `0x4188` | **`+0x1c`** |
| `__TEXT.__unwind_info` | `0x12f0` | `0x12f8` | **`+0x8`** |

### Other Changes

```diff

-1003.0.2.0.0
+1003.0.3.0.0

-  Functions: 1197
+  Functions: 1199

-  CStrings:  1722
+  CStrings:  1724
CStrings:
+ "Insufficient color buffer size %dx%d."
+ "Insufficient color buffer size %zux%zu."
```
