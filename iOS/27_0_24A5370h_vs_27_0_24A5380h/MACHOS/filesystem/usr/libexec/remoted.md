## remoted

> `/usr/libexec/remoted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d274` | `0x3d534` | **`+0x2c0`** |
| `__TEXT.__auth_stubs` | `0x1810` | `0x1860` | **`+0x50`** |
| `__TEXT.__cstring` | `0x21a4` | `0x21d9` | **`+0x35`** |
| `__TEXT.__const` | `0x1fa` | `0x22a` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0xc18` | `0xc40` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x230` | `0x250` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xdb8` | `0xdc8` | **`+0x10`** |
| `__DATA.__bss` | `0x3b0` | `0x3b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-245.0.1.502.2
+245.0.4.0.0

-  Functions: 1370
-  Symbols:   482
-  CStrings:  1769
+  Functions: 1375
+  Symbols:   492
+  CStrings:  1775
Symbols:
+ _ftruncate
+ _kCFAbsoluteTimeIntervalSince1970
+ _mmap
+ _sntp_datestamp_from_double
+ _sntp_header_mmap
+ _sntp_shortstamp_hton
+ _sntp_timestamp_to_shortstamp
+ _umask
+ _warn
+ _write
CStrings:
+ "/var/sntpd/state.bin"
+ "close"
+ "ftruncate"
+ "mmap"
+ "open"
+ "write"
```
