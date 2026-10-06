## PodcastsPlayback

> `/private/var/staged_system_apps/Podcasts.app/Frameworks/PodcastsPlayback.framework/PodcastsPlayback`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x66ffc` | `0x668a0` | **`-0x75c`** |
| `__TEXT.__cstring` | `0xdb2` | `0xa72` | **`-0x340`** |
| `__TEXT.__swift5_reflstr` | `0x1122` | `0x1042` | **`-0xe0`** |
| `__DATA_CONST.__const` | `0x3478` | `0x33c8` | **`-0xb0`** |
| `__TEXT.__const` | `0x3b58` | `0x3ab8` | **`-0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x1000` | `0xf90` | **`-0x70`** |
| `__TEXT.__objc_methname` | `0x2a2d` | `0x29d5` | **`-0x58`** |
| `__DATA_CONST.__got` | `0x8c8` | `0x880` | **`-0x48`** |
| `__TEXT.__auth_stubs` | `0x2520` | `0x24e0` | **`-0x40`** |
| `__TEXT.__constg_swiftt` | `0x1810` | `0x17d4` | **`-0x3c`** |
| `__DATA.__data` | `0x30e0` | `0x3110` | **`+0x30`** |
| `__DATA.__objc_const` | `0x2298` | `0x2270` | **`-0x28`** |
| `__TEXT.__swift5_builtin` | `0xa0` | `0x78` | **`-0x28`** |
| `__DATA_CONST.__auth_got` | `0x1298` | `0x1278` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x86c` | `0x84c` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x1da0` | `0x1dc0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1ab8` | `0x1aa0` | **`-0x18`** |
| `__DATA.__objc_selrefs` | `0xb30` | `0xb20` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x2c1c` | `0x2c0e` | **`-0xe`** |
| `__DATA_CONST.__auth_ptr` | `0xa98` | `0xaa0` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x18` | `0x10` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x10c` | `0x104` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4027.100.59.0.0
+4027.100.70.0.0

-  Functions: 2181
-  Symbols:   1311
-  CStrings:  729
+  Functions: 2171
+  Symbols:   1308
+  CStrings:  710
Symbols:
+ _objc_msgSend$downloadedMediaKinds
+ _symbolic ShySSG
- _get_enum_tag_for_layout_string 16PodcastsPlayback25RemoteQueueOperationErrorO
- _symbolic _____ 16PodcastsPlayback25RemoteQueueOperationErrorO
- _symbolic _____ So18MRMediaRemoteErrorV
- _symbolic ______pSg s5ErrorP
- _type_layout_string 16PodcastsPlayback25RemoteQueueOperationErrorO
CStrings:
+ "downloadedMediaKinds"
- "A subscription is required to listen to this episode"
- "An unknown error occurred"
- "Chapters are not supported with AirPlay or Remote Control"
- "Currently playing item does not support chapters."
- "More than one device is trying to listen"
- "No content is currently playing."
- "Please open the Podcasts app and log in to play this media"
- "Podcasts cannot be queued"
- "Stations cannot be queued"
- "There is no content to play"
- "This content cannot be played while offline"
- "This content is restricted. Please try again in the Podcasts app"
- "This media requires a subscription to play"
- "Unable to enqueue library"
- "You're listening to the first chapter!"
- "You're listening to the last chapter!"
- "You've reached your device limit"
- "didUpdateSubscriptionsSyncVersionForSyncType:"
- "setSyncVersionFlags:"
- "syncVersionFlags"
```
