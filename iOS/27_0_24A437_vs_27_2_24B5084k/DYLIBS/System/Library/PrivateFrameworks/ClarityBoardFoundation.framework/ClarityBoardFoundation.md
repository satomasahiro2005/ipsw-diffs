## ClarityBoardFoundation

> `/System/Library/PrivateFrameworks/ClarityBoardFoundation.framework/ClarityBoardFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe6fc` | `0xec74` | **`+0x578`** |
| `__AUTH_CONST.__objc_const` | `0x708` | `0x7c0` | **`+0xb8`** |
| `__AUTH.__data` | `0x428` | `0x4c8` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x374` | `0x410` | **`+0x9c`** |
| `__AUTH_CONST.__const` | `0x358` | `0x3e8` | **`+0x90`** |
| `__TEXT.__const` | `0x790` | `0x818` | **`+0x88`** |
| `__TEXT.__cstring` | `0xa72` | `0xae5` | **`+0x73`** |
| `__AUTH_CONST.__cfstring` | `0x880` | `0x8e0` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x37c` | `0x3cf` | **`+0x53`** |
| `__TEXT.__swift5_typeref` | `0x23c` | `0x282` | **`+0x46`** |
| `__TEXT.__swift5_fieldmd` | `0x170` | `0x1ac` | **`+0x3c`** |
| `__DATA_CONST.__objc_selrefs` | `0x250` | `0x270` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x430` | `0x448` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x180` | `0x198` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x488` | `0x4a0` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0x202` | `0x212` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x710` | `0x718` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x4` | `0x8` | **`+0x4`** |

### Other Changes

```diff

-168.2.0.0.0
+170.3.0.0.0

+  - /System/Library/Frameworks/LocalAuthentication.framework/LocalAuthentication

-  Functions: 406
-  Symbols:   472
-  CStrings:  109
+  Functions: 428
+  Symbols:   487
+  CStrings:  113
Symbols:
+ _CLBApplicationSceneViewSizeUserInfoKey
+ _CLBDidUpdateApplicationSceneViewSizeNotification
+ _CLBSharingUIServiceBundleIdentifier
+ _MKBGetDeviceLockState
+ _MKBUnlockDeviceWithACM
+ _NSUnderlyingErrorKey
+ _OBJC_CLASS_$_LAContext
+ _OBJC_CLASS_$_NSDictionary
+ __DATA__TtC22ClarityBoardFoundation24ClockLiveHandsController
+ __IVARS__TtC22ClarityBoardFoundation24ClockLiveHandsController
+ __METACLASS_DATA__TtC22ClarityBoardFoundation24ClockLiveHandsController
+ ___swift_memcpy0_1
+ _symbolic $s22ClarityBoardFoundation25ClockLiveHandsControllingP
+ _symbolic _____ 22ClarityBoardFoundation24ClockLiveHandsControllerC
+ _symbolic _____ 22ClarityBoardFoundation37HostedSceneInterfaceOrientationPolicyO
+ _symbolic x
- _MKBUnlockDevice
CStrings:
+ "CLBApplicationSceneViewSizeUserInfoKey"
+ "CLBDidUpdateApplicationSceneViewSizeNotification"
+ "Failed to stash passcode into an ACM context; cannot unlock the keybag: %{public}@"
+ "com.apple.SharingUIService"
```
