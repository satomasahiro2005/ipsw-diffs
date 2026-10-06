## OTSVG

> `/System/Library/PrivateFrameworks/OTSVG.framework/OTSVG`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3671c` | `0x3682c` | **`+0x110`** |
| `__AUTH_CONST.__cfstring` | `0x2a0` | `0x300` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x930` | `0x968` | **`+0x38`** |
| `__TEXT.__cstring` | `0xb94` | `0xbc4` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x2538` | `0x2558` | **`+0x20`** |
| `__DATA.__bss` | `—` | `0x10` | **`+0x10`** |

### Other Changes

```diff

-900.0.0.0.0
+904.0.0.0.0

-  Functions: 986
-  Symbols:   1487
-  CStrings:  284
+  Functions: 987
+  Symbols:   1498
+  CStrings:  288
Symbols:
+ _CFArrayCreate
+ _CFDictionaryCreate
+ __MergedGlobals
+ __NSConcreteGlobalBlock
+ ____ZN3SVGL21getImageFilterOptionsEv_block_invoke
+ ___block_descriptor_tmp
+ ___block_literal_global
+ _dispatch_once
+ _kCFTypeDictionaryKeyCallBacks
+ _kCFTypeDictionaryValueCallBacks
+ _kCGImageSourceAllowableTypes
Functions:
~ __ZN3SVG12ImageElementC2EPKNS_7ElementERKNSt3__113unordered_mapINS_13QualifiedNameENS4_12basic_stringIcNS4_11char_traitsIcEENS4_9allocatorIcEEEENS_17QualifiedNameHashENS_22QualifiedNamePredicateENSA_INS4_4pairIKS6_SC_EEEEEE : 1524 -> 1580
+ -[_OTSVGParserDelegate initWithUnitsPerEm:]
CStrings:
+ "com.compuserve.gif"
+ "public.jpeg"
+ "public.png"
+ "v8@?0"
```
