## com.apple.iokit.IOMobileGraphicsFamily-DCP

> `com.apple.iokit.IOMobileGraphicsFamily-DCP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x29834` | `0x298c4` | **`+0x90`** |
| `__TEXT.__cstring` | `0x57af` | `0x57f6` | **`+0x47`** |

### Other Changes

```diff

-700.50.80.0.0
+700.50.85.0.0

-  CStrings:  471
+  CStrings:  472
Functions:
~ __ZN21IOMobileFramebufferAP21swap_submit_with_tagsEP12IOMFBSwapRecP12IOUserClientjPj : 4572 -> 4716
CStrings:
+ "SwapIdleBuffer received with no idle caching surface; dropping swap %u"
```
