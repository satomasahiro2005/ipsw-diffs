## AVRouting

> `/System/Library/Frameworks/AVRouting.framework/AVRouting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4cefc` | `0x4cf6c` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0xc1a0` | `0xc1e8` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x6798` | `0x67c0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x47e0` | `0x4800` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2030` | `0x2048` | **`+0x18`** |
| `__TEXT.__cstring` | `0xa506` | `0xa513` | **`+0xd`** |
| `__TEXT.__unwind_info` | `0x17c8` | `0x17d0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x5a4` | `0x5a8` | **`+0x4`** |

### Other Changes

```diff

-  Functions: 2500
-  Symbols:   4663
-  CStrings:  1204
+  Functions: 2502
+  Symbols:   4666
+  CStrings:  1205
Symbols:
+ -[AVClusterComponentOutputDeviceDescription initWithDeviceID:deviceName:deviceSubType:isClusterLeader:modelID:surroundRole:]
+ -[AVClusterComponentOutputDeviceDescription surroundRole]
+ _OBJC_IVAR_$_AVClusterComponentOutputDeviceDescription._surroundRole
CStrings:
+ "SurroundRole"
```
