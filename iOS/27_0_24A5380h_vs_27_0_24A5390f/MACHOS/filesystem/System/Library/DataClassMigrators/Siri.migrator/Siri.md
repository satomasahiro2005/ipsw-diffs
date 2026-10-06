## Siri

> `/System/Library/DataClassMigrators/Siri.migrator/Siri`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3aec` | `0x3c1c` | **`+0x130`** |
| `__TEXT.__objc_stubs` | `0xaa0` | `0xb60` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x8e2` | `0x940` | **`+0x5e`** |
| `__TEXT.__oslogstring` | `0x928` | `0x966` | **`+0x3e`** |
| `__DATA.__objc_selrefs` | `0x2d0` | `0x300` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x620` | `0x600` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x450` | `0x460` | **`+0x10`** |
| `__TEXT.__cstring` | `0x855` | `0x861` | **`+0xc`** |
| `__TEXT.__objc_methlist` | `0x19c` | `0x1a8` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x230` | `0x238` | **`+0x8`** |
| `__TEXT.__const` | `0x2c` | `0x34` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xc8` | `0xd0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`

### Other Changes

```diff

-3600.68.39.1.1
+3600.68.45.0.0

+  - /System/Library/PrivateFrameworks/AppProtection.framework/AppProtection

-  Functions: 36
-  Symbols:   119
-  CStrings:  215
+  Functions: 37
+  Symbols:   120
+  CStrings:  222
Symbols:
+ _OBJC_CLASS_$_APApplication
+ _objc_release_x26
+ _objc_retainAutoreleaseReturnValue
- _kTCCServiceSiri
- _objc_retain_x27
CStrings:
+ "%s AppProtection: locked=%lu."
+ "%s Failed to set TCC denial for bundle %@. [sources: ShowContent=%@, ShowApp=%@, Locked=%@]"
+ "%s Marked %@ as denied in kTCCServiceSiriAccess. [sources: ShowContent=%@, ShowApp=%@, Locked=%@]"
+ "%s Source counts — Show-Content-off: %lu, Show-App-off: %lu, Locked: %lu, Hidden (excluded): %lu, union to migrate: %lu."
+ "-[SiriMigrator _bundleIdsWithLockedApps]"
+ "_bundleIdsWithHiddenApps"
+ "_bundleIdsWithLockedApps"
+ "allObjects"
+ "hiddenAppBundleIdentifiers"
+ "kTCCServiceSiriAccess"
+ "lockedAppBundleIdentifiers"
+ "minusSet:"
+ "set"
- "%s Failed to set TCC denial for bundle %@. [sources: LFTA=%@, ShowContent=%@, ShowApp=%@]"
- "%s Marked %@ as denied in kTCCServiceSiri. [sources: LFTA=%@, ShowContent=%@, ShowApp=%@]"
- "%s Source counts — LFTA-off: %lu, Show-Content-off: %lu, Show-App-off: %lu, union to migrate: %lu."
- "SiriCanLearnFromAppBlacklist"
- "_bundleIdsWithLearnFromAppDisabled"
- "com.apple.suggestions"
```
