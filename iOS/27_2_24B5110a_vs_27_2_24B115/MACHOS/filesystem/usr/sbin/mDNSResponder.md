## mDNSResponder

> `/usr/sbin/mDNSResponder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10b364` | `0x10b75c` | **`+0x3f8`** |
| `__TEXT.__oslogstring` | `0x211f9` | `0x212b6` | **`+0xbd`** |
| `__TEXT.__unwind_info` | `0x16e0` | `0x16e8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 1874
-  Symbols:   4156
-  CStrings:  4785
+  Functions: 1876
+  Symbols:   4158
+  CStrings:  4787
Symbols:
+ GCC_except_table1122
+ GCC_except_table1253
+ GCC_except_table1259
+ GCC_except_table1422
+ GCC_except_table1605
+ GCC_except_table1838
+ GCC_except_table489
+ _CacheRecordDecrementIneligibleForRecycling
+ _CacheRecordIncrementIneligibleForRecycling
- GCC_except_table1120
- GCC_except_table1251
- GCC_except_table1257
- GCC_except_table1420
- GCC_except_table1603
- GCC_except_table1836
- GCC_except_table487
CStrings:
+ "ineligibleForRecycling overflow - %{sensitive, mdnsresponder:domain_name}.*P %{mdns:dn_hash}u"
+ "ineligibleForRecycling underflow - %{sensitive, mdnsresponder:domain_name}.*P %{mdns:dn_hash}u"
```
