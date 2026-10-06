## EventKitUI

> `/System/Library/Frameworks/EventKitUI.framework/EventKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f4be8` | `0x1f4824` | **`-0x3c4`** |
| `__TEXT.__const` | `0x2df4` | `0x2e54` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x3fe0` | `0x401c` | **`+0x3c`** |
| `__TEXT.__objc_methlist` | `0x1ffdc` | `0x20014` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0xfa88` | `0xfab0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0xb4a0` | `0xb480` | **`-0x20`** |
| `__TEXT.__cstring` | `0xd154` | `0xd134` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x31510` | `0x31528` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x7d58` | `0x7d70` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x1c7c` | `0x1c84` | **`+0x8`** |

### Other Changes

```diff

-1560.0.0.0.0
+1563.0.0.0.0

-  Functions: 12301
-  Symbols:   18416
-  CStrings:  2362
+  Functions: 12305
+  Symbols:   18420
+  CStrings:  2361
Symbols:
+ -[EKEventEditViewControllerModernImpl requestContactViewPresentationWithParticipant:]
+ -[EKEventViewControllerDefaultImpl _prefersHideNavigationEditButtonFromDelegate]
+ -[UITraitCollection(EventKitUI) ekui_prefersFormSheetPresentation]
+ GCC_except_table123
+ GCC_except_table126
+ GCC_except_table132
+ _CalSolariumCompactChromeEnabled
+ ___85-[EKEventEditViewControllerModernImpl requestContactViewPresentationWithParticipant:]_block_invoke
- -[EKDayAllDayView lockUseOfSmallTextToState:]
- GCC_except_table124
- GCC_except_table130
- _swift_retain_x26
CStrings:
- "How should this change be applied?"
```
