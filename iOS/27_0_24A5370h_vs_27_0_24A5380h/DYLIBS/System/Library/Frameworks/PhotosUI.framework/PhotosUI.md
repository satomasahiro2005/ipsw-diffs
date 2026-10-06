## PhotosUI

> `/System/Library/Frameworks/PhotosUI.framework/PhotosUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x491b4` | `0x41874` | **`-0x7940`** |
| `__AUTH_CONST.__const` | `0x2868` | `0x20f0` | **`-0x778`** |
| `__AUTH_CONST.__objc_const` | `0x7398` | `0x6e38` | **`-0x560`** |
| `__TEXT.__eh_frame` | `0xc5c` | `0x73c` | **`-0x520`** |
| `__TEXT.__const` | `0x32a8` | `0x2e68` | **`-0x440`** |
| `__AUTH.__objc_data` | `0x2400` | `0x1fd8` | **`-0x428`** |
| `__DATA.__data` | `0x1e88` | `0x1ac8` | **`-0x3c0`** |
| `__DATA.__bss` | `0x33a0` | `0x30a0` | **`-0x300`** |
| `__TEXT.__unwind_info` | `0x1b90` | `0x18e8` | **`-0x2a8`** |
| `__TEXT.__swift5_typeref` | `0xe2c` | `0xb92` | **`-0x29a`** |
| `__TEXT.__constg_swiftt` | `0xf2c` | `0xd04` | **`-0x228`** |
| `__TEXT.__swift5_fieldmd` | `0xda0` | `0xba4` | **`-0x1fc`** |
| `__TEXT.__swift5_capture` | `0x684` | `0x4b8` | **`-0x1cc`** |
| `__TEXT.__swift5_reflstr` | `0xc75` | `0xaf1` | **`-0x184`** |
| `__AUTH.__data` | `0x758` | `0x678` | **`-0xe0`** |
| `__TEXT.__oslogstring` | `0x12e1` | `0x120c` | **`-0xd5`** |
| `__AUTH_CONST.__cfstring` | `0x2180` | `0x2220` | **`+0xa0`** |
| `__AUTH_CONST.__auth_got` | `0xa70` | `0xa00` | **`-0x70`** |
| `__TEXT.__objc_methlist` | `0x3e04` | `0x3db4` | **`-0x50`** |
| `__DATA_CONST.__const` | `0xd98` | `0xd60` | **`-0x38`** |
| `__DATA_CONST.__objc_protolist` | `0x250` | `0x218` | **`-0x38`** |
| `__DATA_CONST.__objc_protorefs` | `0x120` | `0xf0` | **`-0x30`** |
| `__DATA.__common` | `0x270` | `0x241` | **`-0x2f`** |
| `__TEXT.__swift_as_cont` | `0x54` | `0x28` | **`-0x2c`** |
| `__DATA_CONST.__got` | `0x620` | `0x5f8` | **`-0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x240` | `0x220` | **`-0x20`** |
| `__TEXT.__swift_as_entry` | `0x4c` | `0x2c` | **`-0x20`** |
| `__TEXT.__swift5_types` | `0x130` | `0x114` | **`-0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x20d0` | `0x20e8` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x1ac` | `0x194` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0x308` | `0x31c` | **`+0x14`** |
| `__TEXT.__swift5_builtin` | `0x154` | `0x168` | **`+0x14`** |
| `__DATA_CONST.__objc_superrefs` | `0xf0` | `0xf8` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xc` | `0x4` | **`-0x8`** |
| `__TEXT.__swift5_protos` | `0x10` | `0xc` | **`-0x4`** |
| `__TEXT.__cstring` | `0x4b7e` | `0x4b7b` | **`-0x3`** |

### Other Changes

```diff

-910.21.101.0.0
+910.27.103.0.0

-  - /System/Library/Frameworks/ExtensionFoundation.framework/ExtensionFoundation
-  - /System/Library/Frameworks/ExtensionKit.framework/ExtensionKit

