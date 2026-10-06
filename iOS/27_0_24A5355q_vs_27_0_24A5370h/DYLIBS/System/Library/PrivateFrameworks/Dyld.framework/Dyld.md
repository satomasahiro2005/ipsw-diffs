## Dyld

> `/System/Library/PrivateFrameworks/Dyld.framework/Dyld`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4fb2c` | `0x51d0c` | **`+0x21e0`** |
| `__TEXT.__cstring` | `0xec4` | `0x1374` | **`+0x4b0`** |
| `__TEXT.__unwind_info` | `0x1138` | `0x11e0` | **`+0xa8`** |
| `__TEXT.__gcc_except_tab` | `0x988` | `0xa18` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0x1400` | `0x1470` | **`+0x70`** |
| `__AUTH.__data` | `0x1628` | `0x1680` | **`+0x58`** |
| `__AUTH_CONST.__const` | `0x2000` | `0x2050` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x290` | `0x2e0` | **`+0x50`** |
| `__TEXT.__const` | `0x3400` | `0x3438` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x684` | `0x6ac` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x40` | `0x60` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x1b50` | `0x1b70` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x358` | `0x370` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x1240` | `0x1258` | **`+0x18`** |
| `__DATA.__data` | `0xba8` | `0xbb8` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x80` | `0x90` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0xe16` | `0xe26` | **`+0x10`** |

### Other Changes

