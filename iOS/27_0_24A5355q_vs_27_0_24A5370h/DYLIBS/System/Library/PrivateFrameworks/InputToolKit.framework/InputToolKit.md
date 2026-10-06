## InputToolKit

> `/System/Library/PrivateFrameworks/InputToolKit.framework/InputToolKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10cf4` | `0x10ca4` | **`-0x50`** |

### Other Changes

```diff
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorIjNS_9allocatorIjEEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIjNS_9allocatorIjEEEC2B9fqe220106Em
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorIjNS_9allocatorIjEEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIjNS_9allocatorIjEEEC2B9fqe220100Em
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
Functions:
~ _ITKGetCanvasSpaceCorners : 560 -> 540
~ -[NSString(ITK) itk_htmlStringEscapingQuotesAndLineBreaks] : 364 -> 360
~ -[NSString(ITK) itk_stringByReplacingCharactersInStringMap:] : 1096 -> 1088
~ -[NSMutableSet(ITK) itk_removeObjectsFromNonNilArray:] : 244 -> 240
~ +[ITKLexiconChecker englishLexiconCheck:] : 2932 -> 2904
~ __ZL25_tokenByNormalizingStringP8NSString : 1128 -> 1116
~ _ITKTransformMixAffineTransforms : 436 -> 432
~ -[NSData(ITKDataExtensions) itk_md5] : 308 -> 316
~ -[NSArray(ITK) itk_countOfObjectsPassingTest:] : 328 -> 324
~ -[NSArray(ITK) itk_arrayByGroupingIntoArraysWithMaxCount:] : 384 -> 380
~ +[NSRegularExpression(ITK) itk_regexForSearchStrings:] : 476 -> 472
~ _ITKStringFromCGColor : 336 -> 344
~ _ITKCGColorCreateWithString : 560 -> 556
```
