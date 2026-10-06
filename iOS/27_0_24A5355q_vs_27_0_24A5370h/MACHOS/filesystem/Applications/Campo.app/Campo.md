## Campo

> `/Applications/Campo.app/Campo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdf0c` | `0xd900` | **`-0x60c`** |
| `__DATA.__bss` | `0x480` | `0x580` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x7b8` | `0x8a0` | **`+0xe8`** |
| `__TEXT.__cstring` | `0x46d` | `0x39d` | **`-0xd0`** |
| `__TEXT.__eh_frame` | `0xaa8` | `0xa00` | **`-0xa8`** |
| `__TEXT.__const` | `0x5b4` | `0x634` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0xe50` | `0xe20` | **`-0x30`** |
| `__TEXT.__constg_swiftt` | `0x28c` | `0x2bc` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0xd72` | `0xda2` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x43e` | `0x462` | **`+0x24`** |
| `__DATA.__objc_const` | `0x950` | `0x930` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x17ec` | `0x17cc` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0x24c` | `0x268` | **`+0x1c`** |
| `__DATA_CONST.__auth_got` | `0x730` | `0x718` | **`-0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x218` | `0x230` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x74` | `0x60` | **`-0x14`** |
| `__DATA_CONST.__got` | `0x1f8` | `0x208` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x18c` | `0x17c` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1cc` | `0x1c0` | **`-0xc`** |
| `__TEXT.__swift5_proto` | `0x24` | `0x2c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x40` | `0x38` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x5d8` | `0x5d0` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x38` | `0x3c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-60.105.0.0.0
+67.4.100.0.0

+  - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics

