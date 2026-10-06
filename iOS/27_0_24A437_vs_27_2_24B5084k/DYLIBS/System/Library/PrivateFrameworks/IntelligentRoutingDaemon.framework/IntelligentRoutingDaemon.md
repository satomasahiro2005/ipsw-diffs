## IntelligentRoutingDaemon

> `/System/Library/PrivateFrameworks/IntelligentRoutingDaemon.framework/IntelligentRoutingDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbab04` | `0xbb36c` | **`+0x868`** |
| `__TEXT.__oslogstring` | `0x5d7a` | `0x5dd1` | **`+0x57`** |
| `__AUTH_CONST.__objc_const` | `0xec20` | `0xec50` | **`+0x30`** |
| `__TEXT.__cstring` | `0xafad` | `0xafdd` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x6680` | `0x66a0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xde8` | `0xe00` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x1ce0` | `0x1cc8` | **`-0x18`** |
| `__DATA.__data` | `0x1a58` | `0x1a68` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x17a8` | `0x17b8` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xfbe` | `0xfca` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x11b8` | `0x11c0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x42c0` | `0x42c8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x77a4` | `0x77ac` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2c08` | `0x2c10` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x960` | `0x964` | **`+0x4`** |

### Other Changes

```diff

-125.0.13.0.0
+125.1.4.0.0

+  - /usr/lib/swift/libswiftAccelerate.dylib

+  - /usr/lib/swift/libswiftIntents.dylib

-  Functions: 4339
-  Symbols:   9355
-  CStrings:  1526
+  Functions: 4341
+  Symbols:   9369
+  CStrings:  1528
Symbols:
+ -[IRPreferences proximitySessionRetryBaseDelaySeconds]
+ -[IRPreferences proximitySessionRetryMaxDelaySeconds]
+ -[IRProximityProvider _retryDelayForCount:]
+ _$s10Foundation4UUIDVACSQAAWL
+ _$s10Foundation4UUIDVACSQAAWl
+ _$s10Foundation4UUIDVSQAAMc
+ _$s10Foundation4UUIDVSgWOhTm
+ _$s10Foundation4UUIDVSg_ADtMR
+ _$s10Foundation4UUIDVSg_ADtMd
+ _$sSQ2eeoiySbx_xtFZTj
+ _OBJC_IVAR_$_IRPreferences._proximitySessionRetryBaseDelaySeconds
+ _OBJC_IVAR_$_IRPreferences._proximitySessionRetryMaxDelaySeconds
+ __swift_FORCE_LOAD_$_swiftAccelerate
+ __swift_FORCE_LOAD_$_swiftAccelerate_$_IntelligentRoutingDaemon
+ __swift_FORCE_LOAD_$_swiftIntents
+ __swift_FORCE_LOAD_$_swiftIntents_$_IntelligentRoutingDaemon
+ _dispatch_after
+ _exp2
+ _symbolic _____Sg_ABt 10Foundation4UUIDV
- -[IRPreferences proximitySessionRetryCountThreshold]
- -[IRProximityProvider _incrementRetryCount:]
- -[IRProximityProvider _resetRetryCount:]
- _OBJC_IVAR_$_IRPreferences._proximitySessionRetryCountThreshold
- ___block_descriptor_64_e8_32s40s48s56w_e5_v8?0lw56l8s32l8s40l8s48l8
CStrings:
+ "#proximity-provider, Bridge failed: %@, retry #%@ in %@s"
+ "#proximity-provider, Skipping delayed retry, bridge %@ was torn down"
+ "IRproximitySessionRetryBaseDelaySeconds"
+ "IRproximitySessionRetryMaxDelaySeconds"
- "#proximity-provider, Bridge failed: %@"
- "IRproximitySessionRetryCountThreshold"
```
