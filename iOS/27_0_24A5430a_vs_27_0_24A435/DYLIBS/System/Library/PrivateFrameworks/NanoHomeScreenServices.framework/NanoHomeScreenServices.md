## NanoHomeScreenServices

> `/System/Library/PrivateFrameworks/NanoHomeScreenServices.framework/NanoHomeScreenServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e20` | `0x5058` | **`+0x238`** |
| `__TEXT.__cstring` | `0x6ca` | `0x799` | **`+0xcf`** |
| `__AUTH_CONST.__cfstring` | `0x580` | `0x600` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x62c` | `0x654` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0xc0` | `0xe0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x260` | `0x280` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x4d8` | `0x4f0` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x900` | `0x910` | **`+0x10`** |
| `__DATA.__bss` | `0x8` | `0x18` | **`+0x10`** |

### Other Changes

```diff

-  Functions: 167
-  Symbols:   379
-  CStrings:  70
+  Functions: 172
+  Symbols:   387
+  CStrings:  74
Symbols:
+ -[NHSSPrivacyDefaults deviceSupportsInstantShazam]
+ -[NHSSSmartStackSuggestionDefaults didResurfaceSoundDetectionForInstantShazam]
+ -[NHSSSmartStackSuggestionDefaults setDidResurfaceSoundDetectionForInstantShazam:]
+ GCC_except_table47
+ GCC_except_table59
+ _MobileGestalt_get_current_device
+ _MobileGestalt_get_deviceSupportsAudioIntelligence
+ ___50-[NHSSPrivacyDefaults deviceSupportsInstantShazam]_block_invoke
+ _deviceSupportsInstantShazam.__isSupported
+ _deviceSupportsInstantShazam.onceToken
- GCC_except_table45
- GCC_except_table57
CStrings:
+ "Localizable-InstantShazam"
+ "PRIVACY_DEFAULTS_MICROPHONE_PERMISSION_ALERT_MESSAGE_INSTANT_SHAZAM"
+ "PRIVACY_DEFAULTS_MICROPHONE_PERMISSION_SWITCH_FOOTNOTE_INSTANT_SHAZAM"
+ "didResurfaceSoundDetectionForInstantShazam"
```
