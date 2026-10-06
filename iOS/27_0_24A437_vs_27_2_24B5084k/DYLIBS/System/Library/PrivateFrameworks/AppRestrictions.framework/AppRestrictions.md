## AppRestrictions

> `/System/Library/PrivateFrameworks/AppRestrictions.framework/AppRestrictions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x106f8` | `0x10efc` | **`+0x804`** |
| `__TEXT.__oslogstring` | `0x262` | `0x332` | **`+0xd0`** |
| `__AUTH_CONST.__const` | `0x738` | `0x7a8` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x2b08` | `0x2b48` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x5d8` | `0x610` | **`+0x38`** |
| `__DATA.__data` | `0x4e0` | `0x510` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x240` | `0x270` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x650` | `0x678` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x358` | `0x380` | **`+0x28`** |
| `__TEXT.__cstring` | `0x4b7` | `0x4d7` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x44c` | `0x464` | **`+0x18`** |
| `__DATA.__bss` | `0x148` | `0x158` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x170` | `0x180` | **`+0x10`** |
| `__DATA_CONST.__objc_catlist` | `0x10` | `0x18` | **`+0x8`** |

### Other Changes

```diff

-21.100.0.0.0
+22.2.2.0.0

+  - /System/Library/PrivateFrameworks/InstallCoordination.framework/InstallCoordination

-  Functions: 406
-  Symbols:   429
-  CStrings:  44
+  Functions: 421
+  Symbols:   443
+  CStrings:  49
Symbols:
+ -[RBSProcessIdentity(ALRApplicationIdentity) alr_applicationIdentity]
+ _ALRPreflightLog
+ _ALRPreflightLog.log
+ _ALRPreflightLog.onceToken
+ _OBJC_CLASS_$_IXAppInstallCoordinator
+ _OBJC_CLASS_$_IXApplicationIdentity
+ _OUTLINED_FUNCTION_0
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_RBSProcessIdentity_$_ALRApplicationIdentity
+ __OBJC_$_CATEGORY_RBSProcessIdentity_$_ALRApplicationIdentity
+ ___ALRPreflightLog_block_invoke
+ __os_log_error_impl
+ __swift_stdlib_bridgeErrorToNSError
+ _objc_opt_respondsToSelector
+ _os_log_create
CStrings:
+ "Encountered error for preflight check. Returning false: %@"
+ "No bundleId found for RBSProcessIdentity: %{public}@"
+ "RBSProcessIdentity returned error when fetching LSApplicationIdentity: %{public}@"
+ "Unable to resolve IXApplicationIdentity for %@"
+ "com.apple.CoreServicesUIAgent"
+ "preflight"
- "No bundleId found for rbsIdentity: %@"
```
