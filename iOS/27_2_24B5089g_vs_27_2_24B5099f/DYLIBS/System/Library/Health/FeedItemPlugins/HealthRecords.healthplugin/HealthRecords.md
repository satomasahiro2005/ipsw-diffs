## HealthRecords

> `/System/Library/Health/FeedItemPlugins/HealthRecords.healthplugin/HealthRecords`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1778b0` | `0x17ad34` | **`+0x3484`** |
| `__TEXT.__cstring` | `0x32e3` | `0x3463` | **`+0x180`** |
| `__TEXT.__constg_swiftt` | `0x3f0c` | `0x3fcc` | **`+0xc0`** |
| `__AUTH_CONST.__auth_got` | `0x3338` | `0x33e0` | **`+0xa8`** |
| `__TEXT.__oslogstring` | `0x3fb9` | `0x404a` | **`+0x91`** |
| `__AUTH.__objc_data` | `0x1488` | `0x1518` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x4440` | `0x44d0` | **`+0x90`** |
| `__TEXT.__const` | `0xbf18` | `0xbfa8` | **`+0x90`** |
| `__AUTH.__data` | `0x1c38` | `0x1cb8` | **`+0x80`** |
| `__DATA.__data` | `0x2470` | `0x24c0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x4da8` | `0x4df0` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x5ac8` | `0x5af8` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x30ac` | `0x30d8` | **`+0x2c`** |
| `__DATA_CONST.__got` | `0x17d8` | `0x1800` | **`+0x28`** |
| `__DATA.__common` | `0x170` | `0x190` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0xc64` | `0xc80` | **`+0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x10b8` | `0x10c8` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x7f84` | `0x7f94` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x2814` | `0x2824` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x270a` | `0x2714` | **`+0xa`** |
| `__TEXT.__swift5_types` | `0x3b8` | `0x3c0` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x5e4` | `0x5e0` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x2a4` | `0x2a0` | **`-0x4`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 6198
+  Functions: 6218

-  CStrings:  571
+  CStrings:  582
CStrings:
+ "CategoryDataFetcher:fetchCategoryCounts"
+ "ConceptAuthorizationMigrationHelper:fetchResolvedConcept"
+ "EscalationDetailsView"
+ "HealthRecords.healthplugin"
+ "HealthRecordsPluginAppDelegate+URLHandling:_showMedicalRecord"
+ "LabsOnboardingExecutor:fetchAllLabConcepts"
+ "MHRChangeInputSignal:beginObservation"
+ "SHOW_ALL_RECORDS"
+ "[%s] Could not create a contributing datum room for %s"
+ "[%s] Not in a tab hierarchy; cannot steer selection off the emptied group"
+ "healthRecords.homaIRDetail"
```
