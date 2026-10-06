## transparency-sysdiagnose

> `/usr/libexec/transparency-sysdiagnose`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf78` | `0x11d0` | **`+0x258`** |
| `__TEXT.__cstring` | `0x15d` | `0x1de` | **`+0x81`** |
| `__DATA_CONST.__cfstring` | `0xe0` | `0x140` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xa8` | `0xe8` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x74` | `0xaf` | **`+0x3b`** |
| `__TEXT.__auth_stubs` | `0x2b0` | `0x2c0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xb8` | `0xc8` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x54` | `0x60` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x168` | `0x170` | **`+0x8`** |
| `__TEXT.__const` | `0x18` | `0x20` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1766.0.60.0.0
+1766.40.47.0.0

-  Functions: 21
-  Symbols:   71
-  CStrings:  102
+  Functions: 25
+  Symbols:   72
+  CStrings:  105
Symbols:
+ _objc_release_x25
CStrings:
+ "no application support directory to read the fallback report from: %@"
+ "no directory to delete %@ from"
+ "no directory to write %@ to"
```
