## ActivityKit

> `/System/Library/Frameworks/ActivityKit.framework/ActivityKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc0740` | `0xc0b78` | **`+0x438`** |
| `__TEXT.__const` | `0xecda` | `0xed4a` | **`+0x70`** |
| `__TEXT.__cstring` | `0x1dd1` | `0x1e01` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x43d8` | `0x4408` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x1e6f` | `0x1e9f` | **`+0x30`** |
| `__DATA.__data` | `0x34f8` | `0x34d8` | **`-0x20`** |
| `__DATA_DIRTY.__data` | `0x2298` | `0x22b0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x3850` | `0x3848` | **`-0x8`** |

### Other Changes

```diff

-304.0.0.0.0
+307.0.0.0.0

-  CStrings:  358
+  CStrings:  360
CStrings:
+ "ACActivityOutputServiceErrorDomain"
+ "activityDescriptor RPC failed: %{public}s"
```
