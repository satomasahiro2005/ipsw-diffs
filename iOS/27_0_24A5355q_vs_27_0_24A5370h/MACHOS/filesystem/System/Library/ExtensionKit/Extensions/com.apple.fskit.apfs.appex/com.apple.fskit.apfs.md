## com.apple.fskit.apfs

> `/System/Library/ExtensionKit/Extensions/com.apple.fskit.apfs.appex/com.apple.fskit.apfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe3c6c` | `0xe42c0` | **`+0x654`** |
| `__DATA.__common` | `0x9d8` | `0x6b8` | **`-0x320`** |
| `__TEXT.__cstring` | `0x3b2ce` | `0x3b3c0` | **`+0xf2`** |
| `__DATA.__bss` | `0x1e391` | `0x1e399` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3277.0.0.0.1
+3283.0.0.0.0

-  Functions: 3279
-  Symbols:   1563
-  CStrings:  5359
+  Functions: 3283
+  Symbols:   1565
+  CStrings:  5364
Symbols:
+ _cst_from_fvkey
+ _get_ino_purgeable_size
+ _is_omap_in_reaper
- _omap_in_reaper
CStrings:
+ "3283"
+ "could not allocate array of %u entries for tracking omap objects in reap list; skipping subsequent ones\n"
+ "encountered more than %u omap objects in reap list; skipping subsequent ones\n"
+ "fsck_reaper.c"
+ "omap_info.omaps_in_reaper == NULL"
+ "set_omap_in_reaper"
- "3277.0.0.0.1"
```
