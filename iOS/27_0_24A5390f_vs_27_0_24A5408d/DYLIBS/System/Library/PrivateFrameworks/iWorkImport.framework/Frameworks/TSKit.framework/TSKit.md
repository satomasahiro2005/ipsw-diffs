## TSKit

> `/System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSKit.framework/TSKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa38c8` | `0xa4210` | **`+0x948`** |
| `__AUTH_CONST.__objc_const` | `0x9f08` | `0xa0e0` | **`+0x1d8`** |
| `__TEXT.__cstring` | `0x16e55` | `0x16fa5` | **`+0x150`** |
| `__TEXT.__objc_methlist` | `0x5f68` | `0x6058` | **`+0xf0`** |
| `__AUTH.__objc_data` | `0x2488` | `0x2548` | **`+0xc0`** |
| `__AUTH_CONST.__cfstring` | `0xb480` | `0xb4e0` | **`+0x60`** |
| `__AUTH_CONST.__objc_intobj` | `0x7368` | `0x73b0` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x3f30` | `0x3f70` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x3c18` | `0x3c50` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x5aa8` | `0x5ad8` | **`+0x30`** |
| `__TEXT.__const` | `0xaff4` | `0xb024` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x3f7` | `0x423` | **`+0x2c`** |
| `__AUTH.__data` | `0x58` | `0x78` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x47d0` | `0x47f0` | **`+0x20`** |
| `__DATA.__bss` | `0x1310` | `0x1320` | **`+0x10`** |
| `__DATA.__data` | `0xa98` | `0xaa8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x910` | `0x920` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x380` | `0x390` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x300` | `0x310` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x528` | `0x530` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0xd0` | `0xd8` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x50` | `0x58` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x260` | `0x268` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x60b0` | `0x60b8` | **`+0x8`** |

### Other Changes

```diff

-487.0.0.0.0
+488.0.0.0.0

+  - /System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSFundamentals.framework/TSFundamentals
+  - /System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSGeometry.framework/TSGeometry

-  Functions: 4462
-  Symbols:   3635
-  CStrings:  2144
+  Functions: 4483
+  Symbols:   3641
+  CStrings:  2151
Symbols:
+ _OBJC_CLASS_$_TSKBehaviorMarshal
+ _OBJC_METACLASS_$_NSMutableArray
+ _OBJC_METACLASS_$_TSKBehaviorMarshal
+ _kTSKOperationPropertyTNSheetTabColor
+ _kTSKOperationPropertyTransitionCustomAttributesAngle
+ _kTSKOperationPropertyTransitionCustomAttributesBlurAmount
CStrings:
+ "-[TSKAccessController p_writeLockAndBlockPrimaryThread:writerQueueItem:]"
+ "-[TSKApplicationPropertiesProvider feedbackFeatureDomain]"
+ "Cached head thread identifier should match queue front"
+ "TSKAnnotationAuthorColors"
+ "Writing thread must be at head of writer queue."
+ "Writing thread must be enqueued correctly."
+ "keynote.slide.transition.setValue.customAngle"
+ "keynote.slide.transition.setValue.customBlurAmount"
+ "style.sheet.tabColor"
- "-[TSKAccessController p_writeLockAndBlockPrimaryThread:]"
- "TSDAnnotationAuthorColors"
```
