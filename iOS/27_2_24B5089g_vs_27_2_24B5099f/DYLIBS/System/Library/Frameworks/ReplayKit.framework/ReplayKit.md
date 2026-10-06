## ReplayKit

> `/System/Library/Frameworks/ReplayKit.framework/ReplayKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0xba8` | `0x4` | **`-0xba4`** |
| `__DATA_DIRTY.__data` | `—` | `0xba0` | **`+0xba0`** |
| `__TEXT.__text` | `0x36cdc` | `0x36d40` | **`+0x64`** |
| `__AUTH_CONST.__cfstring` | `0x1ee0` | `0x1f00` | **`+0x20`** |
| `__TEXT.__cstring` | `0x81d5` | `0x81ea` | **`+0x15`** |
| `__AUTH_CONST.__objc_const` | `0x66e8` | `0x66f8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x3670` | `0x3680` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2198` | `0x21a0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xc00` | `0xc08` | **`+0x8`** |

### Other Changes

```diff

-765.11.1.0.0
+765.14.1.0.0

-  Functions: 1419
-  Symbols:   2241
-  CStrings:  1096
+  Functions: 1420
+  Symbols:   2242
+  CStrings:  1097
Symbols:
+ -[RPFeatureFlagUtility edgeLightDevOverrideActive]
CStrings:
+ "RPEnableEdgeLightDev"
```
