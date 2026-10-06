## libauthinstall.dylib

> `/usr/lib/libauthinstall.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb9a54` | `0xb9adc` | **`+0x88`** |
| `__TEXT.__unwind_info` | `0x2c80` | `0x2c88` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1155.40.6.0.0
+1155.40.7.0.0

-  Functions: 3807
-  Symbols:   4987
+  Functions: 3809
+  Symbols:   4989
Symbols:
+ _AMAuthInstallCopyDebugPath
+ _AMAuthInstallSetDebugPath
CStrings:
+ "VinylRestore-178~8717"
+ "libauthinstall_device-1155.40.7"
- "VinylRestore-178~8275"
- "libauthinstall_device-1155.40.6"
```
