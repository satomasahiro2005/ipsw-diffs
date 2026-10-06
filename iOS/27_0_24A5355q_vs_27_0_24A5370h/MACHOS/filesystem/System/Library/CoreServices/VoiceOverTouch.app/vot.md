## vot

> `/System/Library/CoreServices/VoiceOverTouch.app/vot`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16b540` | `0x16e8f0` | **`+0x33b0`** |
| `__TEXT.__objc_methname` | `0x368e8` | `0x36e78` | **`+0x590`** |
| `__TEXT.__objc_stubs` | `0x29300` | `0x29760` | **`+0x460`** |
| `__TEXT.__oslogstring` | `0x928b` | `0x9591` | **`+0x306`** |
| `__TEXT.__objc_methlist` | `0x110f4` | `0x1125c` | **`+0x168`** |
| `__DATA.__objc_const` | `0x14548` | `0x146a0` | **`+0x158`** |
| `__DATA_CONST.__const` | `0x58c0` | `0x5a00` | **`+0x140`** |
| `__DATA.__objc_selrefs` | `0xc408` | `0xc520` | **`+0x118`** |
| `__TEXT.__objc_methtype` | `0x4e3f` | `0x4ed3` | **`+0x94`** |
| `__DATA.__data` | `0x2320` | `0x23b0` | **`+0x90`** |
| `__TEXT.__gcc_except_tab` | `0x2d14` | `0x2d98` | **`+0x84`** |
| `__TEXT.__unwind_info` | `0x4888` | `0x48f0` | **`+0x68`** |
| `__TEXT.__swift5_capture` | `0x67c` | `0x6cc` | **`+0x50`** |
| `__TEXT.__cstring` | `0xf600` | `0xf647` | **`+0x47`** |
| `__DATA_CONST.__objc_intobj` | `0x1488` | `0x14b8` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x3ac0` | `0x3af0` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0xe100` | `0xe120` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2540` | `0x2560` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x14cc` | `0x14e8` | **`+0x1c`** |
| `__TEXT.__objc_classname` | `0x12c4` | `0x12e0` | **`+0x1c`** |
| `__DATA_CONST.__auth_got` | `0x1d70` | `0x1d88` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x838` | `0x848` | **`+0x10`** |
| `__TEXT.__const` | `0x1b20` | `0x1b30` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x17d8` | `0x17c8` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x410` | `0x418` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x198` | `0x1a0` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x40` | `0x48` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0xc26` | `0xc2e` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2467.1.2.0.0
+2470.0.0.0.0

-  Functions: 7020
-  Symbols:   2271
-  CStrings:  12072
+  Functions: 7065
+  Symbols:   2279
+  CStrings:  12141
Symbols:
+ _$s12TextToSpeech9TTSMarkupO8SentenceV7contentAA0dC0_pSgvg
+ _$s12TextToSpeech9TTSMarkupO8SentenceVMn
+ _$sSS9hasPrefixySbSSF
+ _$sSa12TextToSpeechAA09TTSMarkupC0_pRszlEyAaB_pSicis
+ _OBJC_CLASS_$_AFDictationSecureTouchAuthenticator
+ _OBJC_CLASS_$_AFPreferences
+ _OBJC_CLASS_$_NSXPCInterface
+ _OBJC_CLASS_$_TIKeyboardCandidateSingle
CStrings:
+ "-[VOTElementManager _setCurrentElement:isProtectedApp:shouldResetTextSelection:shouldResetCharacterRange:ignoreIsAccessibilityElementCheck:shouldSetBrailleElement:userInitiated:]"
+ "@40@0:8@16@24q32"
+ "@?24@0:8@?16"
+ "B48@0:8@16B24B28B32B36B40B44"
+ "BSI-KBD _querySuggestions: before=\"%{private}@\" marked=\"%{private}@\" buf=%ld"
+ "BSI-KBD applyAutoCorrection: bufferLength=%lu input=\"%{private}@\" correction=\"%{private}@\""
+ "BSI-KBD applySelectedSuggestion: bufferLength=%lu input=\"%{private}@\" suggestion=\"%{private}@\""
+ "Discarding candidate (zone rules): cur=%ld cand=%ld"
+ "Discarding post-alert recovery candidate (zone rules): cur=%ld cand=%ld"
+ "Discarding screen-change candidate (zone rules): cur=%ld cand=%ld"
+ "Dropping event %{public}@ due to MultiStroke state"
+ "Failed to obtain authentication message for dictation: %{public}@"
+ "Fetch result rejected (zone rules): cur=%ld cand=%ld"
+ "First-element-in-app rejected (zone rules): cur=%ld cand=%ld"
+ "Focus zone change: %ld -> %ld (user_initiated=%d banner=%d)"
+ "Handwriting state -> MultiStroke"
+ "Multi-finger gesture during handwriting; flushing recognition (state=%d)"
+ "Navigation refused (zone rules): cur=%ld cand=%ld"
+ "Not moving focus for layout change because the user interacted recently and the element still exists{%@}"
+ "Not moving focus for screen change because the user interacted recently and the element still exists{%@}"
+ "Realtime navigation refused (zone rules): cur=%ld cand=%ld"
+ "Rejecting layout-change moveToElement (zone rules): cur=%ld cand=%ld"
+ "Rejecting screen-change newElement (zone rules): cur=%ld cand=%ld"
+ "Sonar candidate rejected (zone rules): cur=%ld cand=%ld"
+ "T@\"NSArray\",&,N,V_emojiResult"
+ "T@\"NSArray\",R,N,V_customRotorActionCategories"
+ "T@\"NSString\",R,N,V_input"
+ "TB,N,V_emojiFired"
+ "TIEmojiAlternativesProtocol"
+ "Td,N,V_lastUserNavigationTime"
+ "_currentHostingDisplayID"
+ "_currentZone"
+ "_emojiConnection"
+ "_emojiFired"
+ "_emojiResult"
+ "_handleDisplayContextDidChange:"
+ "_handleEmojiResult:forPending:"
+ "_handlePasscodeSuccess"
+ "_handleSingleLetterQuickNavCallback:"
+ "_handleWordBreak:trailing:"
+ "_hostingDisplayID"
+ "_input"
+ "_isNonUserInitiatedMovementAllowedTo:"
+ "_isNonUserInitiatedMovementAllowedTo:fromZone:"
+ "_isPendingReady:"
+ "_lastSingleLetterQuickNavEnabledState"
+ "_lastUserNavigationTime"
+ "_parseSuggestionsFromList:markedString:emojiAlternatives:"
+ "_pushTypingPropertiesToTranslator"
+ "_rotatedPointForRawLocation:displayID:"
+ "_rotorSelectedCustomActionCategoryFrom:"
+ "_setCurrentElement:isProtectedApp:shouldResetTextSelection:shouldResetCharacterRange:ignoreIsAccessibilityElementCheck:shouldSetBrailleElement:userInitiated:"
+ "_setCurrentElement:userInitiated:"
+ "_zoneFilteredMatchBlock:"
+ "alternativesForText:completionHandler:"
+ "applyAutoCorrectionForResponder:bufferLength:"
+ "applySelectedSuggestionForResponder:trailingWhitespace:bufferLength:"
+ "candidateWithCandidate:forInput:"
+ "com.apple.TextInput.rdt"
+ "currentPhysicalOrientation"
+ "customRotorActionCategories"
+ "emojiFired"
+ "emojiResult"
+ "enableDictationSecureTouch"
+ "firstRotorElementDescendingIntoRemoteFrameForSystemType:direction:"
+ "focusZone"
+ "generateEmojiInProcess"
+ "handleHostingDisplayChanged:"
+ "input"
+ "interfaceWithProtocol:"
+ "lastUserNavigationTime"
+ "remoteObjectProxyWithErrorHandler:"
+ "requestAuthenticationMessageForClientVersionedPID:completionBlock:"
+ "setEmojiFired:"
+ "setEmojiResult:"
+ "setLastUserNavigationTime:"
+ "setRemoteObjectInterface:"
+ "sharedPreferences"
+ "updateForActiveLocaleIdentifiers:"
+ "updateKeyboardType:appIdentifier:"
+ "v24@?0@\"NSString\"8@\"NSArray\"16"
+ "v32@0:8@\"NSString\"16@?<v@?@\"NSString\"@\"NSArray\">24"
+ "v32@0:8Q16@\"NSString\"24"
+ "v32@0:8Q16@24"
+ "\xc1"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xd1"
- "-[VOTElementManager _setCurrentElement:isProtectedApp:shouldResetTextSelection:shouldResetCharacterRange:ignoreIsAccessibilityElementCheck:shouldSetBrailleElement:]"
- "BSI-KBD _querySuggestions: before=\"%{private}@\" marked=\"%{private}@\" buf=%ld composingWordLength=%ld"
- "BSI-KBD applyAutoCorrection: composingWordLength=%lu correction=\"%{private}@\""
- "BSI-KBD applySelectedSuggestion: composingWordLength=%lu suggestion=\"%{private}@\""
- "Not moving focus for layout change because we touched recently on an element and it still exists{%@}"
- "Not moving focus for screen change because we touched recently on an element and it still exists{%@}"
- "Rejecting layout change move-to element because it would pull focus from app into jindo"
- "_composingWordLength"
- "_handleWordBreak:includeSpace:"
- "_parseSuggestionsFromList:markedString:"
- "applyAutoCorrectionForResponder:"
- "applySelectedSuggestionForResponder:trailingWhitespace:"
- "initializing gesture repo with: %@"
- "setComposingWordLength:"
- "tapTotalFingerCount"
- "\xb1"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xc1"
```
