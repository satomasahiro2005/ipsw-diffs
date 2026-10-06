## LiveSpeechUIService

> `/System/Library/AccessibilityBundles/LiveSpeechUIService.axuiservice/LiveSpeechUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb67b8` | `0xb9748` | **`+0x2f90`** |
| `__TEXT.__oslogstring` | `0x1f4f` | `0x24cf` | **`+0x580`** |
| `__TEXT.__swift5_typeref` | `0x13728` | `0x134cc` | **`-0x25c`** |
| `__TEXT.__objc_stubs` | `0x1b80` | `0x1cc0` | **`+0x140`** |
| `__TEXT.__objc_methname` | `0x4469` | `0x4579` | **`+0x110`** |
| `__DATA.__data` | `0x4958` | `0x4a10` | **`+0xb8`** |
| `__DATA.__objc_selrefs` | `0xe10` | `0xe70` | **`+0x60`** |
| `__TEXT.__cstring` | `0x1cc5` | `0x1d15` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x42d0` | `0x4310` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xd98` | `0xdc8` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x10ec` | `0x1114` | **`+0x28`** |
| `__DATA.__objc_const` | `0x26e8` | `0x26c8` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x3960` | `0x3980` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1cbf` | `0x1cdf` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0xf0` | `0x104` | **`+0x14`** |
| `__DATA.__bss` | `0x4928` | `0x4918` | **`-0x10`** |
| `__DATA.__objc_data` | `0x1930` | `0x1920` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x1cc0` | `0x1cd0` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x2474` | `0x2480` | **`+0xc`** |
| `__TEXT.__swift5_fieldmd` | `0x18a4` | `0x18b0` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0xcf0` | `0xcf8` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x1e54` | `0x1e5c` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xe70` | `0xe78` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x24f8` | `0x24f0` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x178` | `0x17c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

-  Functions: 3439
-  Symbols:   405
-  CStrings:  1144
+  Functions: 3450
+  Symbols:   408
+  CStrings:  1168
Symbols:
+ _AVSystemController_CallIsActive
+ _AVSystemController_CallIsActiveDidChangeNotification
+ _AXAIWhiteGloveLoggingEnabled
+ _OBJC_CLASS_$_AVSystemController
- __AXSLiveTranscriptionSetEnabled
CStrings:
+ "AVSystemController CallIsActive changed: %{bool}d"
+ "AXLSTextEntryField"
+ "attributeForKey:"
+ "avSystemCallActive"
+ "frame"
+ "handleAVSystemCallIsActiveChanged:"
+ "initializeViewFromSavedUIState"
+ "isAppSwitcherVisible"
+ "isControlCenterVisible"
+ "isFirstResponder"
+ "isNotificationCenterVisible"
+ "kAXUILiveSpeechSceneClientIdentifier"
+ "rdar://134841355 keyboardDidShow observer fired viewFrame=%{public}s superviewClass=%{public}s windowLevel=%{public}s"
+ "rdar://134841355 restoreKeyboardFocus becomeFirstResponder returned %{bool,public}d"
+ "rdar://134841355 restoreKeyboardFocus enter inputMode=%{public}s presentTextField=%{bool,public}d hasWindow=%{bool,public}d"
+ "rdar://134841355 restoreKeyboardFocus found candidate class=%{public}s canBecomeFirstResponder=%{bool,public}d isFirstResponder=%{bool,public}d"
+ "rdar://134841355 restoreKeyboardFocus no UITextInput candidate found; skipping becomeFirstResponder"
+ "rdar://134841355 systemOverlay event type=%{public}s isVisible=%{bool,public}d inputMode=%{public}s presentTextField=%{bool,public}d"
+ "rdar://134841355 viewDidAppear animated=%{bool,public}d inputMode=%{public}s presentTextField=%{bool,public}d isHUDVisible=%{bool,public}d windowLevel=%{public}s"
+ "rdar://134841355 viewDidLoad displayID=%{public}u inputMode=%{public}s presentTextField=%{bool,public}d willBringToFront=%{bool,public}d"
+ "rdar://134841355 viewDidLoad liveSpeechViewToFront callback ran superviewClass=%{public}s windowLevel=%{public}s"
+ "rdar://134841355 viewWillTransition size=%{public}s shouldRestoreFocus=%{bool,public}d inputMode=%{public}s presentTextField=%{bool,public}d"
+ "setAccessibilityIdentifier:"
+ "setActiveSceneTrackingEnabled:forSceneClientIdentifier:"
+ "viewIfLoaded"
+ "window"
+ "windowLevel"
- "AppleLanguagePreferencesChangedNotification"
- "languageChanged"
- "lastKnownLanguage"
```
