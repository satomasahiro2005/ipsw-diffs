## misagent

> `/usr/libexec/misagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x190bc` | `0x19318` | **`+0x25c`** |
| `__DATA_CONST.__cfstring` | `0x1480` | `0x14e0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xe38` | `0xe78` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x1f07` | `0x1f47` | **`+0x40`** |
| `__DATA.__bss` | `0x170` | `0x190` | **`+0x20`** |
| `__TEXT.__cstring` | `0x345e` | `0x347e` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x14a0` | `0x14b0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x738` | `0x748` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xa60` | `0xa68` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x160` | `0x168` | **`+0x8`** |

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

-  Functions: 659
-  Symbols:   365
-  CStrings:  722
+  Functions: 665
+  Symbols:   367
+  CStrings:  725
Symbols:
+ _CFPreferencesCopyValue
+ _kCFPreferencesAnyHost
CStrings:
+ "Overriding expiry for profile %{public}@ with timestamp %f"
+ "mobile"
+ "relaxProfileExpiry-%@"
```
