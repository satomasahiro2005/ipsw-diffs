## ANSTKit

> `/System/Library/PrivateFrameworks/ANSTKit.framework/ANSTKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd2464` | `0xc8b6c` | **`-0x98f8`** |
| `__AUTH_CONST.__objc_const` | `0x10158` | `0xe778` | **`-0x19e0`** |
| `__TEXT.__objc_methlist` | `0x6fbc` | `0x636c` | **`-0xc50`** |
| `__TEXT.__cstring` | `0x109f9` | `0x1040d` | **`-0x5ec`** |
| `__TEXT.__oslogstring` | `0x3841` | `0x3a86` | **`+0x245`** |
| `__AUTH.__objc_data` | `0x280` | `0x50` | **`-0x230`** |
| `__AUTH_CONST.__cfstring` | `0x81a0` | `0x7fa0` | **`-0x200`** |
| `__TEXT.__unwind_info` | `0x2350` | `0x21c0` | **`-0x190`** |
| `__DATA.__objc_ivar` | `0xd24` | `0xc10` | **`-0x114`** |
| `__DATA.__data` | `0x7c0` | `0x700` | **`-0xc0`** |
| `__DATA_CONST.__const` | `0x1120` | `0x1190` | **`+0x70`** |
| `__DATA_DIRTY.__objc_data` | `0x29e0` | `0x2990` | **`-0x50`** |
| `__DATA_CONST.__got` | `0x628` | `0x5e0` | **`-0x48`** |
| `__DATA_CONST.__objc_superrefs` | `0x430` | `0x3e8` | **`-0x48`** |
| `__DATA_CONST.__objc_classlist` | `0x470` | `0x430` | **`-0x40`** |
| `__AUTH_CONST.__objc_intobj` | `0x348` | `0x318` | **`-0x30`** |
| `__AUTH_CONST.__const` | `0x208` | `0x228` | **`+0x20`** |
| `__DATA.__bss` | `0x198` | `0x178` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x10` | `0x30` | **`+0x20`** |
| `__DATA_CONST.__objc_protorefs` | `0x30` | `0x18` | **`-0x18`** |
| `__TEXT.__gcc_except_tab` | `0x4ba0` | `0x4b88` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x978` | `0x988` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x98` | `0x88` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1de0` | `0x1df0` | **`+0x10`** |

### Other Changes

