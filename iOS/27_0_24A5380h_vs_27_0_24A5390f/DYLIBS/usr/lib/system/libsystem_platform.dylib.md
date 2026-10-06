## libsystem_platform.dylib

> `/usr/lib/system/libsystem_platform.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__script_config` | `0x8000` | `0x4000` | **`-0x4000`** |
| `__TEXT.__text` | `0x6fdc` | `0x6eec` | **`-0xf0`** |
| `__TEXT.__cstring` | `0x872` | `0x815` | **`-0x5d`** |
| `__TEXT.__const` | `0xa0` | `0xb0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x318` | `0x310` | **`-0x8`** |

### Other Changes

```diff

-402.0.0.0.0
+402.0.1.0.0

-  Functions: 290
-  Symbols:   325
-  CStrings:  69
+  Functions: 287
+  Symbols:   322
+  CStrings:  67
Symbols:
- ___restrictions_config
- __freeze_restrictions_config
- _mach_vm_protect
CStrings:
- "BUG IN LIBPLATFORM: Failed to freeze config."
- "BUG IN LIBPLATFORM: Failed to reprotect config."
```
