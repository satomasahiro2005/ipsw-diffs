## com.apple.fskit.msdos

> `/System/Library/ExtensionKit/Extensions/com.apple.fskit.msdos.appex/com.apple.fskit.msdos`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1570c` | `0x15810` | **`+0x104`** |
| `__TEXT.__oslogstring` | `0xe6a` | `0xf6d` | **`+0x103`** |
| `__TEXT.__gcc_except_tab` | `0x470` | `0x464` | **`-0xc`** |
| `__DATA_CONST.__got` | `0xd8` | `0xe0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-845.0.0.0.0
+845.0.2.0.0

-  Functions: 451
+  Functions: 457

-  CStrings:  1016
+  CStrings:  1021
CStrings:
+ "%s: FAT offset overflows (resSectors=%u, bytesPerSector=%u)"
+ "%s: FAT size overflows (fatSectors=%u, bytesPerSector=%u)"
+ "%s: First cluster offset overflows"
+ "%s: Root directory block overflows (FATs=%u, fatSectors=%u, reservedSectors=%u)"
+ "%s: Zero bytes-per-sector"
```
