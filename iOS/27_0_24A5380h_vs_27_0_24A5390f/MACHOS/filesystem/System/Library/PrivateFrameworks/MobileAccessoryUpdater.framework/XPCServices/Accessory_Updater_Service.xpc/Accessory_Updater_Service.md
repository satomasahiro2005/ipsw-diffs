## Accessory Updater Service

> `/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/XPCServices/Accessory Updater Service.xpc/Accessory Updater Service`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77fbc` | `0x780c4` | **`+0x108`** |
| `__TEXT.__const` | `0x5d50` | `0x5db0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x1a10` | `0x1a28` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3696.0.3.0.1
+3696.0.7.0.0

-  Functions: 2744
-  Symbols:   1874
+  Functions: 2745
+  Symbols:   1875
Symbols:
+ _AMAuthInstallErrorFromAMSupportError
CStrings:
+ "libauthinstall_device-1155.0.4"
- "libauthinstall_device-1155.0.3"
```
