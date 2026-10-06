## RTSCV1

> `/System/Library/VideoProcessors/RTSCV1.bundle/RTSCV1`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15ca8` | `0x15fd4` | **`+0x32c`** |
| `__TEXT.__objc_methname` | `0x30fd` | `0x314b` | **`+0x4e`** |
| `__TEXT.__objc_stubs` | `0x16e0` | `0x1700` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x1588` | `0x159b` | **`+0x13`** |
| `__TEXT.__objc_methlist` | `0xf34` | `0xf44` | **`+0x10`** |
| `__TEXT.__cstring` | `0x1cd5` | `0x1ce4` | **`+0xf`** |
| `__DATA.__objc_selrefs` | `0x878` | `0x880` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4b8` | `0x4c0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-758.0.0.122.2
+761.0.0.0.3

-  Functions: 350
-  Symbols:   991
-  CStrings:  949
+  Functions: 351
+  Symbols:   993
+  CStrings:  951
Symbols:
+ -[RTSCFaceReframingV1 _estimateMinShift:maxShift:forViewPortBox:withinBoundingRect:boundingCircle:]
+ -[RTSCFaceReframingV1 _preClampOffset:ofViewPort:toMinShift:maxShift:]
+ -[RTSCFaceReframingV1 _updateOffsetOfViewPortBox:withinBoundingRect:boundingCircle:]
+ _objc_msgSend$_estimateMinShift:maxShift:forViewPortBox:withinBoundingRect:boundingCircle:
+ _objc_msgSend$_preClampOffset:ofViewPort:toMinShift:maxShift:
+ _objc_msgSend$_updateOffsetOfViewPortBox:withinBoundingRect:boundingCircle:
- -[RTSCFaceReframingV1 _estimateMinShift:maxShift:forViewPortBox:withinBoundingRect:]
- -[RTSCFaceReframingV1 _updateOffsetOfViewPortBox:withinBoundingRect:]
- _objc_msgSend$_estimateMinShift:maxShift:forViewPortBox:withinBoundingRect:
- _objc_msgSend$_updateOffsetOfViewPortBox:withinBoundingRect:
CStrings:
+ "-[RTSCFaceReframingV1 _updateOffsetOfViewPortBox:withinBoundingRect:boundingCircle:]"
+ "56@0:816244048"
+ "80@0:816{CGRect={CGPoint=dd}{CGSize=dd}}3264"
+ "_estimateMinShift:maxShift:forViewPortBox:withinBoundingRect:boundingCircle:"
+ "_preClampOffset:ofViewPort:toMinShift:maxShift:"
+ "_updateOffsetOfViewPortBox:withinBoundingRect:boundingCircle:"
+ "v96@0:8^16^2432{CGRect={CGPoint=dd}{CGSize=dd}}4880"
- "-[RTSCFaceReframingV1 _updateOffsetOfViewPortBox:withinBoundingRect:]"
- "64@0:816{CGRect={CGPoint=dd}{CGSize=dd}}32"
- "_estimateMinShift:maxShift:forViewPortBox:withinBoundingRect:"
- "_updateOffsetOfViewPortBox:withinBoundingRect:"
- "v80@0:8^16^2432{CGRect={CGPoint=dd}{CGSize=dd}}48"
```
