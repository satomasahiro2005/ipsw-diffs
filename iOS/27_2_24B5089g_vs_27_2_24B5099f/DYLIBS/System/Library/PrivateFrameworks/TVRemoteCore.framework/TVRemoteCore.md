## TVRemoteCore

> `/System/Library/PrivateFrameworks/TVRemoteCore.framework/TVRemoteCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48918` | `0x48ec0` | **`+0x5a8`** |
| `__TEXT.__objc_methlist` | `0x6530` | `0x6840` | **`+0x310`** |
| `__AUTH_CONST.__objc_const` | `0x9fe0` | `0xa208` | **`+0x228`** |
| `__DATA_CONST.__objc_selrefs` | `0x3108` | `0x3310` | **`+0x208`** |
| `__TEXT.__oslogstring` | `0x6bd5` | `0x6db4` | **`+0x1df`** |
| `__DATA.__data` | `0xa34` | `0xa94` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x1660` | `0x16b8` | **`+0x58`** |
| `__TEXT.__lazy_helpers` | `0x580` | `0x5d4` | **`+0x54`** |
| `__AUTH_CONST.__cfstring` | `0x4a80` | `0x4ac0` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0xb28` | `0xb60` | **`+0x38`** |
| `__TEXT.__cstring` | `0x3738` | `0x3752` | **`+0x1a`** |
| `__TEXT.__unwind_info` | `0x1220` | `0x1238` | **`+0x18`** |
| `__AUTH_CONST.__lazy_load_got` | `0x80` | `0x88` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0xd8` | `0xe0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x69c` | `0x6a0` | **`+0x4`** |
| `__TEXT.__const` | `0x250` | `0x252` | **`+0x2`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_imageinfo`

### Other Changes

```diff

-627.10.47.0.0
+627.10.51.0.0

-  Functions: 2144
-  Symbols:   3714
-  CStrings:  1300
+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftXPC.dylib
+  - /usr/lib/swift/libswift_Builtin_float.dylib
+  Functions: 2150
+  Symbols:   3741
+  CStrings:  1309
Symbols:
+ -[TVRCHMHomeObserver _isAtHome]
+ -[TVRCHMHomeObserver homeDidUpdateHomeLocationStatus:]
+ -[TVRCRPCompanionLinkClientWrapper _finishInvalidatingWithCompletionHandler:]
+ -[TVRCRPCompanionLinkClientWrapper activating]
+ -[TVRCRPCompanionLinkClientWrapper setActivating:]
+ GCC_except_table100
+ GCC_except_table106
+ GCC_except_table116
+ GCC_except_table121
+ GCC_except_table126
+ GCC_except_table132
+ GCC_except_table136
+ GCC_except_table143
+ GCC_except_table148
+ GCC_except_table33
+ GCC_except_table37
+ GCC_except_table46
+ GCC_except_table90
+ GCC_except_table93
+ _HMStringFromHomeLocation
+ _HMStringFromHomeLocation$lazyAuthGOT_IA_ad_0
+ _HMStringFromHomeLocation$lazyLoadStub
+ _OBJC_IVAR_$_TVRCRPCompanionLinkClientWrapper._activating
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HMHomeDelegatePrivate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HMHomeDelegatePrivate
+ __OBJC_$_PROTOCOL_REFS_HMHomeDelegatePrivate
+ __OBJC_LABEL_PROTOCOL_$_HMHomeDelegatePrivate
+ __OBJC_PROTOCOL_$_HMHomeDelegatePrivate
+ ___block_descriptor_48_e8_32w40w_e5_v8?0lw32l8w40l8
+ ___swift_reflection_version
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftCoreFoundation_$_TVRemoteCore
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftDispatch_$_TVRemoteCore
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftFoundation_$_TVRemoteCore
+ __swift_FORCE_LOAD_$_swiftObjectiveC
+ __swift_FORCE_LOAD_$_swiftObjectiveC_$_TVRemoteCore
+ __swift_FORCE_LOAD_$_swiftXPC
+ __swift_FORCE_LOAD_$_swiftXPC_$_TVRemoteCore
+ __swift_FORCE_LOAD_$_swift_Builtin_float
+ __swift_FORCE_LOAD_$_swift_Builtin_float_$_TVRemoteCore
- GCC_except_table104
- GCC_except_table114
- GCC_except_table119
- GCC_except_table124
- GCC_except_table130
- GCC_except_table134
- GCC_except_table141
- GCC_except_table146
- GCC_except_table16
- GCC_except_table32
- GCC_except_table36
- GCC_except_table41
- GCC_except_table80
- GCC_except_table91
- GCC_except_table94
CStrings:
+ "CompanionClient is already activating %@"
+ "CompanionLinkClient is currently invalidating. Queuing request until after invalidation %@"
+ "Executing queued connection request %@"
+ "HomeKit informed us that the home location status for home %{public}@ is now %{public}@"
+ "Ignoring activation from a replaced companionLinkClient. Error - %@ %@"
+ "Ignoring invalidation from a replaced companionLinkClient %@"
+ "Ignoring location status update for a home we are not observing"
+ "Skipping accessory %{public}@ because we are away from home"
+ "activating"
+ "isInvalidating"
- "Executing queued connection request"
```