-  Functions: 433
-  Symbols:   394
-  CStrings:  318
+  Functions: 453
+  Symbols:   395
+  CStrings:  313
Symbols:
+ _$s15CampoUIInternal0A23DefaultSceneContentViewV17campoServerDomain6chatID08retargetD2ToAcA0ahI0C_AA04ChatK0VSgyAJcSgtcfC
+ _$s15CampoUIInternal18CarPlayImageLoaderC04loadE03for10targetSizeSo7UIImageCSgAA0cD16ConversationItemV_So6CGSizeVtYaF
+ _$s15CampoUIInternal18CarPlayImageLoaderC04loadE03for10targetSizeSo7UIImageCSgAA0cD16ConversationItemV_So6CGSizeVtYaFTu
+ _$s15CampoUIInternal18CarPlayImageLoaderC08loadCardE03for12cornerRadius10renderSize07displayM00N5ScaleSo7UIImageCAA0cD16ConversationItemV_12CoreGraphics7CGFloatVSo6CGSizeVArPtYaF
+ _$s15CampoUIInternal18CarPlayImageLoaderC08loadCardE03for12cornerRadius10renderSize07displayM00N5ScaleSo7UIImageCAA0cD16ConversationItemV_12CoreGraphics7CGFloatVSo6CGSizeVArPtYaFTu
+ _$s15CampoUIInternal26CarPlayConversationSectionV4KindO5datedyA2EmFWC
+ _$s15CampoUIInternal26CarPlayConversationSectionV4KindO6pinnedyA2EmFWC
+ _$s15CampoUIInternal26CarPlayConversationSectionV4KindOMa
+ _$s15CampoUIInternal26CarPlayConversationSectionV4KindOMn
+ _$s15CampoUIInternal26CarPlayConversationSectionV4kindAC4KindOvg
+ _$s15CampoUIInternal26CarPlayConversationSectionV5itemsSayAA0cdE4ItemVGvg
+ _$s15CampoUIInternal26CarPlayConversationSectionV5titleSSSgvg
+ _$s15CampoUIInternal26CarPlayConversationSectionVMa
+ _$s15CampoUIInternal26CarPlayConversationSectionVMn
+ _$s15CampoUIInternal29CarPlayConversationDataSourceC20conversationSectionsSayAA0cdE7SectionVGvg
+ _$s19SpotlightUIInternal0A12BootstrapperC9bootstrapyyFZ
+ _$s19SpotlightUIInternal0A12BootstrapperCMa
+ _$sSS15CampoUIInternalE0A0V32chatSectionTitleForConversationsSSvgZ
+ _$sSS15CampoUIInternalE0A0V38chatSectionTitleForPinnedConversationsSSvgZ
+ _$ss27_diagnoseUnexpectedEnumCase4types5NeverOxm_tlF
+ _$ss6HasherV8_combineyySuF
+ _CGContextFillRect
+ _CGContextSetFillColorWithColor
+ _OBJC_CLASS_$_UIGraphicsImageRenderer
+ _objc_retain_x1
+ _swift_isEscapingClosureAtFileLocation
- _$s10Foundation6LocaleV7currentACvgZ
- _$s10Foundation6LocaleVMa
- _$s15CampoUIInternal0A23DefaultSceneContentViewV17campoServerDomain6chatIDAcA0ahI0C_AA04ChatK0VSgtcfC
- _$s15CampoUIInternal18CarPlayImageLoaderC012generateCardE05title10headerText7summary5image10targetSize12displayScaleSo7UIImageCSS_SSSgAmLSgSo6CGSizeV12CoreGraphics7CGFloatVtYaF
- _$s15CampoUIInternal18CarPlayImageLoaderC012generateCardE05title10headerText7summary5image10targetSize12displayScaleSo7UIImageCSS_SSSgAmLSgSo6CGSizeV12CoreGraphics7CGFloatVtYaFTu
- _$s15CampoUIInternal18CarPlayImageLoaderC04loadE03for10headerText10targetSize12displayScaleSo7UIImageCAA0cD16ConversationItemV_SSSgSo6CGSizeV12CoreGraphics7CGFloatVtYaF
- _$s15CampoUIInternal18CarPlayImageLoaderC04loadE03for10headerText10targetSize12displayScaleSo7UIImageCAA0cD16ConversationItemV_SSSgSo6CGSizeV12CoreGraphics7CGFloatVtYaFTu
- _$s15CampoUIInternal18CarPlayImageLoaderC04loadE9FromAsset10identifier10targetSizeSo7UIImageCSgSS_So6CGSizeVtYaF
- _$s15CampoUIInternal18CarPlayImageLoaderC04loadE9FromAsset10identifier10targetSizeSo7UIImageCSgSS_So6CGSizeVtYaFTu
- _$s15CampoUIInternal23CarPlayConversationItemV10headerTextSSvg
- _$s15CampoUIInternal23CarPlayConversationItemV14thumbnailImageSo7UIImageCSgvg
- _$s15CampoUIInternal23CarPlayConversationItemV24thumbnailAssetIdentifierSSSgvg
- _$sSS10FoundationE17LocalizationValueV13stringLiteralACSS_tcfC
- _$sSS10FoundationE17LocalizationValueVMa
- _$sSS10FoundationE9localized5table6bundle6locale7commentS2SAAE17LocalizationValueV_SSSgSo8NSBundleCSgAA6LocaleVs12StaticStringVSgtcfC
- _$sSa10FoundationE36_unconditionallyBridgeFromObjectiveCySayxGSo7NSArrayCSgFZ
- _$ss12_ArrayBufferV19_getElementSlowPathyyXlSiFyXl_Ts5
- _objc_release_x25
- _objc_release_x26
- _objc_release_x27
- _objc_retain_x26
- _swift_arrayInitWithTakeBackToFront
- _swift_arrayInitWithTakeFrontToBack
- _swift_getObjCClassFromObject
- _swift_release_x28
CStrings:
+ "CGContext"
+ "bundleForClass:"
+ "imageNamed:inBundle:withConfiguration:"
+ "imageWithActions:"
+ "initWithIdentifier:titleVariants:image:backgroundImage:repeats:"
+ "initWithSize:"
+ "setTrailingImage:"
+ "setUseCampoGlass:"
+ "v16@?0@\"UIGraphicsImageRendererContext\"8"
- "bundleWithIdentifier:"
- "chatSectionTitleForConversations"
- "chatSectionTitleForPinnedChats"
- "chatSectionTitleForPinnedConversations"
- "chatSectionTitleForRecentChats"
- "com.apple.CampoUIInternal"
- "images"
- "initWithIdentifier:titleVariants:image:repeats:"
- "localizationBundle"
- "mainBundle"
- "setBackgroundImage:"
- "setImage:"
- "setThumbnail:"
- "systemImageNamed:"
```
