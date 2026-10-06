## PodcastsAppEntities

> `/private/var/staged_system_apps/Podcasts.app/Frameworks/PodcastsAppEntities.framework/PodcastsAppEntities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6143c` | `0x61928` | **`+0x4ec`** |
| `__TEXT.__eh_frame` | `0x3e6c` | `0x400c` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x644` | `0x76c` | **`+0x128`** |
| `__TEXT.__swift5_reflstr` | `0xd16` | `0xdd6` | **`+0xc0`** |
| `__TEXT.__const` | `0x6158` | `0x61f8` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x2158` | `0x21f0` | **`+0x98`** |
| `__TEXT.__cstring` | `0x79d` | `0x81d` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x1fe0` | `0x2050` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x1ef8` | `0x1f60` | **`+0x68`** |
| `__TEXT.__swift5_fieldmd` | `0xa2c` | `0xa6c` | **`+0x40`** |
| `__DATA.__data` | `0x1fb0` | `0x1fe8` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0xff8` | `0x1030` | **`+0x38`** |
| `__TEXT.__objc_methname` | `0x74a` | `0x77a` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x760` | `0x780` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x830` | `0x84c` | **`+0x1c`** |
| `__DATA_CONST.__auth_ptr` | `0x970` | `0x980` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x1fc4` | `0x1fd4` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x298` | `0x2a8` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x2e0` | `0x2e8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x540` | `0x548` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xa0` | `0xa4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4027.100.59.0.0
+4027.100.70.0.0

+  - /System/Library/PrivateFrameworks/AppleMediaServices.framework/AppleMediaServices

-  Functions: 2273
-  Symbols:   1111
-  CStrings:  243
+  Functions: 2294
+  Symbols:   1116
+  CStrings:  247
Symbols:
+ _OBJC_CLASS_$_AMSAcknowledgePrivacyTask
+ __swift_closure_destructor.26Tm
+ __swift_closure_destructor.33Tm
+ _objc_msgSend$acknowledgementNeededForPrivacyIdentifier:
+ _swift_retain_x10
+ _symbolic _____ 19PodcastsAppEntities23PrivacyAgreementCheckerO
+ _symbolic _____ySbG 10AppIntents0A10DependencyC
+ _type_layout_string 19PodcastsAppEntities23PodcastCollectionEntityV0deF5QueryV
- __swift_closure_destructor.27Tm
- __swift_closure_destructor.34Tm
- _objc_retain_x10
CStrings:
+ "%s: Querying with ids: %{private,mask.hash}s"
+ "Error parsing siri SiriAssetInfo %{public}@"
+ "Failed to find requested local entities (%{public}s) with MOIDs: %{public}s"
+ "Failed to find requested local entities (%{public}s) with UUIDs: %{public}s"
+ "Failed to find requested local entities (%{public}s) with identifiers: %{private,mask.hash}s"
+ "Failed to find requested remote episodes with identifiers: %{private,mask.hash}s"
+ "Failed to prepare channel share URL, but failing silently: %{public}s"
+ "In order to use Siri, open the Apple Podcasts app and review the privacy information."
+ "NewsBriefEntityQuery: Querying with ids: %{private,mask.hash}s"
+ "PodcastCollectionEntityQuery: Querying with ids: %{private,mask.hash}s"
+ "PrivacyAgreementChecker: User needs to accept on welcome screen, throwing error."
+ "SiriEntityCache: Found entities in cache with ids: %{private,mask.hash}s"
+ "Unable to compute station suggestions: %{public}s"
+ "Unable to compute suggestions: %{public}s"
+ "Unable to find original identifier for entity, this may result in the entity being discarded: %{private,mask.hash}s"
+ "Unable to search for podcasts: %{public}s"
+ "acknowledgementNeededForPrivacyIdentifier:"
+ "radiowaves.right"
- "%s: Querying with ids: %s"
- "Error parsing siri SiriAssetInfo %@"
- "Failed to find requested local entities (%s) with MOIDs: %s"
- "Failed to find requested local entities (%s) with UUIDs: %s"
- "Failed to find requested local entities (%s) with identifiers: %s"
- "Failed to find requested remote episodes with identifiers: %s"
- "Failed to prepare channel share URL, but failing silently: %s"
- "NewsBriefEntityQuery: Querying with ids: %s"
- "PodcastCollectionEntityQuery: Querying with ids: %s"
- "SiriEntityCache: Found entities in cache with ids: %s"
- "Unable to compute station suggestions: %s"
- "Unable to compute suggestions: %s"
- "Unable to find original identifier for entity, this may result in the entity being discarded: %s"
- "Unable to search for podcasts: %s"
```
