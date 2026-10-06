## ScreenTime

> `/System/Library/Frameworks/ScreenTime.framework/ScreenTime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x471c` | `0x54ac` | **`+0xd90`** |
| `__TEXT.__oslogstring` | `0x4a6` | `0x588` | **`+0xe2`** |
| `__AUTH_CONST.__objc_const` | `0xe80` | `0xf40` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x71c` | `0x7ac` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x5c0` | `0x630` | **`+0x70`** |
| `__TEXT.__cstring` | `0x2f3` | `0x35d` | **`+0x6a`** |
| `__TEXT.__gcc_except_tab` | `0xa8` | `0xf0` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x1e0` | `0x220` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x240` | `0x270` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x150` | `0x168` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x54` | `0x64` | **`+0x10`** |
| `__TEXT.__const` | `0x78` | `0x80` | **`+0x8`** |

### Other Changes

```diff

-640.0.100.0.0
+645.1.100.0.0

-  Functions: 165
-  Symbols:   391
-  CStrings:  46
+  Functions: 185
+  Symbols:   413
+  CStrings:  52
Symbols:
+ -[STScreenTimeConfigurationObserver _effectiveEnforcesChildRestrictions]
+ -[STScreenTimeConfigurationObserver _stScreenTimeConfigurationObserverCommonInitWithUpdateQueue:webBrowserSettingsObserver:]
+ -[STScreenTimeConfigurationObserver hasReceivedLegacyConfiguration]
+ -[STScreenTimeConfigurationObserver initWithUpdateQueue:webBrowserSettingsObserver:]
+ -[STScreenTimeConfigurationObserver legacyEnforcesChildRestrictions]
+ -[STScreenTimeConfigurationObserver observeValueForKeyPath:ofObject:change:context:]
+ -[STScreenTimeConfigurationObserver setHasReceivedLegacyConfiguration:]
+ -[STScreenTimeConfigurationObserver setLegacyEnforcesChildRestrictions:]
+ -[STScreenTimeConfigurationObserver webBrowserSettingsObserver]
+ -[STWebHistory dealloc]
+ -[STWebHistory initWithBundleIdentifier:profileIdentifier:screenTimeWebBrowserHistory:]
+ -[STWebHistory initWithBundleIdentifier:profileIdentifier:screenTimeWebBrowserHistory:error:]
+ -[STWebHistory screenTimeWebBrowserHistory]
+ GCC_except_table16
+ GCC_except_table19
+ _OBJC_CLASS_$_STScreenTimeWebBrowserHistory
+ _OBJC_CLASS_$_STScreenTimeWebBrowserSettingsObserver
+ _OBJC_IVAR_$_STScreenTimeConfigurationObserver._hasReceivedLegacyConfiguration
+ _OBJC_IVAR_$_STScreenTimeConfigurationObserver._legacyEnforcesChildRestrictions
+ _OBJC_IVAR_$_STScreenTimeConfigurationObserver._webBrowserSettingsObserver
+ _OBJC_IVAR_$_STWebHistory._screenTimeWebBrowserHistory
+ ___53-[STWebHistory fetchAllHistoryWithCompletionHandler:]_block_invoke_3
+ ___61-[STWebHistory fetchHistoryDuringInterval:completionHandler:]_block_invoke_3
+ _objc_release_x27
- -[STScreenTimeConfigurationObserver _updateWithConfiguration:]
- GCC_except_table14
CStrings:
+ "Failed to delete all web history with ScreenTimeSettings: %{public}@"
+ "Failed to delete history during %{private}@ with ScreenTimeSettings: %{public}@"
+ "Failed to delete history for %{private}@ with ScreenTimeSettings: %{public}@"
+ "KVOContextSTScreenTimeConfigurationObserver"
+ "webBrowserSettings.hasMigrated"
+ "webBrowserSettings.hasPasscode"
```
