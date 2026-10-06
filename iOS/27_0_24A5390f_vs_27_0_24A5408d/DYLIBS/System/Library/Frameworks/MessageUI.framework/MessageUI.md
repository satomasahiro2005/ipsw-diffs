## MessageUI

> `/System/Library/Frameworks/MessageUI.framework/MessageUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14f7f0` | `0x15031c` | **`+0xb2c`** |
| `__TEXT.__oslogstring` | `0x5e0e` | `0x5ffe` | **`+0x1f0`** |
| `__TEXT.__gcc_except_tab` | `0x25208` | `0x253a0` | **`+0x198`** |
| `__TEXT.__cstring` | `0xa0e6` | `0xa1d6` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0x8e60` | `0x8f00` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x4978` | `0x4a18` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0xa5c8` | `0xa620` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x1a810` | `0x1a860` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xc278` | `0xc2c8` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x12aac` | `0x12af4` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x4f8` | `0x4ec` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0x18f8` | `0x1900` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1ee8` | `0x1ef0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1148` | `0x114c` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-3897.100.8.2.5
+3901.100.1.2.7

-  Functions: 6870
-  Symbols:   11652
-  CStrings:  2051
+  Functions: 6882
+  Symbols:   11672
+  CStrings:  2060
Symbols:
+ -[MFMailComposeController _recordSmartReplyCandidateAccepted]
+ -[MFMailComposeController _shouldPresentComposeAccessoryAsPopover]
+ -[MFMailComposeController presentPersonalizeSmartRepliesAlertIfNeededFromViewController:completion:]
+ -[UITraitCollection(Convenience) mf_supportsPopoverPresentationWithoutIdiomCheck]
+ GCC_except_table367
+ GCC_except_table376
+ GCC_except_table378
+ GCC_except_table381
+ GCC_except_table388
+ GCC_except_table389
+ GCC_except_table391
+ GCC_except_table396
+ GCC_except_table399
+ GCC_except_table401
+ GCC_except_table404
+ GCC_except_table406
+ GCC_except_table412
+ GCC_except_table413
+ GCC_except_table414
+ GCC_except_table426
+ GCC_except_table427
+ GCC_except_table436
+ GCC_except_table448
+ GCC_except_table451
+ GCC_except_table452
+ GCC_except_table453
+ GCC_except_table456
+ GCC_except_table459
+ GCC_except_table464
+ GCC_except_table477
+ GCC_except_table479
+ GCC_except_table480
+ GCC_except_table484
+ GCC_except_table487
+ GCC_except_table497
+ GCC_except_table499
+ GCC_except_table509
+ GCC_except_table510
+ GCC_except_table534
+ GCC_except_table535
+ GCC_except_table558
+ GCC_except_table560
+ GCC_except_table564
+ GCC_except_table565
+ GCC_except_table581
+ GCC_except_table585
+ GCC_except_table586
+ GCC_except_table587
+ GCC_except_table588
+ GCC_except_table598
+ GCC_except_table599
+ GCC_except_table604
+ GCC_except_table605
+ GCC_except_table606
+ GCC_except_table623
+ GCC_except_table624
+ GCC_except_table630
+ GCC_except_table644
+ GCC_except_table648
+ GCC_except_table666
+ GCC_except_table673
+ GCC_except_table688
+ GCC_except_table694
+ GCC_except_table695
+ GCC_except_table696
+ GCC_except_table697
+ GCC_except_table699
+ GCC_except_table700
+ GCC_except_table701
+ GCC_except_table702
+ GCC_except_table703
+ GCC_except_table816
+ GCC_except_table819
+ GCC_except_table820
+ GCC_except_table822
+ GCC_except_table824
+ GCC_except_table825
+ _EMIsChinaRegion
+ _EMIsShareOwnerManagedAppleAccount
+ _EMUserDefaultPersonalizedSmartReplies
+ _EMUserDefaultShownPersonalizeSmartRepliesAlert
+ _OBJC_CLASS_$_MSWritingToolsNodePreservation
+ _OBJC_IVAR_$_MFMailComposeController._didAcceptSmartReplyCandidate
+ ___100-[MFMailComposeController presentPersonalizeSmartRepliesAlertIfNeededFromViewController:completion:]_block_invoke
+ ___70-[MFMailComposeController _checkForShareParticipantsWithContinuation:]_block_invoke_3
+ ___block_descriptor_105_ea8_32s40s48s56s64s72s80s88r_e20_v24?0"NSArray"8Q16ls32l8s40l8s48l8s56l8s64l8r88l8s72l8s80l8
+ ___block_descriptor_136_ea8_32s40s48s56s64s72s80s88s96s104s112bs120r128w_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8r120l8w128l8s104l8s112l8
+ ___block_descriptor_48_ea8_32s40bs_e17_v16?0"NSArray"8ls32l8s40l8
+ ___block_descriptor_56_ea8_32s40bs48r_e18_v16?0"NSNumber"8lr48l8s32l8s40l8
+ ___block_descriptor_80_ea8_32s40s48s56bs64r72w_e5_v8?0lw72l8s32l8s40l8s48l8s56l8r64l8
- GCC_except_table368
- GCC_except_table380
- GCC_except_table385
- GCC_except_table386
- GCC_except_table392
- GCC_except_table393
- GCC_except_table395
- GCC_except_table400
- GCC_except_table405
- GCC_except_table407
- GCC_except_table408
- GCC_except_table410
- GCC_except_table420
- GCC_except_table422
- GCC_except_table425
- GCC_except_table430
- GCC_except_table431
- GCC_except_table440
- GCC_except_table454
- GCC_except_table457
- GCC_except_table461
- GCC_except_table465
- GCC_except_table468
- GCC_except_table469
- GCC_except_table471
- GCC_except_table482
- GCC_except_table486
- GCC_except_table488
- GCC_except_table496
- GCC_except_table498
- GCC_except_table506
- GCC_except_table508
- GCC_except_table511
- GCC_except_table519
- GCC_except_table527
- GCC_except_table543
- GCC_except_table544
- GCC_except_table569
- GCC_except_table576
- GCC_except_table582
- GCC_except_table590
- GCC_except_table594
- GCC_except_table595
- GCC_except_table596
- GCC_except_table597
- GCC_except_table607
- GCC_except_table610
- GCC_except_table614
- GCC_except_table615
- GCC_except_table617
- GCC_except_table622
- GCC_except_table632
- GCC_except_table633
- GCC_except_table639
- GCC_except_table654
- GCC_except_table658
- GCC_except_table667
- GCC_except_table675
- GCC_except_table676
- GCC_except_table683
- GCC_except_table805
- GCC_except_table806
- GCC_except_table809
- GCC_except_table810
- GCC_except_table812
- GCC_except_table814
- _EMIsCurrentUserManagedAppleAccountForShare
- _OBJC_CLASS_$_MSWritingToolsSignaturePreservation
- _UIFontWeightRegular
- ___block_descriptor_56_ea8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
CStrings:
+ "<%{public}@: %p> Composition was cancelled or dismissed while identifying compose warnings; abandoning send."
+ "PERSONALIZE_SMART_REPLIES_ALERT_MESSAGE"
+ "PERSONALIZE_SMART_REPLIES_ALERT_NOT_NOW_BUTTON"
+ "PERSONALIZE_SMART_REPLIES_ALERT_PERSONALIZE_BUTTON"
+ "PERSONALIZE_SMART_REPLIES_ALERT_TITLE"
+ "WTKeyboardSmartReplyCandidateIsAccepted"
+ "[SmartReply] Attempting to present Personalize Smart Replies alert. presenter=%{public}@ presenterWindow=%{public}@ didAcceptCandidate=%d resolution=%ld composeType=%ld"
+ "[SmartReply] Cannot present Personalize Smart Replies alert; presenter=%{public}@ already presenting=%{public}@"
+ "[SmartReply] User opted in to personalized smart replies"
+ "[SmartReply] User opted out to personalized smart replies"
+ "v24@?0@\"NSArray\"8Q16"
- "headline"
- "subheadline"
```
