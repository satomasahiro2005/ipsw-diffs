## com.apple.siri.embeddedspeech

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/XPCServices/com.apple.siri.embeddedspeech.xpc/com.apple.siri.embeddedspeech`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x4ad1` | `0x4d58` | **`+0x287`** |
| `__DATA_CONST.__cfstring` | `0x2bc0` | `0x2de0` | **`+0x220`** |
| `__TEXT.__oslogstring` | `0x4cab` | `0x4b2c` | **`-0x17f`** |
| `__TEXT.__text` | `0x332e4` | `0x331ac` | **`-0x138`** |
| `__TEXT.__objc_stubs` | `0x8440` | `0x83a0` | **`-0xa0`** |
| `__TEXT.__objc_methname` | `0xa5ab` | `0xa515` | **`-0x96`** |
| `__DATA_CONST.__got` | `0x848` | `0x818` | **`-0x30`** |
| `__DATA.__objc_selrefs` | `0x24f8` | `0x24d0` | **`-0x28`** |
| `__DATA_CONST.__const` | `0xcd8` | `0xcb8` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1b78` | `0x1b8c` | **`+0x14`** |
| `__DATA.__bss` | `0x150` | `0x140` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x1cf4` | `0x1cec` | **`-0x8`** |
| `__TEXT.__objc_methtype` | `0x1c0c` | `0x1c0a` | **`-0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.64.114.1.5
+3600.70.8.0.0

-  Functions: 610
-  Symbols:   431
-  CStrings:  2538
+  Functions: 607
+  Symbols:   425
+  CStrings:  2546
Symbols:
+ _NSDebugDescriptionErrorKey
+ _OBJC_CLASS_$_CESREncryptedLogger
- _NSTextCheckingCityKey
- _NSTextCheckingCountryKey
- _NSTextCheckingPhoneKey
- _NSTextCheckingStateKey
- _NSTextCheckingStreetKey
- _NSTextCheckingZIPKey
- _OBJC_CLASS_$_NSDataDetector
- _OBJC_CLASS_$_NSMutableCharacterSet
CStrings:
+ "%s (%@) %@"
+ "%s (%@) Created new version file (%@) for fresh database."
+ "%s (%@) Embedding insertion cancelled"
+ "%s Adding #radio vocab to speech profile"
+ "%s Donating edit record to Biome"
+ "%s Set corrections, interactionId: %@"
+ "-[ESSpeechProfileBuilderConnection _cancelledWithLogMessage:completion:]"
+ "1.2.1"
+ "Adding #radio vocab %@ to speech profile"
+ "B32@0:8@16@?24"
+ "Donating edit record to Biome: %@"
+ "Operation cancelled"
+ "Recognition result %@, %lu"
+ "Set alternativeSelection for CESRFidesASRRecord, interactionId: %@, alternatives: %@"
+ "Set correctedText for CESRFidesASRRecord, interactionId: %@, correctedText: %@"
+ "Set correctedTextV2 for CESRFidesASRRecord, interactionId: %@, correctedTextV2: %@"
+ "Set recognized text: %@"
+ "Update cancelled after deletion lookup"
+ "Update cancelled after deletions"
+ "Update cancelled after insertions"
+ "Update cancelled before insertions"
+ "Update cancelled before processing"
+ "Vv40@0:8@\"NSString\"16@\"NSURL\"24@?<v@?BBq@\"NSError\">32"
+ "\\contact-first-pronunciation"
+ "\\contact-last-pronunciation"
+ "_cancelled"
+ "_cancelledWithLogMessage:completion:"
+ "correctedOutput: %@, recognizedOutput %@"
+ "fidesLogger"
+ "isEnabledForType:"
+ "logASRSpeechProfileUpdateFailedWithError:"
+ "logForType:message:"
+ "raw eager recognition candidate: %@"
+ "sanitizeText:"
+ "speechLogger"
+ "speechProfileLogger"
- "%s Adding #radio vocab %@ to speech profile"
- "%s Donating edit record to Biome: %@"
- "%s Entity Cleanup: Failed to initialize NSDataDetector for NSTextCheckingTypes-based entity sanitization, error: %@"
- "%s Recognition result %@, %lu"
- "%s Set alternativeSelection for CESRFidesASRRecord, interactionId: %@, alternatives: %@"
- "%s Set correctedText for CESRFidesASRRecord, interactionId: %@, correctedText: %@"
- "%s Set correctedTextV2 for CESRFidesASRRecord, interactionId: %@, correctedTextV2: %@"
- "%s Set recognized text: %{private}@"
- "%s correctedOutput: %@, recognizedOutput %@"
- "%s raw eager recognition candidate: %@"
- "-[ESConnection speechRecognizer:didRecognizeRawEagerRecognitionCandidate:]_block_invoke"
- "-[ESItemProcessor _textDataTypeDetector]"
- "1.2.0"
- "@\"NSDataDetector\""
- "Vv40@0:8@\"NSString\"16@\"NSURL\"24@?<v@?BB@\"NSError\">32"
- "_textDataTypeDetector"
- "addressComponents"
- "addressComponentsToSanitize"
- "dataDetectorWithTypes:error:"
- "formUnionWithCharacterSet:"
- "logASRSpeechProfileUpdateFailedWithReason:"
- "matchesInString:options:range:"
- "parentEntityIdentifier"
- "replaceOccurrencesOfString:withString:options:range:"
- "resultType"
- "sanitizeText:detector:"
- "setString:"
- "stringWithString:"
```
