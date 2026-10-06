## AppStoreDaemon

> `/System/Library/PrivateFrameworks/AppStoreDaemon.framework/AppStoreDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x2d0` | `0x1680` | **`+0x13b0`** |
| `__DATA_DIRTY.__objc_data` | `0x38e0` | `0x2580` | **`-0x1360`** |
| `__TEXT.__text` | `0x82f9c` | `0x838d4` | **`+0x938`** |
| `__AUTH_CONST.__objc_const` | `0x162d0` | `0x164a8` | **`+0x1d8`** |
| `__TEXT.__objc_methlist` | `0xb2e4` | `0xb3b4` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0x4d3c` | `0x4d86` | **`+0x4a`** |
| `__AUTH_CONST.__cfstring` | `0x6d20` | `0x6d60` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x2790` | `0x27c0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x5919` | `0x5948` | **`+0x2f`** |
| `__DATA_CONST.__const` | `0x26b0` | `0x26d8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x45a0` | `0x45c0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0xde4` | `0xdf8` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x618` | `0x628` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x5f8` | `0x600` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x4a0` | `0x4a8` | **`+0x8`** |

### Other Changes

```diff

-13.0.36.0.0
+13.0.40.0.0

-  Functions: 4463
-  Symbols:   7773
-  CStrings:  1419
+  Functions: 4482
+  Symbols:   7807
+  CStrings:  1422
Symbols:
+ +[ASDInstallApps beginSINFLessAppInstallsWithCompletionHandler:]
+ +[ASDSINFLessInstallResult supportsSecureCoding]
+ -[ASDAppLedgerQuery genreIDs]
+ -[ASDAppLedgerQuery setGenreIDs:]
+ -[ASDExtensionMonitor invalidate]
+ -[ASDSINFLessInstallResult .cxx_destruct]
+ -[ASDSINFLessInstallResult bundleID]
+ -[ASDSINFLessInstallResult description]
+ -[ASDSINFLessInstallResult encodeWithCoder:]
+ -[ASDSINFLessInstallResult error]
+ -[ASDSINFLessInstallResult initWithCoder:]
+ -[ASDSINFLessInstallResult initWithItemID:bundleID:installOrder:error:]
+ -[ASDSINFLessInstallResult installOrder]
+ -[ASDSINFLessInstallResult isSuccess]
+ -[ASDSINFLessInstallResult itemID]
+ _OBJC_CLASS_$_ASDSINFLessInstallResult
+ _OBJC_IVAR_$_ASDAppLedgerQuery._genreIDs
+ _OBJC_IVAR_$_ASDSINFLessInstallResult._bundleID
+ _OBJC_IVAR_$_ASDSINFLessInstallResult._error
+ _OBJC_IVAR_$_ASDSINFLessInstallResult._installOrder
+ _OBJC_IVAR_$_ASDSINFLessInstallResult._itemID
+ _OBJC_METACLASS_$_ASDSINFLessInstallResult
+ __OBJC_$_CLASS_METHODS_ASDSINFLessInstallResult
+ __OBJC_$_CLASS_PROP_LIST_ASDSINFLessInstallResult
+ __OBJC_$_INSTANCE_METHODS_ASDSINFLessInstallResult
+ __OBJC_$_INSTANCE_VARIABLES_ASDSINFLessInstallResult
+ __OBJC_$_PROP_LIST_ASDSINFLessInstallResult
+ __OBJC_CLASS_PROTOCOLS_$_ASDSINFLessInstallResult
+ __OBJC_CLASS_RO_$_ASDSINFLessInstallResult
+ __OBJC_METACLASS_RO_$_ASDSINFLessInstallResult
+ ___64+[ASDInstallApps beginSINFLessAppInstallsWithCompletionHandler:]_block_invoke
+ ___64+[ASDInstallApps beginSINFLessAppInstallsWithCompletionHandler:]_block_invoke_2
+ ___64+[ASDInstallApps beginSINFLessAppInstallsWithCompletionHandler:]_block_invoke_3
+ ___block_descriptor_40_e8_32bs_e74_v24?0"<ASDInstallationServiceProtocol><NSXPCProxyCreating>"8"NSError"16ls32l8
CStrings:
+ "SINF-less app installs failed to acquire installation service: %{public}@"
+ "[%ld] itemID=%lld bundleID=%@ %@"
+ "genreIDs = %@"
```
