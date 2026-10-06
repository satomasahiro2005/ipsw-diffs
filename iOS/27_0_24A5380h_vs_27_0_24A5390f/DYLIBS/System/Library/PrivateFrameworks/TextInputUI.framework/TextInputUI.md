## TextInputUI

> `/System/Library/PrivateFrameworks/TextInputUI.framework/TextInputUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12d03c` | `0x130278` | **`+0x323c`** |
| `__AUTH_CONST.__objc_const` | `0x18d48` | `0x19260` | **`+0x518`** |
| `__TEXT.__objc_methlist` | `0xf7f4` | `0xfb6c` | **`+0x378`** |
| `__DATA_CONST.__objc_selrefs` | `0x9e68` | `0xa0d0` | **`+0x268`** |
| `__TEXT.__cstring` | `0xdabf` | `0xdc7c` | **`+0x1bd`** |
| `__AUTH_CONST.__cfstring` | `0xe560` | `0xe700` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x5b1f` | `0x5cb4` | **`+0x195`** |
| `__TEXT.__dlopen_cstrs` | `0x315` | `0x406` | **`+0xf1`** |
| `__DATA_CONST.__const` | `0x7930` | `0x7a18` | **`+0xe8`** |
| `__AUTH.__objc_data` | `0x3888` | `0x3930` | **`+0xa8`** |
| `__AUTH_CONST.__const` | `0x2ac8` | `0x2b68` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x40c0` | `0x4160` | **`+0xa0`** |
| `__DATA.__bss` | `0x2d50` | `0x2dc0` | **`+0x70`** |
| `__DATA.__data` | `0x27e8` | `0x2848` | **`+0x60`** |
| `__DATA_CONST.__objc_arraydata` | `0x9b0` | `0xa08` | **`+0x58`** |
| `__DATA.__objc_ivar` | `0x117c` | `0x11c8` | **`+0x4c`** |
| `__AUTH_CONST.__objc_intobj` | `0x3c0` | `0x3f0` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x1b98` | `0x1bb0` | **`+0x18`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x240` | `0x258` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x450` | `0x468` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x6e8` | `0x6f8` | **`+0x10`** |
| `__TEXT.__const` | `0x3620` | `0x3630` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x14b0` | `0x14b8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x268` | `0x270` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x17b8` | `0x17c0` | **`+0x8`** |
| `__TEXT.__ustring` | `0x254` | `0x258` | **`+0x4`** |

### Other Changes

