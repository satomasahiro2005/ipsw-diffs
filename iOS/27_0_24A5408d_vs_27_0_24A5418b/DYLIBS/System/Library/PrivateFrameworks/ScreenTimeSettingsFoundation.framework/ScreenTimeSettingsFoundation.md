## ScreenTimeSettingsFoundation

> `/System/Library/PrivateFrameworks/ScreenTimeSettingsFoundation.framework/ScreenTimeSettingsFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1db060` | `0x1dfcf4` | **`+0x4c94`** |
| `__TEXT.__eh_frame` | `0x8a50` | `0x8f08` | **`+0x4b8`** |
| `__TEXT.__oslogstring` | `0xa312` | `0xa672` | **`+0x360`** |
| `__TEXT.__unwind_info` | `0x3258` | `0x3380` | **`+0x128`** |
| `__TEXT.__const` | `0x7600` | `0x7700` | **`+0x100`** |
| `__AUTH_CONST.__const` | `0x7918` | `0x79c0` | **`+0xa8`** |
| `__AUTH_CONST.__auth_got` | `0x3118` | `0x3158` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x2338` | `0x2378` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x2214` | `0x2248` | **`+0x34`** |
| `__TEXT.__swift5_capture` | `0x13f4` | `0x1418` | **`+0x24`** |
| `__AUTH_CONST.__objc_const` | `0x28b0` | `0x28d0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x2933` | `0x2953` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x39cc` | `0x39e8` | **`+0x1c`** |
| `__TEXT.__swift_as_cont` | `0x46c` | `0x484` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x4dda` | `0x4df0` | **`+0x16`** |
| `__DATA_CONST.__objc_selrefs` | `0xf10` | `0xf18` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x208` | `0x210` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x240` | `0x244` | **`+0x4`** |

### Other Changes

```diff

-97.0.100.2.0
+97.0.103.0.0

-  Functions: 4040
-  Symbols:   1818
-  CStrings:  855
+  Functions: 4089
+  Symbols:   1821
+  CStrings:  865
Symbols:
+ ___swift_closure_destructor.128Tm
+ ___swift_closure_destructor.187Tm
+ ___swift_closure_destructor.195Tm
+ ___swift_closure_destructor.221Tm
+ ___swift_memcpy32_8
+ _symbolic _____ 28ScreenTimeSettingsFoundation22SuppressedApplicationsV
+ _symbolic _____ySS_____G s18_DictionaryStorageC 26ScreenTimeSettingsServices0cdE0C11ApplicationV
+ _type_layout_string 28ScreenTimeSettingsFoundation22SuppressedApplicationsV
- ___swift_closure_destructor.125Tm
- ___swift_closure_destructor.185Tm
- ___swift_closure_destructor.188Tm
- ___swift_closure_destructor.222Tm
- _swift_getFunctionTypeMetadata0
CStrings:
+ "Current user is locally migrated and (managed or share-across-devices disabled); not posting userNeedsMigration"
+ "Failed to fetch share across devices policy: %{public}@"
+ "Failed to record self as already migrated: %{public}s"
+ "Hiding suppressed installed app from client: %{public}s"
+ "LocalDevice: overriding isChinaSKU to %{bool,public}d due to the %{public}s internal user default."
+ "Merging alreadyMigratedAltDSIDs from %{public}ld deduplicated FamilyMigrationStateRecords: existing=%{private}s, merged=%{private}s"
+ "Not applying family migration state because the user is not signed in"
+ "RecordSelfAsAlreadyMigrated"
+ "RegulatoryPolicyProvider: no cached override policy for %{public}s; returning fallback while refreshing"
+ "RegulatoryPolicyProvider: no cached presentation policy for %{public}s; returning fallback while refreshing"
```
