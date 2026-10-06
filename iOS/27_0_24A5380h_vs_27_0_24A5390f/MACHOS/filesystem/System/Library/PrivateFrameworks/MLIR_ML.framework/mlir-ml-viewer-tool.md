## mlir-ml-viewer-tool

> `/System/Library/PrivateFrameworks/MLIR_ML.framework/mlir-ml-viewer-tool`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a88` | `0x1ccc` | **`+0x244`** |
| `__TEXT.__cstring` | `0x3fa` | `0x44c` | **`+0x52`** |
| `__TEXT.__gcc_except_tab` | `0x154` | `0x174` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1c0` | `0x1e0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x146` | `0x158` | **`+0x12`** |
| `__TEXT.__unwind_info` | `0xf8` | `0x108` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x70` | `0x78` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`

### Other Changes

```diff

-7.0.75.1.0
+7.0.76.1.0

-  Functions: 32
-  Symbols:   116
-  CStrings:  43
+  Functions: 33
+  Symbols:   119
+  CStrings:  46
Symbols:
+ GCC_except_table31
+ GCC_except_table34
+ __ZN16EmitterViewerSPI15dumpToTextualIREP6NSDataP26MLViewerGraphDescriptorSPI
+ __ZN4llvm2cl3optIbLb0ENS0_6parserIbEEEC2IJA7_cNS0_4descENS0_11initializerIbEEEEEDpRKT_
+ __ZN4llvm2cl3optIbLb0ENS0_6parserIbEEED1Ev
+ __ZNSt3__18functionIFvRKbEED1Ev
+ _objc_msgSend$setInlineRegions:
- GCC_except_table32
- __ZN16EmitterViewerSPI15dumpToTextualIREP6NSData
- __ZN4llvm2cl3optIbLb0ENS0_6parserIbEEED2Ev
- __ZNSt3__18functionIFvRKbEED2Ev
Functions:
~ _main : 2564 -> 2840
+ __ZN4llvm2cl3optIbLb0ENS0_6parserIbEEED1Ev
- __ZN4llvm2cl3optIbLb0ENS0_6parserIbEEED2Ev
+ __ZN4llvm2cl3optIbLb0ENS0_6parserIbEEEC2IJA7_cNS0_4descENS0_11initializerIbEEEEEDpRKT_
CStrings:
+ "Perform graph stitching by inlining callable operations for visualization."
+ "inline"
+ "setInlineRegions:"
```
