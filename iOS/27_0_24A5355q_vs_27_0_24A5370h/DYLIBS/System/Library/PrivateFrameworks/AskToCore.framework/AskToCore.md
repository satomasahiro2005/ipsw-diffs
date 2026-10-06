## AskToCore

> `/System/Library/PrivateFrameworks/AskToCore.framework/AskToCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x882f4` | `0x91cf4` | **`+0x9a00`** |
| `__TEXT.__const` | `0x8294` | `0x84f4` | **`+0x260`** |
| `__DATA.__data` | `0x1ca0` | `0x1e80` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0x21ba` | `0x238a` | **`+0x1d0`** |
| `__DATA.__bss` | `0xe090` | `0xe210` | **`+0x180`** |
| `__AUTH_CONST.__const` | `0x5430` | `0x52e8` | **`-0x148`** |
| `__TEXT.__unwind_info` | `0x2570` | `0x2658` | **`+0xe8`** |
| `__DATA_CONST.__objc_selrefs` | `0x688` | `0x768` | **`+0xe0`** |
| `__TEXT.__eh_frame` | `0x2fb8` | `0x3080` | **`+0xc8`** |
| `__TEXT.__cstring` | `0x3283` | `0x3303` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0xd60` | `0xdb0` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x1dbc` | `0x1e00` | **`+0x44`** |
| `__TEXT.__swift5_typeref` | `0x1dd4` | `0x1e18` | **`+0x44`** |
| `__TEXT.__swift5_assocty` | `0x3a8` | `0x378` | **`-0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x2350` | `0x2370` | **`+0x20`** |
| `__DATA.__common` | `0x280` | `0x298` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x2ab0` | `0x2aa0` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x3a8` | `0x398` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x744` | `0x754` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1d7c` | `0x1d8c` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x50` | `0x54` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x250` | `0x254` | **`+0x4`** |

### Other Changes

```diff

-88.0.0.0.0
+90.1.0.0.0

+  - /System/Library/PrivateFrameworks/vCard.framework/vCard

-  Functions: 3357
-  Symbols:   1305
-  CStrings:  486
+  Functions: 3437
+  Symbols:   1318
+  CStrings:  495
Symbols:
+ _OBJC_CLASS_$_CNLabeledValue
+ _OBJC_CLASS_$_CNMutableContact
+ _OBJC_CLASS_$_CNVCardWritingOptions
+ __swift_stdlib_strtod_clocale
+ _associated conformance 9AskToCore13ATApplicationV10CodingKeysOSHAASQ
+ _associated conformance 9AskToCore13ATApplicationV10CodingKeysOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 9AskToCore13ATApplicationV10CodingKeysOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 9AskToCore21_ATPayload_Deprecated33_5ABD3F553B1D5C9771EFF65AEF248FBELLV10CodingKeysOSHAASQ
+ _associated conformance 9AskToCore21_ATPayload_Deprecated33_5ABD3F553B1D5C9771EFF65AEF248FBELLV10CodingKeysOs0N3KeyAAs23CustomStringConvertible
+ _associated conformance 9AskToCore21_ATPayload_Deprecated33_5ABD3F553B1D5C9771EFF65AEF248FBELLV10CodingKeysOs0N3KeyAAs28CustomDebugStringConvertible
+ _get_enum_tag_for_layout_string 10Foundation4DataV15_RepresentationO
+ _get_enum_tag_for_layout_string 10Foundation4DataVSg
+ _swift_retain_x26
+ _symbolic $s9AskToCore16ContactResolvingP
+ _symbolic _____ 9AskToCore13ATApplicationV10CodingKeysO
+ _symbolic _____ 9AskToCore21_ATPayload_Deprecated33_5ABD3F553B1D5C9771EFF65AEF248FBELLV
+ _symbolic _____ 9AskToCore21_ATPayload_Deprecated33_5ABD3F553B1D5C9771EFF65AEF248FBELLV10CodingKeysO
+ _symbolic _____Sg 9AskToCore4IconV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 9AskToCore13ATApplicationV10CodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 9AskToCore21_ATPayload_Deprecated33_5ABD3F553B1D5C9771EFF65AEF248FBELLV10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 9AskToCore13ATApplicationV10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 9AskToCore21_ATPayload_Deprecated33_5ABD3F553B1D5C9771EFF65AEF248FBELLV10CodingKeysO
+ _type_layout_string 9AskToCore21_ATPayload_Deprecated33_5ABD3F553B1D5C9771EFF65AEF248FBELLV
- _associated conformance 9AskToCore13ATApplicationV10CodingKeys33_2D22B03A6F7FB991CC31CC62988E0A86LLOSHAASQ
- _associated conformance 9AskToCore13ATApplicationV10CodingKeys33_2D22B03A6F7FB991CC31CC62988E0A86LLOs0E3KeyAAs23CustomStringConvertible
- _associated conformance 9AskToCore13ATApplicationV10CodingKeys33_2D22B03A6F7FB991CC31CC62988E0A86LLOs0E3KeyAAs28CustomDebugStringConvertible
- _associated conformance 9AskToCore13ATApplicationVs12IdentifiableAA2IDsADP_SH
- _associated conformance 9AskToCore4IconV6SourceOSHAASQ
- _symbolic _____ 9AskToCore13ATApplicationV10CodingKeys33_2D22B03A6F7FB991CC31CC62988E0A86LLO
- _symbolic _____ 9AskToCore4IconV6SourceO
- _symbolic _____y_____G s22KeyedDecodingContainerV 9AskToCore13ATApplicationV10CodingKeys33_2D22B03A6F7FB991CC31CC62988E0A86LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 9AskToCore13ATApplicationV10CodingKeys33_2D22B03A6F7FB991CC31CC62988E0A86LLO
- _symbolic _____y_____G s23_ContiguousArrayStorageC 9AskToCore4IconV6SourceO
CStrings:
+ "\nresponseExtensionButtonTitle: "
+ "%s: Injected an icon into ATApplication.stashedIcon"
+ "%s: No icon in payload to inject. Bailing"
+ "%s: Using ATApplication with no bundle ID"
+ "Decoded vCardData: %ld, contacts: %ld"
+ "Encoded vCardData: %ld"
+ "Failed to decode _ATPayload_Deprecated from ATPayload. Error: %@"
+ "Icon image compression failed. Error: %@"
+ "Resized and downsampled icon image data was nil"
+ "VisualRepresentation"
+ "com.apple.Safari"
+ "com.apple.iBooks"
+ "com.apple.mobilesafari"
+ "contacts: %ld, nonEmptyContacts: %ld"
+ "injectIconIfNeeded(from:parameter:compressedLegacyData:existingApplication:write:)"
+ "responseExtensionButtonTitle"
- "\nassociatedContentIconData: "
- "\nclientIconData: "
- "iconServices"
- "knownClient"
- "mediaAPI"
- "payloadClientIconData"
- "storeAdamIdentifier"
```
