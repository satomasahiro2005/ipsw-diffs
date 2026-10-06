## TextInputCore

> `/System/Library/PrivateFrameworks/TextInputCore.framework/TextInputCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x220b74` | `0x2221c8` | **`+0x1654`** |
| `__AUTH_CONST.__cfstring` | `0x137a0` | `0x13d60` | **`+0x5c0`** |
| `__TEXT.__ustring` | `0x51e` | `0x7d8` | **`+0x2ba`** |
| `__TEXT.__cstring` | `0x1c6fc` | `0x1c939` | **`+0x23d`** |
| `__AUTH.__objc_data` | `0x2210` | `0x2080` | **`-0x190`** |
| `__DATA_DIRTY.__objc_data` | `0x3160` | `0x32f0` | **`+0x190`** |
| `__AUTH_CONST.__const` | `0x8748` | `0x8850` | **`+0x108`** |
| `__AUTH_CONST.__objc_const` | `0x1a540` | `0x1a610` | **`+0xd0`** |
| `__DATA_CONST.__got` | `0x17a0` | `0x1868` | **`+0xc8`** |
| `__DATA_DIRTY.__bss` | `0xb98` | `0xc50` | **`+0xb8`** |
| `__TEXT.__unwind_info` | `0x6588` | `0x65f8` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x4ef0` | `0x4f58` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x9ff8` | `0xa048` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x10a58` | `0x10aa0` | **`+0x48`** |
| `__DATA.__bss` | `0x1f10` | `0x1ed0` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1ae0` | `0x1b00` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x390` | `0x3a8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x12a8` | `0x12c0` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x1038` | `0x1050` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x43e7` | `0x43e8` | **`+0x1`** |

### Other Changes

```diff

-3557.15.100.0.0
+3559.100.0.0.0

