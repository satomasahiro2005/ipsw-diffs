## Heart

> `/System/Library/Health/FeedItemPlugins/Heart.healthplugin/Heart`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d515c` | `0x2e874c` | **`+0x135f0`** |
| `__AUTH_CONST.__const` | `0x12a30` | `0x12f38` | **`+0x508`** |
| `__DATA.__data` | `0x7650` | `0x7a78` | **`+0x428`** |
| `__TEXT.__eh_frame` | `0x6bdc` | `0x6fd4` | **`+0x3f8`** |
| `__TEXT.__unwind_info` | `0x86c8` | `0x8948` | **`+0x280`** |
| `__TEXT.__swift5_typeref` | `0x72a6` | `0x7500` | **`+0x25a`** |
| `__TEXT.__swift5_capture` | `0x34b4` | `0x36c0` | **`+0x20c`** |
| `__TEXT.__cstring` | `0x12d1e` | `0x12f1e` | **`+0x200`** |
| `__AUTH_CONST.__auth_got` | `0x47a8` | `0x4978` | **`+0x1d0`** |
| `__AUTH.__data` | `0x8588` | `0x86e8` | **`+0x160`** |
| `__DATA_CONST.__got` | `0x2a40` | `0x2b78` | **`+0x138`** |
| `__TEXT.__const` | `0x18e24` | `0x18f44` | **`+0x120`** |
| `__TEXT.__swift5_reflstr` | `0x7fca` | `0x80e6` | **`+0x11c`** |
| `__TEXT.__swift5_fieldmd` | `0x7940` | `0x7a04` | **`+0xc4`** |
| `__TEXT.__constg_swiftt` | `0xc98c` | `0xca48` | **`+0xbc`** |
| `__DATA.__bss` | `0x13b68` | `0x13bf8` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0xe360` | `0xe3e0` | **`+0x80`** |
| `__TEXT.__swift_as_cont` | `0x474` | `0x4a4` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x9a4e` | `0x9a71` | **`+0x23`** |
| `__DATA.__common` | `0x950` | `0x968` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1cf0` | `0x1d08` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0xf10` | `0xf28` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x238` | `0x250` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x1c8` | `0x1dc` | **`+0x14`** |
| `__TEXT.__objc_methlist` | `0x2004` | `0x2014` | **`+0x10`** |
| `__AUTH.__objc_data` | `0x7c70` | `0x7c78` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x12e8` | `0x12f0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1148` | `0x114c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x948` | `0x94c` | **`+0x4`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

+  - /System/Library/PrivateFrameworks/HealthAppServices.framework/HealthAppServices

+  - /System/Library/PrivateFrameworks/HealthHeartRateStream.framework/HealthHeartRateStream

-  Functions: 12320
-  Symbols:   680
-  CStrings:  2177
+  Functions: 12555
+  Symbols:   682
+  CStrings:  2187
Symbols:
+ _OBJC_CLASS_$_HKHRHypertensionNotificationsFeatureAvailabilityRequirements
+ _dispatch_sync
CStrings:
+ "App-wide override. Affects all heart rate streaming in this app. Internal builds only — if the chosen lane has no connected device, no HR will stream."
+ "Apple Watch (Remote)"
+ "Connected Devices ("
+ "Failed to start HR streaming: %@"
+ "Force streaming from AirPods or 3rd-party sensor"
+ "Force streaming from paired watch"
+ "HeartRateStreamItem"
+ "No devices found"
+ "Use default priority (3rd-party → AirPods → Apple Watch)"
+ "com.apple.Health.HeartPromotionAvailability"
+ "init(title:detailText:heroImage:heroMaxHeight:linkButtonText:linkButtonAccessibilityIdentifier:)"
- "init(title:detailText:heroImage:heroImageHeight:linkButtonText:linkButtonAccessibilityIdentifier:)"
```
