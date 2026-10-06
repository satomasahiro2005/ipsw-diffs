## NewsUI

> `/System/Library/PrivateFrameworks/NewsUI.framework/NewsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35380` | `0x35a80` | **`+0x700`** |
| `__TEXT.__oslogstring` | `0xfe2` | `0x11f9` | **`+0x217`** |
| `__AUTH_CONST.__objc_const` | `0xe4d0` | `0xe678` | **`+0x1a8`** |
| `__TEXT.__objc_methlist` | `0x6644` | `0x671c` | **`+0xd8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3810` | `0x3870` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x1918` | `0x1940` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x604` | `0x620` | **`+0x1c`** |
| `__TEXT.__unwind_info` | `0x1128` | `0x1140` | **`+0x18`** |
| `__TEXT.__const` | `0x260` | `0x268` | **`+0x8`** |

### Other Changes

```diff

-5916.1.0.0.0
+5920.0.0.0.0

-  Functions: 1693
-  Symbols:   4103
-  CStrings:  359
+  Functions: 1712
+  Symbols:   4132
+  CStrings:  368
Symbols:
+ -[NUArticleHostViewController checkForLiveCoverageUpdatesWithCompletion:]
+ -[NUArticleHostViewController offline]
+ -[NUArticleHostViewController setOffline:]
+ -[NUArticleViewController checkForLiveCoverageUpdatesWithCompletion:]
+ -[NUArticleViewController offline]
+ -[NUArticleViewController setOffline:]
+ -[NULiveCoverageManager checkForUpdatesWithCompletion:]
+ -[NULiveCoverageManager evaluatePollingState]
+ -[NULiveCoverageManager fetchAndProcessContextWithCompletion:]
+ -[NULiveCoverageManager isManuallyChecking]
+ -[NULiveCoverageManager lowDataMode]
+ -[NULiveCoverageManager lowPowerMode]
+ -[NULiveCoverageManager networkReachabilityDidChange:]
+ -[NULiveCoverageManager offline]
+ -[NULiveCoverageManager powerStateDidChange:]
+ -[NULiveCoverageManager setIsManuallyChecking:]
+ -[NULiveCoverageManager setLowDataMode:]
+ -[NULiveCoverageManager setLowPowerMode:]
+ -[NULiveCoverageManager setOffline:]
+ -[NULiveCoverageManager setViewVisible:]
+ -[NULiveCoverageManager shouldBePolling]
+ -[NULiveCoverageManager viewVisible]
+ GCC_except_table17
+ GCC_except_table22
+ GCC_except_table25
+ GCC_except_table37
+ GCC_except_table38
+ _OBJC_IVAR_$_NUArticleHostViewController._offline
+ _OBJC_IVAR_$_NUArticleViewController._offline
+ _OBJC_IVAR_$_NULiveCoverageManager._isManuallyChecking
+ _OBJC_IVAR_$_NULiveCoverageManager._lowDataMode
+ _OBJC_IVAR_$_NULiveCoverageManager._lowPowerMode
+ _OBJC_IVAR_$_NULiveCoverageManager._offline
+ _OBJC_IVAR_$_NULiveCoverageManager._viewVisible
+ __OBJC_CLASS_PROTOCOLS_$_NULiveCoverageManager
+ ___62-[NULiveCoverageManager fetchAndProcessContextWithCompletion:]_block_invoke
+ ___block_descriptor_48_e8_32bs40w_e55_v32?0"SXContext"8"<NUFontRegistrator>"16"NSError"24lw40l8s32l8
- -[NULiveCoverageManager shouldEnablePolling]
- -[NULiveCoverageManager startPolling]
- -[NULiveCoverageManager stopPolling]
- GCC_except_table15
- GCC_except_table23
- GCC_except_table35
- GCC_except_table36
- ___44-[NULiveCoverageManager performPollingCheck]_block_invoke
CStrings:
+ "Live coverage check failed: %{public}@"
+ "Live coverage check returned nil context"
+ "Live coverage lowDataMode changed to %{BOOL}d"
+ "Live coverage lowPowerMode changed to %{BOOL}d"
+ "Live coverage offline changed to %{BOOL}d"
+ "Live coverage polling disabled: device offline"
+ "Live coverage polling disabled: view not visible"
+ "Live coverage polling started, conditions met, interval=%f"
+ "Live coverage polling stopped, conditions no longer met"
+ "Live coverage viewVisible changed to %{BOOL}d"
+ "Manual check for updates skipped: already in progress"
+ "Manual check for updates started"
+ "Manual check: rescheduling polling timer to avoid race"
+ "NUArticleHostViewController: content type is not NUArticleViewController, skipping manual check"
+ "NUArticleHostViewController: forwarding manual check to article view controller"
+ "NUArticleViewController: forwarding manual check to live coverage manager"
+ "Skipping polling check: manual check in progress"
- "Live coverage polling already active, skipping start"
- "Live coverage polling check failed: %{public}@"
- "Live coverage polling check received new context"
- "Live coverage polling check returned nil context"
- "Live coverage polling conditions no longer met, stopping"
- "Live coverage polling not enabled, skipping start"
- "Live coverage polling started, interval=%f"
- "Live coverage polling stopped"
```
