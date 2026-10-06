## com.apple.fskit.exfat

> `/System/Library/ExtensionKit/Extensions/com.apple.fskit.exfat.appex/com.apple.fskit.exfat`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12434` | `0x1287c` | **`+0x448`** |
| `__DATA_CONST.__const` | `0x370` | `0x3e8` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0x5bc` | `0x5f3` | **`+0x37`** |
| `__TEXT.__gcc_except_tab` | `0x374` | `0x39c` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x2f8` | `0x310` | **`+0x18`** |
| `__TEXT.__cstring` | `0x3e5c` | `0x3e6b` | **`+0xf`** |
| `__DATA.__common` | `0x2b0` | `0x2b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-561.0.1.0.0
+561.0.3.0.0

-  Functions: 277
-  Symbols:   414
-  CStrings:  577
+  Functions: 284
+  Symbols:   416
+  CStrings:  579
Symbols:
+ _fsckRunGuarded
+ _fsck_set_run_guarded_func
CStrings:
+ "%s: caught exception on fsck worker thread, error = %d"
+ "fsckRunGuarded"
```
