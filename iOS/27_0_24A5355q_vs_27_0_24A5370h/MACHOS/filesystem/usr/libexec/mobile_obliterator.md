## mobile_obliterator

> `/usr/libexec/mobile_obliterator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ab40` | `0x1b338` | **`+0x7f8`** |
| `__TEXT.__cstring` | `0xa88c` | `0xaa47` | **`+0x1bb`** |
| `__TEXT.__auth_stubs` | `0x14e0` | `0x1520` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0xa88` | `0xaa8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x3f8` | `0x400` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-395.0.0.0.0
+397.0.0.0.0

+  - /System/Library/PrivateFrameworks/AppleNVMe.framework/AppleNVMe

-  Functions: 271
-  Symbols:   394
-  CStrings:  1375
+  Functions: 273
+  Symbols:   398
+  CStrings:  1384
Symbols:
+ _AKSIdentityCreateFirstWithACM
+ _AKSIdentitySetPrimaryWithACM
+ _AppleNVMeSanitizeGetProgress
+ _AppleNVMeSanitizeStart
+ _AppleNVMeSanitizeSupportsSanitize
+ _archive_read_free
+ _archive_write_add_filter_bzip2
+ _archive_write_free
+ _objc_release_x19
- _AKSIdentityCreateFirst
- _AKSIdentitySetPrimary
- _archive_write_finish
- _archive_write_set_compression_bzip2
- _objc_release_x24
CStrings:
+ "%s: %s: AKSIdentityCreateFirstWithACM attempt (no passcode, acmcred=NULL)"
+ "%s: %s: AKSIdentityCreateFirstWithACM attempt with UUID %s"
+ "%s: %s: AKSIdentityCreateFirstWithACM not called (cfuuid unavailable) or failed with error:%s"
+ "%s: %s: AKSIdentityCreateFirstWithACM success, loading the identity"
+ "%s: %s: AKSIdentitySetPrimaryWithACM failed with error:%s"
+ "%s: %s: AKSIdentitySetPrimaryWithACM succeded, binding Shared data volume"
+ "%s: %s: AppleNVMeSanitizeStart failed on %s: %d"
+ "%s: %s: Could not determine BSD name for NVMe sanitize from %s"
+ "%s: %s: Could not find IOMedia for NVMe sanitize from %s"
+ "%s: %s: Could not find physical disk for NVMe sanitize from %s"
+ "%s: %s: NVMe sanitize completed on %s"
+ "%s: %s: NVMe sanitize not supported on %s"
+ "%s: %s: Option: set gSanitizeStorage to %s"
+ "%s: %s: Starting NVMe sanitize on %s"
+ "sanitizeStorage"
- "%s: %s: AKSIdentityCreateFirst attempt with UUID %s"
- "%s: %s: AKSIdentityCreateFirst attempt with emptyPass %s"
- "%s: %s: AKSIdentityCreateFirst not called (cfuuid or emptyPassRef unavailable) or failed with error:%s"
- "%s: %s: AKSIdentityCreateFirst success, loading the identity"
- "%s: %s: AKSIdentitySetPrimary failed with error:%s"
- "%s: %s: AKSIdentitySetPrimary succeded, binding Shared data volume"
```
