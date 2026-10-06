## SpeakThis

> `/System/Library/AccessibilityBundles/SpeakThis.axuiservice/SpeakThis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a750` | `0x1aadc` | **`+0x38c`** |
| `__TEXT.__oslogstring` | `0x11e2` | `0x1319` | **`+0x137`** |
| `__TEXT.__objc_methname` | `0x5e65` | `0x5f65` | **`+0x100`** |
| `__TEXT.__objc_stubs` | `0x4ec0` | `0x4f20` | **`+0x60`** |
| `__DATA.__objc_const` | `0x2180` | `0x21d0` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x1b9c` | `0x1bcc` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x17b0` | `0x17d0` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x780` | `0x760` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x6f8` | `0x710` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0xc79` | `0xc8a` | **`+0x11`** |
| `__DATA_CONST.__got` | `0x368` | `0x378` | **`+0x10`** |
| `__TEXT.__const` | `0x260` | `0x270` | **`+0x10`** |
| `__TEXT.__cstring` | `0x896` | `0x88d` | **`-0x9`** |
| `__DATA.__objc_ivar` | `0x1e4` | `0x1ec` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0

-  Functions: 619
-  Symbols:   339
-  CStrings:  1303
+  Functions: 623
+  Symbols:   341
+  CStrings:  1314
Symbols:
+ _UISceneDidActivateNotification
+ _UISceneDidEnterBackgroundNotification
CStrings:
+ "@\"UIWindowScene\""
+ "External display connected: speakThisEnabled:%d showSpeechController:%d wantsControllerVisible:%d"
+ "Gesture: setting _wantsControllerVisible=YES, loading speak UI at app point"
+ "Scene connected: %p sceneIdentifier:%@ activationState:%ld speakThisEnabled:%d showSpeechController:%d wantsControllerVisible:%d"
+ "SpeakScreen active embedded scene changed to %@"
+ "T@\"UIWindowScene\",W,N,V_lastActiveEmbeddedScene"
+ "_addContentViewControllerForWindowScene: called with no scene identifier (windowScene:%p)"
+ "_isEmbeddedScreen"
+ "_lastActiveEmbeddedScene"
+ "_newOverlayViewController"
+ "_pendingViewController"
+ "_preferredActiveEmbeddedScene"
+ "_sceneActivationStateDidChange:"
+ "lastActiveEmbeddedScene"
+ "requestScenesForService:atPreferredSceneLevel:forSceneClientIdentifier:"
+ "setLastActiveEmbeddedScene:"
+ "\xf0\xf0\xa1"
- "External display connected"
- "MAIN-DISPLAY"
- "Scene connected: %p sceneIdentifier:%@ activationState:%ld speakThisEnabled:%d showSpeechController:%d"
- "connectedScenes"
- "isMainDisplay"
- "windowSceneIdentifierForWindowScene:"
```
