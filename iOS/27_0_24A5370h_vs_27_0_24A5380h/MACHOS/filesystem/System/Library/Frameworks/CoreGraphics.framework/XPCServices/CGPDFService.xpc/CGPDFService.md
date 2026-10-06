## CGPDFService

> `/System/Library/Frameworks/CoreGraphics.framework/XPCServices/CGPDFService.xpc/CGPDFService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22cc` | `0x26d0` | **`+0x404`** |
| `__TEXT.__cstring` | `0x34e` | `0x408` | **`+0xba`** |
| `__TEXT.__gcc_except_tab` | `0x4a8` | `0x52c` | **`+0x84`** |
| `__TEXT.__objc_methname` | `0x47b` | `0x4e8` | **`+0x6d`** |
| `__TEXT.__objc_methtype` | `0x42f` | `0x475` | **`+0x46`** |
| `__DATA_CONST.__cfstring` | `0x80` | `0xc0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x130` | `0x170` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x420` | `0x460` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x2e0` | `0x320` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x88` | `0xb0` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x220` | `0x240` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x230` | `0x250` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1e8` | `0x200` | **`+0x18`** |
| `__TEXT.__const` | `0x58` | `0x70` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x364` | `0x374` | **`+0x10`** |
| `__DATA.__objc_const` | `0x6c0` | `0x6c8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-2043.0.0.0.0
+2045.0.0.0.0

-  Functions: 56
-  Symbols:   267
-  CStrings:  150
+  Functions: 60
+  Symbols:   285
+  CStrings:  158
Symbols:
+ -[CGPDFService newPDFDocumentWithData:withReplyOrError:]
+ GCC_except_table17
+ GCC_except_table22
+ _NSDebugDescriptionErrorKey
+ _OBJC_CLASS_$_NSDictionary
+ _OBJC_CLASS_$_NSError
+ __ZN21CGPDFServiceExceptionD0Ev
+ __ZN21CGPDFServiceExceptionD1Ev
+ __ZNKSt9exception4whatEv
+ __ZNSt9exceptionD2Ev
+ __ZTI21CGPDFServiceException
+ __ZTS21CGPDFServiceException
+ __ZTV21CGPDFServiceException
+ __ZTVN10__cxxabiv120__si_class_type_infoE
+ __ZdlPvSt19__type_descriptor_t
+ ___56-[CGPDFService newPDFDocumentWithData:withReplyOrError:]_block_invoke
+ ___stack_chk_fail
+ ___stack_chk_guard
+ _objc_msgSend$dictionaryWithObjects:forKeys:count:
+ _objc_msgSend$errorWithDomain:code:userInfo:
+ _objc_release_x22
- GCC_except_table20
- GCC_except_table3
- GCC_except_table6
CStrings:
+ "%s caught CGPDFServiceException: code=%ld"
+ "-[CGPDFService newPDFDocumentWithData:withReplyOrError:]_block_invoke"
+ "CGPDFServiceErrorDataProviderCreationFailed"
+ "CGPDFServiceErrorInvalidPDFData"
+ "CGPDFServiceErrorUnknown"
+ "com.apple.CoreGraphics.CGPDFService"
+ "dictionaryWithObjects:forKeys:count:"
+ "errorWithDomain:code:userInfo:"
+ "newPDFDocumentWithData:withReplyOrError:"
+ "v32@0:8@\"NSData\"16@?<v@?@\"<CGRemotePDFDocumentProtocol>\"@\"NSError\">24"
- "Failed to create CGDataProvoder"
- "Failed to create CGPDFDocument"
```
