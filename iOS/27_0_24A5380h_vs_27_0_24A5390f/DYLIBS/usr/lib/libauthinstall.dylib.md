## libauthinstall.dylib

> `/usr/lib/libauthinstall.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb9248` | `0xb9544` | **`+0x2fc`** |
| `__TEXT.__const` | `0x6456` | `0x64b6` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x4560` | `0x45bc` | **`+0x5c`** |
| `__TEXT.__unwind_info` | `0x2bf8` | `0x2c28` | **`+0x30`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1155.0.3.0.0
+1155.0.4.0.0

-  Functions: 3796
-  Symbols:   4963
+  Functions: 3794
+  Symbols:   4965
Symbols:
+ _AMAuthInstallErrorFromAMSupportError
+ __ZN11ACFULogging14getUpdaterNameEv
CStrings:
+ "HelsinkiRestore-58.0.44"
+ "VinylRestore-178~3428"
+ "libauthinstall_device-1155.0.4"
- "HelsinkiRestore-58.0.42"
- "VinylRestore-178~2206"
- "libauthinstall_device-1155.0.3"
```
