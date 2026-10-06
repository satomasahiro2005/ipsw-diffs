## libsandbox.1.dylib

> `/usr/lib/libsandbox.1.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x182c` | `0x18ac` | **`+0x80`** |
| `__TEXT.__cstring` | `0x1c2` | `0x1d5` | **`+0x13`** |

### Other Changes

```diff

-3033.0.0.0.1
+3051.0.18.0.3

-  Symbols:   69
-  CStrings:  22
+  Symbols:   68
+  CStrings:  23
Symbols:
- _reallocf
CStrings:
+ "(bytes_to_advance % ITEM_ALIGNMENT) == 0"
+ "FC875440-875A-419D-94A1-5367A943F40B"
+ "buffer != NULL"
+ "sb_packbuff_init_with_buffer"
- "(bytes_to_advance % BYTE_ALIGNMENT) == 0"
- "C7CDAAD8-33DB-4677-8224-7E1A0221C01C"
- "additional_bytes != NULL"
```
