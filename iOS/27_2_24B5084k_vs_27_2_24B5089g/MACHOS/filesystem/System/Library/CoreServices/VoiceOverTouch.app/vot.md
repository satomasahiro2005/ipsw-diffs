## vot

> `/System/Library/CoreServices/VoiceOverTouch.app/vot`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1838b4` | `0x184584` | **`+0xcd0`** |
| `__TEXT.__cstring` | `0xff83` | `0x1014d` | **`+0x1ca`** |
| `__TEXT.__objc_methname` | `0x38b38` | `0x38cd8` | **`+0x1a0`** |
| `__DATA_CONST.__cfstring` | `0xe920` | `0xea60` | **`+0x140`** |
| `__TEXT.__objc_stubs` | `0x2a900` | `0x2a9e0` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0xa55d` | `0xa5e7` | **`+0x8a`** |
| `__TEXT.__objc_methlist` | `0x1177c` | `0x117dc` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0xca28` | `0xca80` | **`+0x58`** |
| `__DATA.__objc_const` | `0x147c0` | `0x147f0` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x26d8` | `0x26e8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4b10` | `0x4b20` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2ec8` | `0x2ed0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x155c` | `0x1560` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
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
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2482.13.0.0.0
+2482.13.1.0.0

-  Functions: 7255
-  Symbols:   2347
-  CStrings:  12525
+  Functions: 7263
+  Symbols:   2349
+  CStrings:  12551
Symbols:
+ _kVOTEventCommandOutputCurrentElement
+ _kVOTEventCommandReconnectBrailleDisplays
CStrings:
+ "ALERT-DECISION"
+ "APP-EVENT:alert"
+ "BSI-KBD _querySuggestions: skipped, secure text input"
+ "BrailleDisplayEmergencyScanTriggered"
+ "FIRST-RESPONDER-MOVE"
+ "Home gesture detected. isLocked: %@"
+ "LabelElement"
+ "NEXT-ELEMENT-ARMED"
+ "T@\"VOTBrailleGestureSpellingSuggestionHandler\",&,N,V_spellingSuggestionHandler"
+ "TwoFingerDoubleTapAndHold"
+ "Zone-filtering user swipe navigation (zone=%ld)"
+ "_focusDebugArmedTargetDescription"
+ "_handleOutputCurrentElement:"
+ "_handleReconnectBrailleDisplays:"
+ "_isSecureTextInput"
+ "_nextElementToFocusArmTime"
+ "_twoFingerTapAndHoldLabelsElement"
+ "_userNavigationMayCrossFocusZones"
+ "app=%@"
+ "armed=none"
+ "armed={%@} armedAgo=%.3f"
+ "braille.display.reconnection.triggered"
+ "editing=%d nativeFocus=%d %@"
+ "has_element=%@ %@"
+ "new_in_alert=%d cur_in_alert=%d cur_is_first_responder=%d appFirstResponder={%@} afr_in_alert=%d afr_accessible=%d hadData=%d"
+ "outputLatency"
+ "reason=%@ was_valid=%d cur_native_focus=%d cur_editing=%d cur_is_first_responder=%d armedAgo=%.3f"
+ "reason=%@ was_valid=%d same_app=%d cur_native_focus=%d cur_editing=%d cur_is_first_responder=%d armedAgo=%.3f"
+ "replacing=%@"
+ "setSpellingSuggestionHandler:"
+ "spellingSuggestionHandler"
+ "unlockDevice"
+ "\xb1"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xa1"
- "TwoFingerSingleTapAndHold"
- "_accessibilityViewIsVisible"
- "has_element=NO"
- "has_element=YES"
- "reason=%@ was_valid=%d"
- "reason=%@ was_valid=%d same_app=%d"
- "\xc1"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\x91"
```
