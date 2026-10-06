## PodcastsAppIntents

> `/private/var/staged_system_apps/Podcasts.app/Frameworks/PodcastsAppIntents.framework/PodcastsAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3a900` | `0x3c464` | **`+0x1b64`** |
| `__TEXT.__oslogstring` | `0xded` | `0x135d` | **`+0x570`** |
| `__TEXT.__swift5_reflstr` | `0x568` | `0x633` | **`+0xcb`** |
| `__TEXT.__eh_frame` | `0x2fe8` | `0x3070` | **`+0x88`** |
| `__DATA_CONST.__const` | `0xf88` | `0x1000` | **`+0x78`** |
| `__TEXT.__auth_stubs` | `0x18c0` | `0x1930` | **`+0x70`** |
| `__TEXT.__const` | `0x2b38` | `0x2ba8` | **`+0x70`** |
| `__DATA.__common` | `0x48` | `0x90` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x4e8` | `0x524` | **`+0x3c`** |
| `__DATA_CONST.__auth_got` | `0xc68` | `0xca0` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x1090` | `0x10c8` | **`+0x38`** |
| `__DATA.__data` | `0xd40` | `0xd68` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x2c0` | `0x2e0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x698` | `0x6b0` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0xcc` | `0xe0` | **`+0x14`** |
| `__TEXT.__objc_methname` | `0x260` | `0x271` | **`+0x11`** |
| `__TEXT.__swift5_typeref` | `0xbe3` | `0xbed` | **`+0xa`** |
| `__DATA.__objc_selrefs` | `0xb0` | `0xb8` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x808` | `0x810` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4027.100.59.0.0
+4027.100.70.0.0

-  Functions: 1036
-  Symbols:   510
-  CStrings:  122
+  Functions: 1052
+  Symbols:   512
+  CStrings:  128
Symbols:
+ ___swift_memcpy40_8
+ ___swift_memcpy56_8
+ _objc_msgSend$underlyingErrors
+ _swift_retain_x27
+ _symbolic _____ySbG 10AppIntents0A10DependencyC
- ___swift_memcpy32_8
- ___swift_memcpy48_8
- _swift_release_x28
CStrings:
+ "AddAudioToLibraryIntent: attempt to add unsupported entityID: %{private,mask.hash}s"
+ "AddAudioToLibraryIntent: bookmarking entityID: %{private,mask.hash}s"
+ "AddAudioToLibraryIntent: following entityID: %{private,mask.hash}s"
+ "Converting ErrorDialog's PodcastsAppIntentError from: %{public}@ to: %{public}@"
+ "Converting PodcastsAppIntentError directly from: %{public}@ to: %{public}@"
+ "Donated add item to library (%{public}s; %{private,mask.hash}s) with donation ID: %{public}s"
+ "Donated item play (%{public}s; %{private,mask.hash}s) with donation ID: %{public}s"
+ "Donating OpenAudioAppIntent for view: [ %{public}s; %{private,mask.hash}s ]"
+ "Failed to donate add item to library: %{public}s"
+ "Failed to donate open audio intent: %{public}s"
+ "Failed to donate play audio intent for media identifier: [ %{private,mask.hash}s ], error: %{public}s"
+ "Inserting at queue position: %{public}s"
+ "Opening App Location from intent: %{public}s"
+ "PlayAudioIntent Legacy: entityID: %{private,mask.hash}s"
+ "PlayAudioIntent failed: %{public}s"
+ "PlayAudioIntent: MediaIdentifier: %{private,mask.hash}s"
+ "PlayAudioIntent: already prewarmed with %{private,mask.hash}s, starting playback without setting the queue"
+ "PlayAudioIntent: entityID: %{private,mask.hash}s"
+ "PlaybackIntent created with requestIdentifier: %{public}s"
+ "Player queue successfully set for: %{private,mask.hash}s"
+ "Skipping add item to library donation, unable to resolve entity for identifier: [ %{public}s; %{private,mask.hash}s ]"
+ "Skipping open audio donation, unable to resolve entity for identifier: [ %{public}s; %{private,mask.hash}s ]"
+ "Throwing ErrorDialog's underlying error: %{public}@"
+ "Trying to queue an entity which does not support queueing"
+ "Unknown spotlight entity type (%{public}s). Falling back to unknown identifier construction."
+ "Warmup Result (%{private,mask.hash}s) doesn't match"
+ "WarmupAudioQueueIntent Legacy: entityID: %{private,mask.hash}s"
+ "WarmupAudioQueueIntent failed: %{public}s"
+ "WarmupAudioQueueIntent: MediaIdentifier: %{private,mask.hash}s"
+ "WarmupAudioQueueIntent: entityID: %{private,mask.hash}s"
+ "[%{public}s] %{private,mask.hash}s: Failed to hydrate with siriAssetInfo"
+ "[%{public}s] %{private,mask.hash}s: Hydrating with siriAssetInfo"
+ "[%{public}s] %{private,mask.hash}s: SiriAssetInfo missing or invalid, querying for id"
+ "[%{public}s] %{private,mask.hash}s: siriAssetInfo hydration successful"
+ "[%{public}s] Catalog: Searching for podcast episode with identifier: %{private,mask.hash}s."
+ "[%{public}s] Catalog: Searching for podcast news brief with identifier: %{private,mask.hash}s."
+ "[%{public}s] Catalog: Searching for podcast show with identifier: %{private,mask.hash}s."
+ "[%{public}s] Catalog: Searching for podcast station with identifier: %{private,mask.hash}s... this is unlikely to succeed as these aren't catalog entities"
+ "[%{public}s] Incomplete search results"
+ "[%{public}s] Looking up entity for %s."
+ "[%{public}s] Mapping audio search to catalog entity."
+ "[%{public}s] Mapping audio search to spotlight entity with type '%{public}s'."
+ "[%{public}s] Resolution failed, unable to progress with identifier: %{private,mask.hash}s."
+ "[%{public}s] Resolved to collection with ID: %{private,mask.hash}s."
+ "[%{public}s] Resolved to episode with ID: %{private,mask.hash}s."
+ "[%{public}s] Resolved to show with ID: %{private,mask.hash}s."
+ "[%{public}s] Spotlight: Searching for podcast collection with identifier: %{private,mask.hash}s."
+ "[%{public}s] Spotlight: Searching for podcast episode with identifier: %{private,mask.hash}s."
+ "[%{public}s] Spotlight: Searching for podcast show with identifier: %{private,mask.hash}s."
+ "[%{public}s] Starting mapping of internal AudioSearchCriteria"
+ "[%{public}s] Unable to find podcast entity with ID: %{private,mask.hash}s"
+ "[%{public}s] Undefined media type."
+ "[%{public}s] Unsupported media type: %{public}s."
+ "[%{public}s] User is asking to \"Play Apple Podcasts\", returning library entity."
+ "[%{public}s] User is asking to \"Play Podcasts\", returning library entity."
+ "[%{public}s] found entity %{private,mask.hash}s."
+ "appIntentPlayDestination: Failed to resolve: %{public}s"
+ "appIntentPlayDestination: Routing to %{public}s"
+ "underlyingErrors"
- "Converting ErrorDialog's PodcastsAppIntentError from: %@ to: %@"
- "Converting PodcastsAppIntentError directly from: %@ to: %@"
- "Donated add item to library (%s; %s) with donation ID: %s"
- "Donated item play (%s; %s) with donation ID: %s"
- "Donating OpenAudioAppIntent for view: [ %s; %s ]"
- "Failed to donate add item to library: %s"
- "Failed to donate open audio intent: %s"
- "Failed to donate play audio intent for media identifier: [ %s ], error: %s"
- "Inserting at queue position: %s"
- "Opening App Location from intent: %s"
- "PlayAudioIntent Legacy: entityID: %s"
- "PlayAudioIntent failed: %s"
- "PlayAudioIntent: MediaIdentifier: %s"
- "PlayAudioIntent: already prewarmed with %s, starting playback without setting the queue"
- "PlayAudioIntent: entityID: %s"
- "PlaybackIntent created with requestIdentifier: %s"
- "Player queue successfully set for: %s"
- "Skipping add item to library donation, unable to resolve entity for identifier: [ %s; %s ]"
- "Skipping open audio donation, unable to resolve entity for identifier: [ %s; %s ]"
- "Throwing ErrorDialog's underlying error: %@"
- "Unknown spotlight entity type (%s). Falling back to unknown identifier construction."
- "WarmupAudioQueueIntent Legacy: entityID: %s"
- "WarmupAudioQueueIntent failed: %s"
- "WarmupAudioQueueIntent: MediaIdentifier: %s"
- "WarmupAudioQueueIntent: entityID: %s"
- "[%s] %s: Failed to hydrate with siriAssetInfo"
- "[%s] %s: Hydrating with siriAssetInfo"
- "[%s] %s: SiriAssetInfo missing or invalid, querying for id"
- "[%s] %s: siriAssetInfo hydration successful"
- "[%s] Catalog: Searching for podcast episode with identifier: %s."
- "[%s] Catalog: Searching for podcast news brief with identifier: %s."
- "[%s] Catalog: Searching for podcast show with identifier: %s."
- "[%s] Catalog: Searching for podcast station with identifier: %s... this is unlikely to succeed as these aren't catalog entities"
- "[%s] Incomplete search results"
- "[%s] Looking up entity for %s."
- "[%s] Mapping audio search to catalog entity."
- "[%s] Mapping audio search to spotlight entity with type '%s'."
- "[%s] Resolution failed, unable to progress with identifier: %s."
- "[%s] Resolved to collection with ID: %s."
- "[%s] Resolved to episode with ID: %s."
- "[%s] Resolved to show with ID: %s."
- "[%s] Spotlight: Searching for podcast collection with identifier: %s."
- "[%s] Spotlight: Searching for podcast episode with identifier: %s."
- "[%s] Spotlight: Searching for podcast show with identifier: %s."
- "[%s] Starting mapping of internal AudioSearchCriteria"
- "[%s] Unable to find podcast entity with ID: %s"
- "[%s] Undefined media type."
- "[%s] Unsupported media type: %s."
- "[%s] User is asking to \"Play Apple Podcasts\", returning library entity."
- "[%s] User is asking to \"Play Podcasts\", returning library entity."
- "[%s] found entity %s."
- "appIntentPlayDestination: Failed to resolve: %s"
- "appIntentPlayDestination: Routing to %s"
```