```diff

-43.2.0.0.0
+44.0.0.0.0

-  Functions: 3217
-  Symbols:   1204
-  CStrings:  1855
+  Functions: 2994
+  Symbols:   1190
+  CStrings:  1822
Symbols:
+ _OBJC_CLASS_$_ANSTFsincInferencePostprocessorV2
+ _OBJC_METACLASS_$_ANSTFsincInferencePostprocessorV2
+ _dispatch_block_create_with_qos_class
+ _os_variant_allows_internal_security_policies
- _OBJC_CLASS_$_ANSTISPAlgorithmV5Dot0
- _OBJC_CLASS_$_ANSTISPAlgorithmV5Dot2
- _OBJC_CLASS_$_ANSTISPAlgorithmV5Dot3
- _OBJC_CLASS_$_ANSTISPInferenceDescriptorV5Dot0
- _OBJC_CLASS_$_ANSTISPInferenceDescriptorV5Dot2
- _OBJC_CLASS_$_ANSTISPInferenceDescriptorV5Dot3
- _OBJC_CLASS_$_ANSTISPInferencePostprocessorV5Dot0
- _OBJC_CLASS_$_ANSTISPInferencePostprocessorV5Dot2
- _OBJC_CLASS_$_ANSTISPInferencePostprocessorV5Dot3
- _OBJC_METACLASS_$_ANSTISPAlgorithmV5Dot0
- _OBJC_METACLASS_$_ANSTISPAlgorithmV5Dot2
- _OBJC_METACLASS_$_ANSTISPAlgorithmV5Dot3
- _OBJC_METACLASS_$_ANSTISPInferenceDescriptorV5Dot0
- _OBJC_METACLASS_$_ANSTISPInferenceDescriptorV5Dot2
- _OBJC_METACLASS_$_ANSTISPInferenceDescriptorV5Dot3
- _OBJC_METACLASS_$_ANSTISPInferencePostprocessorV5Dot0
- _OBJC_METACLASS_$_ANSTISPInferencePostprocessorV5Dot2
- _OBJC_METACLASS_$_ANSTISPInferencePostprocessorV5Dot3
CStrings:
+ "\"downloadingProgressReporter\" spuriously becomes `nil`."
+ "ANST Fatal Error: %s has been removed. Automatically falling back to ANSTISPInferenceVersion5Latest."
+ "ANST Fatal Error: ANSTISPAlgorithmVersion5Dot0 has been removed. Automatically falling back to ANSTISPAlgorithmVersion5Latest."
+ "ANST Fatal Error: ANSTISPAlgorithmVersion5Dot2 has been removed. Automatically falling back to ANSTISPAlgorithmVersion5Latest."
+ "ANST Fatal Error: ANSTISPAlgorithmVersion5Dot3 has been removed. Automatically falling back to ANSTISPAlgorithmVersion5Latest."
+ "ANST Fatal Error: ANSTISPInferenceVersion5Dot0 has been removed. Automatically falling back to ANSTISPInferenceVersion5Latest."
+ "ANST Fatal Error: ANSTISPInferenceVersion5Dot2 has been removed. Automatically falling back to ANSTISPInferenceVersion5Latest."
+ "ANST Fatal Error: ANSTISPInferenceVersion5Dot3 has been removed. Automatically falling back to ANSTISPInferenceVersion5Latest."
+ "[Query] background catalog refresh completed"
+ "[Query] background catalog refresh failed: %{public}@"
+ "[Query] catalog is outdated, triggering a background fresh..."
+ "version"
- "%s: ANSTISPInferenceDescriptor does not conform to ANSTISPInferenceIOV5!"
- "+[ANSTISPAlgorithmV5Dot0 networkDescriptorForConfig:]"
- "+[ANSTISPAlgorithmV5Dot2 networkDescriptorForConfig:]"
- "+[ANSTISPAlgorithmV5Dot3 networkDescriptorForConfig:]"
- "-[ANSTISPAlgorithmV5Dot0 _prepareWithError:]"
- "-[ANSTISPAlgorithmV5Dot0 _resultForPixelBuffer:focalLength:error:]"
- "-[ANSTISPAlgorithmV5Dot0 initWithConfiguration:]"
- "-[ANSTISPAlgorithmV5Dot0 resultForPixelBuffer:orientation:error:]"
- "-[ANSTISPAlgorithmV5Dot2 _prepareWithError:]"
- "-[ANSTISPAlgorithmV5Dot2 _resultForPixelBuffer:focalLength:error:]"
- "-[ANSTISPAlgorithmV5Dot2 initWithConfiguration:]"
- "-[ANSTISPAlgorithmV5Dot2 resultForPixelBuffer:orientation:error:]"
- "-[ANSTISPAlgorithmV5Dot3 _prepareWithError:]"
- "-[ANSTISPAlgorithmV5Dot3 _resultForPixelBuffer:focalLength:error:]"
- "-[ANSTISPAlgorithmV5Dot3 initWithConfiguration:]"
- "-[ANSTISPAlgorithmV5Dot3 resultForPixelBuffer:orientation:error:]"
- "-[ANSTISPInferencePostprocessorV5Dot0 _processWithError:]"
- "-[ANSTISPInferencePostprocessorV5Dot2 _processWithError:]"
- "-[ANSTISPInferencePostprocessorV5Dot3 _processWithError:]"
- "ANSTISPAlgorithm v5.0 initialized with config %{public}@."
- "ANSTISPAlgorithm v5.2 initialized with config %{public}@."
- "ANSTISPAlgorithm v5.3 initialized with config %{public}@."
- "ANSTISPAlgorithmV5Dot0_prepareWithError"
- "ANSTISPAlgorithmV5Dot0_resultForPixelBuffer"
- "ANSTISPAlgorithmV5Dot2_prepareWithError"
- "ANSTISPAlgorithmV5Dot2_resultForPixelBuffer"
- "ANSTISPAlgorithmV5Dot3_prepareWithError"
- "ANSTISPAlgorithmV5Dot3_resultForPixelBuffer"
- "Input pixel buffer width < height. ANSTISPAlgorithmV5Dot0 only supports landscape input."
- "Input pixel buffer width < height. ANSTISPAlgorithmV5Dot2 only supports landscape input."
- "Input pixel buffer width < height. ANSTISPAlgorithmV5Dot3 only supports landscape input."
- "anst_v5d0"
- "anst_v5d2"
- "anst_v5d3"
- "anst_v5dot0_%@"
- "anst_v5dot2_%@"
- "anst_v5dot3_%@"
- "avg_feat@output"
- "face_landmark_fdm@output"
- "ovd_bbox_reg@output"
- "ovd_class_id@output"
- "ovd_embeddings@output"
- "ovd_objectness@output"
- "ovd_saliency@output"
- "scene_output@output"
```
