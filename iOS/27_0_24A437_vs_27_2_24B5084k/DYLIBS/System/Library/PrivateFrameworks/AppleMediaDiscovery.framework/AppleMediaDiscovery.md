## AppleMediaDiscovery

> `/System/Library/PrivateFrameworks/AppleMediaDiscovery.framework/AppleMediaDiscovery`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf3cb0` | `0xf1bd8` | **`-0x20d8`** |
| `__AUTH_CONST.__cfstring` | `0xdaa0` | `0xd760` | **`-0x340`** |
| `__TEXT.__cstring` | `0xac68` | `0xaa08` | **`-0x260`** |
| `__AUTH_CONST.__objc_const` | `0x62d0` | `0x6120` | **`-0x1b0`** |
| `__AUTH.__objc_data` | `0x670` | `0x580` | **`-0xf0`** |
| `__TEXT.__oslogstring` | `0x46f7` | `0x4617` | **`-0xe0`** |
| `__TEXT.__objc_methlist` | `0x3b60` | `0x3af8` | **`-0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x2808` | `0x27b8` | **`-0x50`** |
| `__AUTH_CONST.__objc_intobj` | `0xcf0` | `0xca8` | **`-0x48`** |
| `__TEXT.__gcc_except_tab` | `0x28f0` | `0x28ac` | **`-0x44`** |
| `__DATA_CONST.__got` | `0x6d8` | `0x6a8` | **`-0x30`** |
| `__AUTH_CONST.__objc_dictobj` | `0x1068` | `0x1040` | **`-0x28`** |
| `__DATA_CONST.__const` | `0xda8` | `0xd80` | **`-0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x2e8` | `0x2d0` | **`-0x18`** |
| `__DATA.__data` | `0x660` | `0x650` | **`-0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x12c0` | `0x12b0` | **`-0x10`** |

### Other Changes

```diff

-1.5.6.0.0
+1.5.7.0.0

-  - /System/Library/PrivateFrameworks/CipherML.framework/CipherML

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

-  Functions: 2037
-  Symbols:   2804
-  CStrings:  2394
+  Functions: 2031
+  Symbols:   2774
+  CStrings:  2361
Symbols:
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ __swift_FORCE_LOAD_$_swiftCoreMIDI_$_AppleMediaDiscovery
- +[AMDJSCipherMLQueryHandler triggerPECCall:withError:]
- +[AMDJSCipherMLQueryHandler triggerPIRKVFetch:withError:]
- +[AMDJSPIRResponseHandler persistPIRData:error:]
- +[AMDPirTest testPir:]
- -[AMDClient sendPECSimilarityScores:withCallHandle:andRequestError:error:]
- -[AMDClient sendPIRData:forKeyword:withCallHandle:error:]
- _AMD_CIPHERML_CALL_HANDLE
- _AMD_CIPHERML_REQUEST_ERROR
- _AMD_PEC_SIMILARITY_SCORES_ARRAY
- _AMD_PIR_DATA_ARRAY
- _AMD_PIR_KEYWORD_ARRAY
- _AMD_PIR_MISSING_KEYWORD_ARRAY
- _OBJC_CLASS_$_AMDJSCipherMLQueryHandler
- _OBJC_CLASS_$_AMDJSPIRResponseHandler
- _OBJC_CLASS_$_AMDPirTest
- _OBJC_CLASS_$_CMLClientConfig
- _OBJC_CLASS_$_CMLKeywordPIRClient
- _OBJC_CLASS_$_CMLSimilarityScore
- _OBJC_METACLASS_$_AMDJSCipherMLQueryHandler
- _OBJC_METACLASS_$_AMDJSPIRResponseHandler
- _OBJC_METACLASS_$_AMDPirTest
- _TEST_PEC
- _TEST_PIR
- __OBJC_$_CLASS_METHODS_AMDJSCipherMLQueryHandler
- __OBJC_$_CLASS_METHODS_AMDJSPIRResponseHandler
- __OBJC_$_CLASS_METHODS_AMDPirTest
- __OBJC_CLASS_RO_$_AMDJSCipherMLQueryHandler
- __OBJC_CLASS_RO_$_AMDJSPIRResponseHandler
- __OBJC_CLASS_RO_$_AMDPirTest
- __OBJC_METACLASS_RO_$_AMDJSCipherMLQueryHandler
- __OBJC_METACLASS_RO_$_AMDJSPIRResponseHandler
- __OBJC_METACLASS_RO_$_AMDPirTest
CStrings:
+ "score does not respond to identifier, score and metadata"
- "Deprecated method"
- "Error deserializing PIR data for keyword %@: %@"
- "Error deserializing PIR keyword: %@"
- "KVStore cleanup failed: %@"
- "KVStore fetch failed: %@"
- "Keywords absent in PIR query payload"
- "Keywords are not an array"
- "Nil call handle present in PIR response"
- "Nil data present in PIR response"
- "Nil keyword present in PIR response"
- "Non string keyword present in PIR response"
- "PIR Error: Unrecognized call handler"
- "PIR call handle, usecase %@: %@"
- "PIR use case %@ error: %@"
- "PIRQueryPayload is nil"
- "PIRQueryPayload is not a dictionary"
- "Taste profile save failed: %@"
- "This codepath is not being used currently."
- "add_pir_call_handle"
- "callHandle"
- "keywords"
- "pirCallHandleAdd"
- "pirCallHandleAddError"
- "pirTestStatus"
- "run_pec_queries"
- "run_pir_queries"
- "savePIRData"
- "score not an instance of CMLSimilarityScore"
- "testPEC"
- "testPIR"
- "test_call_handle"
- "test_pir"
- "usecase absent in PIR query payload"
- "usecase is not a string"
```
