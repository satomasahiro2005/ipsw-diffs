## QuartzCore

> `/System/Library/Frameworks/QuartzCore.framework/QuartzCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4053a4` | `0x4053e0` | **`+0x3c`** |
| `__TEXT.__oslogstring` | `0x13a25` | `0x13a5f` | **`+0x3a`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1223.10.16.0.0
+1223.10.19.0.0

-  CStrings:  8651
+  CStrings:  8652
Functions:
~ __ZN2CA12WindowServer12IOMFBDisplay13finish_updateEPNS_6Render6UpdateEjy : 19948 -> 19872
~ __ZN2CA12WindowServer13IOMFBFlipBook5_exitENS0_23FlipBookStateTransitionE : 384 -> 388
~ __ZN2CA12WindowServer8FlipBook5_exitENS0_23FlipBookStateTransitionE : 236 -> 368
CStrings:
+ "24B5104s"
+ "FlipBook::_exit from suspended, skip cancel (swapped %zu)"
- "24B5098u"
```
