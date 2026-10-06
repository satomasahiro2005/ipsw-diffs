## ControlCenterUI

> `/System/Library/PrivateFrameworks/ControlCenterUI.framework/ControlCenterUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbb4ac` | `0xbb590` | **`+0xe4`** |
| `__AUTH_CONST.__const` | `0x4471` | `0x4511` | **`+0xa0`** |
| `__TEXT.__const` | `0x2c3a` | `0x2c7a` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0xf88` | `0xfc8` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xb538` | `0xb560` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x2c40` | `0x2c2e` | **`-0x12`** |
| `__AUTH_CONST.__auth_got` | `0x1368` | `0x1358` | **`-0x10`** |
| `__AUTH_CONST.__objc_const` | `0x111d0` | `0x111e0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xd30` | `0xd40` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x6948` | `0x6958` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x445b` | `0x446b` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2d60` | `0x2d68` | **`+0x8`** |

### Other Changes

```diff

-704.0.2.0.0
+704.2.2.0.0

-  Functions: 5048
-  Symbols:   5623
+  Functions: 5057
+  Symbols:   5625
Symbols:
+ -[CCUICellularDataModuleViewController _rebuildContentMenuActions]
+ -[CCUISensorAttributionCompactControl updateContentIfDisplayedAttributionsAreStale]
+ ___113-[CCUICellularDataModuleViewController profileConnectionDidReceiveEffectiveSettingsChangedNotification:userInfo:]_block_invoke
- _symbolic So11NSHashTableC
CStrings:
+ "[Cellular Data Module] Cellular Data state updated to %{public}@ [ capable: %d enabled: %d airplaneMode: %d multipleSubscriptionsAvailable: %d showsMenu: %d subtitle: %{private}@ ]"
- "[Cellular Data Module] Cellular Data state updated to %{public}@ [ capable: %d enabled: %d airplaneMode: %d multipleSubscriptionsAvailable: %d subtitle: %{private}@ ]"
```
