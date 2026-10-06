## DoNotDisturb

> `/System/Library/PrivateFrameworks/DoNotDisturb.framework/DoNotDisturb`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43a98` | `0x43e84` | **`+0x3ec`** |
| `__TEXT.__oslogstring` | `0x546a` | `0x5541` | **`+0xd7`** |
| `__TEXT.__unwind_info` | `0x15c0` | `0x15f0` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0xe6c` | `0xe88` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x46ac` | `0x46c4` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1a20` | `0x1a30` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0xccd8` | `0xcce0` | **`+0x8`** |

### Other Changes

```diff

-511.0.0.0.0
+511.2.3.0.0

-  Functions: 1682
-  Symbols:   3075
-  CStrings:  835
+  Functions: 1686
+  Symbols:   3081
+  CStrings:  838
Symbols:
+ -[DNDModeConfigurationService migrateAppSettingsFromBundleIdentifier:toBundleIdentifier:error:]
+ -[DNDRemoteServiceConnection migrateAppSettingsFromBundleIdentifier:toBundleIdentifier:withRequestDetails:completionHandler:]
+ GCC_except_table12
+ GCC_except_table121
+ GCC_except_table123
+ GCC_except_table126
+ GCC_except_table133
+ GCC_except_table38
+ GCC_except_table43
+ GCC_except_table60
+ GCC_except_table67
+ GCC_except_table70
+ GCC_except_table73
+ GCC_except_table85
+ GCC_except_table90
+ GCC_except_table98
+ ___95-[DNDModeConfigurationService migrateAppSettingsFromBundleIdentifier:toBundleIdentifier:error:]_block_invoke
- GCC_except_table120
- GCC_except_table122
- GCC_except_table124
- GCC_except_table132
- GCC_except_table39
- GCC_except_table57
- GCC_except_table68
- GCC_except_table71
- GCC_except_table78
- GCC_except_table81
- GCC_except_table91
CStrings:
+ "[%{public}@] Error when migrating app settings, error='%{public}@'"
+ "[%{public}@] Migrated app settings, source=%{public}@, destination=%{public}@"
+ "com.apple.donotdisturb.DNDModeConfigurationService.migrateAppSettings"
```
