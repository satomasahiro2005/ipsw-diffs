## System

> `/System/Library/CoreAccessories/PlugIns/Platform/System.platform/System`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ea8` | `0x4d9c` | **`-0x10c`** |
| `__AUTH_CONST.__objc_const` | `0xad8` | `0xaa8` | **`-0x30`** |
| `__AUTH_CONST.__cfstring` | `0x540` | `0x520` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x4a0` | `0x480` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x600` | `0x5e8` | **`-0x18`** |
| `__TEXT.__cstring` | `0x68b` | `0x676` | **`-0x15`** |
| `__DATA_CONST.__got` | `0x140` | `0x138` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1c0` | `0x1b8` | **`-0x8`** |
| `__DATA.__data` | `0x200` | `0x1fc` | **`-0x4`** |
| `__DATA.__objc_ivar` | `0x34` | `0x30` | **`-0x4`** |

### Other Changes

```diff

-1203.0.0.0.0
+1210.0.0.502.1

-  Functions: 134
-  Symbols:   350
-  CStrings:  99
+  Functions: 132
+  Symbols:   344
+  CStrings:  98
Symbols:
- -[MediaLibraryHelper _updateITunesRadioEnabled]
- -[MediaLibraryHelper iTunesRadioEnabled]
- _CFPreferencesGetAppIntegerValue
- _OBJC_CLASS_$_MPRadioLibrary
- _OBJC_IVAR_$_MediaLibraryHelper._iTunesRadioEnabled
- ___iTunesRadioEnabledOverride.__overrideRadioAvailable
CStrings:
- "overrideRadioEnabled"
```
