## MapsSettings

> `/System/Library/PreferenceBundles/MapsSettings.bundle/MapsSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7bd64` | `0x7c6bc` | **`+0x958`** |
| `__DATA_CONST.__const` | `0x1c430` | `0x1c680` | **`+0x250`** |
| `__TEXT.__swift5_typeref` | `0x5219` | `0x5349` | **`+0x130`** |
| `__TEXT.__cstring` | `0xe3c0` | `0xe4b0` | **`+0xf0`** |
| `__DATA_CONST.__cfstring` | `0x92a0` | `0x9340` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0x72a0` | `0x7320` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0xb085` | `0xb0f5` | **`+0x70`** |
| `__DATA.__data` | `0x35e0` | `0x3640` | **`+0x60`** |
| `__TEXT.__const` | `0x43b0` | `0x4410` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x21b0` | `0x2200` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x32ec` | `0x332c` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x2ad0` | `0x2af8` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x10e8` | `0x1110` | **`+0x28`** |
| `__DATA.__bss` | `0x2fa0` | `0x2fc0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1e10` | `0x1e30` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x748` | `0x760` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x1495` | `0x14a5` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xae8` | `0xaf0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2972.31.6.17.20
+2972.31.6.17.31

-  Functions: 4094
-  Symbols:   1861
-  CStrings:  3711
+  Functions: 4113
+  Symbols:   1867
+  CStrings:  3722
Symbols:
+ _MapsConfig_CustomPOIControllerSkipsHashCheck
+ _MapsConfig_DeferAuxiliaryTasksUntilForegrounded
+ _MapsConfig_ParkedCarDonationSeedRetryInterval
+ _MapsConfig_SearchHomeEnrichmentRequestGenerationBudget
+ _MapsConfig_SearchResultsEnrichmentRequestGenerationBudget
+ _dispatch_sync
CStrings:
+ "CustomPOIControllerSkipsHashCheck"
+ "DeferAuxiliaryTasksUntilForegrounded"
+ "ParkedCarDonationSeedRetryInterval"
+ "Saved %{public}@ %@ to %{public}@"
+ "SearchHomeEnrichmentRequestGenerationBudget"
+ "SearchResultsEnrichmentRequestGenerationBudget"
+ "_synchronizeWaitingForWrite:"
+ "_writeValues:forKeys:toDefaults:"
+ "com.apple.Maps.WatchSyncedPreferencesQueue"
+ "initWithCapacity:"
+ "syncedPreferencesQueue"
+ "synchronizeInBackground"
- "Saving %@ to %{public}@"
```
