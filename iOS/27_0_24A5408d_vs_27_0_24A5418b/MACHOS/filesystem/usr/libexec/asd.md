## asd

> `/usr/libexec/asd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x829110` | `0x830a38` | **`+0x7928`** |
| `__TEXT.__cstring` | `0x2c82` | `0x3342` | **`+0x6c0`** |
| `__TEXT.__const` | `0xd0e70` | `0xd10f0` | **`+0x280`** |
| `__TEXT.__eh_frame` | `0x6c50` | `0x6e50` | **`+0x200`** |
| `__DATA.__bss` | `0x7b30` | `0x7cb0` | **`+0x180`** |
| `__DATA.__data` | `0xebc0` | `0xed30` | **`+0x170`** |
| `__TEXT.__auth_stubs` | `0x30e0` | `0x3210` | **`+0x130`** |
| `__TEXT.__swift5_reflstr` | `0x176d` | `0x189d` | **`+0x130`** |
| `__TEXT.__unwind_info` | `0x46f8` | `0x4818` | **`+0x120`** |
| `__DATA.__objc_data` | `0x2ea0` | `0x2fb0` | **`+0x110`** |
| `__TEXT.__constg_swiftt` | `0x2014` | `0x2120` | **`+0x10c`** |
| `__TEXT.__swift5_fieldmd` | `0x1ef8` | `0x2000` | **`+0x108`** |
| `__TEXT.__swift5_typeref` | `0x1f5d` | `0x2053` | **`+0xf6`** |
| `__DATA.__objc_const` | `0x8250` | `0x8340` | **`+0xf0`** |
| `__DATA_CONST.__const` | `0x28fd8` | `0x29098` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0xa334` | `0xa3f4` | **`+0xc0`** |
| `__DATA_CONST.__auth_got` | `0x1880` | `0x1918` | **`+0x98`** |
| `__TEXT.__objc_stubs` | `0x7580` | `0x75e0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x35c4` | `0x360c` | **`+0x48`** |
| `__DATA_CONST.__auth_ptr` | `0x6c8` | `0x700` | **`+0x38`** |
| `__TEXT.__objc_classname` | `0xcd9` | `0xd09` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x2160` | `0x2180` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x11c2b` | `0x11c4b` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x3987` | `0x39a7` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x2280` | `0x2298` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x1128` | `0x113c` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x488` | `0x49c` | **`+0x14`** |
| `__DATA_CONST.__got` | `0xe70` | `0xe80` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x23c` | `0x24c` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x288` | `0x298` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x2d4` | `0x2e4` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x52c` | `0x538` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x3d0` | `0x3d8` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x5c` | `0x64` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_ivar`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`

### Other Changes

```diff

+  - /System/Library/PrivateFrameworks/HybridSearch.framework/HybridSearch

