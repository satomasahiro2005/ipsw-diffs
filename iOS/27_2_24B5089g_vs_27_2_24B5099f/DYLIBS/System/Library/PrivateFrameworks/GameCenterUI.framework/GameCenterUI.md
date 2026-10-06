## GameCenterUI

> `/System/Library/PrivateFrameworks/GameCenterUI.framework/GameCenterUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4cc898` | `0x4ccc68` | **`+0x3d0`** |
| `__TEXT.__oslogstring` | `0x93c7` | `0x9537` | **`+0x170`** |
| `__DATA_CONST.__objc_selrefs` | `0xdf58` | `0xdf88` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x1d1f4` | `0x1d224` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x9c64` | `0x9c8c` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x135f0` | `0x13608` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x553a0` | `0x553b0` | **`+0x10`** |
| `__DATA.__bss` | `0x1f668` | `0x1f658` | **`-0x10`** |
| `__DATA.__data` | `0xfb70` | `0xfb60` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x7d0` | `0x7e0` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1a3c` | `0x1a4c` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2e38` | `0x2e30` | **`-0x8`** |

### Other Changes

```diff

-821.1.8.0.0
+821.1.16.0.0

-  Functions: 33748
-  Symbols:   20304
-  CStrings:  3252
+  Functions: 33752
+  Symbols:   20307
+  CStrings:  3255
Symbols:
+ -[GKDashboardMultiplayerPickerViewController updateAddRecipientButtonVisibility:]
+ -[GKLeaderboardScoreDataSource hasMoreEntriesToLoad]
+ -[GKMatchmakerViewController _finishWithMatchAfterPlayerResolution]
+ -[GKMatchmakerViewController setWaitingForPlayerResolution:]
+ -[GKMatchmakerViewController waitingForPlayerResolution]
+ GCC_except_table100
+ GCC_except_table55
+ GCC_except_table75
+ GCC_except_table97
+ _OBJC_IVAR_$_GKMatchmakerViewController._waitingForPlayerResolution
+ ___45-[GKMatchmakerViewController finishWithMatch]_block_invoke
- -[GKDashboardMultiplayerPickerViewController setExcludesContacts:]
- GCC_except_table47
- GCC_except_table48
- GCC_except_table60
- GCC_except_table74
- GCC_except_table95
- GCC_except_table98
- _OBJC_IVAR_$_GKDashboardMultiplayerPickerViewController._excludesContacts
CStrings:
+ "Not forming contact from picked contact, since contacts are excluded. GKPreferences.shared.multiplayerAllowedPlayerType is set to: %@, pickerOrigin: %@"
+ "Not presenting contact picker, since contacts are excluded. GKPreferences.shared.multiplayerAllowedPlayerType is set to: %@, pickerOrigin: %@"
+ "finishWithMatch: still waiting for player resolution, ignoring repeat call"
```
