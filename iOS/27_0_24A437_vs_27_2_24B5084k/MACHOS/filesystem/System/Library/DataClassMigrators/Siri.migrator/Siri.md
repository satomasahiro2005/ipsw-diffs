## Siri

> `/System/Library/DataClassMigrators/Siri.migrator/Siri`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f80` | `0x415c` | **`+0x1dc`** |
| `__TEXT.__oslogstring` | `0xa79` | `0xc42` | **`+0x1c9`** |
| `__TEXT.__objc_stubs` | `0xbc0` | `0xb20` | **`-0xa0`** |
| `__TEXT.__objc_methname` | `0x9d3` | `0x965` | **`-0x6e`** |
| `__DATA_CONST.__cfstring` | `0x680` | `0x6e0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x90c` | `0x968` | **`+0x5c`** |
| `__TEXT.__auth_stubs` | `0x470` | `0x4a0` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x318` | `0x2f0` | **`-0x28`** |
| `__DATA_CONST.__auth_got` | `0x240` | `0x258` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1d0` | `0x1c4` | **`-0xc`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.68.61.11.11
+3605.23.1.1.1

-  Functions: 40
-  Symbols:   121
-  CStrings:  234
+  Functions: 39
+  Symbols:   124
+  CStrings:  238
Symbols:
+ _AFIsHomePod
+ _AFIsLinwoodEnabled
+ _TCCAccessReset
+ _objc_release_x26
+ _objc_release_x27
+ _objc_retain_x27
- _AFIsHorseman
- _objc_release_x25
- _objc_retain_x25
CStrings:
+ "%s App Clips: \"Learn from App Clips\" is OFF — adding com.apple.app-clips to deny set."
+ "%s App Clips: \"Learn from App Clips\" is ON (or unset/default) — not adding from this signal."
+ "%s Failed to reset kTCCServiceSiriAccess entries. Proceeding with migration anyway (writes are idempotent)."
+ "%s Failed to set TCC denial for bundle %@. [sources: LFTA=%@, ShowContent=%@, ShowApp=%@]"
+ "%s Marked %@ as denied in kTCCServiceSiriAccess. [sources: LFTA=%@, ShowContent=%@, ShowApp=%@]"
+ "%s Pre-migration reset check: hasV1Flag=%{BOOL}d, isLinwoodEnabled=%{BOOL}d"
+ "%s Resetting all kTCCServiceSiriAccess entries."
+ "%s Source counts — LFTA-off: %lu, Show-Content-off: %lu, Show-App-off: %lu, Locked (excluded): %lu, AppClips-Learn-off: %@, union to migrate: %lu."
+ "%s Successfully reset kTCCServiceSiriAccess entries."
+ "AppAccessExclusionListMigrationPerformedV2"
+ "SuggestionsLearnFromAppClips"
+ "com.apple.app-clips"
+ "isEnabledForDataclass:"
- "%s Failed to set TCC denial for bundle %@. [sources: LFTA=%@, ShowContent=%@, ShowApp=%@, Locked=%@]"
- "%s Marked %@ as denied in kTCCServiceSiriAccess. [sources: LFTA=%@, ShowContent=%@, ShowApp=%@, Locked=%@]"
- "%s Source counts — LFTA-off: %lu, Show-Content-off: %lu, Show-App-off: %lu, Locked: %lu, Hidden (excluded): %lu, union to migrate: %lu."
- "_bundleIdsWithHiddenApps"
- "cloudSyncEnabled"
- "hiddenAppBundleIdentifiers"
- "saveAccount:withCompletionHandler:"
- "set"
- "setEnabled:forDataclass:"
```
