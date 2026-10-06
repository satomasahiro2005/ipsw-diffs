## libFDR.dylib

> `/usr/lib/libFDR.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8af30` | `0x8b490` | **`+0x560`** |
| `__TEXT.__cstring` | `0x232a6` | `0x234aa` | **`+0x204`** |
| `__TEXT.__unwind_info` | `0x1210` | `0x1228` | **`+0x18`** |
| `__TEXT.__const` | `0x1ff0` | `0x2000` | **`+0x10`** |

### Other Changes

```diff

-1624.0.0.0.0
+1636.0.1.0.0

-  Functions: 4610
-  Symbols:   1721
-  CStrings:  4170
+  Functions: 4626
+  Symbols:   1724
+  CStrings:  4185
Symbols:
+ _AMFDRCryptoCreateECDSADerData
+ _AMFDRRegisterModuleChallengeCallbackV2
+ _AMFDRSetModuleChallengeCallbackV2Context
CStrings:
+ "AMFDRCryptoCreateECDSADerData"
+ "AMFDRCryptoCreateECDSADerData failed, status: %d"
+ "AMFDRRegisterModuleChallengeCallbackV2"
+ "AMFDRSetModuleChallengeCallbackV2Context"
+ "Both callback and callbackV2 are NULL"
+ "DEREncoderAddData failed for r"
+ "DEREncoderAddData failed for s"
+ "Invalid data digest input"
+ "Invalid data digest length: %ld"
+ "_Img4DecodeInitDummyPayloadForDataDigest"
+ "callbackV2 is NULL"
+ "dataClass:%@ already exists, callbackV2 is updated"
+ "dataClass:%@ not found, cannot set context"
+ "failed to allocate rWithZero"
+ "failed to allocate sWithZero"
+ "fdrDecode->dataImg4.payload_hashed is false"
+ "find the exeNode, dataClass:%@"
+ "inData is NULL"
+ "invalid inDataLength:%u"
+ "kAMFDRDecodeOptionManifestOnly, kAMFDRDecodeOptionSubCCOnly, kAMFDRDecodeOptionDataDigestOnly needs to be exclusive to each other"
+ "outDerData is NULL"
+ "outDerDataLength is NULL"
+ "trust evaluation on customized payload format requires a reStitchManifest"
- "DEREncoderAddData failed"
- "_AMFDRCryptoCreateECDSADerData"
- "_AMFDRCryptoCreateECDSADerData failed, status: %d"
- "cannot set kAMFDRDecodeOptionManifestOnly and kAMFDRDecodeOptionSubCCOnly at the same time"
- "exeNode->callback is NULL"
- "fdrDecode->sealingManifestImg4.payload_hashed is false"
- "find the exeNode, dataClass:%@,callback:%x"
- "trust evaluation on subCC requires a reStitchManifest"
```
