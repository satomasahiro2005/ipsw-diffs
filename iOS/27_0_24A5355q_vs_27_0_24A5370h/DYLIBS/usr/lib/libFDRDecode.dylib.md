## libFDRDecode.dylib

> `/usr/lib/libFDRDecode.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb510` | `0xb5d4` | **`+0xc4`** |
| `__TEXT.__cstring` | `0x4f3e` | `0x4fd9` | **`+0x9b`** |

### Other Changes

```diff

-1624.0.0.0.0
+1636.0.1.0.0

-  CStrings:  443
+  CStrings:  446
Functions:
~ _AMFDRDecodeEvaluateTrustInternal : 936 -> 932
~ _AMFDRDecodeTrustEvaluation : 668 -> 664
~ __AMFDRDecodeVerifyData : 1224 -> 1412
~ _AMFDRDecodeIterateSysconfigBegin : 616 -> 628
~ _AMFDRDecodeIterateSysconfigPayloadNext : 524 -> 532
~ _AMFDRDecodeImage4Certificate : 848 -> 844
CStrings:
+ "%s: Invalid data digest input"
+ "%s: Invalid data digest length: %ld"
+ "%s: fdrDecode->dataImg4.payload_hashed is false"
+ "%s: kAMFDRDecodeOptionManifestOnly, kAMFDRDecodeOptionSubCCOnly, kAMFDRDecodeOptionDataDigestOnly needs to be exclusive to each other"
+ "%s: trust evaluation on customized payload format requires a reStitchManifest"
+ "_Img4DecodeInitDummyPayloadForDataDigest"
- "%s: cannot set kAMFDRDecodeOptionManifestOnly and kAMFDRDecodeOptionSubCCOnly at the same time"
- "%s: fdrDecode->sealingManifestImg4.payload_hashed is false"
- "%s: trust evaluation on subCC requires a reStitchManifest"
```
