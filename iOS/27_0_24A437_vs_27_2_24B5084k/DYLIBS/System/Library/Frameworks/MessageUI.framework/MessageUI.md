## MessageUI

> `/System/Library/Frameworks/MessageUI.framework/MessageUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x150358` | `0x151084` | **`+0xd2c`** |
| `__TEXT.__oslogstring` | `0x5ffe` | `0x63de` | **`+0x3e0`** |
| `__AUTH_CONST.__objc_const` | `0x1a860` | `0x1a690` | **`-0x1d0`** |
| `__TEXT.__gcc_except_tab` | `0x253a0` | `0x254c8` | **`+0x128`** |
| `__TEXT.__cstring` | `0xa1d6` | `0xa2f6` | **`+0x120`** |
| `__AUTH.__objc_data` | `0x3588` | `0x34e8` | **`-0xa0`** |
| `__TEXT.__objc_methlist` | `0x12af4` | `0x12a7c` | **`-0x78`** |
| `__AUTH_CONST.__cfstring` | `0x8f00` | `0x8ec0` | **`-0x40`** |
| `__AUTH_CONST.__const` | `0x1c90` | `0x1cd0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xa620` | `0xa5f8` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xc2c8` | `0xc2a8` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1900` | `0x18f0` | **`-0x10`** |
| `__DATA.__bss` | `0x1d60` | `0x1d50` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x114c` | `0x113c` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x628` | `0x618` | **`-0x10`** |
| `__DATA.__data` | `0x3818` | `0x3820` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x4a18` | `0x4a10` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1ef0` | `0x1ee8` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x4b0` | `0x4a8` | **`-0x8`** |

### Other Changes

```diff

-3901.100.1.2.14
+3901.200.34.0.0

