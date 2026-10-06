## videosubscriptionsd

> `/usr/libexec/videosubscriptionsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaf2c` | `0xafa8` | **`+0x7c`** |
| `__TEXT.__oslogstring` | `0x14d0` | `0x1502` | **`+0x32`** |
| `__TEXT.__cstring` | `0x667` | `0x68c` | **`+0x25`** |
| `__DATA_CONST.__const` | `0x760` | `0x780` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x330` | `0x338` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-608.0.0.0.0
+609.0.0.0.0

-  Functions: 247
+  Functions: 250

-  CStrings:  554
+  CStrings:  556
CStrings:
+ "Received legacy distnoted matching event."
+ "Received trusted distnoted matching event."
+ "com.apple.distnoted.matching.trusted"
- "Received distnoted matching event."
```
