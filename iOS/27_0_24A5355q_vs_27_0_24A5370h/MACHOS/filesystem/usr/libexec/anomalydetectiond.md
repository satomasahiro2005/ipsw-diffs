## anomalydetectiond

> `/usr/libexec/anomalydetectiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36a7b4` | `0x36b4ac` | **`+0xcf8`** |
| `__TEXT.__cstring` | `0x1c7b7` | `0x1c836` | **`+0x7f`** |
| `__DATA_CONST.__const` | `0x27400` | `0x27450` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xc6f8` | `0xc730` | **`+0x38`** |
| `__TEXT.__oslogstring` | `0x117d8` | `0x11809` | **`+0x31`** |
| `__TEXT.__const` | `0xfa8e` | `0xfaae` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x18d0` | `0x18c0` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1042c` | `0x10438` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0xc80` | `0xc78` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-163.0.0.0.0
+164.0.0.0.0

-  Functions: 17094
-  Symbols:   617
-  CStrings:  9317
+  Functions: 17112
+  Symbols:   616
+  CStrings:  9325
Symbols:
- _objc_release_x10
CStrings:
+ "On realtime proxy, removed %@ since it's too old"
+ "altitudeInMeters"
+ "companionAltitude"
+ "l2NormGMMError"
+ "magneticInclinationError"
+ "magneticMagnitudeError"
+ "progress"
+ "uncertaintyInMeters"
```