```diff

-9127.0.75.1.101
+9127.0.79.0.0

-  Functions: 6698
-  Symbols:   10525
-  CStrings:  2674
+  Functions: 6781
+  Symbols:   10661
+  CStrings:  2704
Symbols:
+ +[TUITestSupport sharedInstance]
+ -[TUIFlickVariantCell initWithFrame:string:annotation:traits:]
+ -[TUIInputSession localizedAppName]
+ -[TUIInputSessionManager localizedNameForHostAuditToken:]
+ -[TUIKeyboardHitDebugOverlay .cxx_destruct]
+ -[TUIKeyboardHitDebugOverlay buildLayers]
+ -[TUIKeyboardHitDebugOverlay chargeToken]
+ -[TUIKeyboardHitDebugOverlay dealloc]
+ -[TUIKeyboardHitDebugOverlay decisionToken]
+ -[TUIKeyboardHitDebugOverlay drawKeyFramesAndCentersFromSource:]
+ -[TUIKeyboardHitDebugOverlay drawTapDecisionFromSource:]
+ -[TUIKeyboardHitDebugOverlay effectiveHitCenterLayer]
+ -[TUIKeyboardHitDebugOverlay effectiveHitCenterOffset]
+ -[TUIKeyboardHitDebugOverlay effectiveHitRadius]
+ -[TUIKeyboardHitDebugOverlay engineOverrodeTappedKey]
+ -[TUIKeyboardHitDebugOverlay geometrySource]
+ -[TUIKeyboardHitDebugOverlay hasEffectiveHitCenter]
+ -[TUIKeyboardHitDebugOverlay hasTapDecision]
+ -[TUIKeyboardHitDebugOverlay hitKeyReason]
+ -[TUIKeyboardHitDebugOverlay initWithFrame:]
+ -[TUIKeyboardHitDebugOverlay isHitTestCorrection]
+ -[TUIKeyboardHitDebugOverlay mostLikelyKeyCode]
+ -[TUIKeyboardHitDebugOverlay mostLikelyKeyLayer]
+ -[TUIKeyboardHitDebugOverlay physicallyTappedKeyCode]
+ -[TUIKeyboardHitDebugOverlay physicallyTappedKeyLayer]
+ -[TUIKeyboardHitDebugOverlay refresh]
+ -[TUIKeyboardHitDebugOverlay setChargeToken:]
+ -[TUIKeyboardHitDebugOverlay setDecisionToken:]
+ -[TUIKeyboardHitDebugOverlay setEffectiveHitCenterLayer:]
+ -[TUIKeyboardHitDebugOverlay setEffectiveHitCenterOffset:]
+ -[TUIKeyboardHitDebugOverlay setEffectiveHitRadius:]
+ -[TUIKeyboardHitDebugOverlay setEngineOverrodeTappedKey:]
+ -[TUIKeyboardHitDebugOverlay setGeometrySource:]
+ -[TUIKeyboardHitDebugOverlay setHasEffectiveHitCenter:]
+ -[TUIKeyboardHitDebugOverlay setHasTapDecision:]
+ -[TUIKeyboardHitDebugOverlay setHitKeyReason:]
+ -[TUIKeyboardHitDebugOverlay setIsHitTestCorrection:]
+ -[TUIKeyboardHitDebugOverlay setMostLikelyKeyCode:]
+ -[TUIKeyboardHitDebugOverlay setMostLikelyKeyLayer:]
+ -[TUIKeyboardHitDebugOverlay setPhysicallyTappedKeyCode:]
+ -[TUIKeyboardHitDebugOverlay setPhysicallyTappedKeyLayer:]
+ -[TUIKeyboardHitDebugOverlay setVisibleKeyFramesLayer:]
+ -[TUIKeyboardHitDebugOverlay startObservingEngineChannels]
+ -[TUIKeyboardHitDebugOverlay stopObservingEngineChannels]
+ -[TUIKeyboardHitDebugOverlay visibleKeyFramesLayer]
+ -[TUIKeyplaneRow _needsFlexibleControlKeyPriorities]
+ -[TUIKeyplaneRow constraintsForCoreKeys:inRowGuide:matchingSizingGuide:splitIndex:]
+ -[TUIKeyplaneView _engineHitFrameForKeyView:]
+ -[TUIKeyplaneView _maximumHandwritingResizeOffset]
+ -[TUIKeyplaneView _updateHitDebugOverlay]
+ -[TUIKeyplaneView debugOverlayBounds]
+ -[TUIKeyplaneView debugOverlayHitFrameForKeyCode:]
+ -[TUIKeyplaneView debugOverlayIsAcceptOnHitKeyForKeyCode:]
+ -[TUIKeyplaneView debugOverlayKeyHitFrames]
+ -[TUIKeyplaneView hitDebugOverlay]
+ -[TUIKeyplaneView setHitDebugOverlay:]
+ -[TUIPasteboardItem linkPresentationThumbnailWithCompletion:]
+ -[TUIPasteboardItem thumbnailFromLinkPresentationData:completion:]
+ -[TUIPasteboardItem webURLFallbackThumbnailImage]
+ -[TUIRecentPasteCandidate initWithPasteboardName:pasteboardChangeCount:contentTitle:thumbnailImage:sourceApp:contentIdentifier:]
+ -[TUIRecentPasteCandidate pasteboardChangeCount]
+ -[TUIRecentPasteCandidate pasteboardName]
+ -[TUIRecentPasteCandidate setPasteboardChangeCount:]
+ -[TUIRecentPasteCandidate setPasteboardName:]
+ -[TUIRecentPasteGenerator quickCheckShouldGenerateCandidateForContext:]
+ -[TUIRecentPasteGenerator responderCanPerformPasteForContext:]
+ -[TUISmartActionGLPSearchCandidate _maskedValueForResult:]
+ -[TUISmartActionGLPSearchCandidate localizedAuthenticationReason]
+ -[TUITestSupport init]
+ -[TUITestSupport setTestApplicationType:]
+ -[TUITestSupport testApplicationType]
+ -[TUIVariantCell attributedKeycapStringForString:]
+ _LinkPresentationLibraryCore.frameworkLibrary
+ _OBJC_CLASS_$_TUIKeyboardHitDebugOverlay
+ _OBJC_CLASS_$_TUITestSupport
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._chargeToken
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._decisionToken
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._effectiveHitCenterLayer
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._effectiveHitCenterOffset
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._effectiveHitRadius
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._engineOverrodeTappedKey
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._geometrySource
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._hasEffectiveHitCenter
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._hasTapDecision
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._hitKeyReason
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._isHitTestCorrection
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._mostLikelyKeyCode
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._mostLikelyKeyLayer
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._physicallyTappedKeyCode
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._physicallyTappedKeyLayer
+ _OBJC_IVAR_$_TUIKeyboardHitDebugOverlay._visibleKeyFramesLayer
+ _OBJC_IVAR_$_TUIKeyplaneView._hitDebugOverlay
+ _OBJC_IVAR_$_TUIRecentPasteCandidate._pasteboardChangeCount
+ _OBJC_IVAR_$_TUIRecentPasteCandidate._pasteboardName
+ _OBJC_IVAR_$_TUITestSupport._testConversationType
+ _OBJC_METACLASS_$_TUIKeyboardHitDebugOverlay
+ _OBJC_METACLASS_$_TUITestSupport
+ _TIGetShowAllKeysDebugHitAreaValue.onceToken
+ _TIGetSplitHWRKeyboardEnabledValue.onceToken
+ _TUITestSupportLog
+ _TUITestSupportLog.log
+ _TUITestSupportLog.onceToken
+ __OBJC_$_CLASS_METHODS_TUITestSupport
+ __OBJC_$_INSTANCE_METHODS_TUIKeyboardHitDebugOverlay
+ __OBJC_$_INSTANCE_METHODS_TUITestSupport
+ __OBJC_$_INSTANCE_VARIABLES_TUIKeyboardHitDebugOverlay
+ __OBJC_$_INSTANCE_VARIABLES_TUITestSupport
+ __OBJC_$_PROP_LIST_TUIKeyboardHitDebugOverlay
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_TUIKeyboardHitDebugGeometrySource
+ __OBJC_$_PROTOCOL_METHOD_TYPES_TUIKeyboardHitDebugGeometrySource
+ __OBJC_$_PROTOCOL_REFS_TUIKeyboardHitDebugGeometrySource
+ __OBJC_CLASS_RO_$_TUIKeyboardHitDebugOverlay
+ __OBJC_CLASS_RO_$_TUITestSupport
+ __OBJC_LABEL_PROTOCOL_$_TUIKeyboardHitDebugGeometrySource
+ __OBJC_METACLASS_RO_$_TUIKeyboardHitDebugOverlay
+ __OBJC_METACLASS_RO_$_TUITestSupport
+ __OBJC_PROTOCOL_$_TUIKeyboardHitDebugGeometrySource
+ ___32+[TUITestSupport sharedInstance]_block_invoke
+ ___49-[TUIPasteboardItem webURLFallbackThumbnailImage]_block_invoke
+ ___58-[TUIKeyboardHitDebugOverlay startObservingEngineChannels]_block_invoke
+ ___58-[TUIKeyboardHitDebugOverlay startObservingEngineChannels]_block_invoke_2
+ ___58-[TUISmartActionGLPSearchCandidate _maskedValueForResult:]_block_invoke
+ ___61-[TUIPasteboardItem linkPresentationThumbnailWithCompletion:]_block_invoke
+ ___66-[TUIPasteboardItem thumbnailFromLinkPresentationData:completion:]_block_invoke
+ ___LinkPresentationLibraryCore_block_invoke
+ ___TIGetShowAllKeysDebugHitAreaValue_block_invoke
+ ___TIGetSplitHWRKeyboardEnabledValue_block_invoke
+ ___TUITestSupportLog_block_invoke
+ ___block_descriptor_40_8_32bs_e45_v24?0"<NSItemProviderReading>"8"NSError"16ls32l8
+ ___block_descriptor_40_8_32s_e52_v56?0"NSString"8{_NSRange=QQ}16{_NSRange=QQ}32^B48ls32l8
+ ___block_descriptor_40_8_32w_e8_v12?0i8lw32l8
+ ___block_descriptor_48_8_32s40bs_e17_v16?0"UIImage"8ls40l8s32l8
+ ___getLPLinkMetadataClass_block_invoke
+ ___getSTKGenerativeModelsAvailabilityClass_block_invoke
+ ___swift_closure_destructor.35Tm
+ _audit_stringLinkPresentation
+ _getLPLinkMetadataClass.softClass
+ _getSTKGenerativeModelsAvailabilityClass.softClass
+ _notify_cancel
+ _notify_get_state
+ _notify_register_dispatch
+ _sharedInstance.instance
+ _webURLFallbackThumbnailImage.fallbackImage
+ _webURLFallbackThumbnailImage.onceToken
- -[TUIKeyplaneRow constraintsForStringKeys:inRowGuide:matchingSizingGuide:splitIndex:]
- -[TUIRecentPasteCandidate initWithPasteboard:contentTitle:thumbnailImage:sourceApp:contentIdentifier:]
- -[TUIRecentPasteGenerator responderCanPerformPaste]
- -[TUISmartActionGLPSearchCandidate searchResults]
- -[TUIVariantCell attributedKeycapStringForString:withSymbolStyle:]
- _OBJC_IVAR_$_TUIRecentPasteCandidate._pasteboard
- _UIFontSystemFontDesignDefault
- ___swift_closure_destructor.34Tm
CStrings:
+ "4"
+ "Authenticate to Add"
+ "Belarusian"
+ "Dhivehi-QWERTY"
+ "Failed to decode LinkPresentation metadata: %{public}@"
+ "Failed to load LinkPresentation preview image: %{public}@"
+ "Jawi"
+ "Kurdish-Sorani"
+ "LPLinkMetadata"
+ "No session found for versionedPID: %@ (%@); cannot resolve localized name"
+ "Pashto"
+ "Persian"
+ "STKGenerativeModelsAvailability"
+ "Serbian-Cyrillic"
+ "ShowAllKeysDebugHitArea"
+ "Sindhi"
+ "SplitHWRKeyboardEnabled"
+ "TestSupport"
+ "Uzbek-Arabic"
+ "Web URL thumbnail: no preview image; using safari.fill fallback glyph"
+ "Web URL thumbnail: returning rich-link preview image"
+ "canInsertGenmoji"
+ "com.apple.keyboard.debugCharge"
+ "com.apple.keyboard.debugDecision"
+ "com.apple.linkpresentation.metadata"
+ "safari.fill"
+ "setTestApplicationType: called from non-InputUI process — ignoring"
+ "softlink:r:path:/System/Library/Frameworks/LinkPresentation.framework/LinkPresentation"
+ "supportsGenmojiCreation"
+ "testApplicationType = %ld"
+ "v24@?0@\"<NSItemProviderReading>\"8@\"NSError\"16"
+ "v56@?0@\"NSString\"8{_NSRange=QQ}16{_NSRange=QQ}32^B48"
+ "•"
- "AUTOFILL_FROM_APP_NAME"
- "Authenticate to view suggestion"
- "value"
```
