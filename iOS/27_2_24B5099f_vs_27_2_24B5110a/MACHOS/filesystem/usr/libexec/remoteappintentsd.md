## remoteappintentsd

> `/usr/libexec/remoteappintentsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x833e0` | `0x8a144` | **`+0x6d64`** |
| `__TEXT.__eh_frame` | `0x63c8` | `0x6bc0` | **`+0x7f8`** |
| `__TEXT.__unwind_info` | `0x2560` | `0x2758` | **`+0x1f8`** |
| `__DATA_CONST.__const` | `0x3a70` | `0x3c48` | **`+0x1d8`** |
| `__TEXT.__const` | `0x2670` | `0x2818` | **`+0x1a8`** |
| `__DATA.__bss` | `0x1080` | `0x1180` | **`+0x100`** |
| `__DATA.__data` | `0x2a60` | `0x2b30` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0x212a` | `0x21b9` | **`+0x8f`** |
| `__TEXT.__swift_as_cont` | `0x404` | `0x490` | **`+0x8c`** |
| `__TEXT.__auth_stubs` | `0x2c80` | `0x2d00` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x11ec` | `0x126c` | **`+0x80`** |
| `__TEXT.__cstring` | `0x138a` | `0x13fa` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0xc60` | `0xcbc` | **`+0x5c`** |
| `__DATA_CONST.__auth_ptr` | `0xc30` | `0xc88` | **`+0x58`** |
| `__DATA_CONST.__got` | `0x848` | `0x8a0` | **`+0x58`** |
| `__DATA_CONST.__auth_got` | `0x1648` | `0x1688` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x1485` | `0x14c5` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0xc40` | `0xc80` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x130c` | `0x1348` | **`+0x3c`** |
| `__DATA.__common` | `0x2c0` | `0x2f0` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x2e4` | `0x314` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0x2a8` | `0x2d4` | **`+0x2c`** |
| `__TEXT.__swift5_typeref` | `0x17fc` | `0x1822` | **`+0x26`** |
| `__DATA.__objc_const` | `0x1768` | `0x1748` | **`-0x20`** |
| `__TEXT.__swift5_assocty` | `0x90` | `0xa8` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x460` | `0x470` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0xb4` | `0xbc` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x104` | `0x108` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-41.1.15.0.0
+41.1.16.1.102

+  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

+  - /System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration

-  Functions: 2900
-  Symbols:   1148
-  CStrings:  572
+  Functions: 2996
+  Symbols:   1169
+  CStrings:  583
Symbols:
+ _$s12FeatureFlags02isA7EnabledySbAA0aB3Key_pF
+ _$s12FeatureFlags0aB3KeyMp
+ _$s12FeatureFlags0aB3KeyP6domains12StaticStringVvgTq
+ _$s12FeatureFlags0aB3KeyP7features12StaticStringVvgTq
+ _$s18AppIntentsServices06RemoteaB5ActorC11Distributed0fE0AAMc
+ _$s18AppIntentsServices06RemoteaB5ActorC7Network020NWSingletonPublishedE0AAMc
+ _$s18AppIntentsServices0bC0O10DeviceTypeO13homeAccessoryyA2EmFWC
+ _$s7Network10NWListenerC16debugDescriptionSSvg
+ _$s7Network10NWListenerC5StateO5readyyA2EmFWC
+ _$s7Network10NWListenerC5StateO5setupyA2EmFWC
+ _$s7Network10NWListenerC5StateO6failedyAeA7NWErrorOcAEmFWC
+ _$s7Network10NWListenerC5StateO7waitingyAeA7NWErrorOcAEmFWC
+ _$s7Network10NWListenerC5StateO9cancelledyA2EmFWC
+ _$s7Network10NWListenerC5StateOMa
+ _$s7Network10NWListenerC5stateAC5StateOvg
+ _$s7Network13NWActorSystemC8listenerAA10NWListenerCSgvg
+ _$sScT2eeoiySbScTyxq_G_ABtFZ
+ _$ss12StaticStringVMn
+ _OBJC_CLASS_$_MCProfileConnection
+ _swift_checkMetadataState
+ _swift_getTupleTypeMetadata2
CStrings:
+ "%s: Listener activated for %s, republishOnWake: %{bool}d"
+ "%s: already started (%s), start() called twice?"
+ "%s: failed to publish actor over %s: %@"
+ "%s: republish requested over %s, will republish: %s current state: %s, actorSystem.listener: %s"
+ "%s: republish requested while %s, joining the in-flight publish"
+ "%s: republish requested while %s, nothing to republish"
+ "%s: republishing actor failed, retrying once: %@"
+ "%s: stopping after a failed publish"
+ "%sHome device pairing management enabled. Allowed: %{bool}d"
+ "AppIntentsServices"
+ "Joining existing listener for %s"
+ "Listener for %s failed to publish, discarding it: %@"
+ "applicationID"
+ "cancelled"
+ "failed"
+ "initial"
+ "isPairingWithHomeDevicesAllowed"
+ "published"
+ "publishing"
+ "republishListenerOnRapportWake"
+ "sharedConnection"
- "%s: actor already published, start() called twice?"
- "%s: already started publishing actor, start() called twice?"
- "%sHome device pairing management disabled. Default to allow: true."
- "BUG? A listener was already active for %s"
- "ERROR: %@"
- "Rapport service %s has already been initialized. Rapport bug?"
- "Rapport service %s initialization completed, success: %{bool}d"
- "Terminus service %s has already been initialized"
- "Terminus service %s initialization completed, success: %{bool}d"
- "initializedServices"
```
