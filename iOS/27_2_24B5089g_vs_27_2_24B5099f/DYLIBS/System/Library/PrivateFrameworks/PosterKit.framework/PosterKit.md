## PosterKit

> `/System/Library/PrivateFrameworks/PosterKit.framework/PosterKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x187e04` | `0x1884cc` | **`+0x6c8`** |
| `__TEXT.__objc_methlist` | `0x1a374` | `0x1a41c` | **`+0xa8`** |
| `__DATA_CONST.__objc_selrefs` | `0xc5f0` | `0xc650` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x55950` | `0x559a0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x38e8` | `0x3910` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x6338` | `0x6350` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1be8` | `0x1bf0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1adc` | `0x1ae4` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1ea0` | `0x1e98` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-355.2.6.200.0
+355.2.10.100.0

-  Functions: 10607
-  Symbols:   15707
+  Functions: 10621
+  Symbols:   15726
Symbols:
+ +[PRRenderingServiceSceneComponent pr_assertionTestComponent]
+ -[PRComplicationsSnapshotSceneSpecification allowsHostedSoftwareKeyboard]
+ -[PRInlineComplicationSnapshotSceneSpecification allowsHostedSoftwareKeyboard]
+ -[PRRenderingServiceSceneComponent pr_deviceMotionEventGenerationAssertion]
+ -[PRRenderingServiceSceneComponent pr_displayStateProgressEventGenerationAssertion]
+ -[PRRenderingServiceSceneComponent pr_eventGenerationAssertions]
+ -[PRRenderingServiceSceneComponent pr_setTestActiveRenderingServiceConnection:]
+ -[PRSidebarComplicationsSnapshotSceneSpecification allowsHostedSoftwareKeyboard]
+ -[PRWidgetGridViewController _clearWidgetHighlighting]
+ -[PRWidgetGridViewController _highlightWidgetAtPoint:]
+ -[PRWidgetGridViewController handleWidgetSelectionGesture:]
+ -[PRWidgetGridViewController viewDidDisappear:]
+ -[PRWidgetIconViewController isHighlighted]
+ -[PRWidgetIconViewController setHighlighted:]
+ _OBJC_IVAR_$_PRWidgetIconViewController._dimmingView
+ _OBJC_IVAR_$_PRWidgetIconViewController._highlighted
+ _PUIPosterSceneSpecificationForSceneRole
+ __OBJC_$_CLASS_METHODS_PRRenderingServiceSceneComponent
+ ___block_descriptor_64_e8_32s40s48s56s_e31_v16?0"PUISceneConfiguration"8ls32l8s40l8s48l8s56l8
CStrings:
+ "\xb1"
- "\xa1"
```
