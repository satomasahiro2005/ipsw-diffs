## launchd

> `/sbin/launchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a620` | `0x5b820` | **`+0x1200`** |
| `__TEXT.__cstring` | `0x16514` | `0x16a38` | **`+0x524`** |
| `__DATA_CONST.__const` | `0x59a0` | `0x5a68` | **`+0xc8`** |
| `__TEXT.__unwind_info` | `0x1110` | `0x1150` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x26d0` | `0x2700` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x1370` | `0x1388` | **`+0x18`** |
| `__DATA.__bss` | `0xde8` | `0xdf8` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x98` | `0xa0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__os_assumes_log`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__dof_launchd`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-3298.0.21.0.0
+3298.0.26.502.1

-  Functions: 1477
-  Symbols:   707
-  CStrings:  2808
+  Functions: 1489
+  Symbols:   710
+  CStrings:  2835
Symbols:
+ _mkdirat
+ _objc_retain_x23
+ _objc_retain_x25
+ _renameatx_np
- _objc_retain_x22
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Wed Aug  5 00:07:47 PDT 2026; root:libxpc_executables-3298.0.26.502.1~2/launchd/RELEASE_ARM64E"
+ "Booting-out existing multi-instance extension with different path: existing = %s, conflicting = %s"
+ "Cannot rename secure socket; UIDs mismatch: socket owner=%d, path=%d"
+ "Darwin Bootstrapper Version 7.0.0: Wed Aug  5 00:07:47 PDT 2026; root:libxpc_executables-3298.0.26.502.1~2/launchd/RELEASE_ARM64E"
+ "Failed to basename_r() socket directory path: path=%s, error=%s (%d)"
+ "Failed to dirname_r() socket directory path: path=%s, error=%s (%d)"
+ "Failed to dirname_r() socket path: path=%s, error=%s (%d)"
+ "Failed to fstatat() secure socket path: path=%s, error=%s (%d)"
+ "Failed to fstatat() socket path: path=%s, error=%s (%d)"
+ "Failed to open() socket parent directory: path=%s, error=%s (%d)"
+ "Failed to renameat() passive socket from secure path to known path: secure path=%s, known path=%s, error=%s (%d)"
+ "Failed to resolve BundlePath: error=%s: %d, caller=%s"
+ "Failed to stat() socket directory path: path=%s, error=%s (%d)"
+ "Invalid socket name: %s"
+ "No hidden path for socket: path=%s"
+ "Secure socket path is not a socket; path=%s"
+ "Unable to open stderr path (%s)"
+ "Unable to open stdin path (%s)"
+ "Unable to open stdout path (%s)"
+ "_BundlePath"
+ "bundle path = %s"
+ "caller failed %s sandbox check on parent directory %s"
+ "caller failed %s sandbox check on path %s"
+ "caller failed file-write-create sandbox check on grand parent directory %s"
+ "com.apple.private.xpc.launchd.allow-set-bundle-path"
+ "file-write-create"
+ "file-write-unlink"
+ "needs_rename = %s"
+ "setup unix domain socket"
- "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Fri Jul 10 23:04:38 PDT 2026; root:libxpc_executables-3298.0.21~14/launchd/RELEASE_ARM64E"
- "Darwin Bootstrapper Version 7.0.0: Fri Jul 10 23:04:38 PDT 2026; root:libxpc_executables-3298.0.21~14/launchd/RELEASE_ARM64E"
```
