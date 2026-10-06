## GameOverlayUI

> `/System/Library/CoreServices/GameOverlayUI.app/GameOverlayUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf5e60` | `0xf6fc0` | **`+0x1160`** |
| `__DATA_CONST.__const` | `0x5188` | `0x51b0` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x4e10` | `0x4e20` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x40b0` | `0x40a0` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x1b4c` | `0x1b5c` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2710` | `0x2718` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2c70` | `0x2c68` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3.1.12.0.0
+3.1.18.0.0

-  Functions: 3721
-  Symbols:   2319
+  Functions: 3725
+  Symbols:   2320
Symbols:
+ _$s12GameStoreKit10PageLayoutV10MarginSpecO7resolve2in26isVerticalSizeClassCompact23horizontalSafeAreaEdges17maxContainerWidthAC08ResolvedfG0V12CoreGraphics7CGFloatV_Sb7SwiftUI14HorizontalEdgeO3SetVAOtF
+ _$s12GameStoreKit13ArtworkLoaderC10cacheLimit12renderIntent10urlSession24windowResizeStateMonitorACSi_So014ASKImageRenderI0VAA0dE10URLSessionCAA06WindowmnO0CSgtcfC
+ _$s7SwiftUI10EdgeInsetsV12GameStoreKitE22nonZeroHorizontalEdgesAA0jC0O3SetVvg
- _$s12GameStoreKit10PageLayoutV10MarginSpecO7resolve2in26isVerticalSizeClassCompact21hasHorizontalSafeArea17maxContainerWidthAC08ResolvedfG0V12CoreGraphics7CGFloatV_S2bAOtF
- _$s12GameStoreKit13ArtworkLoaderC10cacheLimit12renderIntent10urlSessionACSi_So014ASKImageRenderI0VAA0dE10URLSessionCtcfC
```
