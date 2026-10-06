## devicerecoveryd

> `/System/Library/PrivateFrameworks/DeviceRecovery.framework/Support/devicerecoveryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22f50` | `0x2304c` | **`+0xfc`** |
| `__TEXT.__cstring` | `0x7b10` | `0x7a90` | **`-0x80`** |
| `__DATA_CONST.__cfstring` | `0x2c60` | `0x2ca0` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0xfb0` | `0xfc0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x6e0` | `0x6f0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x7e8` | `0x7f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-142.0.0.0.0
+144.0.0.0.0

-  Functions: 809
-  Symbols:   329
+  Functions: 811
+  Symbols:   330
Symbols:
+ _APFSExtendedSpaceInfo
+ _CFNumberGetTypeID
- _APFSVolumeGetSpaceInfo
CStrings:
+ "09:33:51"
+ "APFSExtendedSpaceInfo(%s) failed: %d (%#x)\n"
+ "Jun 13 2026"
+ "fs_free"
+ "fs_used"
- "23:58:12"
- "APFSVolumeGetSpaceInfo for data volume failed with result:%d"
- "APFSVolumeGetSpaceInfo for preboot volume failed with result:%d"
- "APFSVolumeGetSpaceInfo for system volume failed with result:%d"
- "Jun  2 2026"
```
