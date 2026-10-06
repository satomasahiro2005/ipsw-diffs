## CMPhoto

> `/System/Library/PrivateFrameworks/CMPhoto.framework/CMPhoto`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29efc8` | `0x29f610` | **`+0x648`** |
| `__TEXT.__cstring` | `0x4d7c7` | `0x4d867` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x60a40` | `0x60ac0` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x7f25` | `0x7f65` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x10120` | `0x10140` | **`+0x20`** |
| `__DATA.__bss` | `0xc6c8` | `0xc6d8` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x992b0` | `0x992c0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2a60` | `0x2a68` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x5d98` | `0x5da0` | **`+0x8`** |

### Other Changes

```diff

-488.22.4.0.0
+488.40.4.0.0

-  Functions: 9748
-  Symbols:   12510
-  CStrings:  14037
+  Functions: 9775
+  Symbols:   12520
+  CStrings:  14043
Symbols:
+ _CFPreferencesGetAppBooleanValue
+ _CMPhotoAllowProvenanceVerificationWithQASigningPolicy
+ _CMPhotoAllowProvenanceVerificationWithQASigningPolicy.onceToken
+ _CMPhotoAllowProvenanceVerificationWithQASigningPolicy.sAllowQASigningPolicy
+ _CMPhotoValidateProvidedPixelBufferSize
+ _CMPhotoValidateRectFitsInPixelBuffer
+ _OUTLINED_FUNCTION_178
+ ___CMPhotoAllowProvenanceVerificationWithQASigningPolicy_block_invoke
+ _kCMPhotoProvenanceResult_CertificateChainData
+ _kCMPhotoProvenanceResult_CertificateSecTrustVerifiedWithQASigningPolicy
CStrings:
+ "CertificateChainData"
+ "CertificateSecTrustVerifiedWithQASigningPolicy"
+ "Protobuf is missing the required pixelFormatType field"
+ "allocationCertDataArray"
+ "cmphoto_allow_provenance_qa_signing_policy"
+ "copyCertificateData"
```
