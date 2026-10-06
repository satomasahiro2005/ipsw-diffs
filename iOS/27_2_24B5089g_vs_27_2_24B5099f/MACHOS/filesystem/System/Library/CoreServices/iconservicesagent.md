## iconservicesagent

> `/System/Library/CoreServices/iconservicesagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x79b8` | `0x7608` | **`-0x3b0`** |
| `__TEXT.__gcc_except_tab` | `0x1c8` | `0x2d8` | **`+0x110`** |
| `__DATA_CONST.__cfstring` | `0xa80` | `0xa40` | **`-0x40`** |
| `__TEXT.__objc_methtype` | `0x449` | `0x426` | **`-0x23`** |
| `__TEXT.__objc_stubs` | `0x1a20` | `0x1a40` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x186c` | `0x184f` | **`-0x1d`** |
| `__TEXT.__oslogstring` | `0xcb9` | `0xca1` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x208` | `0x220` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x650` | `0x640` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x54c` | `0x53c` | **`-0x10`** |
| `__TEXT.__cstring` | `0x7ce` | `0x7c5` | **`-0x9`** |
| `__DATA.__objc_const` | `0xa90` | `0xa88` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x338` | `0x330` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-793.1.7.0.0
+793.1.10.0.0

-  Functions: 133
-  Symbols:   173
-  CStrings:  535
+  Functions: 140
+  Symbols:   172
+  CStrings:  533
Symbols:
- _objc_retain_x28
CStrings:
+ "%@"
+ "B24@?0@\"NSURL\"8@\"NSError\"16"
+ "CacheContents"
+ "Error enumerating store contents: %@"
+ "Failed to assemble diagnostics bundle"
+ "Failed to produce UUID from store entry name: %@"
+ "Failed to produce image from store unit for UUID %@"
+ "Image collection had errors during diagnostics bundle: %@"
+ "UUID %@ failed to produce store unit"
+ "UUIDString"
+ "com.apple.iconservices.diagnostics"
+ "localizedDescription"
- "Failed to copy cache contents"
- "Failed to create archive directory"
- "Failed to create bundle directory"
- "Failed to write dump.txt"
- "Icon cache not found"
- "Image encoding had errors during diagnostics archive: %@"
- "Image encoding had errors during minimal diagnostics archive: %@"
- "Index"
- "Minimal diagnostics archive collection requires an internal build"
- "Store"
- "collectMinimalDiagnosticsArchiveWithReply:"
- "fileExistsAtPath:"
- "minimal diagnostics archive collection"
- "v24@0:8@?<v@?@\"NSURL\"@\"NSError\">16"
```
