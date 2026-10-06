## BulletinDistributorCompanion

> `/System/Library/PrivateFrameworks/BulletinDistributorCompanion.framework/BulletinDistributorCompanion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x1540` | `0xaa0` | **`-0xaa0`** |
| `__DATA_DIRTY.__objc_data` | `0x1b78` | `0x2618` | **`+0xaa0`** |
| `__TEXT.__text` | `0x8cee4` | `0x8d2dc` | **`+0x3f8`** |
| `__TEXT.__oslogstring` | `0x6525` | `0x6865` | **`+0x340`** |
| `__DATA.__bss` | `0x340` | `0x2e0` | **`-0x60`** |
| `__DATA_DIRTY.__bss` | `0x1c0` | `0x220` | **`+0x60`** |
| `__DATA_CONST.__got` | `0xa08` | `0xa18` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x4770` | `0x4778` | **`+0x8`** |

### Other Changes

```diff

-382.0.13.0.0
+382.0.14.0.0

-  Functions: 3887
-  Symbols:   6503
-  CStrings:  1183
+  Functions: 3892
+  Symbols:   6505
+  CStrings:  1191
Symbols:
+ _NSURLFileProtectionKey
+ _NSURLFileProtectionNone
CStrings:
+ "BLTSectionInfoListAccessorySettingsProvider: failed to re-apply Class D protection to persisted state: %{public}@"
+ "BLTSectionInfoListAccessorySettingsProvider: failed to remove corrupt state file: %{public}@"
+ "BLTSectionInfoListAccessorySettingsProvider: failed to remove invalid state file: %{public}@"
+ "BLTSectionInfoListAccessorySettingsProvider: failed to remove outdated state file: %{public}@"
+ "BLTSectionInfoListAccessorySettingsProvider: persisted state already Class D, nothing to migrate"
+ "BLTSectionInfoListAccessorySettingsProvider: persisted state protection is %{public}@, re-applying Class D"
+ "BLTSectionInfoListAccessorySettingsProvider: re-applied Class D protection to persisted state at %{public}@"
+ "BLTSectionInfoListAccessorySettingsProvider: unable to read protection class of persisted state (%{public}@), re-applying Class D"
```
