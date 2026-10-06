## Portrait

> `/System/Library/PrivateFrameworks/Portrait.framework/Portrait`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x88b48` | `0x88a44` | **`-0x104`** |
| `__TEXT.__cstring` | `0x4e7a` | `0x4e42` | **`-0x38`** |
| `__TEXT.__oslogstring` | `0x4b0c` | `0x4b3b` | **`+0x2f`** |
| `__DATA_CONST.__objc_selrefs` | `0x4ee8` | `0x4ec8` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x910` | `0x918` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x828` | `0x820` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1e88` | `0x1e90` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x19e4` | `0x19e0` | **`-0x4`** |

### Other Changes

```diff

-556.0.0.0.1
+558.0.0.0.0

-  Functions: 3716
-  Symbols:   6458
-  CStrings:  1386
+  Functions: 3717
+  Symbols:   6459
+  CStrings:  1384
Symbols:
+ _PTSerializableFocusDistance
+ _kPTCinematographyIdentifier
- _OBJC_CLASS_$_MTLRenderPipelineDescriptor
CStrings:
+ "Failed to seek color reader to (%lld / %d): %@"
- "fragmentFunction"
- "pipelineStateDescriptor"
- "vertexFunction"
```
