## HearingUI

> `/System/Library/PrivateFrameworks/HearingUI.framework/HearingUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a540` | `0x5aa3c` | **`+0x4fc`** |
| `__TEXT.__oslogstring` | `0x11f9` | `0x1508` | **`+0x30f`** |
| `__TEXT.__const` | `0x2638` | `0x2658` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xa2c` | `0xa44` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x14b8` | `0x14c8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xfe8` | `0xff0` | **`+0x8`** |

### Other Changes

```diff

-536.0.0.0.0
+539.1.0.0.0

-  Symbols:   2731
-  CStrings:  492
+  Symbols:   2732
+  CStrings:  497
Symbols:
+ _AXAIWhiteGloveLoggingEnabled
Functions:
~ ___86-[HUICCMenuCheckmarkView personalAudioToggleBlockForType:withYodelEnabled:andAddress:]_block_invoke : 404 -> 368
~ -[HACCShortcutViewController updateHeight] : 468 -> 684
~ -[HACCShortcutViewController moduleHeight] : 200 -> 488
~ -[HACCShortcutViewController controlDidActivate:] : 1940 -> 2144
~ ___42-[HACCLiveListenButton subscribeListeners]_block_invoke_2 : 488 -> 800
~ ___42-[HACCLiveListenButton subscribeListeners]_block_invoke_2.444 -> ___42-[HACCLiveListenButton subscribeListeners]_block_invoke_2.450 : 276 -> 568
CStrings:
+ "rdar://148155597 HACCLiveListenButton stateChange (LiveListenControls FF path) oldState=%ld newState=%ld isListening=%d isPlayingBack=%d frame={%f,%f,%f,%f} superview=%{public}@"
+ "rdar://148155597 HACCLiveListenButton stateChange (legacy path) oldIsListening=%d newIsListening=%d frame={%f,%f,%f,%f} superview=%{public}@"
+ "rdar://148155597 HACCShortcutViewController controlDidActivate LiveListen wasOn=%d moduleHeight=%f mainModuleOriginY=%f controlFrame={%f,%f,%f,%f}"
+ "rdar://148155597 HACCShortcutViewController moduleHeight viewBounds={%f,%f} screenH=%f _moduleHeight=%f top=%f maxHeight=%f returnedHeight=%f mainModuleOriginY=%f"
+ "rdar://148155597 HACCShortcutViewController updateHeight viewBounds={%f,%f} computedMaxY=%f moduleHeight=%f mainModuleOriginY=%f stackFrame={%f,%f,%f,%f}"
```
