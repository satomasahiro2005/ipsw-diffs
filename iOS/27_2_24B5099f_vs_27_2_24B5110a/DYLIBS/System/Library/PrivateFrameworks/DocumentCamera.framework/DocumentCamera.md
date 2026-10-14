## DocumentCamera

> `/System/Library/PrivateFrameworks/DocumentCamera.framework/DocumentCamera`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa7328` | `0xa7a74` | **`+0x74c`** |
| `__TEXT.__gcc_except_tab` | `0x9578` | `0x963c` | **`+0xc4`** |
| `__TEXT.__oslogstring` | `0x1e01` | `0x1e81` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x97d8` | `0x9838` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x15238` | `0x15280` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x3060` | `0x30a0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x62d8` | `0x6310` | **`+0x38`** |
| `__TEXT.__const` | `0x1b74` | `0x1b84` | **`+0x10`** |

### Other Changes

```diff

-211.40.1.0.0
+211.40.2.0.0

-  Functions: 4229
-  Symbols:   6479
-  CStrings:  788
+  Functions: 4236
+  Symbols:   6491
+  CStrings:  790
Symbols:
+ +[ICDocCamViewController documentInfoForSingleImageDelivery:]
+ +[ICDocCamViewController isQuadPlausibleForEmbeddedCapture:]
+ +[ICDocCamViewController quadByExtruding:byFraction:withinBounds:wasConstrained:]
+ -[ICDocCamImageQuad containsAngleOutOfValidThreshold:]
+ -[ICDocCamViewController notifyDelegateExtrusionIsConstrained]
+ -[VNDocumentCameraViewController_InProcess documentCameraControllerExtrusionIsConstrained:]
+ GCC_except_table232
+ GCC_except_table233
+ GCC_except_table234
+ GCC_except_table235
+ GCC_except_table242
+ GCC_except_table251
+ GCC_except_table255
+ GCC_except_table258
+ GCC_except_table268
+ GCC_except_table272
+ GCC_except_table274
+ GCC_except_table278
+ GCC_except_table282
+ GCC_except_table285
+ GCC_except_table295
+ GCC_except_table296
+ GCC_except_table298
+ GCC_except_table304
+ GCC_except_table313
+ GCC_except_table328
+ GCC_except_table331
+ GCC_except_table357
+ GCC_except_table358
+ GCC_except_table360
+ GCC_except_table361
+ GCC_except_table364
+ ___62-[ICDocCamViewController notifyDelegateExtrusionIsConstrained]_block_invoke
- GCC_except_table237
- GCC_except_table238
- GCC_except_table239
- GCC_except_table240
- GCC_except_table257
- GCC_except_table261
- GCC_except_table263
- GCC_except_table270
- GCC_except_table273
- GCC_except_table277
- GCC_except_table283
- GCC_except_table284
- GCC_except_table287
- GCC_except_table290
- GCC_except_table300
- GCC_except_table301
- GCC_except_table303
- GCC_except_table309
- GCC_except_table318
- GCC_except_table333
- GCC_except_table336
CStrings:
+ "Requested quad extrusion of %f does not fit within the image"
+ "The detected quad is not plausibly a document in perspective: %@"
```
