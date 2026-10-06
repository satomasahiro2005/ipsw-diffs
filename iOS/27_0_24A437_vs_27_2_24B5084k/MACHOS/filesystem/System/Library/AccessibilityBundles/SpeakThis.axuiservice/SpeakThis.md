## SpeakThis

> `/System/Library/AccessibilityBundles/SpeakThis.axuiservice/SpeakThis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1af4c` | `0x1b290` | **`+0x344`** |
| `__TEXT.__objc_methname` | `0x5f75` | `0x6097` | **`+0x122`** |
| `__TEXT.__objc_stubs` | `0x4f40` | `0x4fa0` | **`+0x60`** |
| `__DATA.__objc_const` | `0x2260` | `0x22b8` | **`+0x58`** |
| `__DATA_CONST.__const` | `0xa30` | `0xa88` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x1be4` | `0x1c34` | **`+0x50`** |
| `__TEXT.__cstring` | `0x8af` | `0x8fb` | **`+0x4c`** |
| `__TEXT.__oslogstring` | `0x137c` | `0x13b8` | **`+0x3c`** |
| `__DATA.__objc_selrefs` | `0x17e0` | `0x1810` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0xd30` | `0xd60` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x780` | `0x7a0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x6a8` | `0x6c0` | **`+0x18`** |
| `__DATA_CONST.__objc_arrayobj` | `0x30` | `0x48` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x718` | `0x730` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x380` | `0x390` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x50` | `0x60` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x4c` | `0x5c` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1ec` | `0x1f4` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x1b8` | `0x1bc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3240.9.0.0.0
+3245.7.1.0.0

-  Functions: 628
-  Symbols:   345
-  CStrings:  1320
+  Functions: 636
+  Symbols:   350
+  CStrings:  1332
Symbols:
+ _CFPreferencesAppSynchronize
+ _STSMessageReplyKeyPresentation
+ _kAXSAccessibilityPreferenceDomain
+ _swift_isEscapingClosureAtFileLocation
+ _swift_release_x24
+ _swift_release_x27
+ _swift_retain_x27
- _swift_release_x25
- _swift_retain_x25
CStrings:
+ "Scene connected: %p sceneIdentifier:%@ activationState:%ld speakThisEnabled:%d showSpeechController:%d wantsControllerVisible:%d requestedOverSPI:%d"
+ "Speech Controller collapsed changed: %d"
+ "SpeechControllerWindow"
+ "TB,N,V_speechControllerCollapsed"
+ "_controllerRequestedOverSPI"
+ "_handleSpeechControllerPresentation"
+ "_shouldHostControllerForConnectingScene"
+ "_speechControllerCollapsed"
+ "com.apple.accessibility.api"
+ "setAccessibilityIdentifier:"
+ "setSpeechControllerCollapsed:"
+ "speechControllerCollapsed"
+ "speechControllerCollapsedChanged:"
- "Scene connected: %p sceneIdentifier:%@ activationState:%ld speakThisEnabled:%d showSpeechController:%d wantsControllerVisible:%d"
```
