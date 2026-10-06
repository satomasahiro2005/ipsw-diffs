## NewsUI

> `/System/Library/PrivateFrameworks/NewsUI.framework/NewsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35b04` | `0x35958` | **`-0x1ac`** |
| `__TEXT.__cstring` | `0x2218` | `0x2178` | **`-0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x1300` | `0x1280` | **`-0x80`** |
| `__TEXT.__objc_methlist` | `0x672c` | `0x6714` | **`-0x18`** |
| `__DATA_CONST.__const` | `0x1940` | `0x1930` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3870` | `0x3860` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x734` | `0x72c` | **`-0x8`** |

### Other Changes

```diff

-5934.3.0.0.0
+5960.0.0.0.0

-  Functions: 1712
-  Symbols:   4132
-  CStrings:  369
+  Functions: 1709
+  Symbols:   4126
+  CStrings:  365
Symbols:
+ GCC_except_table69
- -[NUArticleViewController nowPlayingDidDisappear:]
- -[NUArticleViewController nowPlayingWillDisappear:]
- GCC_except_table19
- GCC_except_table72
- _NUNowPlayingViewControllerDidDisappearNotification
- _NUNowPlayingViewControllerWillDisappearNotification
- ___286-[NUArticleViewController initWithArticleDataProvider:scrollViewController:appStateMonitor:keyCommandManager:loadingListeners:headerBlueprintProvider:debugSettingsProvider:videoPlayerViewControllerManager:articleScrollPositionManager:chromeControl:spotlightManager:liveCoverageManager:]_block_invoke_6
CStrings:
- "NUNowPlayingViewControllerDidDisappearNotification"
- "NUNowPlayingViewControllerWillDisappearNotification"
- "nowPlayingDidDisappearEvent"
- "nowPlayingWillDisappearEvent"
```
