## HomeAI

> `/System/Library/PrivateFrameworks/HomeAI.framework/HomeAI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17b54c` | `0x17f344` | **`+0x3df8`** |
| `__AUTH_CONST.__objc_const` | `0x15ce0` | `0x16420` | **`+0x740`** |
| `__TEXT.__objc_methlist` | `0xa25c` | `0xa67c` | **`+0x420`** |
| `__TEXT.__oslogstring` | `0xe4cc` | `0xe87d` | **`+0x3b1`** |
| `__AUTH.__objc_data` | `0x41f0` | `0x42e0` | **`+0xf0`** |
| `__DATA_CONST.__objc_arraydata` | `0x618` | `0x6e8` | **`+0xd0`** |
| `__AUTH_CONST.__cfstring` | `0x8a60` | `0x8ae0` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x5088` | `0x5108` | **`+0x80`** |
| `__DATA.__objc_ivar` | `0xcf8` | `0xd64` | **`+0x6c`** |
| `__TEXT.__cstring` | `0xd9f1` | `0xda5c` | **`+0x6b`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x360` | `0x390` | **`+0x30`** |
| `__AUTH_CONST.__objc_doubleobj` | `0x1b0` | `0x180` | **`-0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x4800` | `0x4820` | **`+0x20`** |
| `__TEXT.__const` | `0x495d` | `0x497d` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x700` | `0x718` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x5f8` | `0x610` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xe90` | `0xe98` | **`+0x8`** |

### Other Changes

```diff

-378.0.0.0.0
+381.0.0.0.0

