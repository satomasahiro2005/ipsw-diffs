## libdyld.dylib

> `/usr/lib/system/libdyld.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c3f0` | `0x1c7cc` | **`+0x3dc`** |
| `__TEXT.__cstring` | `0x4b37` | `0x4be0` | **`+0xa9`** |
| `__DATA_CONST.__const` | `0x1958` | `0x1990` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0xd80` | `0xda0` | **`+0x20`** |
| `__TEXT.__const` | `0x31c` | `0x32c` | **`+0x10`** |

### Other Changes

```diff

-27050.4.0.0.0
+27056.0.0.0.0

-  Functions: 846
-  Symbols:   1067
-  CStrings:  533
+  Functions: 853
+  Symbols:   1078
+  CStrings:  536
Symbols:
+ __ZN6mach_o19GradedArchitectures19launch_iOS_internalE
+ __ZN6mach_o21FunctionVariantFixupsC1ENSt3__14spanIKhLm18446744073709551615EEE
+ __ZN6mach_oL18archs_iOS_internalE
+ __ZNK6mach_o13ChainedFixups13validLinkeditEybNSt3__14spanIKNS_13MappedSegmentELm18446744073709551615EEEb
+ __ZNK6mach_o13ChainedFixups5validEyNSt3__14spanIKNS_13MappedSegmentELm18446744073709551615EEEbbb
+ __ZNK6mach_o21FunctionVariantFixups5validENSt3__14spanIKNS_13MappedSegmentELm18446744073709551615EEE
+ __ZNKSt3__117basic_string_viewIcNS_11char_traitsIcEEE11starts_withB9nqn220106EPKc
+ __ZNKSt3__117basic_string_viewIcNS_11char_traitsIcEEE7compareB9nqn220106EmmS3_
+ __ZNSt3__16__itoa8__traitsIjE6__readB9nqn220106EPKcS4_RjS5_
+ ____ZNK6mach_o13ChainedFixups13validLinkeditEybNSt3__14spanIKNS_13MappedSegmentELm18446744073709551615EEEb_block_invoke
+ _dyld_image_get_cpu_subtype
+ _dyld_image_get_cpu_type
+ _dyld_shared_cache_for_each_unattributed_range
+ _dyld_shared_cache_get_cpu_subtype
+ _dyld_shared_cache_get_cpu_type
+ _dyld_shared_cache_range_type_all
+ _dyld_shared_cache_range_type_all_code
- __ZNK6mach_o13ChainedFixups13validLinkeditEybNSt3__14spanIKNS_13MappedSegmentELm18446744073709551615EEE
- __ZNK6mach_o13ChainedFixups5validEyNSt3__14spanIKNS_13MappedSegmentELm18446744073709551615EEEbb
- __ZNKSt3__117basic_string_viewIcNS_11char_traitsIcEEE11starts_withB9nqn220100EPKc
- __ZNKSt3__117basic_string_viewIcNS_11char_traitsIcEEE7compareB9nqn220100EmmS3_
- __ZNSt3__16__itoa8__traitsIjE6__readB9nqn220100EPKcS4_RjS5_
- ____ZNK6mach_o13ChainedFixups13validLinkeditEybNSt3__14spanIKNS_13MappedSegmentELm18446744073709551615EEE_block_invoke
CStrings:
+ "FunctionVariantFixups segIndex=%d exceeds number of segments (%lu)"
+ "FunctionVariantFixups segOffset=0x%08X exceeds segment size (0x%llX)"
+ "too many segments %llu (max 255)"
```
