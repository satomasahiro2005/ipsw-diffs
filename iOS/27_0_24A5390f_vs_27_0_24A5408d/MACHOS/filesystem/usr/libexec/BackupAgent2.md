## BackupAgent2

> `/usr/libexec/BackupAgent2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x90c98` | `0x90d80` | **`+0xe8`** |
| `__TEXT.__cstring` | `0x18fb5` | `0x1900c` | **`+0x57`** |
| `__TEXT.__oslogstring` | `0xdf81` | `0xdfd8` | **`+0x57`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3039.0.1.0.0
+3039.2.2.0.0

-  Functions: 2455
+  Functions: 2457

-  CStrings:  5763
+  CStrings:  5765
CStrings:
+ "Ignoring DLRequestFile message from the host"
+ "Ignoring DLSendFile message from the host"
```