-  Functions: 5428
-  Symbols:   10124
-  CStrings:  3199
+  Functions: 5516
+  Symbols:   10264
+  CStrings:  3222
Symbols:
+ +[NSError(HMIError) hmiPrivateErrorWithCode:reason:]
+ +[SignificantActivityYolo URLOfModelInThisBundle]
+ +[SignificantActivityYolo loadContentsOfURL:configuration:completionHandler:]
+ +[SignificantActivityYolo loadWithConfiguration:completionHandler:]
+ -[HMIDataReader canReadLength:]
+ -[HMIDataReader failReadOfLength:]
+ -[HMIDataReader remainingLength]
+ -[SignificantActivityYolo .cxx_destruct]
+ -[SignificantActivityYolo initWithConfiguration:error:]
+ -[SignificantActivityYolo initWithContentsOfURL:configuration:error:]
+ -[SignificantActivityYolo initWithContentsOfURL:error:]
+ -[SignificantActivityYolo initWithMLModel:]
+ -[SignificantActivityYolo init]
+ -[SignificantActivityYolo model]
+ -[SignificantActivityYolo predictionFromFeatures:completionHandler:]
+ -[SignificantActivityYolo predictionFromFeatures:error:]
+ -[SignificantActivityYolo predictionFromFeatures:options:completionHandler:]
+ -[SignificantActivityYolo predictionFromFeatures:options:error:]
+ -[SignificantActivityYolo predictionFromImage_Placeholder:error:]
+ -[SignificantActivityYolo predictionsFromInputs:options:error:]
+ -[SignificantActivityYoloInput dealloc]
+ -[SignificantActivityYoloInput featureNames]
+ -[SignificantActivityYoloInput featureValueForName:]
+ -[SignificantActivityYoloInput image_Placeholder]
+ -[SignificantActivityYoloInput initWithImage_Placeholder:]
+ -[SignificantActivityYoloInput initWithImage_PlaceholderAtURL:error:]
+ -[SignificantActivityYoloInput initWithImage_PlaceholderFromCGImage:error:]
+ -[SignificantActivityYoloInput setImage_Placeholder:]
+ -[SignificantActivityYoloInput setImage_PlaceholderWithCGImage:error:]
+ -[SignificantActivityYoloInput setImage_PlaceholderWithURL:error:]
+ -[SignificantActivityYoloOutput .cxx_destruct]
+ -[SignificantActivityYoloOutput HomeSSD_box0_offset0]
+ -[SignificantActivityYoloOutput HomeSSD_box0_offset1]
+ -[SignificantActivityYoloOutput HomeSSD_box0_offset2]
+ -[SignificantActivityYoloOutput HomeSSD_box0_offset3]
+ -[SignificantActivityYoloOutput HomeSSD_box0_offset4]
+ -[SignificantActivityYoloOutput HomeSSD_box1_offset0]
+ -[SignificantActivityYoloOutput HomeSSD_box1_offset1]
+ -[SignificantActivityYoloOutput HomeSSD_box1_offset2]
+ -[SignificantActivityYoloOutput HomeSSD_box1_offset3]
+ -[SignificantActivityYoloOutput HomeSSD_box1_offset4]
+ -[SignificantActivityYoloOutput HomeSSD_class_prob0]
+ -[SignificantActivityYoloOutput HomeSSD_class_prob1]
+ -[SignificantActivityYoloOutput HomeSSD_class_prob2]
+ -[SignificantActivityYoloOutput HomeSSD_class_prob3]
+ -[SignificantActivityYoloOutput HomeSSD_class_prob4]
+ -[SignificantActivityYoloOutput HomeSSD_object_roll0]
+ -[SignificantActivityYoloOutput HomeSSD_object_roll1]
+ -[SignificantActivityYoloOutput HomeSSD_object_roll2]
+ -[SignificantActivityYoloOutput HomeSSD_object_roll3]
+ -[SignificantActivityYoloOutput HomeSSD_object_roll4]
+ -[SignificantActivityYoloOutput HomeSSD_object_yaw0]
+ -[SignificantActivityYoloOutput HomeSSD_object_yaw1]
+ -[SignificantActivityYoloOutput HomeSSD_object_yaw2]
+ -[SignificantActivityYoloOutput HomeSSD_object_yaw3]
+ -[SignificantActivityYoloOutput HomeSSD_object_yaw4]
+ -[SignificantActivityYoloOutput featureNames]
+ -[SignificantActivityYoloOutput featureValueForName:]
+ -[SignificantActivityYoloOutput initWithHomeSSD_class_prob0:HomeSSD_box0_offset0:HomeSSD_box1_offset0:HomeSSD_object_roll0:HomeSSD_object_yaw0:HomeSSD_class_prob1:HomeSSD_box0_offset1:HomeSSD_box1_offset1:HomeSSD_object_roll1:HomeSSD_object_yaw1:HomeSSD_class_prob2:HomeSSD_box0_offset2:HomeSSD_box1_offset2:HomeSSD_object_roll2:HomeSSD_object_yaw2:HomeSSD_class_prob3:HomeSSD_box0_offset3:HomeSSD_box1_offset3:HomeSSD_object_roll3:HomeSSD_object_yaw3:HomeSSD_class_prob4:HomeSSD_box0_offset4:HomeSSD_box1_offset4:HomeSSD_object_roll4:HomeSSD_object_yaw4:]
+ -[SignificantActivityYoloOutput setHomeSSD_box0_offset0:]
+ -[SignificantActivityYoloOutput setHomeSSD_box0_offset1:]
+ -[SignificantActivityYoloOutput setHomeSSD_box0_offset2:]
+ -[SignificantActivityYoloOutput setHomeSSD_box0_offset3:]
+ -[SignificantActivityYoloOutput setHomeSSD_box0_offset4:]
+ -[SignificantActivityYoloOutput setHomeSSD_box1_offset0:]
+ -[SignificantActivityYoloOutput setHomeSSD_box1_offset1:]
+ -[SignificantActivityYoloOutput setHomeSSD_box1_offset2:]
+ -[SignificantActivityYoloOutput setHomeSSD_box1_offset3:]
+ -[SignificantActivityYoloOutput setHomeSSD_box1_offset4:]
+ -[SignificantActivityYoloOutput setHomeSSD_class_prob0:]
+ -[SignificantActivityYoloOutput setHomeSSD_class_prob1:]
+ -[SignificantActivityYoloOutput setHomeSSD_class_prob2:]
+ -[SignificantActivityYoloOutput setHomeSSD_class_prob3:]
+ -[SignificantActivityYoloOutput setHomeSSD_class_prob4:]
+ -[SignificantActivityYoloOutput setHomeSSD_object_roll0:]
+ -[SignificantActivityYoloOutput setHomeSSD_object_roll1:]
+ -[SignificantActivityYoloOutput setHomeSSD_object_roll2:]
+ -[SignificantActivityYoloOutput setHomeSSD_object_roll3:]
+ -[SignificantActivityYoloOutput setHomeSSD_object_roll4:]
+ -[SignificantActivityYoloOutput setHomeSSD_object_yaw0:]
+ -[SignificantActivityYoloOutput setHomeSSD_object_yaw1:]
+ -[SignificantActivityYoloOutput setHomeSSD_object_yaw2:]
+ -[SignificantActivityYoloOutput setHomeSSD_object_yaw3:]
+ -[SignificantActivityYoloOutput setHomeSSD_object_yaw4:]
+ GCC_except_table82
+ _OBJC_CLASS_$_SignificantActivityYolo
+ _OBJC_CLASS_$_SignificantActivityYoloInput
+ _OBJC_CLASS_$_SignificantActivityYoloOutput
+ _OBJC_IVAR_$_SignificantActivityYolo._model
+ _OBJC_IVAR_$_SignificantActivityYoloInput._image_Placeholder
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_box0_offset0
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_box0_offset1
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_box0_offset2
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_box0_offset3
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_box0_offset4
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_box1_offset0
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_box1_offset1
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_box1_offset2
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_box1_offset3
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_box1_offset4
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_class_prob0
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_class_prob1
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_class_prob2
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_class_prob3
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_class_prob4
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_object_roll0
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_object_roll1
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_object_roll2
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_object_roll3
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_object_roll4
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_object_yaw0
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_object_yaw1
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_object_yaw2
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_object_yaw3
+ _OBJC_IVAR_$_SignificantActivityYoloOutput._HomeSSD_object_yaw4
+ _OBJC_METACLASS_$_SignificantActivityYolo
+ _OBJC_METACLASS_$_SignificantActivityYoloInput
+ _OBJC_METACLASS_$_SignificantActivityYoloOutput
+ __OBJC_$_CLASS_METHODS_SignificantActivityYolo
+ __OBJC_$_INSTANCE_METHODS_SignificantActivityYolo
+ __OBJC_$_INSTANCE_METHODS_SignificantActivityYoloInput
+ __OBJC_$_INSTANCE_METHODS_SignificantActivityYoloOutput
+ __OBJC_$_INSTANCE_VARIABLES_SignificantActivityYolo
+ __OBJC_$_INSTANCE_VARIABLES_SignificantActivityYoloInput
+ __OBJC_$_INSTANCE_VARIABLES_SignificantActivityYoloOutput
+ __OBJC_$_PROP_LIST_SignificantActivityYolo
+ __OBJC_$_PROP_LIST_SignificantActivityYoloInput
+ __OBJC_$_PROP_LIST_SignificantActivityYoloOutput
+ __OBJC_CLASS_PROTOCOLS_$_SignificantActivityYoloInput
+ __OBJC_CLASS_PROTOCOLS_$_SignificantActivityYoloOutput
+ __OBJC_CLASS_RO_$_SignificantActivityYolo
+ __OBJC_CLASS_RO_$_SignificantActivityYoloInput
+ __OBJC_CLASS_RO_$_SignificantActivityYoloOutput
+ __OBJC_METACLASS_RO_$_SignificantActivityYolo
+ __OBJC_METACLASS_RO_$_SignificantActivityYoloInput
+ __OBJC_METACLASS_RO_$_SignificantActivityYoloOutput
+ ___68-[SignificantActivityYolo predictionFromFeatures:completionHandler:]_block_invoke
+ ___76-[SignificantActivityYolo predictionFromFeatures:options:completionHandler:]_block_invoke
+ ___77+[SignificantActivityYolo loadContentsOfURL:configuration:completionHandler:]_block_invoke
+ __os_feature_enabled_impl
CStrings:
+ "CameraSignificantActivityModelV2"
+ "Could not load SignificantActivityYolo.mlmodelc in the bundle resource"
+ "Home"
+ "No activity"
+ "Refusing to read %llu bytes at position %llu, only %llu bytes remain."
+ "Refusing to seek to %llu, data is only %lu bytes long."
+ "Sensitive content"
+ "SignificantActivityYolo"
+ "Truncated atom header at offset %llu."
+ "Truncated atom header, expected an mfhd atom."
+ "Truncated extended size field for atom at offset %llu."
+ "Truncated mfhd atom."
+ "Unexpected %@ atom, expected an mfhd atom."
+ "Unexpected sequence number %u, expected greater than %u."
+ "Unsafe content"
+ "[%{public}@] Refusing to read %llu bytes at position %llu, only %llu bytes remain."
+ "[%{public}@] Refusing to seek to %llu, data is only %lu bytes long."
+ "[%{public}@] Truncated atom header at offset %llu."
+ "[%{public}@] Truncated atom header, expected an mfhd atom."
+ "[%{public}@] Truncated extended size field for atom at offset %llu."
+ "[%{public}@] Truncated mfhd atom."
+ "[%{public}@] Unexpected %@ atom, expected an mfhd atom."
+ "[%{public}@] Unexpected sequence number %u, expected greater than %u."
```
