## online-auth-agent

> `/usr/libexec/online-auth-agent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c768` | `0x3ca2c` | **`+0x2c4`** |
| `__DATA_CONST.__const` | `0x2440` | `0x2488` | **`+0x48`** |
| `__TEXT.__cstring` | `0x3c06` | `0x3c4b` | **`+0x45`** |
| `__DATA_CONST.__cfstring` | `0x1460` | `0x14a0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x2d9b` | `0x2ddb` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x1df0` | `0x1e20` | **`+0x30`** |
| `__DATA.__bss` | `0x3030` | `0x3050` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xf08` | `0xf20` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x450` | `0x458` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xeb8` | `0xec0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-486.0.0.0.0
+487.0.0.0.0

-  Functions: 1260
-  Symbols:   430
-  CStrings:  1013
+  Functions: 1265
+  Symbols:   434
+  CStrings:  1017
Symbols:
+ _CFNumberGetTypeID
+ _CFNumberGetValue
+ _CFPreferencesCopyValue
+ _kCFPreferencesAnyHost
CStrings:
+ "1cf29dc4-4f08-457d-b9a7-512c89f0e142"
+ "Overriding expiry for profile %{public}@ with timestamp %f"
+ "mobile"
+ "relaxProfileExpiry-%@"
```
