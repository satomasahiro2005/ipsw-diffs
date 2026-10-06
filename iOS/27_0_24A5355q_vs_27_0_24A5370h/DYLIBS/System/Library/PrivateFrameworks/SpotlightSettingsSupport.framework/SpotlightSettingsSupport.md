## SpotlightSettingsSupport

> `/System/Library/PrivateFrameworks/SpotlightSettingsSupport.framework/SpotlightSettingsSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4984` | `0x4974` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x1e0` | `0x1e8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3e8` | `0x3f0` | **`+0x8`** |

### Other Changes

```diff

-228.102.0.0.0
+235.3.100.0.0

+  - /System/Library/PrivateFrameworks/GenerativeModels.framework/GenerativeModels
Symbols:
+ _OBJC_CLASS_$_GMAvailabilityWrapper
- _AFIsLinwoodEnabledAndAvailable
Functions:
~ ___71-[SpotlightDetailController setWhileSearchingShowAppEnabled:specifier:]_block_invoke_3 : 36 -> 32
~ ___75-[SpotlightDetailController setWhileSearchingShowContentEnabled:specifier:]_block_invoke_3 : 36 -> 32
~ -[SpotlightSettingsController configureSafariSearchEngine:] : 1192 -> 1188
~ -[SpotlightSettingsController configureApplicationListSpecifiersFor:] : 1900 -> 1892
~ +[SpotlightSettingsUtilities updateSearchPreferencesModificationForKeys:] : 580 -> 576
~ +[SpotlightSettingsUtilities linwoodEnabled] : 4 -> 12
```
