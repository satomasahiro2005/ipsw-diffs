## IntlPreferences

> `/System/Library/PrivateFrameworks/IntlPreferences.framework/IntlPreferences`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c144` | `0x1d488` | **`+0x1344`** |
| `__TEXT.__oslogstring` | `0xfec` | `0x160c` | **`+0x620`** |
| `__AUTH.__objc_data` | `0xa0` | `—` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x690` | `0x730` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x12e5` | `0x1385` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x6c8` | `0x740` | **`+0x78`** |
| `__AUTH_CONST.__cfstring` | `0x1a80` | `0x1ae0` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x10c8` | `0x1108` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1204` | `0x122c` | **`+0x28`** |
| `__TEXT.__const` | `0x200` | `0x220` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x234` | `0x21c` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x618` | `0x630` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x320` | `0x330` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x610` | `0x618` | **`+0x8`** |
| `__AUTH_CONST.__objc_const` | `0x1648` | `0x1650` | **`+0x8`** |

### Other Changes

```diff

-498.0.0.0.0
+500.1.1.0.0

-  Functions: 474
-  Symbols:   993
-  CStrings:  338
+  Functions: 487
+  Symbols:   1006
+  CStrings:  356
Symbols:
+ +[IntlUtility _forwardPreferredLanguagesToWatchAppForCompanionBundleID:languages:context:completion:]
+ +[IntlUtility _migratePreferredLanguageFromBundleID:sourceContainerPath:toBundleID:destinationContainerPath:carriedLanguages:error:]
+ GCC_except_table100
+ GCC_except_table108
+ _NSLocalizedDescriptionKey
+ _OBJC_CLASS_$_NSError
+ _OUTLINED_FUNCTION_2
+ _OUTLINED_FUNCTION_3
+ __CFPreferencesSynchronizeWithContainer
+ ___101+[IntlUtility _forwardPreferredLanguagesToWatchAppForCompanionBundleID:languages:context:completion:]_block_invoke
+ ___101+[IntlUtility _forwardPreferredLanguagesToWatchAppForCompanionBundleID:languages:context:completion:]_block_invoke_2
+ ___block_descriptor_40_e8_32bs_e8_v12?0B8ls32l8
+ ___block_descriptor_72_e8_32s40s48s56bs_e5_v8?0ls56l8s32l8s40l8s48l8
+ ___block_descriptor_80_e8_32s40s48s56s64bs_e17_v16?0"NSError"8ls32l8s40l8s48l8s56l8s64l8
+ __appleLanguagesInContainer
- GCC_except_table107
- GCC_except_table99
CStrings:
+ "### [%{public}@]: Per-app language migration failed: could not synchronize AppleLanguages for %{private}@"
+ "### [%{public}@]: Watch language forward (%{public}@) failed: could not query install state for %{private}@: %{public}@ (domain %{public}@ code %ld)"
+ "### [%{public}@]: Watch language forward (%{public}@) failed: could not write preferences for %{private}@: %{public}@ (domain %{public}@ code %ld)"
+ "### [%{public}@]: Watch language forward (%{public}@) failed: no watch app bundle ID for %{private}@: %{public}@ (domain %{public}@ code %ld)"
+ "Empty bundle identifier or container path"
+ "Failed to synchronize AppleLanguages for the destination app"
+ "[%{public}@]: Per-app language migration complete: %{private}@ -> %{private}@, override language [%{public}@], %lu entries"
+ "[%{public}@]: Per-app language migration complete: [%{public}@] resolves to the default for %{private}@, so nothing was recorded"
+ "[%{public}@]: Per-app language migration complete: source %{private}@ had no override to carry over"
+ "[%{public}@]: Per-app language migration rejected: empty bundle identifier or container path"
+ "[%{public}@]: Per-app language migration skipped: source and destination are the same app"
+ "[%{public}@]: Watch language forward (%{public}@) complete: %{private}@ -> %{private}@, %lu entries"
+ "[%{public}@]: Watch language forward (%{public}@) deferred: no watch app installed for %{private}@"
+ "[%{public}@]: Watch language forward (%{public}@) skipped: no AppConduit connection"
+ "[%{public}@]: Watch language forward (%{public}@) skipped: no active paired watch"
+ "[IntlUtility]: Per-app language migration could not read the destination bundle for %{private}@; carrying the override over"
+ "com.apple.IntlPreferences.PerAppLanguageMigration"
+ "v12@?0B8"
```
