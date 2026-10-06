## AskToMessages

> `/System/Library/Messages/iMessageApps/AskToMessages.bundle/AskToMessages`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22a90` | `0x18234` | **`-0xa85c`** |
| `__TEXT.__cstring` | `0xd89` | `0x6b9` | **`-0x6d0`** |
| `__TEXT.__auth_stubs` | `0x18d0` | `0x1450` | **`-0x480`** |
| `__DATA_CONST.__auth_got` | `0xc70` | `0xa30` | **`-0x240`** |
| `__TEXT.__const` | `0xad4` | `0x894` | **`-0x240`** |
| `__DATA.__data` | `0xa58` | `0x830` | **`-0x228`** |
| `__DATA.__objc_const` | `0x658` | `0x4a8` | **`-0x1b0`** |
| `__TEXT.__objc_methname` | `0x991` | `0x801` | **`-0x190`** |
| `__TEXT.__oslogstring` | `0xbea` | `0xa5a` | **`-0x190`** |
| `__DATA.__bss` | `0x5b0` | `0x4b0` | **`-0x100`** |
| `__TEXT.__swift5_reflstr` | `0x40d` | `0x30d` | **`-0x100`** |
| `__DATA_CONST.__const` | `0x6f0` | `0x600` | **`-0xf0`** |
| `__TEXT.__unwind_info` | `0x500` | `0x410` | **`-0xf0`** |
| `__TEXT.__swift5_typeref` | `0x596` | `0x4b2` | **`-0xe4`** |
| `__DATA_CONST.__auth_ptr` | `0x348` | `0x268` | **`-0xe0`** |
| `__TEXT.__eh_frame` | `0x5b8` | `0x4d8` | **`-0xe0`** |
| `__TEXT.__objc_stubs` | `0x800` | `0x720` | **`-0xe0`** |
| `__TEXT.__swift5_fieldmd` | `0x348` | `0x29c` | **`-0xac`** |
| `__TEXT.__constg_swiftt` | `0x464` | `0x3bc` | **`-0xa8`** |
| `__DATA_CONST.__got` | `0x2a0` | `0x200` | **`-0xa0`** |
| `__TEXT.__swift5_capture` | `0x1ec` | `0x158` | **`-0x94`** |
| `__DATA.__objc_data` | `0x2f8` | `0x2a8` | **`-0x50`** |
| `__TEXT.__objc_classname` | `0x1cd` | `0x18d` | **`-0x40`** |
| `__DATA.__objc_selrefs` | `0x270` | `0x238` | **`-0x38`** |
| `__DATA.__common` | `0x98` | `0x78` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0x3c` | `0x24` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x38` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x30` | `0x28` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x40` | `0x3c` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x2c` | `0x28` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x28` | `0x24` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-88.0.0.0.0
-  - /System/Library/Frameworks/Contacts.framework/Contacts
+90.1.0.0.0
+  - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics

+  - /System/Library/Frameworks/ImageIO.framework/ImageIO

+  - /System/Library/Frameworks/QuartzCore.framework/QuartzCore

-  Functions: 378
-  Symbols:   191
-  CStrings:  255
+  Functions: 302
+  Symbols:   188
+  CStrings:  198
Symbols:
+ _CGBitmapContextCreate
+ _CGBitmapContextCreateImage
+ _CGColorSpaceCreateDeviceRGB
+ _CGImageGetColorSpace
+ _CGImageGetHeight
+ _CGImageGetWidth
+ _CGImageSourceCreateImageAtIndex
+ _CGImageSourceCreateWithData
+ _OBJC_CLASS_$_CALayer
+ _kCACornerCurveContinuous
+ _kCAGravityResize
+ _swift_release_x27
- _OBJC_CLASS_$_CNPhoneNumber
- _OBJC_CLASS_$_UITraitCollection
- ___stack_chk_fail
- ___stack_chk_guard
- __swiftEmptyDictionarySingleton
- __swiftEmptySetSingleton
- __swift_stdlib_strtod_clocale
- _bzero
- _objc_retain_x28
- _objc_retain_x9
- _swift_bridgeObjectRetain_n
- _swift_release_x26
- _swift_retain
- _swift_retain_x28
- _swift_setDeallocating
CStrings:
+ "%s Staging URL exceeds 5KB limit (%ld bytes); insert may fail"
+ "AskToBuyActionApprove"
+ "AskToBuyActionDecline"
+ "AskToBuyRequestTitle"
+ "com.apple.AskPermission.AskToBuy"
+ "com.apple.askpermission.AskToResponseExtension"
+ "com.apple.askpermissiond"
+ "plus.arrow.trianglehead.clockwise"
+ "renderInContext:"
+ "setContents:"
+ "setContentsGravity:"
+ "setCornerCurve:"
+ "setCornerRadius:"
+ "setFrame:"
+ "setGeometryFlipped:"
+ "setMasksToBounds:"
+ "showContent(for:conversationContext:messageContext:presentationStyle:)"
- "$__lazy_storage_$_choices"
- "%s conversationContext.myHandle was empty. answerChoice: %@"
- "Add to Your Child’s Contacts"
- "CommLimitsReviewSheetExplanationContactName"
- "CommLimitsReviewSheetExplanationContactNameAppName"
- "CommLimitsReviewSheetExplanationEmail"
- "CommLimitsReviewSheetExplanationEmailAppName"
- "CommLimitsReviewSheetExplanationEmailPlural"
- "CommLimitsReviewSheetExplanationEmailPluralAppName"
- "CommLimitsReviewSheetExplanationHandle"
- "CommLimitsReviewSheetExplanationHandleAppName"
- "CommLimitsReviewSheetExplanationHandlePlural"
- "CommLimitsReviewSheetExplanationHandlePluralAppName"
- "CommLimitsReviewSheetExplanationPhoneNumber"
- "CommLimitsReviewSheetExplanationPhoneNumberAppName"
- "CommLimitsReviewSheetExplanationPhoneNumberPlural"
- "CommLimitsReviewSheetExplanationPhoneNumberPluralAppName"
- "CommLimitsReviewSheetExplanationYourChildContactName"
- "CommLimitsReviewSheetExplanationYourChildContactNameAppName"
- "CommLimitsReviewSheetExplanationYourChildEmail"
- "CommLimitsReviewSheetExplanationYourChildEmailAppName"
- "CommLimitsReviewSheetExplanationYourChildEmailPlural"
- "CommLimitsReviewSheetExplanationYourChildEmailPluralAppName"
- "CommLimitsReviewSheetExplanationYourChildHandle"
- "CommLimitsReviewSheetExplanationYourChildHandleAppName"
- "CommLimitsReviewSheetExplanationYourChildHandlePlural"
- "CommLimitsReviewSheetExplanationYourChildHandlePluralAppName"
- "CommLimitsReviewSheetExplanationYourChildPhoneNumber"
- "CommLimitsReviewSheetExplanationYourChildPhoneNumberAppName"
- "CommLimitsReviewSheetExplanationYourChildPhoneNumberPlural"
- "CommLimitsReviewSheetExplanationYourChildPhoneNumberPluralAppName"
- "Could not send response because answerChoices was nil"
- "Could not send response because question was nil"
- "Error sending response: %@"
- "Failed to get expiration date from URL"
- "In your contacts as “"
- "Successfully sent response: %@"
- "User selected answer choice. answerChoice: %@, question: %@"
- "Using legacy payload expiration date: %s"
- "YouCanManageYourChild"
- "_TtC13AskToMessages30CommLimitsReviewSheetViewModel"
- "bundleURL"
- "buttonTitle"
- "com.apple.contacts.commlimits.approve"
- "com.apple.contactsd"
- "com.apple.parentalconsent.choice.approve"
- "com.apple.parentalconsent.communicationlimits"
- "conversationContext"
- "cornerRadiusIncludedInThumbnailData"
- "currentTraitCollection"
- "decompressedDataUsingAlgorithm:error:"
- "dismissAction"
- "displayScale"
- "familyName"
- "formattedStringValue"
- "givenName"
- "handleInformation"
- "initWithStringValue:"
- "isShowingResponseErrorAlert"
- "messageContext"
- "messagesAppController"
- "middleName"
- "namePrefix"
- "nameSuffix"
- "nickname"
- "phoneticFamilyName"
- "phoneticGivenName"
- "phoneticMiddleName"
- "responseTransmitter"
- "responseTransmitter.sendResult is nil"
- "showContent(for:mainIcon:badgeIcon:conversationContext:messageContext:presentationStyle:)"
- "subtitle"
- "title"
- "userDidSelectAnswerChoice(_:)"
```
