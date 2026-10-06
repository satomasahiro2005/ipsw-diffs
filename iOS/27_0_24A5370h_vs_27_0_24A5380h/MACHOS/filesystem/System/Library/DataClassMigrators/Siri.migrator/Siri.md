## Siri

> `/System/Library/DataClassMigrators/Siri.migrator/Siri`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2edc` | `0x3aec` | **`+0xc10`** |
| `__TEXT.__oslogstring` | `0x5de` | `0x928` | **`+0x34a`** |
| `__TEXT.__objc_stubs` | `0x8e0` | `0xaa0` | **`+0x1c0`** |
| `__TEXT.__objc_methname` | `0x72f` | `0x8e2` | **`+0x1b3`** |
| `__TEXT.__cstring` | `0x717` | `0x855` | **`+0x13e`** |
| `__DATA_CONST.__cfstring` | `0x520` | `0x620` | **`+0x100`** |
| `__TEXT.__auth_stubs` | `0x360` | `0x450` | **`+0xf0`** |
| `__DATA_CONST.__auth_got` | `0x1b8` | `0x230` | **`+0x78`** |
| `__DATA.__objc_selrefs` | `0x260` | `0x2d0` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x140` | `0x19c` | **`+0x5c`** |
| `__DATA_CONST.__got` | `0xf0` | `0x130` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x20` | `0x39` | **`+0x19`** |
| `__TEXT.__const` | `0x1c` | `0x2c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xb8` | `0xc8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`

### Other Changes

```diff

-3600.68.16.1.1
+3600.68.39.1.1

+  - /System/Library/PrivateFrameworks/TCC.framework/TCC

-  Functions: 29
-  Symbols:   96
-  CStrings:  176
+  Functions: 36
+  Symbols:   119
+  CStrings:  215
Symbols:
+ _NSStringFromClass
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_NSMutableArray
+ _OBJC_CLASS_$_NSMutableSet
+ _OBJC_CLASS_$_NSSet
+ _OBJC_CLASS_$_NSString
+ _TCCAccessSetForBundleIdWithOptions
+ ___NSArray0__struct
+ ___stack_chk_fail
+ ___stack_chk_guard
+ __os_feature_enabled_impl
+ _kTCCServiceSiri
+ _objc_enumerationMutation
+ _objc_opt_class
+ _objc_opt_isKindOfClass
+ _objc_release_x25
+ _objc_release_x27
+ _objc_release_x8
+ _objc_retain_x2
+ _objc_retain_x21
+ _objc_retain_x22
+ _objc_retain_x23
+ _objc_retain_x27
CStrings:
+ "%s %@ has unexpected type %@; ignoring."
+ "%s %@ read returned nil — pref absent, sandboxed, or unentitled."
+ "%s %@: read %lu raw entries, %lu valid string bundle IDs."
+ "%s %lu TCC write(s) failed; NOT marking migration complete — will retry on next migration."
+ "%s Failed to set TCC denial for bundle %@. [sources: LFTA=%@, ShowContent=%@, ShowApp=%@]"
+ "%s Marked %@ as denied in kTCCServiceSiri. [sources: LFTA=%@, ShowContent=%@, ShowApp=%@]"
+ "%s Marking one-time App Access exclusion list migration as complete."
+ "%s One-time App Access exclusion list migration has already been performed. Skipping."
+ "%s SiriSetup/restrict_access_ui FF is not enabled. Skipping (will retry on future migration)."
+ "%s Source counts — LFTA-off: %lu, Show-Content-off: %lu, Show-App-off: %lu, union to migrate: %lu."
+ "%s TCC write summary — succeeded: %lu, failed: %lu."
+ "+[SiriMigrator _parseBundleIdsFromPreferenceValue:forKey:]"
+ "-[SiriMigrator _performAppAccessExclusionListMigrationIfNeeded]"
+ "@32@0:8@16@24"
+ "AppAccessExclusionListMigrationPerformed"
+ "B24@0:8Q16"
+ "NO"
+ "SBSearchDisabledApps"
+ "SBSearchDisabledBundles"
+ "SiriCanLearnFromAppBlacklist"
+ "SiriSetup"
+ "YES"
+ "_bundleIdsWithLearnFromAppDisabled"
+ "_bundleIdsWithShowAppInSearchDisabled"
+ "_bundleIdsWithShowContentInSearchDisabled"
+ "_markAppAccessExclusionListMigrationPerformed"
+ "_parseBundleIdsFromPreferenceValue:forKey:"
+ "_performAppAccessExclusionListMigrationIfNeeded"
+ "_shouldMarkAppAccessExclusionListMigrationCompleteWithFailureCount:"
+ "addObject:"
+ "arrayWithCapacity:"
+ "com.apple.spotlightui"
+ "com.apple.suggestions"
+ "count"
+ "countByEnumeratingWithState:objects:count:"
+ "restrict_access_ui"
+ "setWithArray:"
+ "setWithSet:"
+ "unionSet:"
```
