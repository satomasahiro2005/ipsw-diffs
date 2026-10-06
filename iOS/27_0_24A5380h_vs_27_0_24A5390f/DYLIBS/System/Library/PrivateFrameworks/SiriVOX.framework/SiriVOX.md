## SiriVOX

> `/System/Library/PrivateFrameworks/SiriVOX.framework/SiriVOX`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x84098` | `0x8430c` | **`+0x274`** |
| `__AUTH_CONST.__objc_const` | `0x13558` | `0x13598` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x8ae0` | `0x8b20` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d30` | `0x3d60` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x770` | `0x788` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x23b0` | `0x23c0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xc9c` | `0xca0` | **`+0x4`** |
| `__TEXT.__cstring` | `0x1184e` | `0x11850` | **`+0x2`** |

### Other Changes

```diff

-3600.52.2.0.0
+3600.52.4.0.0

-  Functions: 3134
-  Symbols:   6657
+  Functions: 3138
+  Symbols:   6662
Symbols:
+ -[SVXSession activationInterceptor]
+ -[SVXSession setActivationInterceptor:]
+ -[SVXSessionManager session:performMyriadForActivationContext:]
+ GCC_except_table1809
+ GCC_except_table1810
+ GCC_except_table1917
+ GCC_except_table2077
+ GCC_except_table2210
+ GCC_except_table2333
+ GCC_except_table2348
+ GCC_except_table2349
+ GCC_except_table2472
+ GCC_except_table2474
+ GCC_except_table2477
+ GCC_except_table2779
+ GCC_except_table2934
+ GCC_except_table3009
+ _OBJC_IVAR_$_SVXSession._activationInterceptor
+ ___63-[SVXSessionManager session:performMyriadForActivationContext:]_block_invoke
- GCC_except_table1805
- GCC_except_table1808
- GCC_except_table1915
- GCC_except_table2075
- GCC_except_table2208
- GCC_except_table2329
- GCC_except_table2344
- GCC_except_table2345
- GCC_except_table2464
- GCC_except_table2470
- GCC_except_table2473
- GCC_except_table2775
- GCC_except_table2930
- GCC_except_table3005
CStrings:
+ "\xf0\xe1\xf0\xf1"
- "\xf0\xe1"
```
