## inboxupdaterd

> `/usr/libexec/inboxupdaterd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8cdd4` | `0x8d6a8` | **`+0x8d4`** |
| `__TEXT.__objc_stubs` | `0x8960` | `0x8ac0` | **`+0x160`** |
| `__TEXT.__objc_methname` | `0x9040` | `0x9190` | **`+0x150`** |
| `__DATA.__objc_const` | `0x99e8` | `0x9a80` | **`+0x98`** |
| `__TEXT.__objc_methlist` | `0x4164` | `0x41f4` | **`+0x90`** |
| `__TEXT.__cstring` | `0x550d` | `0x5593` | **`+0x86`** |
| `__DATA_CONST.__cfstring` | `0x4cc0` | `0x4d40` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0xa8b7` | `0xa92c` | **`+0x75`** |
| `__TEXT.__objc_methtype` | `0x1792` | `0x1806` | **`+0x74`** |
| `__DATA_CONST.__const` | `0xf2f0` | `0xf358` | **`+0x68`** |
| `__DATA.__objc_selrefs` | `0x2750` | `0x27b0` | **`+0x60`** |
| `__TEXT.__const` | `0x11573` | `0x115d3` | **`+0x60`** |
| `__DATA_CONST.__objc_intobj` | `0x1ae8` | `0x1b18` | **`+0x30`** |
| `__DATA.__data` | `0x25c8` | `0x25f0` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x1778` | `0x17a0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1f90` | `0x1fb0` | **`+0x20`** |
| `__DATA_CONST.__objc_arrayobj` | `0x600` | `0x618` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x1520` | `0x1530` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x450` | `0x45c` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0xaa0` | `0xaa8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x598` | `0x5a0` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x4d8` | `0x4e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-274.2.2.0.0
+274.40.15.0.0

-  Functions: 4271
-  Symbols:   510
-  CStrings:  3764
+  Functions: 4288
+  Symbols:   511
+  CStrings:  3792
Symbols:
+ __CFCopySystemVersionDictionary
CStrings:
+ "@28@0:8@16B24"
+ "Current build version: %@(%@); target version: %@"
+ "Failed to install factory assets."
+ "Failed to purge asset file: %{public}@"
+ "Idle timer fired with context: %{public}@"
+ "Initializing MIBUSUController with delegate: %{public}@, use SSDC: %{public}d"
+ "Overriding personalization server URL to SSDC: %{public}@"
+ "SigningServerForSU"
+ "TB,N,V_useSSDC"
+ "TB,N,V_useSSDCForSU"
+ "T{os_unfair_lock_s=I},N,V_idleTimerLock"
+ "_handleIdleTimerWithContext:"
+ "_idleTimerLock"
+ "_useSSDC"
+ "_useSSDCForSU"
+ "acquireFullWake"
+ "buildVersionWithoutSplat"
+ "https://ssdc.ist.apple.com:443"
+ "idleTimerLock"
+ "initWithDelegate:useSSDC:"
+ "releaseFullWake"
+ "setIdleTimerLock:"
+ "setPersonalizationServerURL:"
+ "setUseSSDC:"
+ "setUseSSDCForSU:"
+ "useSSDC"
+ "useSSDCForSU"
+ "v20@0:8{os_unfair_lock_s=I}16"
+ "{os_unfair_lock_s=\"_os_unfair_lock_opaque\"I}"
+ "{os_unfair_lock_s=I}16@0:8"
- "Idle timer fired with user info: %{public}@"
- "Initializing MIBUSUController with delegate: %{public}@"
```
