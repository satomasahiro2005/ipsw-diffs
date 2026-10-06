## clocksyncd

> `/usr/libexec/clocksyncd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b364` | `0x3b498` | **`+0x134`** |
| `__DATA_CONST.__cfstring` | `0x1f00` | `0x1f60` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x5a00` | `0x5a40` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x919d` | `0x91d0` | **`+0x33`** |
| `__TEXT.__cstring` | `0x2835` | `0x2866` | **`+0x31`** |
| `__DATA_CONST.__const` | `0x948` | `0x968` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x592c` | `0x5945` | **`+0x19`** |
| `__DATA.__bss` | `0x141` | `0x151` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1da0` | `0x1db0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x278` | `0x288` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xd30` | `0xd40` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1aa8` | `0x1ab4` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x6b0` | `0x6b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Functions: 1532
-  Symbols:   281
-  CStrings:  2459
+  Functions: 1534
+  Symbols:   284
+  CStrings:  2466
Symbols:
+ _OBJC_CLASS_$_NSBundle
+ _OBJC_CLASS_$_TSMSGService
+ __os_feature_enabled_impl
CStrings:
+ "Genlock"
+ "Localizable"
+ "Localized clockName: %@\n"
+ "bundleForClass:"
+ "fall_2026"
+ "genlock-clock-name"
+ "localizedStringForKey:value:table:"
```
