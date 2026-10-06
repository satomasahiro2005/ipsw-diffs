## PodcastsPlayback

> `/private/var/staged_system_apps/Podcasts.app/Frameworks/PodcastsPlayback.framework/PodcastsPlayback`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x66ac8` | `0x688d4` | **`+0x1e0c`** |
| `__DATA_CONST.__const` | `0x33d8` | `0x35b8` | **`+0x1e0`** |
| `__TEXT.__const` | `0x3ad8` | `0x3c48` | **`+0x170`** |
| `__TEXT.__swift5_fieldmd` | `0xf9c` | `0x10c8` | **`+0x12c`** |
| `__DATA.__objc_const` | `0x2290` | `0x23a8` | **`+0x118`** |
| `__TEXT.__swift5_reflstr` | `0x1032` | `0x1132` | **`+0x100`** |
| `__DATA.__data` | `0x3110` | `0x3200` | **`+0xf0`** |
| `__TEXT.__oslogstring` | `0x1124` | `0x11e4` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x2c0c` | `0x2cca` | **`+0xbe`** |
| `__TEXT.__constg_swiftt` | `0x17f4` | `0x1878` | **`+0x84`** |
| `__TEXT.__objc_methname` | `0x29e5` | `0x2a35` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1aa0` | `0x1af0` | **`+0x50`** |
| `__TEXT.__objc_classname` | `0x82b` | `0x86b` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x7bc` | `0x7ec` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x1e00` | `0x1e20` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x104` | `0x110` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0xb40` | `0xb48` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xa98` | `0xaa0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xc0` | `0xc8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1b8` | `0x1bc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4027.200.26.0.0
+4027.200.32.0.0

-  Functions: 2179
-  Symbols:   1310
-  CStrings:  714
+  Functions: 2220
+  Symbols:   1327
+  CStrings:  721
Symbols:
+ __DATA__TtC16PodcastsPlayback38PlayerResponsePlaybackPositionReporter
+ __IVARS__TtC16PodcastsPlayback38PlayerResponsePlaybackPositionReporter
+ __METACLASS_DATA__TtC16PodcastsPlayback38PlayerResponsePlaybackPositionReporter
+ ___swift_memcpy88_8
+ ___swift_memcpy98_8
+ _objc_msgSend$supportsSubscription
+ _symbolic So8NSNumberCSg
+ _symbolic _____ 16PodcastsPlayback014PlayerResponseB16PositionReporterC
+ _symbolic _____ 16PodcastsPlayback014PlayerResponseB16PositionReporterC07DerivedbE5Event33_DAFA366CA1B54DC5AA858A422C588EDALLV
+ _symbolic _____ 16PodcastsPlayback014PlayerResponseB16PositionReporterC14PlayingEpisode33_DAFA366CA1B54DC5AA858A422C588EDALLV
+ _symbolic _____Sg 16PodcastsPlayback014PlayerResponseB16PositionReporterC14PlayingEpisode33_DAFA366CA1B54DC5AA858A422C588EDALLV
+ _symbolic _____SgXw 16PodcastsPlayback014PlayerResponseB16PositionReporterC
+ _symbolic ______p 16PodcastsPlayback0B15PositionTrackerP
+ _symbolic _____y______ySo17MPCPlayerResponseCSg_____G_____G 7Combine10PublishersO10CompactMapV AA12AnyPublisherV s5NeverO 16PodcastsPlayback014PlayerResponseI16PositionReporterC14PlayingEpisode33_DAFA366CA1B54DC5AA858A422C588EDALLV
+ _symbolic _____y______y______ySo17MPCPlayerResponseCSg_____G_____GSo17OS_dispatch_queueCG 7Combine10PublishersO9ReceiveOnV AC10CompactMapV AA12AnyPublisherV s5NeverO 16PodcastsPlayback014PlayerResponseK16PositionReporterC14PlayingEpisode33_DAFA366CA1B54DC5AA858A422C588EDALLV
+ _type_layout_string 16PodcastsPlayback014PlayerResponseB16PositionReporterC07DerivedbE5Event33_DAFA366CA1B54DC5AA858A422C588EDALLV
+ _type_layout_string 16PodcastsPlayback014PlayerResponseB16PositionReporterC14PlayingEpisode33_DAFA366CA1B54DC5AA858A422C588EDALLV
CStrings:
+ "Episode left the player at %f/%fs, reporting it as %s"
+ "Error reporting position for episode that left the player: %@"
+ "Not allowing sync for episode that left the player"
+ "_TtC16PodcastsPlayback38PlayerResponsePlaybackPositionReporter"
+ "lastPlayingEpisode"
+ "subscription"
+ "supportsSubscription"
```
