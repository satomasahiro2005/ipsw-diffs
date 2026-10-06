## fontservicesd

> `/System/Library/PrivateFrameworks/FontServices.framework/Support/fontservicesd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc36c` | `0xca10` | **`+0x6a4`** |
| `__TEXT.__cstring` | `0x15cd` | `0x16b4` | **`+0xe7`** |
| `__DATA_CONST.__cfstring` | `0x1400` | `0x1460` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xa80` | `0xaa8` | **`+0x28`** |
| `__TEXT.__objc_methname` | `0x2429` | `0x244c` | **`+0x23`** |
| `__DATA.__objc_const` | `0x978` | `0x998` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1d80` | `0x1da0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x350` | `0x370` | **`+0x20`** |
| `__DATA.__bss` | `0xc8` | `0xd0` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0xa08` | `0xa10` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x908` | `0x910` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x54` | `0x58` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-167.0.0.0.0
+168.0.0.0.0

-  Functions: 220
+  Functions: 225

-  CStrings:  675
+  CStrings:  681
CStrings:
+ "\v"
+ "_issuedFontsQueue"
+ "checkin received malformed options; dropping the connection."
+ "com.apple.fontservicesd.issuedFonts"
+ "fontChanged received malformed changedInfo; dropping the connection."
+ "issuedFontsQueue"
+ "requestFonts received malformed params; dropping the connection."
- "\n"
```
