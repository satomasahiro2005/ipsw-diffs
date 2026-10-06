## MediaDevice

> `/System/Library/Frameworks/MediaDevice.framework/MediaDevice`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__eh_frame` | `0xf80` | `0x16c0` | **`+0x740`** |
| `__TEXT.__cstring` | `0xd2f` | `0x83f` | **`-0x4f0`** |
| `__AUTH.__objc_data` | `0x50` | `0x538` | **`+0x4e8`** |
| `__TEXT.__text` | `0x314d4` | `0x317e8` | **`+0x314`** |
| `__TEXT.__swift5_capture` | `0xbbc` | `0x97c` | **`-0x240`** |
| `__TEXT.__unwind_info` | `0x840` | `0xa50` | **`+0x210`** |
| `__TEXT.__const` | `0x1098` | `0x1242` | **`+0x1aa`** |
| `__AUTH_CONST.__const` | `0x14b8` | `0x1360` | **`-0x158`** |
| `__DATA.__bss` | `0xf90` | `0x1090` | **`+0x100`** |
| `__TEXT.__constg_swiftt` | `0x734` | `0x7c0` | **`+0x8c`** |
| `__AUTH_CONST.__auth_got` | `0x898` | `0x8f8` | **`+0x60`** |
| `__DATA.__data` | `0x578` | `0x5c8` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0xa48` | `0xa90` | **`+0x48`** |
| `__TEXT.__swift_as_cont` | `0x64` | `0xa8` | **`+0x44`** |
| `__TEXT.__swift_as_entry` | `0x68` | `0xac` | **`+0x44`** |
| `__AUTH.__data` | `0x1e8` | `0x218` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x368` | `0x384` | **`+0x1c`** |
| `__TEXT.__swift5_typeref` | `0x6e2` | `0x6fc` | **`+0x1a`** |
| `__TEXT.__swift5_assocty` | `0xc0` | `0xd8` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__TEXT.__swift5_reflstr` | `0x399` | `0x3a9` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x80` | `0x88` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x34` | `0x38` | **`+0x4`** |

### Other Changes

```diff

-360.66.1.11.1
+360.70.2.0.0

-  Functions: 807
-  Symbols:   452
-  CStrings:  183
+  Functions: 812
+  Symbols:   468
+  CStrings:  158
Symbols:
+ _NSSelectorFromString
+ _OBJC_CLASS_$__TtC11MediaDevice32_SMCBridgeExtensionConfiguration
+ _OBJC_METACLASS_$__TtC11MediaDevice32_SMCBridgeExtensionConfiguration
+ __DATA__TtC11MediaDevice32_SMCBridgeExtensionConfiguration
+ __METACLASS_DATA__TtC11MediaDevice32_SMCBridgeExtensionConfiguration
+ ___swift_closure_destructor.104Tm
+ ___swift_closure_destructor.385Tm
+ ___swift_closure_destructor.392Tm
+ ___swift_closure_destructor.432Tm
+ ___swift_closure_destructor.463Tm
+ _get_witness_table 11MediaDevice0aB9ExtensionRzlAA010_SMCBridgeC13ConfigurationCAA0abcE0HPyHC
+ _objc_retain_x25
+ _objc_retain_x27
+ _swift_release_x24
+ _swift_release_x25
+ _swift_release_x28
+ _swift_retain_x24
+ _swift_retain_x26
+ _swift_retain_x28
+ _swift_updateClassMetadata2
+ _symbolic SDy_____ypGIeghg_ s11AnyHashableV
+ _symbolic SayypG
+ _symbolic Sf
+ _symbolic _____ 10Foundation3URLV
+ _symbolic _____ 10Foundation4DataV
+ _symbolic _____ So24MDESandboxExtension_Typea
+ _symbolic _____ s5Int64V
+ _symbolic _____ s6UInt16V
+ _symbolic _____SgXw 11MediaDevice32_SMCBridgeExtensionConfigurationC
+ _symbolic _____SgXwz_Xx 11MediaDevice32_SMCBridgeExtensionConfigurationC
+ _symbolic ______p 11MediaDevice0aB9ExtensionP
+ _symbolic ______pypIeghgn_ s5ErrorP
+ _symbolic yp
+ _type_layout_string So24MDESandboxExtension_Typea
- _NSHelpAnchorErrorKey
- ___swift_closure_destructor.18Tm
- ___swift_destroy_boxed_opaque_existential_1
- ___swift_instantiateGenericMetadata
- ___unnamed_3
- _get_witness_table 11MediaDevice0aB9ExtensionRzlAA010_SMCBridgeC13ConfigurationCyxGAA0abcE0HPyHC
- _swift_allocateGenericClassMetadata
- _swift_checkMetadataState
- _swift_getGenericMetadata
- _swift_initClassMetadata2
- _swift_isaMask
- _symbolic B0
- _symbolic B1
- _symbolic G0R0_
- _symbolic G0R1_
- _symbolic _____yxG 11MediaDevice32_SMCBridgeExtensionConfigurationC
- _symbolic _____yxGSgXw 11MediaDevice32_SMCBridgeExtensionConfigurationC
- _symbolic _____yxGSgXwz_x_qd_______Rz_____Rd__r__lXX 11MediaDevice32_SMCBridgeExtensionConfigurationC AA0abD0P 5AVKit35AVPlaybackUserInterfaceControllableP
CStrings:
+ "Fallback title when the failing media device extension's display name is unavailable"
+ "Recovery suggestion shown when a media device extension operation fails"
+ "Title shown when a media device extension operation fails; the placeholder is the extension's display name"
+ "Unable to Connect"
+ "Unable to Connect with \""
+ "You can try again later."
+ "activateDeviceWithDescription:completionHandler:"
+ "deactivateDeviceWithDescription:completionHandler:"
+ "decreaseVolumeByCount:forDevice:completionHandler:"
+ "getVolumeForDevice:completionHandler:"
+ "increaseVolumeByCount:forDevice:completionHandler:"
+ "setVolume:forDevice:completionHandler:"
- "Authorization Failed"
- "Check network settings and try again."
- "Connection Failed"
- "Discovery Failed"
- "Explanation of why authorization to use the media device failed"
- "Explanation of why media device discovery failed"
- "Explanation of why the connection to the media device failed"
- "Explanation of why the media session failed on the device"
- "Explanation that the media device is currently in use by another session"
- "Help anchor for media device authorization failure errors"
- "Help anchor for media device connection failure errors"
- "Help anchor for media device discovery failure errors"
- "Help anchor for media device in use errors"
- "Help anchor for media device session failure errors"
- "Recovery suggestion when a connection to the media device fails"
- "Recovery suggestion when authorization to use the media device fails"
- "Recovery suggestion when media device discovery fails"
- "Recovery suggestion when the media device is occupied by another session"
- "Recovery suggestion when the media session fails on the device"
- "Stop any other actions on the device and try again."
- "The device is busy."
- "Title shown when device discovery could not be completed"
- "Title shown when the connection to the device could not be established"
- "Title shown when the media device is occupied by another session"
- "Title shown when the session fails for a media device"
- "Title shown when the user is not authorized to use the media device"
- "authorizationFailed_failureReason"
- "authorizationFailed_helpAnchor"
- "authorizationFailed_recoverySuggestion"
- "connectionFailed_failureReason"
- "connectionFailed_helpAnchor"
- "deviceInUse_helpAnchor"
- "discoveryFailed_failureReason"
- "discoveryFailed_helpAnchor"
- "sessionFailed_failureReason"
- "sessionFailed_helpAnchor"
- "sessionFailed_recoverySuggestion"
```
