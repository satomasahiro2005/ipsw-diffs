## ReplayKitModule

> `/System/Library/ControlCenter/Bundles/ReplayKitModule.bundle/ReplayKitModule`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbb48` | `0xbf6c` | **`+0x424`** |
| `__TEXT.__objc_stubs` | `0x1fc0` | `0x20e0` | **`+0x120`** |
| `__TEXT.__objc_methname` | `0x2fa9` | `0x307a` | **`+0xd1`** |
| `__DATA.__objc_selrefs` | `0xc60` | `0xca8` | **`+0x48`** |
| `__TEXT.__cstring` | `0x1f96` | `0x1fcf` | **`+0x39`** |
| `__TEXT.__oslogstring` | `0x1011` | `0x1049` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0xdb0` | `0xde0` | **`+0x30`** |
| `__DATA.__objc_const` | `0x1ed8` | `0x1ef8` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x540` | `0x530` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x350` | `0x360` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2b0` | `0x2a8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x168` | `0x170` | **`+0x8`** |
| `__TEXT.__const` | `0xb8` | `0xc0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xd0` | `0xd4` | **`+0x4`** |
| `__TEXT.__objc_methtype` | `0x965` | `0x967` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-740.57.1.0.0
+740.63.1.1.0

-  Functions: 240
-  Symbols:   154
-  CStrings:  816
+  Functions: 244
+  Symbols:   153
+  CStrings:  829
Symbols:
+ _CGRectIsEmpty
+ _objc_opt_isKindOfClass
- _CCUIIsPortrait
- _CCUIReferenceScreenBounds
- _CCUIScreenBounds
CStrings:
+ " [INFO] %{public}s:%d %p module no longer visible, tearing down stale ScreenCaptureKit picker"
+ " [INFO] %{public}s:%d %p userVisibilityStatus %ld -> %ld isSCKPicker=%i"
+ " [INFO] %{public}s:%d Dismissing ScreenCaptureKit picker"
+ " [INFO] %{public}s:%d End ScreenCaptureKit picker"
+ "-[RPControlCenterMenuModuleViewController dismissScreenCaptureKitPicker]"
+ "-[RPControlCenterMenuModuleViewController setUserVisibilityStatus:]"
+ "_geometryProvider"
+ "_referenceBounds"
+ "_userVisibilityStatus"
+ "_usesVerticallyStackedLayout"
+ "controlCenterOrientation"
+ "dismissScreenCaptureKitPicker"
+ "geometryProvider"
+ "maximumExpandedContentModuleHeight"
+ "pickerDidDismiss:forStreamInfo:isCancelled:"
+ "q"
+ "screen"
+ "supportsEdgeAlignedLayout"
+ "viewIfLoaded"
+ "windowScene"
- " [INFO] %{public}s:%d Cancel ScreenCaptureKit picker, will call dismissModule"
- " [INFO] %{public}s:%d End ScreenCaptureKit picker, will call dismissModule"
- " [INFO] %{public}s:%d ScreenCaptureKit picker cancelled by user"
- "-[RPControlCenterMenuModuleViewController cancelScreenCaptureKitPickerWithDismiss:]"
- "cancelScreenCaptureKitPickerWithDismiss:"
- "dismissModule"
- "pickerDidCancel:forStreamInfo:"
```