-  Functions: 10494
-  Symbols:   17339
-  CStrings:  4025
+  Functions: 10533
+  Symbols:   17412
+  CStrings:  4076
Symbols:
+ -[TIKeyboardInputManager(ZephyrEngineSpecializations) _publishDebugChargeForKeyCode:touchLocation:]
+ -[TIKeyboardInputManagerMecabra contextBeforeWithDesiredLength:]
+ -[TIKeyboardInputManagerMecabra onScreenContextForCandidates]
+ -[TIMecabraEnvironment onScreenContext]
+ -[TIMecabraEnvironment setOnScreenContext:]
+ -[TIMecabraEnvironmentContextWrapper setOnScreenStringContext:]
+ -[TIWordSearch setOnScreenContext:]
+ _CGRectIsEmpty
+ _OBJC_CLASS_$_NSDataDetector
+ _OBJC_IVAR_$_TIKeyboardInputManager._debugChargeBias
+ _OBJC_IVAR_$_TIKeyboardInputManager._debugChargeSigma
+ _OBJC_IVAR_$_TIMecabraEnvironment._onScreenContext
+ _OBJC_IVAR_$_TIStickerCandidateGenerator._admissionLock
+ _OBJC_IVAR_$_TIStickerCandidateGenerator._spotlightBackoffDeadlineNanos
+ _OBJC_IVAR_$_TIStickerCandidateGenerator._spotlightQueryInFlight
+ __ZL14TIIsPureDigitsP8NSString
+ __ZL17TICollectAllTextsRKNSt3__110shared_ptrI14TIScreenUINodeEEP14NSMutableArrayIP8NSStringE
+ __ZL17TIDeduplicatePairRKNSt3__110shared_ptrI14TIScreenUINodeEES4_
+ __ZL17TIPruneNoisyNodesRKNSt3__110shared_ptrI14TIScreenUINodeEE
+ __ZL20_TIPublishDebugStatePKcPiy
+ __ZL21libmecabraLibraryCorePPc
+ __ZL23TIDeduplicateSubstringsRKNSt3__110shared_ptrI14TIScreenUINodeEE
+ __ZL24TICollectDescendantNodesRKNSt3__110shared_ptrI14TIScreenUINodeEERNS_6vectorIS2_NS_9allocatorIS2_EEEE
+ __ZL24TINormalizeForComparisonP8NSString
+ __ZL27TIDeduplicateCollectionItemRKNSt3__110shared_ptrI14TIScreenUINodeEE
+ __ZL31TINormalizeScreenScrapingStringP8NSString
+ __ZL33TIHasVerticalScrollableDescendantRKNSt3__110shared_ptrI14TIScreenUINodeEE
+ __ZL42getMecabraContextSetStringContextSymbolLocv
+ __ZN2TI8Favonius10BeamSearch20choose_hit_test_nodeERKN3WTF6RefPtrINS0_10SearchNodeEEERKNS3_INS0_8KeyMatchEEES7_S7_PNS0_12HitKeyReasonE
+ __ZNK2TI8Favonius10BeamSearch14hit_key_reasonEv
+ __ZNK2TI8Favonius26FavoniusStrokeBuildManager21debug_last_touch_infoEv
+ __ZNSt3__120__shared_ptr_emplaceI14TIScreenUINodeNS_9allocatorIS1_EEE16__on_zero_sharedEv
+ __ZNSt3__120__shared_ptr_emplaceI14TIScreenUINodeNS_9allocatorIS1_EEE21__on_zero_shared_weakEv
+ __ZNSt3__120__shared_ptr_emplaceI14TIScreenUINodeNS_9allocatorIS1_EEED0Ev
+ __ZNSt3__120__shared_ptr_emplaceI14TIScreenUINodeNS_9allocatorIS1_EEED1Ev
+ __ZNSt3__16vectorINS_10shared_ptrI14TIScreenUINodeEENS_9allocatorIS3_EEE16__destroy_vectorclB9fon220106Ev
+ __ZNSt3__16vectorINS_10shared_ptrI14TIScreenUINodeEENS_9allocatorIS3_EEE20__throw_length_errorB9fon220106Ev
+ __ZNSt3__16vectorINS_10shared_ptrI14TIScreenUINodeEENS_9allocatorIS3_EEE24__emplace_back_slow_pathIJRKS3_EEEPS3_DpOT_
+ __ZNSt3__16vectorINS_10shared_ptrI14TIScreenUINodeEENS_9allocatorIS3_EEE5clearB9fon220106Ev
+ __ZNSt3__16vectorINS_10shared_ptrI14TIScreenUINodeEENS_9allocatorIS3_EEE9push_backB9fon220106ERKS3_
+ __ZTVNSt3__120__shared_ptr_emplaceI14TIScreenUINodeNS_9allocatorIS1_EEEE
+ __ZZ99-[TIKeyboardInputManager(ZephyrEngineSpecializations) _publishDebugChargeForKeyCode:touchLocation:]E11chargeToken
+ __ZZ99-[TIKeyboardInputManager(ZephyrEngineSpecializations) _publishDebugChargeForKeyCode:touchLocation:]E11decisionSeq
+ __ZZ99-[TIKeyboardInputManager(ZephyrEngineSpecializations) _publishDebugChargeForKeyCode:touchLocation:]E13decisionToken
+ __ZZ99-[TIKeyboardInputManager(ZephyrEngineSpecializations) _publishDebugChargeForKeyCode:touchLocation:]E9chargeSeq
+ __ZZL20TIIsSystemNoiseLabelP8NSStringE12dateDetector
+ __ZZL20TIIsSystemNoiseLabelP8NSStringE12onceTokenDay
+ __ZZL20TIIsSystemNoiseLabelP8NSStringE13exactNoiseSet
+ __ZZL20TIIsSystemNoiseLabelP8NSStringE13onceTokenTime
+ __ZZL20TIIsSystemNoiseLabelP8NSStringE13pureTimeRegex
+ __ZZL20TIIsSystemNoiseLabelP8NSStringE14onceTokenExact
+ __ZZL20TIIsSystemNoiseLabelP8NSStringE15onceTokenPrefix
+ __ZZL20TIIsSystemNoiseLabelP8NSStringE15prefixNoiseList
+ __ZZL20TIIsSystemNoiseLabelP8NSStringE8dayRegex
+ __ZZL20TIIsSystemNoiseLabelP8NSStringE9onceToken
+ __ZZL21libmecabraLibraryCorePPcE16frameworkLibrary
+ __ZZL27TIDeduplicateCollectionItemRKNSt3__110shared_ptrI14TIScreenUINodeEEEN16SubtreeCollector7collectES4_b
+ __ZZL33TIGetShowAllKeysDebugHitAreaValuevE9onceToken
+ __ZZL42getMecabraContextSetStringContextSymbolLocvE3ptr
+ ___35-[TIWordSearch setOnScreenContext:]_block_invoke
+ ___99-[TIKeyboardInputManager(ZephyrEngineSpecializations) _publishDebugChargeForKeyCode:touchLocation:]_block_invoke
+ ____ZL20TIIsSystemNoiseLabelP8NSString_block_invoke
+ ____ZL20TIIsSystemNoiseLabelP8NSString_block_invoke_2
+ ____ZL20TIIsSystemNoiseLabelP8NSString_block_invoke_3
+ ____ZL20TIIsSystemNoiseLabelP8NSString_block_invoke_4
+ ____ZL20TIIsSystemNoiseLabelP8NSString_block_invoke_5
+ ____ZL21libmecabraLibraryCorePPc_block_invoke
+ ____ZL33TIGetShowAllKeysDebugHitAreaValuev_block_invoke
+ ____ZL42getMecabraContextSetStringContextSymbolLocv_block_invoke
+ ___block_descriptor_48_a8_32r_e5_v8?0lr32l8
+ ___block_descriptor_56_8_32s40bs_e17_v16?0"NSArray"8ls32l8s40l8
+ ___block_descriptor_96_a8_32r40r48r56r64r_e50_v64?0r*8{CGRect={CGPoint=dd}{CGSize=dd}}16Q48^B56lr32l8r40l8r48l8r56l8r64l8
+ _clock_gettime_nsec_np
+ _notify_post
+ _notify_set_state
- __ZN2TI8Favonius10BeamSearch20choose_hit_test_nodeERKN3WTF6RefPtrINS0_10SearchNodeEEERKNS3_INS0_8KeyMatchEEES7_S7_
- ___block_descriptor_48_8_32r_e5_v8?0lr32l8
CStrings:
+ "%s  Setting OnScreenContext to MecabraContext(%p) %{sensitive}@"
+ "%s [Environment] Set on-screen context with length: %@"
+ "(NULL)"
+ "-[TIMecabraEnvironmentContextWrapper setOnScreenStringContext:]"
+ "-[TIWordSearch setOnScreenContext:]_block_invoke"
+ "/usr/lib/libmecabra.dylib"
+ "/usr/local/lib/libmecabra.dylib"
+ "Button"
+ "CollectionItem"
+ "EditableText"
+ "Element("
+ "MecabraContextSetStringContext"
+ "Scrollable"
+ "ShowAllKeysDebugHitArea"
+ "[ \\t\\r\\n,]"
+ "^[\\d\\s,:]+$"
+ "^\\d{1,2}/\\d{1,2}\\s*\\d{1,2}:\\d{2}$|^\\d{1,2}/\\d{1,2}$|^\\d{1,2}:\\d{2}$|^\\d{1,4}/\\d{1,2}/\\d{1,2}$"
+ "accessibilityLabel:\\s*\"((?:[^\"\\\\]|\\\\.)+)\""
+ "com.apple.keyboard.debugCharge"
+ "com.apple.keyboard.debugDecision"
+ "content:\\s*([A-Za-z0-9_]+)"
+ "scrollableAxes: [horizontal,"
+ "scrollableAxes: [horizontal]"
+ "scrollableAxes: [vertical,"
+ "scrollableAxes: [vertical]"
+ "text:\\s*\"((?:[^\"\\\\]|\\\\.)+)\""
+ "オンライン:"
+ "オンライン中"
+ "グループビデオ通話を開始"
+ "グループ音声通話を開始"
+ "スタンプ"
+ "ビデオ通話を開始"
+ "プロフィールを開く"
+ "プロフィール写真"
+ "メッセージの開封証明を表示"
+ "メディア"
+ "令和|平成|昭和|大正|明治|[\\(（][月火水木金土日](?:曜日)?[\\)）]|[\\(（]?(?:星期[一二三四五六日天]|[周週][一二三四五六日天])[\\)）]?|(?:^|[^0-9])[月火水木金土日](?:曜日?|(?=[\\s,，、\\)）]))|昨天|今天|昨日|今日|午前|午[後后]|上午|下午|晚上|早上|凌晨|[\\s,\\.，、]"
+ "关注后可邀请通话"
+ "大頭貼"
+ "头像"
+ "对方头像"
+ "對方頭像"
+ "已讀"
+ "已读"
+ "年"
+ "我的头像"
+ "我的頭像"
+ "投稿"
+ "既読"
+ "日"
+ "最近のメッセージに移動"
+ "月"
+ "貼圖"
+ "音声通話を開始"
+ "頭像"
+ "￼"
+ "\xf0\xf0a"
- "%s  Input mode %@ includes screen contents: %@, with length %@"
- "-[TIKeyboardInputManagerMecabra updateDocumentContext]"
- "Text\\([^)]*text:\\s*\"([^\"]+)\""
- "accessibilityLabel:\\s*\"([^\"]+)\""
- "on_screen_context_for_candidates_predictions"
- "\xf0\xf0!"
```
