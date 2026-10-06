## libNFC_HAL.dylib

> `/usr/lib/libNFC_HAL.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x180cc` | `0x17ed8` | **`-0x1f4`** |
| `__TEXT.__oslogstring` | `0x2578` | `0x24fc` | **`-0x7c`** |
| `__TEXT.__cstring` | `0x2e33` | `0x2dc6` | **`-0x6d`** |
| `__TEXT.__const` | `0x120` | `0xf0` | **`-0x30`** |
| `__DATA.__bss` | `—` | `0x18` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0x248` | `0x230` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x238` | `0x248` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x2` | `0x10` | **`+0xe`** |

### Other Changes

```diff

-370.37.0.0.0
+370.38.2.0.0

-  CStrings:  649
+  CStrings:  644
CStrings:
+ "Error : read received after shutdown : %p / %p. Driver context 0x%016llX"
- "%s:%i Read aborted while in progress since %llu."
- "%s:%i Socket is non-blocking"
- "%{public}s:%i Read aborted while in progress since %llu."
- "%{public}s:%i Socket is non-blocking"
- "Error : read received after shutdown : %p / %p. Driver controller type 0x%x, Controller config type %d"
- "NFHardwareSerialReadBlockAbort"
```
