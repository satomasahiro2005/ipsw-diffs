## UniformTypeIdentifiers

> `/System/Library/Frameworks/UniformTypeIdentifiers.framework/UniformTypeIdentifiers`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbcdc` | `0xc1e8` | **`+0x50c`** |
| `__AUTH_CONST.__objc_const` | `0x688` | `0x790` | **`+0x108`** |
| `__TEXT.__gcc_except_tab` | `0x12e8` | `0x13c8` | **`+0xe0`** |
| `__AUTH_CONST.__cfstring` | `0x2580` | `0x2600` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x79c` | `0x804` | **`+0x68`** |
| `__AUTH.__objc_data` | `0xa0` | `0xf0` | **`+0x50`** |
| `__TEXT.__cstring` | `0x2431` | `0x247f` | **`+0x4e`** |
| `__DATA_CONST.__objc_selrefs` | `0x688` | `0x6b0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x678` | `0x6a0` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x30` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x18` | `0x20` | **`+0x8`** |
| `__DATA.__common` | `0x2` | `0x6` | **`+0x4`** |
| `__DATA.__objc_ivar` | `0x8` | `0xc` | **`+0x4`** |

### Other Changes

```diff

-905.0.0.0.0
+910.0.0.0.0

-  Functions: 225
-  Symbols:   792
-  CStrings:  403
+  Functions: 232
+  Symbols:   815
+  CStrings:  407
Symbols:
+ +[UTTypeCodingBox supportsSecureCoding]
+ -[UTTypeCodingBox .cxx_destruct]
+ -[UTTypeCodingBox copyWithZone:]
+ -[UTTypeCodingBox encodeWithCoder:]
+ -[UTTypeCodingBox initWithCoder:]
+ -[UTTypeCodingBox initWithType:]
+ -[UTTypeCodingBox type]
+ _OBJC_CLASS_$_NSData
+ _OBJC_CLASS_$_NSKeyedArchiver
+ _OBJC_CLASS_$_NSKeyedUnarchiver
+ _OBJC_CLASS_$_UTTypeCodingBox
+ _OBJC_IVAR_$_UTTypeCodingBox._type
+ _OBJC_METACLASS_$_UTTypeCodingBox
+ __OBJC_$_CLASS_METHODS_UTTypeCodingBox
+ __OBJC_$_CLASS_PROP_LIST_UTTypeCodingBox
+ __OBJC_$_INSTANCE_METHODS_UTTypeCodingBox
+ __OBJC_$_INSTANCE_VARIABLES_UTTypeCodingBox
+ __OBJC_$_PROP_LIST_UTTypeCodingBox
+ __OBJC_CLASS_PROTOCOLS_$_UTTypeCodingBox
+ __OBJC_CLASS_RO_$_UTTypeCodingBox
+ __OBJC_METACLASS_RO_$_UTTypeCodingBox
+ __UTTypeCodingBoxSkipIdentifierLookupForTesting
+ __ZNKSt3__121__murmur2_or_cityhashImLm64EEclB9fqe220106EPKvm
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIP9objc_ivarEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__127__throw_bad_optional_accessB9fqe220106Ev
+ __ZNSt3__16vectorIP12UTTypeRecordNS_9allocatorIS3_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIP12UTTypeRecordNS_9allocatorIS3_EEEC2B9fqe220106EmRKS2_
+ __ZNSt3__16vectorIP9objc_ivarNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIcNS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIcNS_9allocatorIcEEEC2B9fqe220106EmRKc
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ _objc_release_x27
+ _objc_retain_x27
- __ZNKSt3__121__murmur2_or_cityhashImLm64EEclB9fqe220100EPKvm
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIP9objc_ivarEENS_16allocator_traitsIS4_EEEENS_19__allocation_resultINT0_7pointerENS8_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__127__throw_bad_optional_accessB9fqe220100Ev
- __ZNSt3__16vectorIP12UTTypeRecordNS_9allocatorIS3_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIP12UTTypeRecordNS_9allocatorIS3_EEEC2B9fqe220100EmRKS2_
- __ZNSt3__16vectorIP9objc_ivarNS_9allocatorIS2_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIcNS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIcNS_9allocatorIcEEEC2B9fqe220100EmRKc
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- _objc_retain_x28
CStrings:
+ "UTTypeCodingBox.mm"
+ "no record data"
+ "recordData"
+ "type creation with record failed"
```
