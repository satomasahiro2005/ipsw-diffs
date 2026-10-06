## cameraispd

> `/usr/libexec/cameraispd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7cb80` | `0x7cd44` | **`+0x1c4`** |
| `__TEXT.__oslogstring` | `0x5f4b` | `0x5f8f` | **`+0x44`** |
| `__TEXT.__gcc_except_tab` | `0x18c8` | `0x18e0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xc90` | `0xc98` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-20.55.3.0.0
+20.57.3.0.0

-  Functions: 1556
-  Symbols:   917
-  CStrings:  1840
+  Functions: 1560
+  Symbols:   918
+  CStrings:  1841
Symbols:
+ _kFigCaptureStreamMetadata_IAD
CStrings:
+ "%s - ABDNet: Failed to allocate dictionary\n"
+ "%s - ABDNet: couldn't allocate address (%lu/%zu)\n"
+ "20.57.3"
- "%s - ABDNet: No Address?\n"
- "20.55.3"
```
