## TextInputUI

> `/System/Library/PrivateFrameworks/TextInputUI.framework/TextInputUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12a35c` | `0x12d03c` | **`+0x2ce0`** |
| `__AUTH_CONST.__objc_const` | `0x189b8` | `0x18d48` | **`+0x390`** |
| `__TEXT.__oslogstring` | `0x585b` | `0x5b1f` | **`+0x2c4`** |
| `__TEXT.__objc_methlist` | `0xf574` | `0xf7f4` | **`+0x280`** |
| `__TEXT.__cstring` | `0xd8c3` | `0xdabf` | **`+0x1fc`** |
| `__DATA_CONST.__const` | `0x77a0` | `0x7930` | **`+0x190`** |
| `__DATA_CONST.__objc_selrefs` | `0x9d08` | `0x9e68` | **`+0x160`** |
| `__TEXT.__dlopen_cstrs` | `0x207` | `0x315` | **`+0x10e`** |
| `__AUTH_CONST.__cfstring` | `0xe4a0` | `0xe560` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x4008` | `0x40c0` | **`+0xb8`** |
| `__DATA_DIRTY.__objc_data` | `0x2028` | `0x20c0` | **`+0x98`** |
| `__DATA_CONST.__got` | `0x1480` | `0x14b0` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x2a8` | `0x2d8` | **`+0x30`** |
| `__AUTH.__data` | `0x9b8` | `0x990` | **`-0x28`** |
| `__DATA.__objc_ivar` | `0x1158` | `0x117c` | **`+0x24`** |
| `__TEXT.__const` | `0x3600` | `0x3620` | **`+0x20`** |
| `__DATA.__bss` | `0x2d40` | `0x2d50` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x6d8` | `0x6e8` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x440` | `0x450` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x4e0` | `0x4f0` | **`+0x10`** |
| `__AUTH.__objc_data` | `0x3880` | `0x3888` | **`+0x8`** |
| `__DATA.__common` | `0x281` | `0x288` | **`+0x7`** |

### Same-size Content Changes

- `__TEXT.__ustring`

### Other Changes

```diff

-9127.0.71.1.101
+9127.0.75.1.101

