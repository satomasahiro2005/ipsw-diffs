## HomeAutomationInternal

> `/System/Library/PrivateFrameworks/HomeAutomationInternal.framework/HomeAutomationInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x51b5a0` | `0x5205b4` | **`+0x5014`** |
| `__TEXT.__cstring` | `0x3914a` | `0x395da` | **`+0x490`** |
| `__TEXT.__eh_frame` | `0x1fbf4` | `0x1fddc` | **`+0x1e8`** |
| `__AUTH.__data` | `0x18970` | `0x18b38` | **`+0x1c8`** |
| `__AUTH_CONST.__objc_const` | `0x14968` | `0x14b18` | **`+0x1b0`** |
| `__AUTH_CONST.__const` | `0x1ff20` | `0x20038` | **`+0x118`** |
| `__TEXT.__swift5_typeref` | `0x9176` | `0x9274` | **`+0xfe`** |
| `__TEXT.__const` | `0x296b0` | `0x297a0` | **`+0xf0`** |
| `__TEXT.__constg_swiftt` | `0x14524` | `0x14614` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0xdbe0` | `0xdc80` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x1c78` | `0x1cdc` | **`+0x64`** |
| `__DATA.__data` | `0x7288` | `0x72e0` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x1a48` | `0x1a98` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0xd96c` | `0xd9bc` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0xb8da` | `0xb8fa` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0xbf0` | `0xc00` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x1a80` | `0x1a90` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x12a8` | `0x12b4` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x3128` | `0x3130` | **`+0x8`** |
| `__DATA.__common` | `0xae8` | `0xaf0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xc3c` | `0xc44` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x15d8` | `0x15e0` | **`+0x8`** |

### Other Changes

```diff

-3600.27.2.0.0
+3600.27.3.0.0

+  - /System/Library/PrivateFrameworks/IntelligentRouting.framework/IntelligentRouting

-  Functions: 17198
-  Symbols:   5443
-  CStrings:  5257
+  Functions: 17245
+  Symbols:   5472
+  CStrings:  5275
Symbols:
+ _IRHomeSuggestionPresentationModeAuto
+ _IRHomeSuggestionPresentationModeExplicit
+ _IRHomeSuggestionPresentationModeImplicit
+ _OBJC_CLASS_$_IRConfiguration
+ _OBJC_CLASS_$_IRHomeEvent
+ _OBJC_CLASS_$_IRHomeSuggestion
+ _OBJC_CLASS_$_IRHomeSuggestionTarget
+ _OBJC_CLASS_$_IRServiceToken
+ _OBJC_CLASS_$_IRSession
+ __DATA__TtC22HomeAutomationInternal16IRSessionManager
+ __DATA__TtC22HomeAutomationInternal26RoomAwareCandidateResolver
+ __IVARS__TtC22HomeAutomationInternal16IRSessionManager
+ __IVARS__TtC22HomeAutomationInternal26RoomAwareCandidateResolver
+ __METACLASS_DATA__TtC22HomeAutomationInternal16IRSessionManager
+ __METACLASS_DATA__TtC22HomeAutomationInternal26RoomAwareCandidateResolver
+ _symbolic SaySo16IRHomeSuggestionCGSg
+ _symbolic Say_____G 22HomeAutomationInternal4RoomC
+ _symbolic SccySo9IRContextC______pG s5ErrorP
+ _symbolic ShySo22IRHomeSuggestionTargetCG
+ _symbolic Shy_____G 22HomeAutomationInternal4RoomC
+ _symbolic So11IRHomeEventCSg
+ _symbolic So9IRContextCSg
+ _symbolic So9IRContextCSgz_Xx
+ _symbolic So9IRSessionC
+ _symbolic So9IRSessionCSg
+ _symbolic _____ 22HomeAutomationInternal16IRSessionManagerC
+ _symbolic _____ 22HomeAutomationInternal26RoomAwareCandidateResolverC
+ _symbolic _____ySo22IRHomeSuggestionTargetCG s11_SetStorageC
+ _symbolic _____y______G Sh5IndexV 22HomeAutomationInternal4RoomC
CStrings:
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriHomeAutomation/HomeAutomationInternal/Flow/Shared/RoomAwareCandidateResolver.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/SiriHomeAutomation/HomeAutomationInternal/Shared/Utilities/IRSessionManager.swift"
+ "Calling IRSession to resolve room"
+ "Closing IRSession"
+ "Could not resolve the room using room resolver"
+ "Created IRSession with IntelligentRouting."
+ "Created Service token for IRSession "
+ "Created Service token for IRSession token is nil."
+ "Donating to IRD event: "
+ "Error when calling IRSession to resolve room: "
+ "IRD recommended unique explicit room. Will need confirmation"
+ "Resolved room suggestions "
+ "User rejected the confirmation, should fallback: "
+ "Will disambiguate with multiple IRD recommended filters "
+ "Will skip disambiguation since auto room was resolved."
+ "Will skip disambiguation since implicit room was resolved."
+ "com.apple.HomeKit"
+ "requestContextSync(with:timeout:)"
```
