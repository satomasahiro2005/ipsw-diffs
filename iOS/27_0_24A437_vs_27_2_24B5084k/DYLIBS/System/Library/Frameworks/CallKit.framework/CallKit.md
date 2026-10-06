## CallKit

> `/System/Library/Frameworks/CallKit.framework/CallKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x678a8` | `0x68358` | **`+0xab0`** |
| `__TEXT.__oslogstring` | `0x3c25` | `0x3cf6` | **`+0xd1`** |
| `__TEXT.__objc_methlist` | `0x92a4` | `0x9324` | **`+0x80`** |
| `__TEXT.__cstring` | `0x63ab` | `0x641a` | **`+0x6f`** |
| `__AUTH_CONST.__objc_const` | `0xf0e8` | `0xf138` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x34e8` | `0x3530` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x4360` | `0x43a0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0xdb8` | `0xde0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1de8` | `0x1e10` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x94c` | `0x950` | **`+0x4`** |

### Other Changes

```diff

-1403.100.1.0.0
+1406.200.51.2.1

-  Functions: 3244
-  Symbols:   5453
-  CStrings:  1006
+  Functions: 3259
+  Symbols:   5469
+  CStrings:  1013
Symbols:
+ -[CXCallDirectoryHost migrateAllDataFromExtensionWithBundleID:toExtensionWithBundleID:withReply:]
+ -[CXCallDirectoryHost synchronizeExtensionsIfPlistValidationChangesWithReply:]
+ -[CXCallDirectoryManager migrateAllDataFromExtensionWithBundleID:toExtensionWithBundleID:withCompletionHandler:]
+ -[CXCallDirectoryManager synchronizeExtensionsIfPlistValidationChangesWithCompletionHandler:]
+ -[CXCallDirectoryStore featureFlags]
+ -[CXCallDirectoryStore initReadOnly:temporary:featureFlags:error:]
+ -[CXCallDirectoryStore initWithTemplateURL:readOnly:temporary:featureFlags:error:]
+ -[CXCallDirectoryStore migrateAllDataFromExtensionWithBundleID:toExtensionWithBundleID:error:]
+ -[CXFeatures isCallDirectoryApplicationMigrationEnabled]
+ GCC_except_table13
+ GCC_except_table18
+ GCC_except_table46
+ GCC_except_table51
+ GCC_except_table53
+ GCC_except_table55
+ GCC_except_table57
+ GCC_except_table77
+ GCC_except_table79
+ GCC_except_table85
+ _OBJC_IVAR_$_CXCallDirectoryStore._featureFlags
+ ___112-[CXCallDirectoryManager migrateAllDataFromExtensionWithBundleID:toExtensionWithBundleID:withCompletionHandler:]_block_invoke
+ ___112-[CXCallDirectoryManager migrateAllDataFromExtensionWithBundleID:toExtensionWithBundleID:withCompletionHandler:]_block_invoke_2
+ ___78-[CXCallDirectoryHost synchronizeExtensionsIfPlistValidationChangesWithReply:]_block_invoke
+ ___93-[CXCallDirectoryManager synchronizeExtensionsIfPlistValidationChangesWithCompletionHandler:]_block_invoke
+ ___93-[CXCallDirectoryManager synchronizeExtensionsIfPlistValidationChangesWithCompletionHandler:]_block_invoke_2
+ ___97-[CXCallDirectoryHost migrateAllDataFromExtensionWithBundleID:toExtensionWithBundleID:withReply:]_block_invoke
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s56l8s40l8s48l8
- -[CXCallDirectoryStore initWithTemplateURL:readOnly:temporary:error:]
- GCC_except_table12
- GCC_except_table15
- GCC_except_table17
- GCC_except_table43
- GCC_except_table47
- GCC_except_table52
- GCC_except_table56
- GCC_except_table76
- GCC_except_table78
- GCC_except_table84
CStrings:
+ "CallDirectoryApplicationMigration"
+ "UPDATE Extension SET bundle_id = ? WHERE bundle_id = ?"
+ "[WARN] Application migration is disabled by feature flag"
+ "application-migration"
+ "compactStoreWithReply"
+ "migrateAllDataFromExtensionWithBundleID:toExtensionWithBundleID:withReply:"
+ "synchronizeExtensionsIfPlistValidationChangesWithReply"
```
