## TSPersistence

> `/System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSPersistence.framework/TSPersistence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x2f63f` | `0x2f258` | **`-0x3e7`** |
| `__TEXT.__text` | `0x24540c` | `0x2450cc` | **`-0x340`** |
| `__TEXT.__gcc_except_tab` | `0x28b78` | `0x28a70` | **`-0x108`** |
| `__AUTH_CONST.__cfstring` | `0x40c0` | `0x4180` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0xaac0` | `0xab60` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x54b0` | `0x5530` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x5628` | `0x5668` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x10380` | `0x103b8` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x740` | `0x768` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x18040` | `0x18030` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0xa28` | `0xa30` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xd010` | `0xd018` | **`+0x8`** |

### Other Changes

```diff

-487.0.0.0.0
+488.0.0.0.0

+  - /System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/AppEditIn.framework/AppEditIn
+  - /System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSFundamentals.framework/TSFundamentals
+  - /System/Library/PrivateFrameworks/iWorkImport.framework/Frameworks/TSGeometry.framework/TSGeometry

-  Functions: 12786
-  Symbols:   5096
-  CStrings:  3446
+  Functions: 12802
+  Symbols:   5103
+  CStrings:  3445
Symbols:
+ _CFRetain
+ _OBJC_CLASS_$_AEIPixelmatorDocumentPreviewProvider
+ _TSPVersionG15_3
+ _TSUAppEditInCat_init_token
+ _TSUAppEditInCat_log_t
+ _TSUPXDBinary
+ _TSUPXDPackage
CStrings:
+ "Sheet Tab Color"
+ "Sheet Tab Hiding"
+ "TNSheetTabColor"
+ "TNSheetTabHiding"
+ "TSUAppEditInCat"
+ "dyn."
+ "pxd"
+ "v16@?0^{CGImageSource=}8"
+ "v24@?0^{CGImageSource=}8@\"NSError\"16"
+ "v32@?0^{CGImageSource=}8@\"AEIPixelmatorDocumentInfo\"16@\"NSError\"24"
- "%{public}@ package read two objects with identifier %llu: (component:[%{public}@-%llu], object:[%@]) and (component:[%{public}@-%llu], object:[%@])."
- "-[TSPLazyReference retainObject:]"
- "Object [%{public}@-%llu] resolved to an unknown object, referenced from component [%{public}@-%llu] in the %{public}@ package."
- "Object [%{public}@-%llu] resolved to an unknown object."
- "Object [%{public}@-%llu] was not unarchived, referenced from component [%{public}@-%llu] in the %{public}@ package."
- "Object [%{public}@-%llu] was not unarchived."
- "void TSPLogObjectNotUnarchived(__unsafe_unretained Class, TSPObjectIdentifier, TSPObject *__strong)"
- "void TSPLogObjectNotUnarchivedFromDifferentComponent(__unsafe_unretained Class, TSPObjectIdentifier, TSPObject *__strong, TSPComponent *__strong)"
- "void TSPLogObjectResolvedToUnknown(BOOL, __unsafe_unretained Class, TSPObjectIdentifier, TSPObject *__strong)"
- "void TSPLogObjectResolvedToUnknownFromDifferentComponent(BOOL, __unsafe_unretained Class, TSPObjectIdentifier, TSPObject *__strong, TSPComponent *__strong)"
- "void TSPPackageReadCoordinatorInstrumentedAssertObjectWasNotReadTwice(TSPPackageIdentifier, TSPObjectIdentifier, TSPObject *__strong, TSPComponent *__strong, NSMapTable *__strong)"
```
