## MobileAsset

> `/System/Library/PrivateFrameworks/MobileAsset.framework/MobileAsset`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8e848` | `0x8e950` | **`+0x108`** |
| `__AUTH_CONST.__objc_const` | `0xac90` | `0xacc0` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x10180` | `0x101a0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x13f25` | `0x13f45` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x6f6c` | `0x6f84` | **`+0x18`** |
| `__DATA.__bss` | `0x1f8` | `0x1e8` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x38c8` | `0x38d8` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x1e8` | `0x1f8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x92c` | `0x930` | **`+0x4`** |

### Other Changes

```diff

-2215.40.18.0.0
+2215.40.19.0.0

-  Functions: 3117
-  Symbols:   5120
-  CStrings:  2861
+  Functions: 3119
+  Symbols:   5123
+  CStrings:  2862
Symbols:
+ -[MAAutoAssetMigrationResults migrationBuild]
+ -[MAAutoAssetMigrationResults setMigrationBuild:]
+ _OBJC_IVAR_$_MAAutoAssetMigrationResults._migrationBuild
CStrings:
+ "[MigrationResults>>>\nSuccessully migrated assets:\n%@\nFailed migrated assets:\n%@\nSetupError:\n%@\nMigrationDate:\n%@\nMigrationBuild:\n%@\n<<<]"
+ "migrationBuild"
- "[MigrationResults>>>\nSuccessully migrated assets:\n%@\nFailed migrated assets:\n%@\nSetupError:\n%@\nMigrationDate:\n%@\n<<<]"
```
