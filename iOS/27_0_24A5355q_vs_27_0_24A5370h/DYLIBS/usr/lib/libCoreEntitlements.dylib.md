## libCoreEntitlements.dylib

> `/usr/lib/libCoreEntitlements.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7c54` | `0x7c78` | **`+0x24`** |

### Other Changes

```diff

-93.0.0.0.0
+94.0.0.0.0
Symbols:
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorI19CESerializedElementNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorI19CESerializedElementNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
Functions:
~ _der_vm_execute_nocopy : 3060 -> 3044
~ __Z11serializeIdP11objc_objectRNSt3__16vectorI19CESerializedElementNS1_9allocatorIS3_EEEE : 1024 -> 1020
~ _CESerializeWithOptions : 592 -> 608
~ _CESerializeXML : 1912 -> 1960
~ _CEPrepareQuery : 228 -> 236
~ _der_vm_execute_match_string : 256 -> 252
~ _der_vm_execute_match_string_prefix : 276 -> 272
~ _string_value_allowed_iterate : 344 -> 340
~ _string_prefix_allowed_iterate : 268 -> 264
```
