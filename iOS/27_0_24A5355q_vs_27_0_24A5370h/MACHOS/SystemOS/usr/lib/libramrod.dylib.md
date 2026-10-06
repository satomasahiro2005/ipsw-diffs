## libramrod.dylib

> `/usr/lib/libramrod.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xef0e8` | `0xeeef4` | **`-0x1f4`** |
| `__TEXT.__cstring` | `0x2bb76` | `0x2bbc9` | **`+0x53`** |
| `__TEXT.__oslogstring` | `0xab4` | `0xada` | **`+0x26`** |
| `__AUTH_CONST.__cfstring` | `0xc360` | `0xc380` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1ea0` | `0x1e80` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x1f78` | `0x1f88` | **`+0x10`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH.__objc_data`
- `__AUTH_CONST.__auth_got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__DATA.__data`
- `__DATA_CONST.__objc_selrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3689.0.0.0.1
+3695.0.0.0.0

-  Functions: 2867
-  Symbols:   1883
-  CStrings:  6353
+  Functions: 2863
+  Symbols:   1885
+  CStrings:  6357
Symbols:
+ _ramrod_mark_nonce_slot_nonprovisional
+ _ramrod_mark_nonce_slot_provisional
CStrings:
+ "%s: iBoot variant is 0 bytes"
+ "/usr/standalone/firmware/FUD/"
+ "Generating reference frames files...\n"
+ "RestoreAOP"
+ "Syncing NVRAM after final result.\n"
+ "iboot-stage-one-variant"
+ "invalid block size"
- "%s: iboot-build-variant is 0 bytes"
- "IFileDecoderStreamCreateWithFD"
- "IFileDecoderStreamCreateWithFilename"
```
