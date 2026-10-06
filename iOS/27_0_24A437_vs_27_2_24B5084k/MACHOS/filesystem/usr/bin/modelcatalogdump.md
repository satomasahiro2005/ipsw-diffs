## modelcatalogdump

> `/usr/bin/modelcatalogdump`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ae88` | `0x1ae44` | **`-0x44`** |
| `__TEXT.__auth_stubs` | `0x1250` | `0x1260` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x930` | `0x938` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x3c0` | `0x3c8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-302.6.0.3.0
+308.7.0.1.0

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

+  - /usr/lib/swift/libswift_DarwinFoundation2.dylib

-  Functions: 543
-  Symbols:   124
+  Functions: 542
+  Symbols:   126
Symbols:
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ _setvbuf
```