-  Functions: 3145
-  Symbols:   2955
-  CStrings:  561
+  Functions: 2928
+  Symbols:   2901
+  CStrings:  551
Symbols:
+ +[PHPickerFilter _groupsPeopleQuantityFilterWithMinimumMemberCount:maximumMemberCount:]
+ +[PUPickerGroupsPeopleQuantityFilter supportsSecureCoding]
+ +[_PHPickerSuggestionGroup imagePlaygroundSuggestionGroupWithPinnedItemIdentifiers:defaultsToFaceMode:]
+ -[PUPickerCompoundFilter generatedMaximumSocialGroupMemberCount]
+ -[PUPickerCompoundFilter generatedMinimumSocialGroupMemberCount]
+ -[PUPickerGroupsPeopleQuantityFilter allowsAlbums]
+ -[PUPickerGroupsPeopleQuantityFilter containsFilter:]
+ -[PUPickerGroupsPeopleQuantityFilter copyWithZone:]
+ -[PUPickerGroupsPeopleQuantityFilter encodeWithCoder:]
+ -[PUPickerGroupsPeopleQuantityFilter generatedAssetPredicate]
+ -[PUPickerGroupsPeopleQuantityFilter generatedMaximumSocialGroupMemberCount]
+ -[PUPickerGroupsPeopleQuantityFilter generatedMinimumSocialGroupMemberCount]
+ -[PUPickerGroupsPeopleQuantityFilter generatedPossibleAssetTypes]
+ -[PUPickerGroupsPeopleQuantityFilter generatedRequiredAssetTypes]
+ -[PUPickerGroupsPeopleQuantityFilter hash]
+ -[PUPickerGroupsPeopleQuantityFilter initWithCoder:]
+ -[PUPickerGroupsPeopleQuantityFilter initWithMinimumMemberCount:maximumMemberCount:]
+ -[PUPickerGroupsPeopleQuantityFilter isEqual:]
+ -[PUPickerGroupsPeopleQuantityFilter isValidFilter]
+ -[PUPickerGroupsPeopleQuantityFilter maximumMemberCount]
+ -[PUPickerGroupsPeopleQuantityFilter minimumMemberCount]
+ -[_PHPickerCollectionConfiguration _customKeyAssetIdentifiers]
+ -[_PHPickerCollectionConfiguration _setCustomKeyAssetIdentifiers:]
+ -[_PHPickerSuggestionGroup _initWithSuggestions:defaultSuggestionIndex:isForWallpaper:defaultsToFaceMode:hasPinnedSuggestionItems:]
+ -[_PHPickerSuggestionGroup defaultsToFaceMode]
+ -[_PHPickerSuggestionGroup hasPinnedSuggestionItems]
+ GCC_except_table157
+ GCC_except_table354
+ GCC_except_table385
+ GCC_except_table390
+ GCC_except_table394
+ GCC_except_table398
+ GCC_except_table416
+ GCC_except_table509
+ GCC_except_table862
+ GCC_except_table872
+ GCC_except_table875
+ GCC_except_table877
+ GCC_except_table956
+ _OBJC_CLASS_$_PUPickerGroupsPeopleQuantityFilter
+ _OBJC_IVAR_$_PUPickerGroupsPeopleQuantityFilter._maximumMemberCount
+ _OBJC_IVAR_$_PUPickerGroupsPeopleQuantityFilter._minimumMemberCount
+ _OBJC_IVAR_$__PHPickerCollectionConfiguration.__customKeyAssetIdentifiers
+ _OBJC_IVAR_$__PHPickerSuggestionGroup._defaultsToFaceMode
+ _OBJC_IVAR_$__PHPickerSuggestionGroup._hasPinnedSuggestionItems
+ _OBJC_METACLASS_$_PUPickerGroupsPeopleQuantityFilter
+ _PUPickerFilterGeneratedMaximumSocialGroupMemberCount
+ _PUPickerFilterGeneratedMinimumSocialGroupMemberCount
+ _PUPickerFilterUnionMaximumSocialGroupMemberCount
+ _PUPickerFilterUnionMinimumSocialGroupMemberCount
+ __OBJC_$_CLASS_METHODS_PUPickerGroupsPeopleQuantityFilter
+ __OBJC_$_CLASS_PROP_LIST_PUPickerGroupsPeopleQuantityFilter
+ __OBJC_$_INSTANCE_METHODS_PUPickerGroupsPeopleQuantityFilter
+ __OBJC_$_INSTANCE_VARIABLES_PUPickerGroupsPeopleQuantityFilter
+ __OBJC_$_PROP_LIST_PUPickerGroupsPeopleQuantityFilter
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_PUPickerFilter
+ __OBJC_CLASS_PROTOCOLS_$_PUPickerGroupsPeopleQuantityFilter
+ __OBJC_CLASS_RO_$_PUPickerGroupsPeopleQuantityFilter
+ __OBJC_METACLASS_RO_$_PUPickerGroupsPeopleQuantityFilter
+ ___swift_memcpy17_8
+ _swift_getDynamicType
+ _symbolic SDyS2SG
+ _symbolic SNySiG
+ _symbolic SS12delegateType_t
+ _symbolic SaySo8NSStringCG
+ _symbolic SnySiG
+ _symbolic _____ 8PhotosUI26PVSAngelAlbumConfigurationV
+ _symbolic _____ 8PhotosUI40PVSAngelSharedAlbumCreationConfigurationV
+ _symbolic _____ 8PhotosUI45PVSAngelSharedAlbumCustomizationConfigurationV
+ _symbolic ______p s5ErrorP
+ _symbolic ______p10underlying_t s5ErrorP
+ _symbolic _____ySiG s16PartialRangeFromV
+ _symbolic _____ySiG s16PartialRangeUpToV
+ _symbolic _____ySiG s19PartialRangeThroughV
+ _type_layout_string 8PhotosUI26PVSAngelAlbumConfigurationV
+ _type_layout_string 8PhotosUI40PVSAngelSharedAlbumCreationConfigurationV
+ _type_layout_string 8PhotosUI45PVSAngelSharedAlbumCustomizationConfigurationV
- -[_PHPickerSuggestionGroup _initWithSuggestions:defaultSuggestionIndex:isForWallpaper:]
- GCC_except_table134
- GCC_except_table331
- GCC_except_table362
- GCC_except_table367
- GCC_except_table371
- GCC_except_table375
- GCC_except_table393
- GCC_except_table463
- GCC_except_table833
- GCC_except_table843
- GCC_except_table846
- GCC_except_table848
- GCC_except_table927
- _OBJC_CLASS_$_EXHostViewController
- _OBJC_CLASS_$__TtC8PhotosUI20PVSAlbumHostDelegate
- _OBJC_CLASS_$__TtC8PhotosUI22PVSSyncNowHostDelegate
- _OBJC_CLASS_$__TtC8PhotosUI25PVSPostAssetsHostDelegate
- _OBJC_CLASS_$__TtC8PhotosUI37PVSCreateSharedCollectionHostDelegate
- _OBJC_CLASS_$__TtC8PhotosUI40PVSCustomizeSharedCollectionHostDelegate
- _OBJC_METACLASS_$__TtC8PhotosUI20PVSAlbumHostDelegate
- _OBJC_METACLASS_$__TtC8PhotosUI22PVSSyncNowHostDelegate
- _OBJC_METACLASS_$__TtC8PhotosUI25PVSPostAssetsHostDelegate
- _OBJC_METACLASS_$__TtC8PhotosUI37PVSCreateSharedCollectionHostDelegate
- _OBJC_METACLASS_$__TtC8PhotosUI40PVSCustomizeSharedCollectionHostDelegate
- __DATA__TtC8PhotosUI20PVSAlbumHostDelegate
- __DATA__TtC8PhotosUI22PVSSyncNowHostDelegate
- __DATA__TtC8PhotosUI25PVSPostAssetsHostDelegate
- __DATA__TtC8PhotosUI37PVSCreateSharedCollectionHostDelegate
- __DATA__TtC8PhotosUI40PVSCustomizeSharedCollectionHostDelegate
- __INSTANCE_METHODS__TtC8PhotosUI17PVSViewController
- __INSTANCE_METHODS__TtC8PhotosUI20PVSAlbumHostDelegate
- __INSTANCE_METHODS__TtC8PhotosUI22PVSSyncNowHostDelegate
- __INSTANCE_METHODS__TtC8PhotosUI25PVSPostAssetsHostDelegate
- __INSTANCE_METHODS__TtC8PhotosUI37PVSCreateSharedCollectionHostDelegate
- __INSTANCE_METHODS__TtC8PhotosUI40PVSCustomizeSharedCollectionHostDelegate
- __IVARS__TtC8PhotosUI17PVSViewController
- __IVARS__TtC8PhotosUI20PVSAlbumHostDelegate
- __IVARS__TtC8PhotosUI22PVSSyncNowHostDelegate
- __IVARS__TtC8PhotosUI25PVSPostAssetsHostDelegate
- __IVARS__TtC8PhotosUI37PVSCreateSharedCollectionHostDelegate
- __IVARS__TtC8PhotosUI40PVSCustomizeSharedCollectionHostDelegate
- __METACLASS_DATA__TtC8PhotosUI20PVSAlbumHostDelegate
- __METACLASS_DATA__TtC8PhotosUI22PVSSyncNowHostDelegate
- __METACLASS_DATA__TtC8PhotosUI25PVSPostAssetsHostDelegate
- __METACLASS_DATA__TtC8PhotosUI37PVSCreateSharedCollectionHostDelegate
- __METACLASS_DATA__TtC8PhotosUI40PVSCustomizeSharedCollectionHostDelegate
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_EXHostViewControllerDelegate
- __OBJC_$_PROTOCOL_METHOD_TYPES_EXHostViewControllerDelegate
- __OBJC_$_PROTOCOL_REFS_EXHostViewControllerDelegate
- __OBJC_LABEL_PROTOCOL_$_EXHostViewControllerDelegate
- __OBJC_PROTOCOL_$_EXHostViewControllerDelegate
- __PROTOCOLS__TtC8PhotosUI20PVSAlbumHostDelegate
- __PROTOCOLS__TtC8PhotosUI22PVSSyncNowHostDelegate
- __PROTOCOLS__TtC8PhotosUI25PVSPostAssetsHostDelegate
- __PROTOCOLS__TtC8PhotosUI37PVSCreateSharedCollectionHostDelegate
- __PROTOCOLS__TtC8PhotosUI40PVSCustomizeSharedCollectionHostDelegate
- __PROTOCOL_INSTANCE_METHODS__TtP8PhotosUI16PVSAlbumProtocol_
- __PROTOCOL_INSTANCE_METHODS__TtP8PhotosUI18PVSSyncNowProtocol_
- __PROTOCOL_INSTANCE_METHODS__TtP8PhotosUI21PVSPostAssetsProtocol_
- __PROTOCOL_INSTANCE_METHODS__TtP8PhotosUI33PVSCreateSharedCollectionProtocol_
- __PROTOCOL_INSTANCE_METHODS__TtP8PhotosUI36PVSCustomizeSharedCollectionProtocol_
- __PROTOCOL_METHOD_TYPES__TtP8PhotosUI16PVSAlbumProtocol_
- __PROTOCOL_METHOD_TYPES__TtP8PhotosUI18PVSSyncNowProtocol_
- __PROTOCOL_METHOD_TYPES__TtP8PhotosUI21PVSPostAssetsProtocol_
- __PROTOCOL_METHOD_TYPES__TtP8PhotosUI33PVSCreateSharedCollectionProtocol_
- __PROTOCOL_METHOD_TYPES__TtP8PhotosUI36PVSCustomizeSharedCollectionProtocol_
- __PROTOCOL__TtP8PhotosUI16PVSAlbumProtocol_
- __PROTOCOL__TtP8PhotosUI18PVSSyncNowProtocol_
- __PROTOCOL__TtP8PhotosUI21PVSPostAssetsProtocol_
- __PROTOCOL__TtP8PhotosUI33PVSCreateSharedCollectionProtocol_
- __PROTOCOL__TtP8PhotosUI36PVSCustomizeSharedCollectionProtocol_
- ___swift_memcpy37_8
- ___unnamed_1
- _associated conformance 8PhotosUI20PVSHostConfigurationVyxGSHAASQ
- _flat unique 8PhotosUI16PVSAlbumProtocol_p
- _flat unique 8PhotosUI18PVSSyncNowProtocol_p
- _flat unique 8PhotosUI21PVSPostAssetsProtocol_p
- _flat unique 8PhotosUI33PVSCreateSharedCollectionProtocol_p
- _flat unique 8PhotosUI36PVSCustomizeSharedCollectionProtocol_p
- _swift_allocateGenericClassMetadata
- _swift_getEnumTagSinglePayloadGeneric
- _swift_initClassMetadata2
- _swift_retain_x24
- _swift_storeEnumTagSinglePayloadGeneric
- _symbolic $s8PhotosUI15PVSHostDelegateP
- _symbolic $s8PhotosUI16PVSAlbumProtocolP
- _symbolic $s8PhotosUI18PVSSyncNowProtocolP
- _symbolic $s8PhotosUI21PVSPostAssetsProtocolP
- _symbolic $s8PhotosUI33PVSCreateSharedCollectionProtocolP
- _symbolic $s8PhotosUI36PVSCustomizeSharedCollectionProtocolP
- _symbolic So15NSXPCConnectionCSg
- _symbolic So20EXHostViewControllerC
- _symbolic So20EXHostViewControllerCSg
- _symbolic _____ 10Foundation4UUIDV
- _symbolic _____ 19ExtensionFoundation03AppA8IdentityV
- _symbolic _____ 8PhotosUI17PVSViewControllerC
- _symbolic _____ 8PhotosUI20PVSAlbumHostDelegateC
- _symbolic _____ 8PhotosUI20PVSHostConfigurationV
- _symbolic _____ 8PhotosUI22PVSSyncNowHostDelegateC
- _symbolic _____ 8PhotosUI25PVSPostAssetsHostDelegateC
- _symbolic _____ 8PhotosUI27PVSClientAlbumConfigurationV
- _symbolic _____ 8PhotosUI37PVSCreateSharedCollectionHostDelegateC
- _symbolic _____ 8PhotosUI40PVSCustomizeSharedCollectionHostDelegateC
- _symbolic _____ 8PhotosUI41PVSClientSharedAlbumCreationConfigurationV
- _symbolic _____ 8PhotosUI46PVSClientSharedAlbumCustomizationConfigurationV
- _symbolic _____Sg 19ExtensionFoundation03AppA8IdentityV
- _symbolic _____Sg So20EXHostViewControllerC12ExtensionKitE13ConfigurationV
- _symbolic _____Sg So34PHSharedAlbumCreationSharingPolicyV
- _symbolic _____SgXw 8PhotosUI20PVSAlbumHostDelegateC
- _symbolic _____SgXw 8PhotosUI22PVSSyncNowHostDelegateC
- _symbolic _____SgXw 8PhotosUI25PVSPostAssetsHostDelegateC
- _symbolic _____SgXw 8PhotosUI37PVSCreateSharedCollectionHostDelegateC
- _symbolic _____SgXw 8PhotosUI40PVSCustomizeSharedCollectionHostDelegateC
- _symbolic _____SgXwz_Xx 8PhotosUI20PVSAlbumHostDelegateC
- _symbolic _____SgXwz_Xx 8PhotosUI22PVSSyncNowHostDelegateC
- _symbolic _____SgXwz_Xx 8PhotosUI25PVSPostAssetsHostDelegateC
- _symbolic _____SgXwz_Xx 8PhotosUI37PVSCreateSharedCollectionHostDelegateC
- _symbolic _____SgXwz_Xx 8PhotosUI40PVSCustomizeSharedCollectionHostDelegateC
- _symbolic ______p 8PhotosUI16PVSAlbumProtocolP
- _symbolic ______p 8PhotosUI18PVSSyncNowProtocolP
- _symbolic ______p 8PhotosUI21PVSPostAssetsProtocolP
- _symbolic ______p 8PhotosUI33PVSCreateSharedCollectionProtocolP
- _symbolic ______p 8PhotosUI36PVSCustomizeSharedCollectionProtocolP
- _symbolic _____yxGSg 8PhotosUI20PVSHostConfigurationV
- _symbolic ySbc
- _symbolic ytSg
- _symbolic ytSgIeAgHr_
- _type_layout_string 8PhotosUI27PVSClientAlbumConfigurationV
- _type_layout_string 8PhotosUI41PVSClientSharedAlbumCreationConfigurationV
- _type_layout_string 8PhotosUI46PVSClientSharedAlbumCustomizationConfigurationV
CStrings:
+ " doesn't conform to NSRemoteViewControllerDelegate"
+ "+[PHPickerFilter _groupsPeopleQuantityFilterWithMinimumMemberCount:maximumMemberCount:]"
+ "-[PUPickerGroupsPeopleQuantityFilter isEqual:]"
+ "-[_PHPickerSuggestionGroup _initWithSuggestions:defaultSuggestionIndex:isForWallpaper:defaultsToFaceMode:hasPinnedSuggestionItems:]"
+ "NSRemoteViewControllerWithDelegate.request failed: "
+ "NSRemoteViewControllerWithDelegate.request returned an unexpected controller type"
+ "PHPickerCollectionConfigurationCoderCustomKeyAssetIdentifiersKey"
+ "PHPickerSuggestionGroupCoderDefaultsToFaceModeKey"
+ "PHPickerSuggestionGroupCoderHasPinnedSuggestionItemsKey"
+ "PUPickerGroupsPeopleQuantityFilter: invalid member count range: [%ld, %ld]"
+ "PUPickerGroupsPeopleQuantityFilterDictionaryMaximumMemberCountKey"
+ "PUPickerGroupsPeopleQuantityFilterDictionaryMinimumMemberCountKey"
+ "PhotosUI/PHPickerOverlay.swift"
+ "Unsupported RangeExpression type: "
+ "com.apple.PhotosViewService.hiddenAlbum.header"
+ "com.apple.PhotosViewService.recentlyDeletedAlbum.header"
+ "host PVSViewBridgeViewController was deallocated before the remote view could attach"
+ "maximumMemberCount == 0 || minimumMemberCount <= maximumMemberCount"
+ "minimumMemberCount > 0 || maximumMemberCount > 0"
+ "minimumMemberCount >= 0 && maximumMemberCount >= 0"
+ "pinnedItemIdentifiersKey"
- "%s: Error connecting to extension: %@"
- "%s: Failed to make XPC connection."
- "%s: Host view controller did activate."
- "%s: XPC Connection was interrupted."
- "%s: XPC Connection was invalidated."
- "%s: XPC connection failed with error: %@"
- "-[_PHPickerSuggestionGroup _initWithSuggestions:defaultSuggestionIndex:isForWallpaper:]"
- ".assetCollection"
- ".createSharedCollection"
- ".customizeSharedCollection"
- ".hiddenAlbum.header"
- ".recentlyDeletedAlbum.header"
- ": Connection doesn't exist; not attempting to connect to proxy."
- ": Proxy object doesn't conform to PVSAlbumProtocol."
- ": Proxy object doesn't conform to PVSCreateSharedCollectionProtocol."
- ": Proxy object doesn't conform to PVSCustomizeSharedCollectionProtocol."
- ": Proxy object doesn't conform to PVSPostAssetsProtocol."
- ": Proxy object doesn't conform to PVSSyncNowProtocol."
- ": Unexpected number of identities: "
- "PhotosUI.PVSAlbumHostDelegate"
- "PhotosUI.PVSCreateSharedCollectionHostDelegate"
- "PhotosUI.PVSCustomizeSharedCollectionHostDelegate"
- "PhotosUI.PVSPostAssetsHostDelegate"
- "PhotosUI.PVSSyncNowHostDelegate"
- "PhotosUI/PVSAlbumHostDelegate.swift"
- "PhotosUI/PVSCreateSharedCollectionHostDelegate.swift"
- "PhotosUI/PVSCustomizeSharedCollectionHostDelegate.swift"
- "PhotosUI/PVSPostAssetsHostDelegate.swift"
- "PhotosUI/PVSSyncNowHostDelegate.swift"
- "PhotosUI/PVSUtilities.swift"
- "PhotosUI/PVSViewController.swift"
```
