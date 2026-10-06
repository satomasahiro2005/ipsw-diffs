## libramrod.dylib

> `/usr/lib/libramrod.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf0530` | `0xf0074` | **`-0x4bc`** |
| `__TEXT.__cstring` | `0x2beef` | `0x2bd87` | **`-0x168`** |
| `__AUTH_CONST.__cfstring` | `0xc4c0` | `0xc400` | **`-0xc0`** |
| `__TEXT.__auth_stubs` | `0x2b50` | `0x2b20` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0x15b0` | `0x1598` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x1eb8` | `0x1eb0` | **`-0x8`** |

### Same-size Content Changes

- `__AUTH.__data`
- `__AUTH.__objc_data`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__DATA.__data`
- `__DATA.__objc_classrefs`
- `__DATA.__objc_superrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_selrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3696.40.12.0.1
+3696.40.14.0.1

-  - /usr/lib/updaters/libBMCMCUUpdater.dylib
-  Functions: 2874
-  Symbols:   1896
-  CStrings:  6388
+  Functions: 2869
+  Symbols:   1893
+  CStrings:  6377
Symbols:
- _BMCMCUUpdaterCleanupDeviceInfo
- _BMCMCUUpdaterGetDeviceInfo
- _BMCMCUUpdaterUpdateDevice
CStrings:
- "%s: %s failed\n"
- "%s: bad argument - no options"
- "%s: copy_available_fud_image_names returned NULL"
- "%s: failed to copy fud data for: %@"
- "%s: failed to get device name and tag from %s\n"
- "/usr/lib/updaters/libBMCMCUUpdater.dylib"
- "BMCMCUUpdaterGetDeviceInfo"
- "Could not find: %s, skipping update\n"
- "device has no BMC MCU, skipping update\n"
- "libBMCMCUUpdater.dylib"
- "update_bmc_mcu"
```
