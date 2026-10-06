## IntlPreferences

> `/System/Library/PrivateFrameworks/IntlPreferences.framework/IntlPreferences`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b9c4` | `0x1c144` | **`+0x780`** |
| `__TEXT.__oslogstring` | `0xeca` | `0xfec` | **`+0x122`** |
| `__DATA_CONST.__const` | `0x678` | `0x6c8` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x11bc` | `0x1204` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x1098` | `0x10c8` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x5e8` | `0x618` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x220` | `0x234` | **`+0x14`** |
| `__AUTH_CONST.__objc_const` | `0x1638` | `0x1648` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x310` | `0x320` | **`+0x10`** |
| `__TEXT.__const` | `0x1f0` | `0x200` | **`+0x10`** |

### Other Changes

```diff

-496.0.0.0.0
+498.0.0.0.0

-  Functions: 465
-  Symbols:   982
-  CStrings:  335
+  Functions: 474
+  Symbols:   993
+  CStrings:  338
Symbols:
+ +[IntlUtility _migratePerAppLanguageSelectionOutOfGlobalDomain]
+ +[IntlUtility _perAppLanguageSelectionBundleIdentifiersFromPrivateDomain]
+ +[IntlUtility _updatePerAppLanguageSelectionInPrivateDomainForBundleID:selected:]
+ +[IntlUtility perAppLanguageSelectionBundleIdentifiersWithCompletion:]
+ GCC_except_table107
+ ___55+[IntlUtility perAppLanguageSelectionBundleIdentifiers]_block_invoke
+ ___70+[IntlUtility perAppLanguageSelectionBundleIdentifiersWithCompletion:]_block_invoke
+ ___NSArray0__struct
+ ___block_descriptor_40_e8_32r_e17_v16?0"NSArray"8lr32l8
+ ___block_descriptor_48_e8_32bs_e17_v16?0"NSError"8ls32l8
+ _kCFPreferencesCurrentApplication
CStrings:
+ "[%{public}@]: Error obtaining remote object proxy to update per-app-language selection, %{public}@"
+ "[%{public}@]: Migrated per-app-language index (%lu entries) from global domain into private domain"
+ "[%{public}@]: Private per-app-language index already present; discarding legacy global copy"
```
