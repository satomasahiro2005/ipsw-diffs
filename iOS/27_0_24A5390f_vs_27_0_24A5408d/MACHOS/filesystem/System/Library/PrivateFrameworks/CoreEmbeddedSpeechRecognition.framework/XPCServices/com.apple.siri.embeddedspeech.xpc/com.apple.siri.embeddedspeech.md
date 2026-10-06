## com.apple.siri.embeddedspeech

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/XPCServices/com.apple.siri.embeddedspeech.xpc/com.apple.siri.embeddedspeech`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33468` | `0x33cdc` | **`+0x874`** |
| `__TEXT.__objc_methname` | `0xa51c` | `0xa6dc` | **`+0x1c0`** |
| `__DATA_CONST.__objc_intobj` | `0xf0` | `0x240` | **`+0x150`** |
| `__TEXT.__objc_stubs` | `0x83c0` | `0x8500` | **`+0x140`** |
| `__TEXT.__cstring` | `0x4e02` | `0x4e7f` | **`+0x7d`** |
| `__DATA.__objc_const` | `0x3200` | `0x3260` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x24d8` | `0x2528` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x4b37` | `0x4b76` | **`+0x3f`** |
| `__DATA_CONST.__const` | `0xce0` | `0xd00` | **`+0x20`** |
| `__DATA.__bss` | `0x148` | `0x158` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x858` | `0x868` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x960` | `0x970` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1cec` | `0x1cfc` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x1c0a` | `0x1c1a` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2f8` | `0x304` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x4c0` | `0x4c8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x790` | `0x798` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x1b80` | `0x1b84` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-3600.70.32.0.0
+3600.70.47.0.0

-  Functions: 609
-  Symbols:   425
-  CStrings:  2550
+  Functions: 611
+  Symbols:   428
+  CStrings:  2564
Symbols:
+ _OBJC_CLASS_$_CCASRRankedEntityTermMetaContent
+ _OBJC_CLASS_$_CCItemInstance
+ ___udivti3
CStrings:
+ "%s No Cascade field type mapping for contact component key: %@"
+ "+[ESContactItemProcessor recordEnrolledContactEntitiesInMetrics:firstPartyContacts:thirdPartyContacts:groupNames:]"
+ "-[ESSpeechProfileBuilderConnection beginWithCategoriesAndVersions:trigger:completion:]"
+ "@84@0:8@16@24B32@36@44@52@60@68@76"
+ "S"
+ "Vv40@0:8@\"NSDictionary\"16@\"NSString\"24@?<v@?B@\"NSError\">32"
+ "_speechProfileMetrics"
+ "addEnrolledEntitiesCount:forCascadeFieldType:"
+ "addEnrolledEntityForCascadeFieldType:"
+ "beginWithCategoriesAndVersions:trigger:completion:"
+ "initWithEntityCleanupConfig:entityCleanupHandler:speechProfileMetrics:"
+ "initWithEntityCleanupHandler:entityCleanupConfig:speechProfileMetrics:"
+ "initWithEntityCleanupHandler:entityExtractionHandler:enableDatatypeCleanupFromNonAppEntities:appEntityConfig:extractedEntityBudget:entitiesExtractedPerCategory:applicableSpeechCategories:entityCleanupConfig:speechProfileMetrics:"
+ "interactionOnlyRanking"
+ "logASRSpeechProfileUpdateStartedWithTrigger:"
+ "metaContent"
+ "numEnrolledEntitiesPerCascadeFieldType"
+ "rank"
+ "recordEnrolledContactEntitiesInMetrics:firstPartyContacts:thirdPartyContacts:groupNames:"
+ "setSpeechProfileSize:"
+ "unsignedShortValue"
- "-[ESSpeechProfileBuilderConnection beginWithCategoriesAndVersions:completion:]"
- "@76@0:8@16@24B32@36@44@52@60@68"
- "Vv32@0:8@\"NSDictionary\"16@?<v@?B@\"NSError\">24"
- "beginWithCategoriesAndVersions:completion:"
- "initWithEntityCleanupConfig:entityCleanupHandler:"
- "initWithEntityCleanupHandler:entityExtractionHandler:enableDatatypeCleanupFromNonAppEntities:appEntityConfig:extractedEntityBudget:entitiesExtractedPerCategory:applicableSpeechCategories:entityCleanupConfig:"
- "logASRSpeechProfileUpdateStarted"
```