```diff

-27050.4.0.0.0
+27056.0.0.0.0

-  Functions: 1425
-  Symbols:   1033
-  CStrings:  118
+  Functions: 1454
+  Symbols:   1054
+  CStrings:  148
Symbols:
+ GCC_except_table104
+ GCC_except_table105
+ GCC_except_table107
+ GCC_except_table108
+ GCC_except_table109
+ GCC_except_table48
+ GCC_except_table49
+ GCC_except_table50
+ GCC_except_table60
+ GCC_except_table62
+ GCC_except_table73
+ GCC_except_table77
+ GCC_except_table81
+ GCC_except_table89
+ GCC_except_table90
+ GCC_except_table91
+ GCC_except_table92
+ GCC_except_table93
+ GCC_except_table94
+ __ZN14CStringBuilder14moveStringFromERS_
+ __ZN6mach_o12UnsafeHeader21isValidMachOStructureENSt3__14spanIKhLm18446744073709551615EEE
+ __ZN6mach_o5ErrorC1EOS0_
+ __ZN6mach_o5ErrorC2EOS0_
+ __ZN6mach_o5ErroraSEOS0_
+ __ZN6mach_oL14stringOverflowEPK12load_commandjj
+ __ZNK6mach_o12UnsafeHeader26validStructureLoadCommandsEy
+ __ZNKSt3__111__copy_implclB9fqn220106IPSt4byteS3_NS_20back_insert_iteratorI10ByteStreamEELi0EEENS_4pairIT_T1_EES8_T0_S9_
+ __ZNKSt3__111__copy_implclB9fqn220106IPSt4byteS3_NS_20back_insert_iteratorIN3lsl6VectorIS2_EEEELi0EEENS_4pairIT_T1_EESA_T0_SB_
+ __ZNSt3__119__unwrap_range_implIN3lsl6VectorISt4byteE15CheckedIteratorIS3_EES6_E8__unwrapB9fqn220106ES6_S6_
+ __ZNSt3__124__copy_move_unwrap_itersB9fqn220106INS_11__copy_implEN3lsl6VectorISt4byteE15CheckedIteratorIS4_EES7_PS4_Li0EEENS_4pairIT0_T2_EESA_T1_SB_
+ __ZNSt3__18_IterOpsINS_17_ClassicAlgPolicyEE9iter_swapB9fqn220106IRN3lsl6VectorIPN12PropertyList4DataEE15CheckedIteratorIS8_EESC_EEvOT_OT0_
+ __ZNSt3__18_IterOpsINS_17_ClassicAlgPolicyEE9iter_swapB9fqn220106IRN3lsl6VectorIPN12PropertyList6StringEE15CheckedIteratorIS8_EESC_EEvOT_OT0_
+ __ZNSt3__18_IterOpsINS_17_ClassicAlgPolicyEE9iter_swapB9fqn220106IRN3lsl6VectorIPN12PropertyList7IntegerEE15CheckedIteratorIS8_EESC_EEvOT_OT0_
+ ___Block_byref_object_copy_
+ ___Block_byref_object_dispose_
+ ____ZNK6mach_o12UnsafeHeader26validStructureLoadCommandsEy_block_invoke
+ ___block_descriptor_64_ea8_32s40bs_e16_v32?0r^v8Q16Q24ls32l8s40l8
+ ___dyld_shared_cache_for_each_unattributed_range_block_invoke
+ _dyld_image_get_cpu_subtype
+ _dyld_image_get_cpu_type
+ _dyld_shared_cache_for_each_unattributed_range
+ _dyld_shared_cache_get_cpu_subtype
+ _dyld_shared_cache_get_cpu_type
+ _dyld_shared_cache_range_type_all
+ _dyld_shared_cache_range_type_all_code
- GCC_except_table100
- GCC_except_table101
- GCC_except_table44
- GCC_except_table47
- GCC_except_table51
- GCC_except_table54
- GCC_except_table55
- GCC_except_table58
- GCC_except_table59
- GCC_except_table66
- GCC_except_table69
- GCC_except_table71
- GCC_except_table79
- GCC_except_table82
- GCC_except_table86
- GCC_except_table97
- GCC_except_table98
- __ZNKSt3__111__copy_implclB9fqn220100IPSt4byteS3_NS_20back_insert_iteratorI10ByteStreamEELi0EEENS_4pairIT_T1_EES8_T0_S9_
- __ZNKSt3__111__copy_implclB9fqn220100IPSt4byteS3_NS_20back_insert_iteratorIN3lsl6VectorIS2_EEEELi0EEENS_4pairIT_T1_EESA_T0_SB_
- __ZNSt3__119__unwrap_range_implIN3lsl6VectorISt4byteE15CheckedIteratorIS3_EES6_E8__unwrapB9fqn220100ES6_S6_
- __ZNSt3__124__copy_move_unwrap_itersB9fqn220100INS_11__copy_implEN3lsl6VectorISt4byteE15CheckedIteratorIS4_EES7_PS4_Li0EEENS_4pairIT0_T2_EESA_T1_SB_
- __ZNSt3__18_IterOpsINS_17_ClassicAlgPolicyEE9iter_swapB9fqn220100IRN3lsl6VectorIPN12PropertyList4DataEE15CheckedIteratorIS8_EESC_EEvOT_OT0_
- __ZNSt3__18_IterOpsINS_17_ClassicAlgPolicyEE9iter_swapB9fqn220100IRN3lsl6VectorIPN12PropertyList6StringEE15CheckedIteratorIS8_EESC_EEvOT_OT0_
- __ZNSt3__18_IterOpsINS_17_ClassicAlgPolicyEE9iter_swapB9fqn220100IRN3lsl6VectorIPN12PropertyList7IntegerEE15CheckedIteratorIS8_EESC_EEvOT_OT0_
CStrings:
+ "/usr/lib/libsharedcache.dylib"
+ "__dsc_opt_list"
+ "cput"
+ "gots"
+ "load command #%d LC_ATOM_INFO size wrong"
+ "load command #%d LC_BUILD_VERSION size wrong"
+ "load command #%d LC_DYLD_CHAINED_FIXUPS size wrong"
+ "load command #%d LC_DYLD_EXPORTS_TRIE size wrong"
+ "load command #%d LC_DYLD_INFO_ONLY size wrong"
+ "load command #%d LC_DYSYMTAB size wrong"
+ "load command #%d LC_ENCRYPTION_INFO size wrong"
+ "load command #%d LC_ENCRYPTION_INFO_64 size wrong"
+ "load command #%d LC_FUNCTION_STARTS size wrong"
+ "load command #%d LC_FUNCTION_VARIANTS size wrong"
+ "load command #%d LC_FUNCTION_VARIANT_FIXUPS size wrong"
+ "load command #%d LC_MAIN size wrong"
+ "load command #%d LC_SEGMENT size does not match number of sections"
+ "load command #%d LC_SEGMENT_64 size does not match number of sections"
+ "load command #%d LC_SEGMENT_SPLIT_INFO size wrong"
+ "load command #%d LC_SYMTAB size wrong"
+ "load command #%d LC_UUID size wrong"
+ "load command #%d LC_VERSION_MIN_* size wrong"
+ "load command #%d string extends beyond end of load command"
+ "load command #%d string offset (%u) outside its size (%u)"
+ "load command #%d unknown required load command 0x%08X"
+ "load commands length (%llu) exceeds length of file (%llu)"
+ "objc_stubs"
+ "stubs"
+ "unknown filetype %d"
+ "v32@?0r^v8Q16Q24"
```
