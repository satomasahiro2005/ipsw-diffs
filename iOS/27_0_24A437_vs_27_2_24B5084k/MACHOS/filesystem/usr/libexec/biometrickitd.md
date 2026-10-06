## biometrickitd

> `/usr/libexec/biometrickitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `—` | `0x10` | **`+0x10`** |
| `__DATA.__common` | `0x10` | `—` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x1bb` | `0x1be` | **`+0x3`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`

### Other Changes

```diff

-577.0.0.0.0
+578.40.6.0.0
CStrings:
+ "AssertMacros: %s (value = 0x%lx), version: BiometricKit-578.40.6~32, %s file: %s, line: %d\n\n"
- "AssertMacros: %s (value = 0x%lx), version: BiometricKit-577~3209, %s file: %s, line: %d\n\n"
```
