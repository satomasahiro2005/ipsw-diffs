## mediaanalysisd-generation

> `/System/Library/PrivateFrameworks/MediaAnalysisGeneration.framework/XPCServices/mediaanalysisd-generation.xpc/mediaanalysisd-generation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x771c` | `0x79c0` | **`+0x2a4`** |
| `__TEXT.__objc_stubs` | `0x6a0` | `0x7a0` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x692` | `0x730` | **`+0x9e`** |
| `__TEXT.__oslogstring` | `0x4c3` | `0x553` | **`+0x90`** |
| `__DATA_CONST.__cfstring` | `0x220` | `0x280` | **`+0x60`** |
| `__TEXT.__cstring` | `0x2fd` | `0x35d` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x488` | `0x4e8` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x268` | `0x2a8` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x210` | `0x230` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x254` | `0x26c` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2c0` | `0x2d0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-435.73.2.0.0
+435.79.1.4.0

+  - /System/Library/PrivateFrameworks/RunningBoardServices.framework/RunningBoardServices

-  Functions: 135
-  Symbols:   201
-  CStrings:  172
+  Functions: 138
+  Symbols:   205
+  CStrings:  185
Symbols:
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_RBSAssertion
+ _OBJC_CLASS_$_RBSDomainAttribute
+ _OBJC_CLASS_$_RBSTarget
CStrings:
+ "AlchemistRender"
+ "[MADGenerationXPCService] Acquired render jetsam assertion (active band)"
+ "[MADGenerationXPCService] Failed to acquire render jetsam assertion: %@"
+ "acquireWithError:"
+ "arrayWithObjects:count:"
+ "attributeWithDomain:name:"
+ "beginRequest"
+ "com.apple.mediaanalysisd-generation"
+ "currentProcess"
+ "endRequest:"
+ "initWithExplanation:target:attributes:"
+ "invalidate"
+ "mediaanalysisd-generation Alchemist render"
```
