## restorecameraispd

> `/usr/libexec/restorecameraispd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x2bc038` | `0x3aec00` | **`+0xf2bc8`** |
| `__TEXT.__cstring` | `0x2f4c` | `0x3079` | **`+0x12d`** |
| `__TEXT.__text` | `0x1c634` | `0x1c594` | **`-0xa0`** |
| `__DATA_CONST.__cfstring` | `0x13e0` | `0x1460` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x21af` | `0x21c0` | **`+0x11`** |
| `__TEXT.__auth_stubs` | `0xe70` | `0xe60` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x4a8` | `0x4b8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x748` | `0x740` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x560` | `0x558` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`

### Other Changes

```diff

-20.47.7.0.0
+20.50.6.0.0

-  Symbols:   282
-  CStrings:  607
+  Symbols:   281
+  CStrings:  614
Symbols:
+ _strerror
- _objc_release_x25
- _perror
CStrings:
+ "\tCouldn't read %s: %s"
+ "\tCouldn't write %s: %s"
+ "\tUnexpected local cache size (expected: %ld, found: %ld)"
+ "\tUnexpected written size (expected: %ld, written %ld)"
+ "(Bin) Loading ISPCPU firmware file: %s\n"
+ "/usr/local/share/firmware/isp/2426_02XX.dat"
+ "/usr/local/share/firmware/isp/4127_01XX.dat"
+ "/usr/local/share/firmware/isp/8227_01XX.dat"
+ "/usr/local/share/firmware/isp/9726_01XX.dat"
+ "20.50.6"
+ "Bin ISPCPU firmwareFile does not exist %s\n\n"
- "(Bin) Using ISPCPU firmware override file\n"
- "20.47.7"
- "Load firmware from %s\n\n"
- "error loading ISPCPU firmware "
```
