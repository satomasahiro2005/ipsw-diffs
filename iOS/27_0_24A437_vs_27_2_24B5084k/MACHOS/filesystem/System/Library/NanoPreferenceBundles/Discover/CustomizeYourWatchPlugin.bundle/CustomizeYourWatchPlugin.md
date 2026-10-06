## CustomizeYourWatchPlugin

> `/System/Library/NanoPreferenceBundles/Discover/CustomizeYourWatchPlugin.bundle/CustomizeYourWatchPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f0` | `0x21c` | **`+0x2c`** |
| `__TEXT.__auth_stubs` | `0x80` | `0x90` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x70` | `0x78` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1359.9.0.0.0
+1370.0.0.0.0

-  Symbols:   20
+  Symbols:   21
Symbols:
+ _BPSGetActiveSetupCompletedDevice
Functions:
~ sub_d28 : 8 -> 52
```
