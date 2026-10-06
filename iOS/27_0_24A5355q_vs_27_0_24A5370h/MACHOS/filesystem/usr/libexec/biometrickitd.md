## biometrickitd

> `/usr/libexec/biometrickitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc84` | `0xc60` | **`-0x24`** |
| `__TEXT.__auth_stubs` | `0x1e0` | `0x200` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xf8` | `0x108` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x1ba` | `0x1bb` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-570.0.0.0.0
+573.0.0.0.0

-  Symbols:   45
+  Symbols:   47
Symbols:
+ _objc_release_x25
+ _objc_release_x28
Functions:
~ sub_1000009e8 : 2432 -> 2404
~ sub_1000015f0 -> sub_1000015d4 : 124 -> 116
CStrings:
+ "AssertMacros: %s (value = 0x%lx), version: BiometricKit-573~1109, %s file: %s, line: %d\n\n"
- "AssertMacros: %s (value = 0x%lx), version: BiometricKit-570~896, %s file: %s, line: %d\n\n"
```
