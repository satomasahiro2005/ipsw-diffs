## WebContentRestrictions

> `/System/Library/PrivateFrameworks/WebContentRestrictions.framework/WebContentRestrictions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1098c` | `0x10910` | **`-0x7c`** |
| `__TEXT.__const` | `0x5b0` | `0x5c0` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x7f3` | `0x803` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xae0` | `0xad8` | **`-0x8`** |

### Other Changes

```diff

-73.0.0.0.2
+75.0.0.0.0
Symbols:
+ +[WCRBrowserEngineClient _askToBrowsePopoverSourceRectForBounds:safeAreaInsets:]
- +[WCRBrowserEngineClient _askToBrowsePopoverSourceRectForBounds:safeAreaInsets:isPad:]
Functions:
~ +[WCRBrowserEngineClient _askToBrowsePopoverSourceRectForBounds:safeAreaInsets:isPad:] -> +[WCRBrowserEngineClient _askToBrowsePopoverSourceRectForBounds:safeAreaInsets:] : 176 -> 212
~ ___113-[WCRBrowserEngineClient _presentAskToBrowseMenuForURL:state:presentingView:presentingViewController:completion:]_block_invoke : 1012 -> 940
~ -[WCRPopoverPresentationControllerDelegate popoverPresentationController:willRepositionPopoverToRect:inView:] : 236 -> 148
CStrings:
+ "overridePolicy from DC unrecognized: %{public}s"
+ "overridePolicy from DC: %{public}s"
- "overridePolicy from DC unrecognized: %s"
- "overridePolicy from DC: %s"
```
