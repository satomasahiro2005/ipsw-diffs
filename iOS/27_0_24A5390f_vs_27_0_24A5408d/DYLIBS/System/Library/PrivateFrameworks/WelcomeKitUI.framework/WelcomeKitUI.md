## WelcomeKitUI

> `/System/Library/PrivateFrameworks/WelcomeKitUI.framework/WelcomeKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14324` | `0x14560` | **`+0x23c`** |
| `__TEXT.__cstring` | `0x4df0` | `0x4ec0` | **`+0xd0`** |
| `__AUTH_CONST.__cfstring` | `0x4c20` | `0x4ce0` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x1ac4` | `0x1ae4` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x600` | `0x608` | **`+0x8`** |

### Other Changes

```diff

-1426.0.0.0.0
+1428.0.3.0.0

-  Functions: 494
-  Symbols:   1204
-  CStrings:  643
+  Functions: 497
+  Symbols:   1208
+  CStrings:  649
Symbols:
+ -[WLCompletedViewController viewDidAppear:]
+ -[WLOnboardingViewController viewDidAppear:]
+ -[WLTransferringViewController viewDidAppear:]
+ GCC_except_table5
Functions:
~ -[WLCompletedViewController initWithWelcomeController:context:imported:] : 924 -> 960
~ -[WLCompletedViewController viewDidLoad] : 324 -> 356
+ -[WLCompletedViewController viewDidAppear:]
~ -[WLOnboardingViewController viewDidLoad] : 96 -> 128
+ -[WLOnboardingViewController viewDidAppear:]
~ -[WLTransferringViewController viewDidLoad] : 256 -> 288
+ -[WLTransferringViewController viewDidAppear:]
~ -[WLTransferringViewController setIsImporting:] : 220 -> 284
~ -[WLWelcomeController _pushViewController:andRemovePreviousTopmostViewControllerWithCompletion:] : 600 -> 660
CStrings:
+ "%@ creating Completed pane. title='%@', imported=%d"
+ "%@ pane switched to Importing. title='%@'"
+ "%@ showing pane %@ (replacing %@). migration_state=%ld"
+ "%@ viewDidAppear"
+ "%@ viewDidAppear. isImporting=%d"
+ "%@ viewDidLoad"
```
