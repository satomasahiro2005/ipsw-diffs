## mobile_obliterator

> `/usr/libexec/mobile_obliterator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b76c` | `0x1ba48` | **`+0x2dc`** |
| `__TEXT.__cstring` | `0xad42` | `0xadf4` | **`+0xb2`** |
| `__DATA.__bss` | `0x2a30` | `0x2a48` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x408` | `0x420` | **`+0x18`** |
| `__TEXT.__const` | `0x6f8` | `0x708` | **`+0x10`** |
| `__DATA.__data` | `0x250` | `0x248` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 276
+  Functions: 277

-  CStrings:  1407
+  CStrings:  1411
CStrings:
+ "%s: Got a non-CFData return value from IORegistryEntryCreateCFProperty for property %s\n"
+ "Will use display %s (ctx %d)\n"
+ "aux image path set: %s\n"
+ "ctx[%d] rotation: %d\n"
+ "display-boot-rotation (MG) = %d\n"
+ "ramrod_copy_value_from_IONode"
- "Will use display %s\n"
- "display-boot-rotation = %d\n"
```
