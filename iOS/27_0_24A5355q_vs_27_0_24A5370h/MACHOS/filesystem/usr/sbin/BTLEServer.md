## BTLEServer

> `/usr/sbin/BTLEServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0xd6dc` | `0xd77e` | **`+0xa2`** |
| `__TEXT.__text` | `0x7ec3c` | `0x7ecc0` | **`+0x84`** |
| `__DATA_CONST.__cfstring` | `0x4c60` | `0x4ca0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x360a` | `0x363c` | **`+0x32`** |
| `__DATA_CONST.__const` | `0x17a0` | `0x17c0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1bc0` | `0x1be0` | **`+0x20`** |
| `__DATA.__bss` | `0x1c0` | `0x1d8` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x10c0` | `0x10d0` | **`+0x10`** |
| `__TEXT.__const` | `0x8f0` | `0x900` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x13c4` | `0x13d0` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x878` | `0x880` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-2700.30.2.0.0
+2700.34.0.0.0

-  Functions: 3153
-  Symbols:   569
-  CStrings:  5245
+  Functions: 3155
+  Symbols:   570
+  CStrings:  5251
Symbols:
+ _CFPreferencesGetAppBooleanValue
CStrings:
+ "NativeHealth"
+ "NativeHealth GHS is %{public}s, flagExists=%{public}s"
+ "Skipping NativeHealth service \"%{public}@\" on peripheral \"%{private, mask.hash}@\": NativeHealth not enabled"
+ "disabled"
+ "enableHealthDevices"
+ "enabled"
```
