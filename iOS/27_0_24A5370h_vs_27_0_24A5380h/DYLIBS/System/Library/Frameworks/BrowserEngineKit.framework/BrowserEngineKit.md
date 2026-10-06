## BrowserEngineKit

> `/System/Library/Frameworks/BrowserEngineKit.framework/BrowserEngineKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21164` | `0x21550` | **`+0x3ec`** |
| `__TEXT.__cstring` | `0xb4c` | `0xc1c` | **`+0xd0`** |
| `__AUTH.__objc_data` | `0x9a0` | `0x900` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x6f0` | `0x790` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x11b8` | `0x1240` | **`+0x88`** |
| `__TEXT.__const` | `0x1116` | `0x1166` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x380` | `0x3c0` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x2b0` | `0x2e8` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x470` | `0x498` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xbf8` | `0xc20` | **`+0x28`** |
| `__DATA_DIRTY.__data` | `0x9e0` | `0xa00` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x990` | `0x9a8` | **`+0x18`** |
| `__AUTH_CONST.__weak_auth_got` | `—` | `0x18` | **`+0x18`** |

### Other Changes

```diff

-7625.1.20.0.0
+7625.1.22.3.0

-  Functions: 1027
-  Symbols:   1228
-  CStrings:  118
+  Functions: 1036
+  Symbols:   1252
+  CStrings:  120
Symbols:
+ GCC_except_table19
+ GCC_except_table20
+ GCC_except_table31
+ GCC_except_table32
+ GCC_except_table33
+ __ZNKSt3__119__shared_weak_count13__get_deleterERKSt9type_info
+ __ZNSt3__119__shared_weak_count14__release_weakEv
+ __ZNSt3__119__shared_weak_count16__release_sharedB9fqe220106Ev
+ __ZNSt3__119__shared_weak_countD2Ev
+ __ZNSt3__120__shared_ptr_emplaceINS_6atomicIbEENS_9allocatorIS2_EEE16__on_zero_sharedEv
+ __ZNSt3__120__shared_ptr_emplaceINS_6atomicIbEENS_9allocatorIS2_EEE21__on_zero_shared_weakEv
+ __ZNSt3__120__shared_ptr_emplaceINS_6atomicIbEENS_9allocatorIS2_EEED0Ev
+ __ZNSt3__120__shared_ptr_emplaceINS_6atomicIbEENS_9allocatorIS2_EEED1Ev
+ __ZTINSt3__119__shared_weak_countE
+ __ZTINSt3__120__shared_ptr_emplaceINS_6atomicIbEENS_9allocatorIS2_EEEE
+ __ZTSNSt3__120__shared_ptr_emplaceINS_6atomicIbEENS_9allocatorIS2_EEEE
+ __ZTVN10__cxxabiv120__si_class_type_infoE
+ __ZTVNSt3__120__shared_ptr_emplaceINS_6atomicIbEENS_9allocatorIS2_EEEE
+ __ZdlPv
+ __ZdlPvSt19__type_descriptor_t
+ __ZnwmSt19__type_descriptor_t
+ ___77-[BEWebContentFilter evaluateURL:mainFrameURL:isMainFrame:completionHandler:]_block_invoke_3
+ ___block_descriptor_48_ea8_32bs40r_e19_v20?0B8"NSData"12lr40l8s32l8
+ ___block_descriptor_56_ea8_32bs40c40_ZTSNSt3__110shared_ptrINS_6atomicIbEEEE_e19_v20?0B8"NSData"12l
+ ___copy_helper_block_ea8_40c40_ZTSNSt3__110shared_ptrINS_6atomicIbEEEE
+ ___destroy_helper_block_ea8_40c40_ZTSNSt3__110shared_ptrINS_6atomicIbEEEE
+ _objc_retain_x27
- GCC_except_table13
- GCC_except_table18
- GCC_except_table27
CStrings:
+ "BEWebContentFilter::evaluateURL attempted to invoke its completionHandler more than once."
+ "BEWebContentFilter::evaluateURL:mainFrameURL:isMainFrame attempted to invoke its completionHandler more than once."
```