-  Functions: 6630
-  Symbols:   10412
-  CStrings:  2647
+  Functions: 6698
+  Symbols:   10525
+  CStrings:  2674
Symbols:
+ +[TUIPasteboardSnapshot generalPasteboardSnapshot]
+ +[TUIPasteboardSnapshot itemsForPasteboard:]
+ -[TUIAttributedSearchResultItem contactFirstName]
+ -[TUIKeyplane buildSplitRowInfo]
+ -[TUIKeyplane layoutTypeIsVisibleKey:]
+ -[TUIKeyplaneRowInfo description]
+ -[TUIKeyplaneRowInfo keysOnlyMultiplierTotal]
+ -[TUIKeyplaneRowInfo setKeysOnlyMultiplierTotal:]
+ -[TUIKeyplaneView dockItemLayoutType]
+ -[TUIKeyplaneView setDockItemLayoutType:]
+ -[TUIKeyplaneView sizeAdjustedForDockLayoutType:useSplitHeight:]
+ -[TUIPasteboardItem .cxx_destruct]
+ -[TUIPasteboardItem URLValue]
+ -[TUIPasteboardItem baseDomainForURL:]
+ -[TUIPasteboardItem conformsToType:]
+ -[TUIPasteboardItem contentTitle]
+ -[TUIPasteboardItem description]
+ -[TUIPasteboardItem fileContentType]
+ -[TUIPasteboardItem imageValue]
+ -[TUIPasteboardItem initWithRepresentations:itemProvider:]
+ -[TUIPasteboardItem primaryType]
+ -[TUIPasteboardItem quickLookThumbnailForURL:contentType:completion:]
+ -[TUIPasteboardItem representations]
+ -[TUIPasteboardItem stringValue]
+ -[TUIPasteboardItem suggestedName]
+ -[TUIPasteboardItem thumbnailImageWithCompletion:]
+ -[TUIPasteboardItem typeIdentifiers]
+ -[TUIPasteboardSnapshot .cxx_destruct]
+ -[TUIPasteboardSnapshot changeCount]
+ -[TUIPasteboardSnapshot containsItemOfType:]
+ -[TUIPasteboardSnapshot containsOnlyType:]
+ -[TUIPasteboardSnapshot contentIdentifier]
+ -[TUIPasteboardSnapshot description]
+ -[TUIPasteboardSnapshot firstAvailableThumbnailFromItemAtIndex:completion:]
+ -[TUIPasteboardSnapshot initWithPasteboard:]
+ -[TUIPasteboardSnapshot isEmpty]
+ -[TUIPasteboardSnapshot items]
+ -[TUIPasteboardSnapshot name]
+ -[TUIPasteboardSnapshot originatorBundleID]
+ -[TUIPasteboardSnapshot originatorLocalizedName]
+ -[TUIPasteboardSnapshot pasteboardThumbnailImageWithCompletion:]
+ -[TUIPasteboardSnapshot pasteboardTitle]
+ -[TUIPasteboardSnapshot saveTimestamp]
+ -[TUIRecentPasteCandidate contentTitle]
+ -[TUIRecentPasteCandidate initWithPasteboard:contentTitle:thumbnailImage:sourceApp:contentIdentifier:]
+ -[TUIRecentPasteCandidate sourceApp]
+ -[TUIRecentPasteGenerator candidatesForPasteboard:image:label:sourceApp:]
+ -[TUIRecentPasteGenerator createCandidatesFromPasteboardWithContext:pasteboard:completion:]
+ -[TUIRecentPasteGenerator fetchEnabledCredentialProviderBundleIDsWithCompletion:]
+ -[TUIRecentPasteGenerator generatePasteCandidatesWithContext:pasteboard:completion:]
+ -[TUIRecentPasteGenerator isWebBrowserWithBundleID:]
+ -[TUIRecentPasteGenerator originatorIsCredentialProviderForPasteboard:completion:]
+ -[TUIRecentPasteGenerator originatorIsWebBrowserForPasteboard:]
+ -[TUIRecentPasteGenerator pasteboardContentAlreadyInsertedForContext:pasteboard:]
+ -[TUIRecentPasteGenerator pasteboardIsRecent:]
+ -[TUIRecentPasteGenerator shouldGenerateCandidateForContext:pasteboard:completion:]
+ -[TUISecureInputCandidateContainerView hostedViewHeightConstraint]
+ -[TUISecureInputCandidateContainerView hostedViewHeightFixedConstraint]
+ -[TUISecureInputCandidateContainerView setHostedPredictionViewHeight:]
+ -[TUISecureInputCandidateContainerView setHostedViewHeightConstraint:]
+ -[TUISecureInputCandidateContainerView setHostedViewHeightFixedConstraint:]
+ -[TUISmartActionGLPSearchCandidate _labelForAttributedResult:requiresDisambiguation:]
+ _CoreServicesLibraryCore.frameworkLibrary
+ _OBJC_CLASS_$_NSPersonNameComponentsFormatter
+ _OBJC_CLASS_$_TUIPasteboardItem
+ _OBJC_CLASS_$_TUIPasteboardSnapshot
+ _OBJC_CLASS_$_UTType
+ _OBJC_IVAR_$_TUIKeyplaneRowInfo._keysOnlyMultiplierTotal
+ _OBJC_IVAR_$_TUIKeyplaneView._dockItemLayoutType
+ _OBJC_IVAR_$_TUIPasteboardItem._representations
+ _OBJC_IVAR_$_TUIPasteboardItem._suggestedName
+ _OBJC_IVAR_$_TUIPasteboardSnapshot._changeCount
+ _OBJC_IVAR_$_TUIPasteboardSnapshot._items
+ _OBJC_IVAR_$_TUIPasteboardSnapshot._name
+ _OBJC_IVAR_$_TUIPasteboardSnapshot._originatorBundleID
+ _OBJC_IVAR_$_TUIPasteboardSnapshot._originatorLocalizedName
+ _OBJC_IVAR_$_TUIPasteboardSnapshot._saveTimestamp
+ _OBJC_IVAR_$_TUIRecentPasteCandidate._contentTitle
+ _OBJC_IVAR_$_TUIRecentPasteCandidate._sourceApp
+ _OBJC_IVAR_$_TUISecureInputCandidateContainerView._hostedViewHeightConstraint
+ _OBJC_IVAR_$_TUISecureInputCandidateContainerView._hostedViewHeightFixedConstraint
+ _OBJC_METACLASS_$_TUIPasteboardItem
+ _OBJC_METACLASS_$_TUIPasteboardSnapshot
+ _QuickLookThumbnailingLibrary
+ _QuickLookThumbnailingLibraryCore.frameworkLibrary
+ _SafariFoundationLibraryCore.frameworkLibrary
+ _UIKBAttributeNameConditionalMoreAfter
+ _UTTypeImage
+ _UTTypeText
+ _UTTypeURL
+ __OBJC_$_CLASS_METHODS_TUIPasteboardSnapshot
+ __OBJC_$_INSTANCE_METHODS_TUIPasteboardItem
+ __OBJC_$_INSTANCE_METHODS_TUIPasteboardSnapshot
+ __OBJC_$_INSTANCE_VARIABLES_TUIPasteboardItem
+ __OBJC_$_INSTANCE_VARIABLES_TUIPasteboardSnapshot
+ __OBJC_$_PROP_LIST_TUIPasteboardItem
+ __OBJC_$_PROP_LIST_TUIPasteboardSnapshot
+ __OBJC_CLASS_RO_$_TUIPasteboardItem
+ __OBJC_CLASS_RO_$_TUIPasteboardSnapshot
+ __OBJC_METACLASS_RO_$_TUIPasteboardItem
+ __OBJC_METACLASS_RO_$_TUIPasteboardSnapshot
+ ___44+[TUIPasteboardSnapshot itemsForPasteboard:]_block_invoke
+ ___44-[TUIKeyplaneView prepareForSplitTransition]_block_invoke
+ ___68-[TUIRecentPasteGenerator generateCandidatesWithContext:completion:]_block_invoke
+ ___69-[TUIPasteboardItem quickLookThumbnailForURL:contentType:completion:]_block_invoke
+ ___75-[TUIPasteboardSnapshot firstAvailableThumbnailFromItemAtIndex:completion:]_block_invoke
+ ___81-[TUIRecentPasteGenerator fetchEnabledCredentialProviderBundleIDsWithCompletion:]_block_invoke
+ ___82-[TUIRecentPasteGenerator originatorIsCredentialProviderForPasteboard:completion:]_block_invoke
+ ___83-[TUIRecentPasteGenerator shouldGenerateCandidateForContext:pasteboard:completion:]_block_invoke
+ ___84-[TUIRecentPasteGenerator generatePasteCandidatesWithContext:pasteboard:completion:]_block_invoke
+ ___91-[TUIRecentPasteGenerator createCandidatesFromPasteboardWithContext:pasteboard:completion:]_block_invoke
+ ___CoreServicesLibraryCore_block_invoke
+ ___QuickLookThumbnailingLibraryCore_block_invoke
+ ___SafariFoundationLibraryCore_block_invoke
+ ___block_descriptor_40_8_32bs_e17_v16?0"NSArray"8ls32l8
+ ___block_descriptor_40_8_32bs_e47_v24?0"QLThumbnailRepresentation"8"NSError"16ls32l8
+ ___block_descriptor_48_8_32s40bs_e17_v16?0"NSArray"8ls32l8s40l8
+ ___block_descriptor_48_8_32s40bs_e27_v24?0"NSSet"8"NSError"16ls32l8s40l8
+ ___block_descriptor_48_8_32s40s_e29_v32?0"NSDictionary"8Q16^B24ls32l8s40l8
+ ___block_descriptor_56_8_32s40bs_e17_v16?0"UIImage"8ls40l8s32l8
+ ___block_descriptor_64_8_32s40s48s56bs_e8_v12?0B8ls56l8s32l8s40l8s48l8
+ ___block_descriptor_72_8_32s40s48s56s64bs_e17_v16?0"UIImage"8ls64l8s32l8s40l8s48l8s56l8
+ ___getLSApplicationRecordClass_block_invoke
+ ___getQLThumbnailGenerationRequestClass_block_invoke
+ ___getQLThumbnailGeneratorClass_block_invoke
+ ___getSFCredentialProviderExtensionManagerClass_block_invoke
+ _audit_stringCoreServices
+ _audit_stringQuickLookThumbnailing
+ _audit_stringSafariFoundation
+ _getLSApplicationRecordClass.softClass
+ _getQLThumbnailGenerationRequestClass.softClass
+ _getQLThumbnailGeneratorClass.softClass
+ _getSFCredentialProviderExtensionManagerClass.softClass
- +[TUIRecentPasteCandidate contentIdentifierForPasteboard:]
- +[TUIRecentPasteCandidate displayTextFromRawText:image:imageCount:]
- -[TUIRecentPasteCandidate displayText]
- -[TUIRecentPasteCandidate initWithPasteboard:text:thumbnailImage:imageCount:sourceName:]
- -[TUIRecentPasteCellContentView _captionBaselineDistance]
- -[TUIRecentPasteGenerator createCandidatesFromPasteboardWithContext:]
- -[TUIRecentPasteGenerator generatePasteCandidatesWithContext:completion:]
- -[TUIRecentPasteGenerator originatorIsPasswordManager]
- -[TUIRecentPasteGenerator pasteboardContentAlreadyInsertedForContext:]
- -[TUIRecentPasteGenerator pasteboardIsRecent]
- -[TUIRecentPasteGenerator shouldGenerateCandidateForContext:]
- -[TUISmartActionGLPSearchCandidate _labelForAttributedResult:]
- _OBJC_CLASS_$_NSIndexSet
- _OBJC_IVAR_$_TUIRecentPasteCandidate._displayText
- _OBJC_IVAR_$_TUIRecentPasteCandidate._subtitleText
- _OBJC_IVAR_$_TUIRecentPasteCellContentView._captionBaselineConstraint
- _OBJC_IVAR_$_TUIRecentPasteCellContentView._contentWrapper
- _OBJC_IVAR_$_TUIRecentPasteCellContentView._labelGroup
- _UTTypeUTF8PlainText
- ___39-[TUIKeyplaneView updateSplitProgress:]_block_invoke_5
CStrings:
+ "<%@: contentTitle=%@ sourceApp=%@ thumbnailImage=%@>"
+ "<%@: itemCount=%lu hasStrings=%@ hasWebURLs=%@ hasFiles=%@ hasImages=%@>"
+ "<%@: types=%@ suggestedName=%@>"
+ "Cancelled paste candidate generation due to sensitivity"
+ "Failed to fetch credential provider bundle IDs: %@; falling back to hard-coded list (isCredentialProvider=%{public}d)"
+ "Interactive"
+ "LSApplicationRecord"
+ "Multiplier total: %0.2f Left side: %0.2f Keys only: %0.2f Split index: %li"
+ "No originator bundle ID found; treating pasteboard as non-credential-provider"
+ "Noninteractive"
+ "QLThumbnailGenerationRequest"
+ "QLThumbnailGenerator"
+ "QuickLook thumbnail completion (hasImage=%{public}s error=%{public}@)"
+ "RECENT_PASTE_ITEM_SINGULAR"
+ "RECENT_PASTE_PHOTO_COUNT_PLURAL"
+ "SFCredentialProviderExtensionManager"
+ "SafariFoundation unavailable; cannot fetch credential provider bundle IDs"
+ "TUIRecentPasteGeneratorCredentialProviderErrorDomain"
+ "UIKBAttributeNameConditionalMoreAfter"
+ "[Split] Mismatched row multipliers for %@ row %li: %0.2f [expected %0.2f]"
+ "[Split] No split index found for %@ row %li"
+ "[StateTransitions] Animating transition from %li to %li with type %li"
+ "[StateTransitions] Finished transition to %li with type %li [%@]"
+ "[StateTransitions] Prepare for transition to %li with type %li [%@]"
+ "[StateTransitions] Transitioning to %li with type %li [%0.2f]"
+ "conditional-more-after"
+ "createCandidatesFromPasteboard: mainThread=%{public}s %{public}@"
+ "softlink:r:path:/System/Library/Frameworks/CoreServices.framework/CoreServices"
+ "softlink:r:path:/System/Library/Frameworks/QuickLookThumbnailing.framework/QuickLookThumbnailing"
+ "softlink:r:path:/System/Library/PrivateFrameworks/SafariFoundation.framework/SafariFoundation"
+ "v16@?0@\"UIImage\"8"
+ "v24@?0@\"NSSet\"8@\"NSError\"16"
+ "v24@?0@\"QLThumbnailRepresentation\"8@\"NSError\"16"
+ "v32@?0@\"NSDictionary\"8Q16^B24"
- "<%@: displayText=%@ subtitleText=%@ thumbnailImage=%@>"
- "Cancelled paste candidate generation due to pasteboard from password manager (sensitive)"
- "Pasteboard originator name found for candidate"
- "recentPasteContentIdentifier"
- "recentPasteDisplayText"
- "recentPasteSubtitleText"
- "recentPasteThumbnailImage"
```