-  Functions: 6882
-  Symbols:   11672
-  CStrings:  2060
+  Functions: 6873
+  Symbols:   11637
+  CStrings:  2080
Symbols:
+ +[MFComposeTypeFactory _canReplyFromHMEForOriginalMessageHeaders:]
+ +[MFComposeTypeFactory _recipientAddressLooksLikeHMEAddress:]
+ +[MFComposeTypeFactory _sanitizeRecipientsWithDelegate:]
+ -[MFMailRecipients _sanitizeIsReplyAll:sendingEmailAddress:replyAllCCMatcher:]
+ -[MFMailRecipients sanitizeForReplyAllWithSendingEmailAddress:replyAllCCMatcher:]
+ -[MFMailRecipients sanitize]
+ GCC_except_table544
+ GCC_except_table567
+ GCC_except_table569
+ GCC_except_table574
+ GCC_except_table576
+ GCC_except_table583
+ GCC_except_table590
+ GCC_except_table592
+ GCC_except_table597
+ GCC_except_table601
+ GCC_except_table608
+ GCC_except_table610
+ GCC_except_table615
+ GCC_except_table617
+ GCC_except_table622
+ GCC_except_table633
+ GCC_except_table639
+ GCC_except_table654
+ GCC_except_table658
+ GCC_except_table667
+ GCC_except_table676
+ GCC_except_table683
+ GCC_except_table698
+ GCC_except_table814
+ GCC_except_table818
+ GCC_except_table821
+ GCC_except_table823
+ _EFStringsAreEqual
+ ___66+[MFComposeTypeFactory _canReplyFromHMEForOriginalMessageHeaders:]_block_invoke
+ ___66+[MFComposeTypeFactory _canReplyFromHMEForOriginalMessageHeaders:]_block_invoke_2
+ ___ECEmailAddressConvertiblePublicDescriptions_block_invoke
+ ___block_descriptor_33_e31_B24?0"NSString"8"NSString"16l
+ ___block_descriptor_48_ea8_32s40s_e26_B16?0"UIViewController"8ls32l8s40l8
- +[MFComposeTypeFactory _sanitizeRecipientsForComposeType:sendingAddress:delegate:]
- +[MFDataDetectors _DDURLifierClass]
- +[MFDataDetectors sharedDetectionController]
- +[MFDataDetectors urlIfyNode:]
- +[MFDataDetectors urlIfyNode:phoneNumberTypes:]
- +[MFDataDetectors urlMatchesForString:]
- +[MFDataDetectors urlMatchesForString:includingTel:]
- -[MFComposeDropPreviewView .cxx_destruct]
- -[MFComposeDropPreviewView finalImage]
- -[MFComposeDropPreviewView imageView]
- -[MFComposeDropPreviewView initWithFrame:]
- -[MFComposeDropPreviewView previewClippingPath]
- -[MFComposeDropPreviewView previewView]
- -[MFComposeDropPreviewView setFinalImage:]
- -[MFComposeDropPreviewView setImageView:]
- -[MFComposeDropPreviewView setPreviewClippingPath:]
- -[MFComposeDropPreviewView setPreviewView:]
- -[MFMailRecipients sanitizeForComposeType:sendingEmailAddress:hideMyEmailAddressProvider:]
- GCC_except_table542
- GCC_except_table566
- GCC_except_table568
- GCC_except_table572
- GCC_except_table575
- GCC_except_table581
- GCC_except_table589
- GCC_except_table591
- GCC_except_table593
- GCC_except_table600
- GCC_except_table606
- GCC_except_table609
- GCC_except_table612
- GCC_except_table616
- GCC_except_table621
- GCC_except_table631
- GCC_except_table638
- GCC_except_table653
- GCC_except_table657
- GCC_except_table666
- GCC_except_table674
- GCC_except_table682
- GCC_except_table697
- GCC_except_table703
- GCC_except_table816
- GCC_except_table820
- GCC_except_table822
- _CGAffineTransformTranslate
- _NSClassFromString
- _OBJC_CLASS_$_MFComposeDropPreviewView
- _OBJC_CLASS_$_MFDataDetectors
- _OBJC_IVAR_$_MFComposeDropPreviewView._finalImage
- _OBJC_IVAR_$_MFComposeDropPreviewView._imageView
- _OBJC_IVAR_$_MFComposeDropPreviewView._previewClippingPath
- _OBJC_IVAR_$_MFComposeDropPreviewView._previewView
- _OBJC_METACLASS_$_MFComposeDropPreviewView
- _OBJC_METACLASS_$_MFDataDetectors
- _UISystemRootDirectory
- __DDURLifierClass._DDURLifierClass
- __DDURLifierClass.inited
- __OBJC_$_CLASS_METHODS_MFDataDetectors
- __OBJC_$_INSTANCE_METHODS_MFComposeDropPreviewView
- __OBJC_$_INSTANCE_VARIABLES_MFComposeDropPreviewView
- __OBJC_$_PROP_LIST_MFComposeDropPreviewView
- __OBJC_CLASS_RO_$_MFComposeDropPreviewView
- __OBJC_CLASS_RO_$_MFDataDetectors
- __OBJC_METACLASS_RO_$_MFComposeDropPreviewView
- __OBJC_METACLASS_RO_$_MFDataDetectors
- ___42-[MFComposeDropPreviewView setFinalImage:]_block_invoke
- ___43-[MFComposeDropPreviewView setPreviewView:]_block_invoke
- ___73-[MFMailComposeController composeRecipientViewDidFinishPickingRecipient:]_block_invoke
- ___82+[MFComposeTypeFactory _sanitizeRecipientsForComposeType:sendingAddress:delegate:]_block_invoke
- ___block_descriptor_40_ea8_32s_e14_"NSArray"8?0ls32l8
- ___block_descriptor_48_ea8_32s40s_e26_v16?0"UIViewController"8ls32l8s40l8
- _sharedDetectionController._DDDetectionControllerClass
- _sharedDetectionController.inited
CStrings:
+ "<%{public}@: %p> Adding bcc recipient from contact picker: %{public}@"
+ "<%{public}@: %p> Adding cc recipient from contact picker: %{public}@"
+ "<%{public}@: %p> Adding to recipient from contact picker: %{public}@"
+ "<%{public}@: %p> Clearing all recipient fields"
+ "<%{public}@: %p> Generate HME for reply to recipient: %{public}@"
+ "<%{public}@: %p> Generated HME address for recipient: %{public}@"
+ "<%{public}@: %p> Is reply to HME"
+ "<%{public}@: %p> Restoring bcc addresses: %{public}@"
+ "<%{public}@: %p> Restoring cc addresses: %{public}@"
+ "<%{public}@: %p> Restoring to addresses: %{public}@"
+ "<%{public}@: %p> Saving to addresses: %{public}@, cc addresses: %{public}@, bcc addresses: %{public}@"
+ "<%{public}@: %p> Setting bcc recipients from delegate: %{public}@"
+ "<%{public}@: %p> Setting bcc recipients: %{public}@"
+ "<%{public}@: %p> Setting cc recipients from delegate: %{public}@"
+ "<%{public}@: %p> Setting cc recipients: %{public}@"
+ "<%{public}@: %p> Setting header keys from saved headers: %{public}@"
+ "<%{public}@: %p> Setting to recipients from delegate: %{public}@"
+ "<%{public}@: %p> Setting to recipients: %{public}@"
+ "<%{public}@: %p> Verify HME address: %{public}@, sender address: %{public}@"
+ "B16@?0@\"UIViewController\"8"
+ "FORMAT_STYLE_BODY"
+ "FORMAT_STYLE_CAPTION"
+ "FORMAT_STYLE_SUBTITLE"
+ "FORMAT_STYLE_TITLE"
+ "MFMailRecipients.m"
+ "Name of the Body text style in the compose text formatting panel."
+ "Name of the Caption text style in the compose text formatting panel."
+ "Name of the Subtitle text style in the compose text formatting panel."
+ "Name of the Title text style in the compose text formatting panel."
+ "replyAllCCMatcher"
- "#Warning Failed to load DataDetectorsCore.framework (%s)"
- "#Warning Failed to load DataDetectorsUI.framework (%s)"
- "/System/Library/PrivateFrameworks/DataDetectorsCore.framework/DataDetectorsCore"
- "/System/Library/PrivateFrameworks/DataDetectorsUI.framework/DataDetectorsUI"
- "<%{public}@: %p> Generate HME for reply"
- "<%{public}@: %p> Verify HME address"
- "@\"NSArray\"8@?0"
- "DDDetectionController"
- "DDURLifier"
- "v16@?0@\"UIViewController\"8"
```
