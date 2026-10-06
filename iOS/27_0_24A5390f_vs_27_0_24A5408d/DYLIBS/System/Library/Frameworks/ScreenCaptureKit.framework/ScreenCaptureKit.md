## ScreenCaptureKit

> `/System/Library/Frameworks/ScreenCaptureKit.framework/ScreenCaptureKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36c84` | `0x36c90` | **`+0xc`** |

### Other Changes

```diff

-740.57.1.0.0
+740.63.1.1.0
Symbols:
+ -[SCControlCenterManager pickerDidDismiss:forStreamInfo:isCancelled:]
- -[SCControlCenterManager pickerDidCancel:forStreamInfo:]
Functions:
~ -[SCControlCenterManager pickerDidCancel:forStreamInfo:] -> -[SCControlCenterManager pickerDidDismiss:forStreamInfo:isCancelled:] : 196 -> 208
```
