## intents_helper

> `/System/Library/Frameworks/Intents.framework/XPCServices/intents_helper.xpc/intents_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__lazy_helpers` | `—` | `0x54` | **`+0x54`** |
| `__TEXT.__auth_stubs` | `0x350` | `0x360` | **`+0x10`** |
| `__DATA.__lazy_load_got` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x118` | `0x110` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xd0` | `0xd8` | **`+0x8`** |
| `__DATA.__data` | `0x120` | `0x124` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-4016.0.43.5.0
+4016.0.45.3.0

-  - /System/Library/Frameworks/IntentsUI.framework/IntentsUI

-  Symbols:   100
+  Symbols:   101
Symbols:
+ __dyld_lazy_load
```
