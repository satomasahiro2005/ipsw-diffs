## MTLCompiler

> `/System/Library/PrivateFrameworks/MTLCompiler.framework/Versions/32023/MTLCompiler`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbad3c` | `0xbb1ec` | **`+0x4b0`** |
| `__TEXT.__cstring` | `0x85c4` | `0x860c` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x30c8` | `0x30d8` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x9bd0` | `0x9bcc` | **`-0x4`** |

### Other Changes

```diff

-  Functions: 2260
-  Symbols:   3608
-  CStrings:  1414
+  Functions: 2264
+  Symbols:   3612
+  CStrings:  1416
Symbols:
+ GCC_except_table520
+ GCC_except_table523
+ __ZNK13AirReflection16PersistentFnAttr8HashImplERN11flatbuffers16SignatureBuilderE
+ __ZNK13AirReflection26ForwardProgressUsageFnAttr8HashImplERN11flatbuffers16SignatureBuilderE
+ __ZNK13AirReflection4Node24node_as_PersistentFnAttrEv
+ __ZNK13AirReflection4Node34node_as_ForwardProgressUsageFnAttrEv
- GCC_except_table513
- GCC_except_table519
CStrings:
+ "AirReflection.ForwardProgressUsageFnAttr"
+ "AirReflection.PersistentFnAttr"
```
