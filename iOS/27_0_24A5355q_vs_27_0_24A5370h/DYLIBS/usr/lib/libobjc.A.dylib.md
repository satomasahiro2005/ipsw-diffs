## libobjc.A.dylib

> `/usr/lib/libobjc.A.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3df24` | `0x3d000` | **`-0xf24`** |
| `__TEXT.__unwind_info` | `0xe78` | `0xe58` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0xb10` | `0xb04` | **`-0xc`** |
| `__AUTH_CONST.__const` | `0x580` | `0x578` | **`-0x8`** |
| `__DATA_CONST.__const` | `0x938` | `0x940` | **`+0x8`** |

### Other Changes

```diff

-966.0.0.0.0
+971.0.0.0.0

-  Functions: 885
+  Functions: 867
Symbols:
+ __ZNSt3__112construct_atB9fqn220106IN8method_t9bigSignedEJS2_EPS2_EEPT_S5_DpOT0_
+ __ZNSt3__16vectorI29_dyld_objc_notify_mapped_infoNS_9allocatorIS1_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorINS_4pairIPK14mach_header_64ZL21withHeaderInfoForPathIZ24objc_copyClassesForImageE3$_0EvPKcRKT_E11uuidWrapperEENS_9allocatorISD_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorINS_4pairIPK14mach_header_64ZL21withHeaderInfoForPathIZ27objc_copyClassNamesForImageE3$_0EvPKcRKT_E11uuidWrapperEENS_9allocatorISD_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorIPK11mach_headerNS_9allocatorIS3_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__16vectorIPK14mach_header_64NS_9allocatorIS3_EEE20__throw_length_errorB9fqn220106Ev
+ __ZNSt3__18_IterOpsINS_17_ClassicAlgPolicyEE9iter_swapB9fqn220106IRPN8method_t9bigSignedES7_EEvOT_OT0_
+ __ZSt28__throw_bad_array_new_lengthB9fqn220106v
+ _objc_debug_original_metaclass_map
- __ZNK11header_info7selrefsEPm
- __ZNSt3__112construct_atB9fqn220100IN8method_t9bigSignedEJS2_EPS2_EEPT_S5_DpOT0_
- __ZNSt3__16vectorI29_dyld_objc_notify_mapped_infoNS_9allocatorIS1_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__16vectorINS_4pairIPK14mach_header_64ZL21withHeaderInfoForPathIZ24objc_copyClassesForImageE3$_0EvPKcRKT_E11uuidWrapperEENS_9allocatorISD_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__16vectorINS_4pairIPK14mach_header_64ZL21withHeaderInfoForPathIZ27objc_copyClassNamesForImageE3$_0EvPKcRKT_E11uuidWrapperEENS_9allocatorISD_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__16vectorIPK11mach_headerNS_9allocatorIS3_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__16vectorIPK14mach_header_64NS_9allocatorIS3_EEE20__throw_length_errorB9fqn220100Ev
- __ZNSt3__18_IterOpsINS_17_ClassicAlgPolicyEE9iter_swapB9fqn220100IRPN8method_t9bigSignedES7_EEvOT_OT0_
- __ZSt28__throw_bad_array_new_lengthB9fqn220100v
```
