## diskarbitrationd

> `/usr/libexec/diskarbitrationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bcfc` | `0x1f944` | **`+0x3c48`** |
| `__TEXT.__oslogstring` | `0xb` | `0x1928` | **`+0x191d`** |
| `__TEXT.__const` | `0x80` | `0x120` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x33fe` | `0x3368` | **`-0x96`** |
| `__DATA_CONST.__const` | `0xef8` | `0xf38` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0xa8` | `0xd0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x610` | `0x630` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x1720` | `0x1710` | **`-0x10`** |
| `__DATA.__bss` | `0xdb0` | `0xdb8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xba0` | `0xb98` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-597.0.0.0.0
+597.0.2.0.0

-  Functions: 530
-  Symbols:   421
-  CStrings:  704
+  Functions: 556
+  Symbols:   420
+  CStrings:  699
Symbols:
+ __os_log_debug_impl
+ _objc_retain_x2
- _closelog
- _objc_retain_x28
- _openlog
CStrings:
+ "  dispatched response, id = %016llX:%016llX, kind = %s, disk = %{private}s, orphaned."
+ "%s: Failed to allocate retry context, falling through to cleanup"
+ "%{private}s"
+ "Skipping apfs_userfs.fs as apfsUseFSKitModule pref is on"
+ "__DASetIdleTimer %d %p"
+ "unable to copy disk description, id = %{private}s (status code 0x%08X)."
+ "unable to create session, id = %{private}s [%d] (status code 0x%08X)."
+ "unable to dispatch response, id = %016llX:%016llX, disk = %{private}s (status code 0x%08X)."
+ "unable to get disk claim state, id = %{private}s (status code 0x%08X)."
+ "unable to get disk options, id = %{private}s (status code 0x%08X)."
+ "unable to queue solicitation, id = %016llX:%016llX, kind = %s, disk = %{private}s (status code 0x%08X)."
+ "unable to set disk adoption, id = %{private}s (status code 0x%08X)."
+ "unable to set disk options, id = %{private}s (status code 0x%08X)."
+ "unable to unclaim disk, id = %{private}s (status code 0x%08X)."
- "  dispatched response, id = %016llX:%016llX, kind = %s, disk = %s, orphaned."
- "%{public}s"
- "DALog.c"
- "DALogDebug"
- "Failed to allocate retry context, falling through to cleanup"
- "Skipping apfs.fs as apfsUseFSKitModule pref is on"
- "__DAProbeWithFSKit_block_invoke_2"
- "__DASetIdleTimer %d %x"
- "__gDALogDebugHeaderNext"
- "apfs.fs"
- "unable to copy disk description, id = %s (status code 0x%08X)."
- "unable to create session, id = %s [%d] (status code 0x%08X)."
- "unable to dispatch response, id = %016llX:%016llX, disk = %s (status code 0x%08X)."
- "unable to get disk claim state, id = %s (status code 0x%08X)."
- "unable to get disk options, id = %s (status code 0x%08X)."
- "unable to queue solicitation, id = %016llX:%016llX, kind = %s, disk = %s (status code 0x%08X)."
- "unable to set disk adoption, id = %s (status code 0x%08X)."
- "unable to set disk options, id = %s (status code 0x%08X)."
- "unable to unclaim disk, id = %s (status code 0x%08X)."
```
