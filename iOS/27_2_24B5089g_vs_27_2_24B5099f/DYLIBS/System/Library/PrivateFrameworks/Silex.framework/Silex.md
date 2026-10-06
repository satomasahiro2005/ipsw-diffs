## Silex

> `/System/Library/PrivateFrameworks/Silex.framework/Silex`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x118eb4` | `0x1189b8` | **`-0x4fc`** |
| `__AUTH_CONST.__objc_const` | `0x51cc0` | `0x51b50` | **`-0x170`** |
| `__TEXT.__objc_methlist` | `0x1e70c` | `0x1e694` | **`-0x78`** |
| `__DATA.__data` | `0x9f58` | `0x9ef8` | **`-0x60`** |
| `__DATA_DIRTY.__objc_data` | `0xf1b8` | `0xf168` | **`-0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xb858` | `0xb838` | **`-0x20`** |
| `__DATA.__objc_ivar` | `0x1fb0` | `0x1fa0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x4f20` | `0x4f10` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x2590` | `0x2588` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1ce8` | `0x1ce0` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0xd30` | `0xd28` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1038` | `0x1030` | **`-0x8`** |
| `__TEXT.__cstring` | `0xa0c5` | `0xa0c7` | **`+0x2`** |

### Other Changes

```diff

-5962.0.0.0.0
+5969.0.0.0.0

-  Functions: 8575
-  Symbols:   20680
-  CStrings:  1846
+  Functions: 8564
+  Symbols:   20654
+  CStrings:  1847
Symbols:
+ -[SXAutoPlacementAdvertisingSettings hash]
+ -[SXAutoPlacementAdvertisingSettings isEqual:]
- -[SXFullscreenVideoPlaybackManager .cxx_destruct]
- -[SXFullscreenVideoPlaybackManager addCandidate:]
- -[SXFullscreenVideoPlaybackManager didLayoutForSize:]
- -[SXFullscreenVideoPlaybackManager didTransitionToSize:]
- -[SXFullscreenVideoPlaybackManager enterFullscreenIfNeeded]
- -[SXFullscreenVideoPlaybackManager init]
- -[SXFullscreenVideoPlaybackManager removeCandidate:]
- -[SXFullscreenVideoPlaybackManager willLayoutAndTransitionToSize:]
- -[SXScrollViewController fullscreenVideoPlaybackManager]
- -[SXVideoComponentView canEnterFullscreen]
- -[SXVideoComponentView enterFullscreen]
- -[SXVideoComponentView viewport:interfaceOrientationChangedFromOrientation:]
- -[SXVideoComponentView visibilityStateDidChangeFromState:]
- _OBJC_CLASS_$_SXFullscreenVideoPlaybackManager
- _OBJC_IVAR_$_SXFullscreenVideoPlaybackManager._candidates
- _OBJC_IVAR_$_SXFullscreenVideoPlaybackManager._layoutInProgress
- _OBJC_IVAR_$_SXFullscreenVideoPlaybackManager._transitionInProgress
- _OBJC_IVAR_$_SXScrollViewController._fullscreenVideoPlaybackManager
- _OBJC_METACLASS_$_SXFullscreenVideoPlaybackManager
- __OBJC_$_INSTANCE_METHODS_SXFullscreenVideoPlaybackManager
- __OBJC_$_INSTANCE_VARIABLES_SXFullscreenVideoPlaybackManager
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_SXFullscreenVideoPlaybackCandidate
- __OBJC_$_PROTOCOL_METHOD_TYPES_SXFullscreenVideoPlaybackCandidate
- __OBJC_$_PROTOCOL_REFS_SXFullscreenVideoPlaybackCandidate
- __OBJC_CLASS_RO_$_SXFullscreenVideoPlaybackManager
- __OBJC_LABEL_PROTOCOL_$_SXFullscreenVideoPlaybackCandidate
- __OBJC_METACLASS_RO_$_SXFullscreenVideoPlaybackManager
- __OBJC_PROTOCOL_$_SXFullscreenVideoPlaybackCandidate
CStrings:
+ "\x92"
```
