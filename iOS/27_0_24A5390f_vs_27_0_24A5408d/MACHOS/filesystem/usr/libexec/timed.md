## timed

> `/usr/libexec/timed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17858` | `0x1796c` | **`+0x114`** |
| `__TEXT.__objc_methname` | `0x255c` | `0x2593` | **`+0x37`** |
| `__DATA_CONST.__cfstring` | `0x2b60` | `0x2b80` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x26e0` | `0x2700` | **`+0x20`** |
| `__DATA.__objc_const` | `0x1da0` | `0x1db0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xd6c` | `0xd7c` | **`+0x10`** |
| `__TEXT.__cstring` | `0x20e7` | `0x20f6` | **`+0xf`** |
| `__DATA.__objc_selrefs` | `0xb48` | `0xb50` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-340.0.12.0.0
+340.0.14.0.0

-  Functions: 622
+  Functions: 623

-  CStrings:  1289
+  CStrings:  1293
CStrings:
+ "340.0.14"
+ "AudioAccessory"
+ "TB,R,GisAudioAccessory"
+ "audioAccessory"
+ "isAudioAccessory"
- "340.0.12"
```
