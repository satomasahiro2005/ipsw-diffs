## OnBoardingKit

> `/System/Library/PrivateFrameworks/OnBoardingKit.framework/OnBoardingKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x47a54` | `0x47dac` | **`+0x358`** |
| `__AUTH.__objc_data` | `0xff0` | `0xfa0` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0xc30` | `0xc80` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x4c8` | `0x4e8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x60ec` | `0x610c` | **`+0x20`** |
| `__TEXT.__const` | `0x4f4` | `0x504` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3ef0` | `0x3ef8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xfe0` | `0xfe8` | **`+0x8`** |

### Other Changes

```diff

-3977.0.17.0.0
+3977.0.18.0.0

-  Functions: 1859
-  Symbols:   3422
+  Functions: 1861
+  Symbols:   3425
Symbols:
+ -[OBTableWelcomeController viewSafeAreaInsetsDidChange]
+ -[OBWelcomeController viewSafeAreaInsetsDidChange]
+ _OBBaseWelcomeControllerCompactViewButtonMaxWidth
Functions:
~ -[OBSetupAssistantFinishedController viewDidLoad] : 2476 -> 2852
~ -[OBTableWelcomeController _applyContentInsetAdjustmentBehaviorToTableView] : 140 -> 272
~ -[OBTableWelcomeController viewWillAppear:] : 100 -> 172
+ -[OBTableWelcomeController viewSafeAreaInsetsDidChange]
~ -[OBStableContentSizeScrollView setContentSize:] : 204 -> 228
+ -[OBWelcomeController viewSafeAreaInsetsDidChange]
~ -[OBWelcomeController _contentViewHeight] : 792 -> 780
~ -[OBWelcomeController _headerTopOffset] : 500 -> 480
~ -[OBWelcomeController _layoutButtonTray] : 2440 -> 2528
```
