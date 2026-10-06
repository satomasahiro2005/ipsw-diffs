## Preferences

> `/Applications/Preferences.app/Preferences`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12a998` | `0x129d64` | **`-0xc34`** |
| `__DATA.__objc_const` | `0x75c8` | `0x7978` | **`+0x3b0`** |
| `__TEXT.__eh_frame` | `0x6f74` | `0x6e24` | **`-0x150`** |
| `__DATA.__bss` | `0x83e8` | `0x84e8` | **`+0x100`** |
| `__DATA.__data` | `0x7820` | `0x7900` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0x59c0` | `0x58e8` | **`-0xd8`** |
| `__TEXT.__objc_methname` | `0x40ed` | `0x41bd` | **`+0xd0`** |
| `__DATA.__objc_data` | `0x15e8` | `0x16a8` | **`+0xc0`** |
| `__TEXT.__objc_methtype` | `0x1595` | `0x1625` | **`+0x90`** |
| `__TEXT.__swift5_capture` | `0x16d8` | `0x164c` | **`-0x8c`** |
| `__TEXT.__objc_classname` | `0xfeb` | `0x106b` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x2730` | `0x27a0` | **`+0x70`** |
| `__TEXT.__auth_stubs` | `0x4c90` | `0x4c30` | **`-0x60`** |
| `__TEXT.__const` | `0xaee4` | `0xaf44` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0xc5c` | `0xcbc` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x2c9c` | `0x2cec` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x1fa0` | `0x1fe0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x3a28` | `0x39e8` | **`-0x40`** |
| `__DATA_CONST.__auth_got` | `0x2650` | `0x2620` | **`-0x30`** |
| `__TEXT.__cstring` | `0x6266` | `0x6296` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0xd00` | `0xd28` | **`+0x28`** |
| `__DATA_CONST.__objc_protolist` | `0x130` | `0x150` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x2ae8` | `0x2b04` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x1280` | `0x1268` | **`-0x18`** |
| `__TEXT.__swift5_assocty` | `0xbb8` | `0xbd0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x104` | `0x118` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x5f4` | `0x5e0` | **`-0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x18b8` | `0x18a8` | **`-0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x98` | `0xa8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1c0` | `0x1c8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x464` | `0x46c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x2b4` | `0x2bc` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x2bc` | `0x2b4` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x2ac` | `0x2a8` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_catlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-2027.1.6.0.0
+2027.1.8.0.0

-  - /System/Library/Frameworks/Combine.framework/Combine

-  - /System/Library/PrivateFrameworks/ConversationKit.framework/ConversationKit

+  - /System/Library/PrivateFrameworks/TelephonyUtilities.framework/TelephonyUtilities

-  - /usr/lib/swift/libswiftSpriteKit.dylib

-  Functions: 4430
-  Symbols:   2305
-  CStrings:  1575
+  Functions: 4422
+  Symbols:   2293
+  CStrings:  1591
Symbols:
+ _$sSo17OS_dispatch_queueC8DispatchE4mainABvgZ
+ _OBJC_CLASS_$_TUCallCenter
- _$s15ConversationKit34ScreenSharingInteractionControllerC19remoteControlStatusSo08TURemotehI0VvgTj
- _$s15ConversationKit34ScreenSharingInteractionControllerC6sharedACvgZ
- _$s15ConversationKit34ScreenSharingInteractionControllerC7Combine16ObservableObjectAAMc
- _$s15ConversationKit34ScreenSharingInteractionControllerCMa
- _$s7Combine14AsyncPublisherV04makeB8IteratorAC0E0Vyx_GyF
- _$s7Combine14AsyncPublisherV8IteratorVMn
- _$s7Combine14AsyncPublisherV8IteratorVyx_GScIAAMc
- _$s7Combine14AsyncPublisherVMn
- _$s7Combine16ObservableObjectPA2A0bC9PublisherC0c10WillChangeD0RtzrlE06objecteF0AEvg
- _$s7Combine25ObservableObjectPublisherCAA0D0AAWP
- _$s7Combine25ObservableObjectPublisherCMa
- _$s7Combine25ObservableObjectPublisherCMn
- _$s7Combine9PublisherPAAs5NeverO7FailureRtzrlE6valuesAA05AsyncB0VyxGvg
- __swift_FORCE_LOAD_$_swiftSpriteKit
CStrings:
+ "Remote control status changed, under remote control: %{bool,public}d"
+ "SettingsApp.RemoteControlStatusObserver"
+ "TUCallCenterDelegate"
+ "TUDelegate"
+ "_TtC11SettingsAppP33_7985D8068E8B39B9027E4450DAC7CC4927RemoteControlStatusObserver"
+ "addDelegate:queue:"
+ "callCenter:receivedCaptions:"
+ "callCenter:remoteControlStatusChanged:"
+ "callCenter:reportedCall:receivedDTMFUpdate:"
+ "onChange"
+ "removeDelegate:"
+ "statusObserver"
+ "v32@0:8@\"TUCallCenter\"16@\"TUCaptionsResult\"24"
+ "v32@0:8@\"TUCallCenter\"16q24"
+ "v32@0:8@16q24"
+ "v40@0:8@\"TUCallCenter\"16@\"TUCall\"24@\"TUCallDTMFUpdate\"32"
```
