## PodcastsAppIntents

> `/private/var/staged_system_apps/Podcasts.app/Frameworks/PodcastsAppIntents.framework/PodcastsAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c464` | `0x3eebc` | **`+0x2a58`** |
| `__TEXT.__eh_frame` | `0x3070` | `0x3410` | **`+0x3a0`** |
| `__TEXT.__oslogstring` | `0x135d` | `0x153d` | **`+0x1e0`** |
| `__TEXT.__unwind_info` | `0x10c8` | `0x1178` | **`+0xb0`** |
| `__TEXT.__auth_stubs` | `0x1930` | `0x19a0` | **`+0x70`** |
| `__TEXT.__const` | `0x2ba8` | `0x2c18` | **`+0x70`** |
| `__TEXT.__cstring` | `0x575` | `0x535` | **`-0x40`** |
| `__DATA_CONST.__auth_got` | `0xca0` | `0xcd8` | **`+0x38`** |
| `__TEXT.__swift_as_cont` | `0x2dc` | `0x314` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x6b0` | `0x6e0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1000` | `0x1028` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x160` | `0x188` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x2e0` | `0x300` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x271` | `0x286` | **`+0x15`** |
| `__TEXT.__swift5_capture` | `0x5c` | `0x70` | **`+0x14`** |
| `__DATA.__data` | `0xd68` | `0xd78` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0xe0` | `0xec` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0xb8` | `0xc0` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x810` | `0x818` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0xbed` | `0xbf5` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-4027.100.70.0.0
+4027.100.75.0.0

-  Functions: 1052
-  Symbols:   512
-  CStrings:  128
+  Functions: 1083
+  Symbols:   518
+  CStrings:  134
Symbols:
+ ___swift_destroy_boxed_opaque_existential_1Tm
+ _objc_msgSend$supportsLocalLibrary
+ _objc_retain_x23
+ _swift_task_localValuePop
+ _swift_task_localValuePush
+ _symbolic ______p 18PodcastsFoundation18LibraryFeedUpdaterP
CStrings:
+ "PlaybackIntent.updateFeedIfNeeded: feed update finished"
+ "PlaybackIntent.updateFeedIfNeeded: feed update returned failure: %{public}@"
+ "PlaybackIntent.updateFeedIfNeeded: feed update skipped"
+ "PlaybackIntent.updateFeedIfNeeded: feed update threw: %{public}@"
+ "PlaybackIntent.updateFeedIfNeeded: feed update timed out after %ld seconds, proceeding without refresh"
+ "PlaybackIntent.updateFeedIfNeeded: refreshing feed for %{public}s"
+ "supportsLocalLibrary"
- "PodcastsAppIntents/AudioEntityIntentValueQuery.swift"
```