-  Functions: 6303
-  Symbols:   2022
-  CStrings:  2713
+  Functions: 6373
+  Symbols:   2066
+  CStrings:  2732
Symbols:
+ _$s12HybridSearch0aB6ClientC12performCountys5Int64VAA15ComposableQueryVyxGYaKAA17SearchableContentRzlFTjTu
+ _$s12HybridSearch0aB6ClientC17useCaseIdentifierAcA03UseeF0V_tcfC
+ _$s12HybridSearch0aB6ClientCMa
+ _$s12HybridSearch0aB6ClientCMn
+ _$s12HybridSearch11MailContentVAA010SearchableD0AAMc
+ _$s12HybridSearch11MailContentVMa
+ _$s12HybridSearch11MailContentVMn
+ _$s12HybridSearch15ComposableQueryV2oryACyxGAEF
+ _$s12HybridSearch15ComposableQueryVA2A11MailContentVRszrlE10ccContainsyACyAEGSSF
+ _$s12HybridSearch15ComposableQueryVA2A11MailContentVRszrlE10toContainsyACyAEGSSF
+ _$s12HybridSearch15ComposableQueryVA2A11MailContentVRszrlE14senderContainsyACyAEGSSF
+ _$s12HybridSearch15ComposableQueryVA2A11MailContentVRszrlE26withSourceBundleIdentifieryACyAEGSSF
+ _$s12HybridSearch15ComposableQueryVA2A11MailContentVRszrlE5afteryACyAEG10Foundation4DateVF
+ _$s12HybridSearch15ComposableQueryVA2A11MailContentVRszrlE6beforeyACyAEG10Foundation4DateVF
+ _$s12HybridSearch15ComposableQueryVA2A11MailContentVRszrlE9inMailboxyACyAEGSSF
+ _$s12HybridSearch15ComposableQueryVACyxGycfC
+ _$s12HybridSearch15ComposableQueryVMn
+ _$s12HybridSearch17UseCaseIdentifierV8rawValueACSS_tcfC
+ _$s12HybridSearch17UseCaseIdentifierVMa
+ _$s17_StringProcessing5RegexV06_regexA07versionACyxGSS_SitcfC
+ _$s17_StringProcessing5RegexV10firstMatch2inAC0E0Vyx_GSgSS_tKF
+ _$s17_StringProcessing5RegexV5MatchV6outputxvg
+ _$s17_StringProcessing5RegexVMa
+ _$s3asd14MailSearchableMp
+ _$s3asd14MailSearchableTL
+ _$s3asd22HybridSearchMailHelperC20mailPredicateMatcher33_F74BF9F04537505061E7CA1F8687BC7DLLAA0dG8Matching_pvpfi
+ _$s3asd22HybridSearchMailHelperC5counts5Int64VyYaKF
+ _$s3asd22HybridSearchMailHelperC5counts5Int64VyYaKFTq
+ _$s3asd22HybridSearchMailHelperC5counts5Int64VyYaKFTu
+ _$s3asd22HybridSearchMailHelperC6client9predicate8maxCountAcA0D10Searchable_p_So8NSStringCSitcfC
+ _$s3asd22HybridSearchMailHelperC6client9predicate8maxCountAcA0D10Searchable_p_So8NSStringCSitcfCTq
+ _$s3asd22HybridSearchMailHelperC6client9predicate8maxCountAcA0D10Searchable_p_So8NSStringCSitcfc
+ _$s3asd22HybridSearchMailHelperC8bundleID33_F74BF9F04537505061E7CA1F8687BC7DLLSSvpfi
+ _$s3asd22HybridSearchMailHelperC9predicate8maxCountACSo8NSStringC_SitcfC
+ _$s3asd22HybridSearchMailHelperC9predicate8maxCountACSo8NSStringC_Sitcfc
+ _$s3asd22HybridSearchMailHelperCACycfC
+ _$s3asd22HybridSearchMailHelperCACycfc
+ _$s3asd22HybridSearchMailHelperCMa
+ _$s3asd22HybridSearchMailHelperCMn
+ _$s3asd22HybridSearchMailHelperCN
+ _$s3asd22HybridSearchMailHelperCfD
+ _$sSS14_fromSubstringySSSshFZ
+ _OBJC_CLASS_$__TtC3asd22HybridSearchMailHelper
+ _OBJC_METACLASS_$__TtC3asd22HybridSearchMailHelper
CStrings:
+ "/^\\s*\\(?\\s*kMDItemContentType\\s*==\\s*\"public.email-message\"\\s*&&\\s*_kMDItemBundleID\\s*\\==\\s*\"com.apple.mobilemail\"\\)?\\s*&&\\s*\\(+\\s*kMDItemRecipients\\s*==\\s*\"([^\"]+)\"cdw\\s*\\|\\|\\s*kMDItemPrimaryRecipientEmailAddresses\\s*==\\s*\"\\*.+\\*\"cd\\)?\\s*\\|\\|\\s*\\(*\\s*kMDItemAuthors\\s*==\\s*\".+\"cdw\\s*\\|\\|\\s*kMDItemAuthorEmailAddresses\\s*==\\s*\"\\*.+\\*\"cd\\)+$/"
+ "/^\\s*\\(?\\s*kMDItemContentType\\s*==\\s*\"public.email-message\"\\s*&&\\s*_kMDItemBundleID\\s*\\==\\s*\"com.apple.mobilemail\"\\)?\\s*&&\\s*\\(+\\s*kMDItemRecipients\\s*==\\s*\"([^\"]+)\"cdw\\s*\\|\\|\\s*kMDItemPrimaryRecipientEmailAddresses\\s*==\\s*\"\\*.+\\*\"cd\\)?\\s*\\|\\|\\s*\\(*\\s*kMDItemAuthors\\s*==\\s*\".+\"cdw\\s*\\|\\|\\s*kMDItemAuthorEmailAddresses\\s*==\\s*\"\\*.+\\*\"cd\\)+\\s*&&\\s*\\(?\\s*kMDItemContentCreationDate\\s*<\\s*\\$time\\.now\\(-7776000\\)+$/"
+ "/^\\s*\\(?\\s*kMDItemContentType\\s*==\\s*\"public.email-message\"\\s*&&\\s*_kMDItemBundleID\\s*\\==\\s*\"com.apple.mobilemail\"\\)?\\s*&&\\s*\\(?\\s*kMDItemContentCreationDate\\s*>\\s*\\$time\\.now\\(-604800\\)\\)?\\s*$/"
+ "/^\\s*\\(?\\s*kMDItemContentType\\s*==\\s*\"public.email-message\"\\s*&&\\s*_kMDItemBundleID\\s*\\==\\s*\"com.apple.mobilemail\"\\)?\\s*\\&&\\s*\\(?kMDItemPrimaryRecipientEmailAddresses\\s*==\\s*\"([^\"]+)\"c\\s*&&\\s*kMDItemMailboxes\\s*==\\s*\"mailbox.sent\"\\s*\\)?\\s*&&\\s*\\(?\\s*kMDItemContentCreationDate\\s*<\\s*\\$time\\.now\\(-2592000\\)\\s*\\)?\\s*$/"
+ "/^\\s*\\(?\\s*kMDItemContentType\\s*==\\s*\"public.email-message\"\\s*&&\\s*_kMDItemBundleID\\s*\\==\\s*\"com.apple.mobilemail\"\\)?\\s*\\&&\\s*\\(?kMDItemPrimaryRecipientEmailAddresses\\s*==\\s*\"([^\"]+)\"c\\s*&&\\s*kMDItemMailboxes\\s*==\\s*\"mailbox.sent\"\\s*\\)?\\s*&&\\s*\\(?\\s*kMDItemContentCreationDate\\s*<\\s*\\$time\\.now\\(0\\)\\s*\\)?\\s*$/"
+ "Error fetching count from GLP: %@\n"
+ "_TtC3asd22HybridSearchMailHelper"
+ "asd.HybridSearchMailHelper"
+ "bundleID"
+ "com.apple.mobilemail"
+ "countWithCompletionHandler:"
+ "hybridMailSearchClient"
+ "initWithPredicate:maxCount:"
+ "isMailQuery:"
+ "kMDItemContentType == \"public.email-message\""
+ "mailPredicateMatcher"
+ "maxCount"
+ "predicate"
+ "v24@0:8@?<v@?q@\"NSError\">16"
```
