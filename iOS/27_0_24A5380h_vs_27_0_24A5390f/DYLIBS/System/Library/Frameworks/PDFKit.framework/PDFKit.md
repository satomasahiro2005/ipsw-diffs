## PDFKit

> `/System/Library/Frameworks/PDFKit.framework/PDFKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbcd68` | `0xbf328` | **`+0x25c0`** |
| `__TEXT.__gcc_except_tab` | `0x6468` | `0x7fcc` | **`+0x1b64`** |
| `__TEXT.__unwind_info` | `0x3800` | `0x3c88` | **`+0x488`** |
| `__DATA_CONST.__const` | `0x2348` | `0x2430` | **`+0xe8`** |
| `__TEXT.__cstring` | `0x72b4` | `0x7364` | **`+0xb0`** |
| `__TEXT.__objc_methlist` | `0xb014` | `0xb04c` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0xf0d0` | `0xf100` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x70e8` | `0x7110` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x7680` | `0x7660` | **`-0x20`** |
| `__DATA.__bss` | `0x870` | `0x880` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1790` | `0x1798` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xb10` | `0xb08` | **`-0x8`** |

### Other Changes

```diff

-1532.0.0.0.0
+1534.0.0.0.0

-  Functions: 3748
-  Symbols:   7397
-  CStrings:  1270
+  Functions: 3767
+  Symbols:   7464
+  CStrings:  1272
Symbols:
+ +[PDFCGPDFUtilities valueFromCGPDFObject:]
+ -[PDFDocument pageSubclassOverridingDrawing]
+ -[PDFPage .cxx_construct]
+ GCC_except_table100
+ GCC_except_table110
+ GCC_except_table118
+ GCC_except_table121
+ GCC_except_table122
+ GCC_except_table123
+ GCC_except_table125
+ GCC_except_table127
+ GCC_except_table131
+ GCC_except_table134
+ GCC_except_table141
+ GCC_except_table142
+ GCC_except_table143
+ GCC_except_table145
+ GCC_except_table155
+ GCC_except_table160
+ GCC_except_table164
+ GCC_except_table169
+ GCC_except_table170
+ GCC_except_table172
+ GCC_except_table179
+ GCC_except_table185
+ GCC_except_table186
+ GCC_except_table187
+ GCC_except_table188
+ GCC_except_table189
+ GCC_except_table195
+ GCC_except_table196
+ GCC_except_table199
+ GCC_except_table200
+ GCC_except_table202
+ GCC_except_table203
+ GCC_except_table204
+ GCC_except_table205
+ GCC_except_table206
+ GCC_except_table208
+ GCC_except_table211
+ GCC_except_table212
+ GCC_except_table213
+ GCC_except_table214
+ GCC_except_table215
+ GCC_except_table216
+ GCC_except_table217
+ GCC_except_table218
+ GCC_except_table221
+ GCC_except_table222
+ GCC_except_table226
+ GCC_except_table227
+ GCC_except_table228
+ GCC_except_table63
+ GCC_except_table70
+ GCC_except_table80
+ GCC_except_table81
+ GCC_except_table83
+ GCC_except_table92
+ GCC_except_table95
+ GCC_except_table97
+ __ZNSt3__111__call_onceERVmPvPFvS2_E
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em
+ __ZNSt3__114__split_bufferINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEERNS4_IS6_EEE17__destruct_at_endB9fqe220106EPS6_
+ __ZNSt3__114__split_bufferINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEERNS4_IS6_EEED2Ev
+ __ZNSt3__117__call_once_proxyB9fqe220106INS_5tupleIJOZ24-[PDFPage copyWithZone:]E3$_0EEEEEvPv
+ __ZNSt3__117__call_once_proxyB9fqe220106INS_5tupleIJOZ32-[PDFPage lazilyLoadAnnotations]E3$_1EEEEEvPv
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorINS_12basic_stringIcNS_11char_traitsIcEENS1_IcEEEEEENS_16allocator_traitsIS7_EEEENS_19__allocation_resultINT0_7pointerENSB_9size_typeEEERT_m
+ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE24__emplace_back_slow_pathIJS6_EEEPS6_DpOT_
+ __ZNSt3__16vectorINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS4_IS6_EEE5clearB9fqe220106Ev
+ __ZZ30-[PDFPage renderingProperties]E8sDidWarn
+ __ZZ33+[PDFPage useLegacyImageHandling]E13runningXCTest
+ __ZZ33+[PDFPage useLegacyImageHandling]E9onceToken
+ __ZZ35+[PDFPage displayListCreationQueue]E24displayListCreationQueue
+ __ZZ35+[PDFPage displayListCreationQueue]E9onceToken
+ __ZZ49-[PDFDocument canSaveWithMutablePDFUsingOptions:]E9onceToken
+ ___33-[PDFDocument documentAttributes]_block_invoke
+ ___49-[PDFDocument canSaveWithMutablePDFUsingOptions:]_block_invoke
+ ___block_descriptor_40_ea8_32bs_e15_v32?0816^B24ls32l8
+ ___block_descriptor_40_ea8_32bs_e5_v8?0ls32l8
+ ___block_descriptor_40_ea8_32r_e33_v24?0^{CGDisplayListEntry=}8^B16lr32l8
+ ___block_descriptor_40_ea8_32s_e26_B24?0r*8^{CGPDFObject=}16ls32l8
+ ___block_descriptor_40_ea8_32s_e30_B32?0r*8^{CGPDFObject=}16^v24ls32l8
+ ___block_descriptor_48_e5_v8?0lu32l8
+ ___block_descriptor_48_ea8_32bs40w_e5_v8?0lw40l8s32l8
+ ___block_descriptor_48_ea8_32bs_e5_v8?0ls32l8
+ ___block_descriptor_48_ea8_32s40r_e26_B24?0r*8^{CGPDFObject=}16ls32l8r40l8
+ ___block_descriptor_48_ea8_32s40r_e39_v40?0{CGRect={CGPoint=dd}{CGSize=dd}}8lr40l8s32l8
+ ___block_descriptor_48_ea8_32s40r_e5_B8?0lr40l8s32l8
+ ___block_descriptor_48_ea8_32s40s_e27_v16?0"<PDFPageObserver>"8ls32l8s40l8
+ ___block_descriptor_48_ea8_32s40s_e5_v8?0ls32l8s40l8
+ ___block_descriptor_56_ea8_32r_e15_v32?08Q16^B24lr32l8
+ ___block_descriptor_56_ea8_32r_e17_v16?0"NSArray"8lr32l8
+ ___block_descriptor_56_ea8_32s40bs48w_e5_v8?0lw48l8s32l8s40l8
+ ___block_descriptor_56_ea8_32s40bs48w_e5_v8?0lw48l8s40l8s32l8
+ ___block_descriptor_58_ea8_32s40s48s_e41_v24?0^{CGPDFPage=}8^{CGPDFAnnotation=}16ls32l8s40l8s48l8
- GCC_except_table105
- GCC_except_table115
- GCC_except_table133
- GCC_except_table136
- GCC_except_table139
- GCC_except_table140
- GCC_except_table175
- GCC_except_table191
- GCC_except_table192
- GCC_except_table193
- GCC_except_table194
- GCC_except_table75
- GCC_except_table76
- ___32-[PDFPage lazilyLoadAnnotations]_block_invoke
- ___block_descriptor_40_e8_32bs_e15_v32?0816^B24ls32l8
- ___block_descriptor_40_e8_32r_e33_v24?0^{CGDisplayListEntry=}8^B16lr32l8
- ___block_descriptor_48_e8_32bs40w_e5_v8?0lw40l8s32l8
- ___block_descriptor_48_e8_32bs_e5_v8?0ls32l8
- ___block_descriptor_48_e8_32s40r_e39_v40?0{CGRect={CGPoint=dd}{CGSize=dd}}8lr40l8s32l8
- ___block_descriptor_48_e8_32s40r_e5_B8?0lr40l8s32l8
- ___block_descriptor_48_e8_32s40s_e27_v16?0"<PDFPageObserver>"8ls32l8s40l8
- ___block_descriptor_56_e8_32r_e15_v32?08Q16^B24lr32l8
- ___block_descriptor_56_e8_32r_e17_v16?0"NSArray"8lr32l8
- ___block_descriptor_56_e8_32s40bs48w_e5_v8?0lw48l8s32l8s40l8
- ___block_descriptor_56_e8_32s40bs48w_e5_v8?0lw48l8s40l8s32l8
- ___block_descriptor_58_e8_32s40s48s_e41_v24?0^{CGPDFPage=}8^{CGPDFAnnotation=}16ls32l8s40l8s48l8
- _displayListCreationQueue.displayListCreationQueue
- _displayListCreationQueue.onceToken
- _renderingProperties.sDidWarn
- _useLegacyImageHandling.onceToken
- _useLegacyImageHandling.runningXCTest
CStrings:
+ "%@ overrides -[PDFPage %@]. This is highly discouraged: it opts the document out of fast, lossless saving, forcing PDFKit to re-render every page when saving. Consider adding overlay content another way, e.g. via PDFAnnotation."
+ "PDFPage has loaded all annotations for page %lu in %g secs"
+ "`"
+ "basic_string"
- "AIGC"
- "PDFKit2_LogPerfTime: PDFPage has loaded all annotations for page %d. Milliseconds since epoch: %llu. Time taken: %0.3f."
```
