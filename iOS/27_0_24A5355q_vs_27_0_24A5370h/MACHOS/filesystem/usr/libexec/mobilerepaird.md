## mobilerepaird

> `/usr/libexec/mobilerepaird`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe3c4` | `0xe2b8` | **`-0x10c`** |
| `__TEXT.__cstring` | `0x2303` | `0x23b9` | **`+0xb6`** |
| `__TEXT.__gcc_except_tab` | `0x438` | `0x3a8` | **`-0x90`** |
| `__DATA_CONST.__const` | `0x428` | `0x498` | **`+0x70`** |
| `__DATA_CONST.__cfstring` | `0x22c0` | `0x2300` | **`+0x40`** |
| `__DATA.__bss` | `0x150` | `0x160` | **`+0x10`** |
| `__DATA.__data` | `0x190` | `0x198` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x318` | `0x320` | **`+0x8`** |
| `__TEXT.__const` | `0xb8` | `0xb0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x338` | `0x330` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`

### Other Changes

```diff

-1291.0.0.502.1
+1307.0.16.0.0

-  CStrings:  818
+  CStrings:  820
CStrings:
+ "[%s] First time pending repair. Posting lock-screen notification."
+ "[%s] Sealed SN changed"
+ "[%s] Sealed SN changed. Posting lock-screen notification."
+ "[%s] Sealed SN unchanged. Continuing existing timer."
+ "[%s] Sealed SN unchanged. Silently updating UI to Finish Repair."
+ "[%s] Throttling Finish Repair reminder. Scheduling unlock checker activity for %f seconds"
+ "[%s] reminder threshold met (interval: %lld), posting lock screen notification"
- "[%s] Unknown Part SN differs from Finish Repair SN"
- "[%s] Upgrade to Finish Repair from Unknown Part"
- "[%s] component has displayed follow up"
- "[%s] component has not displayed finish repair"
- "[%s] scheduling finish repair unlock checker activity Interval:%f "
```
