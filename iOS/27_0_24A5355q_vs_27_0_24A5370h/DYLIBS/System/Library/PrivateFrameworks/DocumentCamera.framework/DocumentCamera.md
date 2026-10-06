## DocumentCamera

> `/System/Library/PrivateFrameworks/DocumentCamera.framework/DocumentCamera`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa4540` | `0xa4e18` | **`+0x8d8`** |
| `__AUTH.__objc_data` | `0x1030` | `0x10e0` | **`+0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0x6228` | `0x62a0` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x9714` | `0x9774` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x942c` | `0x9484` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x150c0` | `0x15108` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0xd64` | `0xd90` | **`+0x2c`** |
| `__AUTH.__data` | `0x478` | `0x4a0` | **`+0x28`** |
| `__TEXT.__const` | `0x1a74` | `0x1a94` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2fe0` | `0x3000` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xa30` | `0xa48` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x6f4` | `0x704` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xfb0` | `0xfb8` | **`+0x8`** |
| `__DATA.__common` | `0x48` | `0x40` | **`-0x8`** |
| `__DATA.__data` | `0x14c0` | `0x14b8` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x390` | `0x398` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x530` | `0x536` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0x84` | `0x88` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-205.0.0.0.0
+208.0.0.0.0

-  Functions: 4164
-  Symbols:   6436
+  Functions: 4174
+  Symbols:   6450
Symbols:
+ +[DCDocCamPDFGenerator blockingGeneratepdfURLForDocumentInfoCollection:imageURLs:dataCryptor:withProgress:error:]
+ +[DCDocCamPDFGenerator imageAtURL:uuid:dataCryptor:]
+ +[DCDocCamPDFGenerator performPDFGenerationWithGenerator:docInfoCollection:imageURLs:dataCryptor:progress:]
+ -[ICDocCamExtractedDocumentViewController _makeBarButtonItemFromPillButton:]
+ -[ICDocCamExtractedDocumentViewController _makePillButtonWithSymbol:subtitle:]
+ -[ICDocCamExtractedDocumentViewController actionButton]
+ -[ICDocCamExtractedDocumentViewController addButton]
+ -[ICDocCamExtractedDocumentViewController pillContainerView]
+ -[ICDocCamExtractedDocumentViewController setActionButton:]
+ -[ICDocCamExtractedDocumentViewController setAddButton:]
+ -[ICDocCamExtractedDocumentViewController setPillContainerView:]
+ -[ICDocCamExtractedDocumentViewController updateBottomToolbarPresentation]
+ -[ICDocCamExtractedDocumentViewController updateToolbarItemsForCurrentMode]
+ _NSSelectorFromString
+ _OBJC_CLASS_$_DCGlassHelper
+ _OBJC_CLASS_$_UIButtonConfiguration
+ _OBJC_IVAR_$_ICDocCamExtractedDocumentViewController._actionButton
+ _OBJC_IVAR_$_ICDocCamExtractedDocumentViewController._addButton
+ _OBJC_IVAR_$_ICDocCamExtractedDocumentViewController._pillContainerView
+ _OBJC_METACLASS_$_DCGlassHelper
+ _UIFontTextStyleCallout
+ __CLASS_METHODS_DCGlassHelper
+ __DATA_DCGlassHelper
+ __INSTANCE_METHODS_DCGlassHelper
+ __METACLASS_DATA_DCGlassHelper
+ ___107+[DCDocCamPDFGenerator performPDFGenerationWithGenerator:docInfoCollection:imageURLs:dataCryptor:progress:]_block_invoke
+ ___107+[DCDocCamPDFGenerator performPDFGenerationWithGenerator:docInfoCollection:imageURLs:dataCryptor:progress:]_block_invoke_2
+ ___113+[DCDocCamPDFGenerator blockingGeneratepdfURLForDocumentInfoCollection:imageURLs:dataCryptor:withProgress:error:]_block_invoke
+ ___113+[DCDocCamPDFGenerator blockingGeneratepdfURLForDocumentInfoCollection:imageURLs:dataCryptor:withProgress:error:]_block_invoke_2
+ ___block_descriptor_80_e8_32s40s48s56s64r_e37_v32?0"ICDocCamDocumentInfo"8Q16^B24ls32l8s40l8s48l8r64l8s56l8
+ ___block_descriptor_80_e8_32s40s48s56s64r_e5_v8?0ls32l8s40l8s48l8s56l8r64l8
+ ___block_descriptor_88_e8_32s40s48s56s64r72r80r_e20_v16?0"NSProgress"8lr64l8s32l8s40l8s48l8r72l8r80l8s56l8
+ _symbolic _____ 14DocumentCamera11GlassHelperC
- +[DCDocCamPDFGenerator blockingGeneratepdfURLForDocumentInfoCollection:imageCache:withProgress:error:]
- +[DCDocCamPDFGenerator performPDFGenerationWithGenerator:docInfoCollection:imageCache:progress:]
- -[ICDocCamExtractedDocumentViewController actionLabelledButton]
- -[ICDocCamExtractedDocumentViewController addLabelledButton]
- -[ICDocCamExtractedDocumentViewController glurBar]
- -[ICDocCamExtractedDocumentViewController setActionLabelledButton:]
- -[ICDocCamExtractedDocumentViewController setAddLabelledButton:]
- -[ICDocCamExtractedDocumentViewController setGlurBar:]
- -[ICDocCamExtractedDocumentViewController setupGlurBar]
- _OBJC_IVAR_$_ICDocCamExtractedDocumentViewController._actionLabelledButton
- _OBJC_IVAR_$_ICDocCamExtractedDocumentViewController._addLabelledButton
- _OBJC_IVAR_$_ICDocCamExtractedDocumentViewController._glurBar
- ___102+[DCDocCamPDFGenerator blockingGeneratepdfURLForDocumentInfoCollection:imageCache:withProgress:error:]_block_invoke
- ___102+[DCDocCamPDFGenerator blockingGeneratepdfURLForDocumentInfoCollection:imageCache:withProgress:error:]_block_invoke_2
- ___96+[DCDocCamPDFGenerator performPDFGenerationWithGenerator:docInfoCollection:imageCache:progress:]_block_invoke
- ___96+[DCDocCamPDFGenerator performPDFGenerationWithGenerator:docInfoCollection:imageCache:progress:]_block_invoke_2
- ___block_descriptor_64_e8_32s40s48s56r_e37_v32?0"ICDocCamDocumentInfo"8Q16^B24ls32l8s40l8r56l8s48l8
- ___block_descriptor_72_e8_32s40s48s56r_e5_v8?0ls32l8s40l8s48l8r56l8
- ___block_descriptor_80_e8_32s40s48s56r64r72r_e20_v16?0"NSProgress"8lr56l8s32l8s40l8r64l8r72l8s48l8
CStrings:
+ "\"\xf0Q\xc2"
- "\"\xf0A\xc2"
```
