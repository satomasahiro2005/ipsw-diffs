## BulletinBoard

> `/System/Library/PrivateFrameworks/BulletinBoard.framework/BulletinBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x74748` | `0x748c0` | **`+0x178`** |
| `__TEXT.__oslogstring` | `0x5df6` | `0x5eea` | **`+0xf4`** |
| `__AUTH_CONST.__cfstring` | `0x6920` | `0x6960` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x10778` | `0x107a8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x6284` | `0x62a4` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x85ec` | `0x860c` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3fa8` | `0x3fb8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2070` | `0x2078` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x8c0` | `0x8c4` | **`+0x4`** |

### Other Changes

```diff

-950.0.0.0.0
+952.0.0.0.0

-  Functions: 3352
-  Symbols:   5159
-  CStrings:  1373
+  Functions: 3355
+  Symbols:   5162
+  CStrings:  1378
Symbols:
+ +[BBPersistentStoreMigrator migrateSectionInfoForStore:appProtectionMonitor:]
+ +[BBSectionInfo effectiveContentPreviewSettingForRawSetting:globalSetting:isLocked:]
+ -[BBSectionInfo isLocked]
+ -[BBSectionInfo setIsLocked:]
+ _OBJC_IVAR_$_BBSectionInfo._isLocked
+ ___77+[BBPersistentStoreMigrator migrateSectionInfoForStore:appProtectionMonitor:]_block_invoke
- +[BBPersistentStoreMigrator migrateSectionInfoForStore:]
- GCC_except_table11
- ___56+[BBPersistentStoreMigrator migrateSectionInfoForStore:]_block_invoke
CStrings:
+ "Protection state changed for %{public}@ but no section info exists; skipping"
+ "Protection state changed for %{public}@: isLocked=%d contentPreviewSetting=%ld"
+ "Resetting content preview setting from ShowNever to Default for locked app \"%{public}@\""
+ "isLocked"
+ "protectionStateChanged"
```
