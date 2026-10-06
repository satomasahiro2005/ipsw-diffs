## NanoRegistry

> `/System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x54a84` | `0x547c4` | **`-0x2c0`** |
| `__TEXT.__cstring` | `0x4166` | `0x4145` | **`-0x21`** |
| `__AUTH_CONST.__cfstring` | `0x4ac0` | `0x4aa0` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x498` | `0x488` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x20ee` | `0x20ed` | **`-0x1`** |

### Other Changes

```diff

-1070.0.0.0.0
+1075.0.0.0.0

-  Symbols:   3622
-  CStrings:  826
+  Symbols:   3620
+  CStrings:  823
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIjEENS_16allocator_traitsIS2_EEEENS_19__allocation_resultINT0_7pointerENS6_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorIjNS_9allocatorIjEEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- __os_feature_enabled_impl
- _os_variant_allows_internal_security_policies
CStrings:
+ "Revlock is set to shipping behavior"
+ "apple-internal-install"
- "NanoRegistry"
- "Revlock feature flag is currently %@"
- "disabled"
- "enabled"
- "revlock_shipping_behavior"
```
