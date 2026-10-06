## System

> `/System/Library/CoreAccessories/PlugIns/Platform/System.platform/System`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ef0` | `0x4ea8` | **`-0x48`** |
| `__DATA.__data` | `0x240` | `0x200` | **`-0x40`** |
| `__DATA_DIRTY.__data` | `0x38` | `0x78` | **`+0x40`** |
| `__DATA.__bss` | `0x30` | `0x28` | **`-0x8`** |
| `__DATA_DIRTY.__bss` | `0x10` | `0x18` | **`+0x8`** |

### Other Changes

```diff

-1196.0.0.502.1
+1203.0.0.0.0

-  Symbols:   351
+  Symbols:   350
Symbols:
- _objc_retain_x23
Functions:
~ -[ACCPlatformPluginSystem _observeApplicationState:] : 328 -> 256
```
