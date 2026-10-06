## TemplateKit

> `/System/Library/PrivateFrameworks/TemplateKit.framework/TemplateKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43818` | `0x4387c` | **`+0x64`** |
| `__TEXT.__objc_methlist` | `0x4e88` | `0x4e98` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1180` | `0x1188` | **`+0x8`** |

### Other Changes

```diff

-685.1.3.0.0
+685.1.8.200.0

-  Functions: 1875
-  Symbols:   3096
+  Functions: 1877
+  Symbols:   3098
Symbols:
+ -[TLKTextAreaView usesDefaultLayoutMargins]
+ _TLKImageHasAlphaChannel
Functions:
+ -[TLKTextAreaView usesDefaultLayoutMargins]
~ +[TLKImageView imageIsProbablyOpaque:tlkImage:] : 144 -> 168
+ _TLKImageHasAlphaChannel
```
