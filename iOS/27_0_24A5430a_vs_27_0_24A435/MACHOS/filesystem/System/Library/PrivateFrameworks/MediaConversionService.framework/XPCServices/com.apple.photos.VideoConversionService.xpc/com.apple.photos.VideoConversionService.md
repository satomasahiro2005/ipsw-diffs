## com.apple.photos.VideoConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/XPCServices/com.apple.photos.VideoConversionService.xpc/com.apple.photos.VideoConversionService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21bd0` | `0x22538` | **`+0x968`** |
| `__TEXT.__objc_methname` | `0x7d3d` | `0x8207` | **`+0x4ca`** |
| `__DATA.__objc_const` | `0x29e8` | `0x2da8` | **`+0x3c0`** |
| `__TEXT.__objc_methlist` | `0x1d14` | `0x1e94` | **`+0x180`** |
| `__DATA.__objc_selrefs` | `0x1ca8` | `0x1d70` | **`+0xc8`** |
| `__TEXT.__objc_stubs` | `0x6220` | `0x62e0` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x2f5f` | `0x3008` | **`+0xa9`** |
| `__DATA.__objc_data` | `0x640` | `0x6e0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x34f0` | `0x3584` | **`+0x94`** |
| `__TEXT.__objc_classname` | `0x361` | `0x3d5` | **`+0x74`** |
| `__TEXT.__gcc_except_tab` | `0xb14` | `0xb68` | **`+0x54`** |
| `__DATA_CONST.__const` | `0xbd0` | `0xc20` | **`+0x50`** |
| `__DATA.__objc_ivar` | `0x21c` | `0x250` | **`+0x34`** |
| `__DATA_CONST.__got` | `0x770` | `0x798` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x798` | `0x7c0` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x2740` | `0x2760` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0xa0` | `0xb0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x60` | `0x68` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-912.0.234.0.0
+912.0.235.0.0

-  Functions: 659
-  Symbols:   420
-  CStrings:  1867
+  Functions: 693
+  Symbols:   425
+  CStrings:  1920
Symbols:
+ _OBJC_CLASS_$_PISemanticStyleAutoCalculator
+ _OBJC_CLASS_$_PITextureStyleAdjustmentController
+ _OBJC_CLASS_$_PITextureStyleAutoCalculator
+ _PISemanticStyleAdjustmentKey
+ _PITextureStyleAdjustmentKey
CStrings:
+ "Detected Portrait + Grain, modifying composition with captured values"
+ "Error running semantic style autocalc: %{public}@"
+ "Error running texture style autocalc: %{public}@"
+ "PAMediaConversionServiceContentProvenanceProcessingResult"
+ "PAMediaConversionServiceContentProvenanceValidationResult"
+ "PAMediaConversionServiceOptionPreserveProvenanceKey"
+ "T@\"NSData\",&,V_processedJPEGImageData"
+ "T@\"NSData\",&,V_revocationCheckIdentifier"
+ "T@\"NSDate\",&,V_utcLowerBoundTimestamp"
+ "T@\"NSDate\",&,V_utcProcessingTimestamp"
+ "T@\"NSDate\",&,V_utcUpperBoundTimestamp"
+ "TB,V_diagnosticsRequested"
+ "TB,V_shouldPreserveProvenance"
+ "Ti,V_certificateVerificationStatus"
+ "Ti,V_signatureVerificationStatus"
+ "Tq,V_revocationStatus"
+ "_certificateVerificationStatus"
+ "_diagnosticsRequested"
+ "_processedJPEGImageData"
+ "_revocationCheckIdentifier"
+ "_revocationStatus"
+ "_shouldPreserveProvenance"
+ "_signatureVerificationStatus"
+ "_utcLowerBoundTimestamp"
+ "_utcProcessingTimestamp"
+ "_utcUpperBoundTimestamp"
+ "certificateVerificationStatus"
+ "diagnosticsRequested"
+ "grainIntensityKey"
+ "processedJPEGImageData"
+ "revocationCheckIdentifier"
+ "revocationStatus"
+ "setCertificateVerificationStatus:"
+ "setDiagnosticsRequested:"
+ "setProcessedJPEGImageData:"
+ "setRevocationCheckIdentifier:"
+ "setRevocationStatus:"
+ "setShouldPreserveProvenance:"
+ "setSignatureVerificationStatus:"
+ "setUtcLowerBoundTimestamp:"
+ "setUtcProcessingTimestamp:"
+ "setUtcUpperBoundTimestamp:"
+ "shouldPreserveProvenance"
+ "signatureVerificationStatus"
+ "textureStyleAdjustmentController"
+ "updateWithSemStyleInfo:"
+ "updateWithTextureStyleInfo:"
+ "utcLowerBoundTimestamp"
+ "utcProcessingTimestamp"
+ "utcUpperBoundTimestamp"
+ "v16@?0@\"PISemanticStyleAdjustmentController\"8"
+ "v16@?0@\"PITextureStyleAdjustmentController\"8"
+ "validationStatus"
```
