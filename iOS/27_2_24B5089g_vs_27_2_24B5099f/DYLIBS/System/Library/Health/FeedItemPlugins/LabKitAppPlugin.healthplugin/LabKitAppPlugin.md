## LabKitAppPlugin

> `/System/Library/Health/FeedItemPlugins/LabKitAppPlugin.healthplugin/LabKitAppPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdff4` | `0x8a9c` | **`-0x5558`** |
| `__DATA.__bss` | `0xc00` | `0x600` | **`-0x600`** |
| `__TEXT.__const` | `0x890` | `0x502` | **`-0x38e`** |
| `__AUTH_CONST.__auth_got` | `0x840` | `0x588` | **`-0x2b8`** |
| `__AUTH.__data` | `0x338` | `0x158` | **`-0x1e0`** |
| `__AUTH_CONST.__objc_const` | `0x460` | `0x290` | **`-0x1d0`** |
| `__DATA.__data` | `0x348` | `0x1b0` | **`-0x198`** |
| `__TEXT.__constg_swiftt` | `0x2b4` | `0x12c` | **`-0x188`** |
| `__AUTH.__objc_data` | `0x230` | `0xb0` | **`-0x180`** |
| `__TEXT.__unwind_info` | `0x3a8` | `0x270` | **`-0x138`** |
| `__TEXT.__cstring` | `0xe4` | `0x1` | **`-0xe3`** |
| `__AUTH_CONST.__const` | `0x3b0` | `0x2d0` | **`-0xe0`** |
| `__TEXT.__oslogstring` | `0x3ee` | `0x30e` | **`-0xe0`** |
| `__TEXT.__swift5_typeref` | `0x2af` | `0x1ef` | **`-0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x14c` | `0xb0` | **`-0x9c`** |
| `__DATA_DIRTY.__bss` | `0x100` | `0x80` | **`-0x80`** |
| `__TEXT.__eh_frame` | `0x490` | `0x428` | **`-0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b0` | `0x158` | **`-0x58`** |
| `__DATA.__common` | `0x48` | `—` | **`-0x48`** |
| `__TEXT.__swift5_capture` | `0x184` | `0x13c` | **`-0x48`** |
| `__TEXT.__swift5_proto` | `0x68` | `0x34` | **`-0x34`** |
| `__TEXT.__swift5_reflstr` | `0xcb` | `0x9b` | **`-0x30`** |
| `__TEXT.__swift5_types` | `0x2c` | `0x14` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x18` | **`-0x10`** |
| `__DATA.__objc_stublist` | `0x8` | `—` | **`-0x8`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

-  Functions: 271
-  Symbols:   151
-  CStrings:  22
+  Functions: 167
+  Symbols:   127
+  CStrings:  13
Symbols:
+ _objc_retain_x26
+ _swift_release_x23
- _CFPreferencesGetAppBooleanValue
- _HKSensitiveLogItem
- _NSUserDefaultsDidChangeNotification
- _OBJC_CLASS_$_NSNotificationCenter
- _OBJC_CLASS_$_NSUserDefaults
- _OBJC_CLASS_$_UIColor
- _OBJC_CLASS_$_UIImage
- _OBJC_CLASS_$_UIImageSymbolConfiguration
- _OBJC_METACLASS_$__TtC18HealthExperienceUI24BrowseTileViewController
- _kHKHealthAppDaemonBundleIdentifier
- _kHKInternalSettingsShowLabKitInBrowse
- _objc_retain_x25
- _swift_arrayInitWithTakeBackToFront
- _swift_arrayInitWithTakeFrontToBack
- _swift_getErrorValue
- _swift_getMetatypeMetadata
- _swift_initClassMetadata2
- _swift_release_x22
- _swift_release_x26
- _swift_retain
- _swift_retain_x24
- _swift_setDeallocating
- _swift_task_isCurrentExecutor
- _swift_task_reportUnexpectedExecutor
- _swift_unexpectedError
- _swift_updateClassMetadata2
CStrings:
+ "[%s] ignoring lab deep link: the presenter is still presenting"
- "LabKitAppPlugin/LabKitAppPluginGenerator.swift"
- "LabKitAppPlugin/LabKitAppPluginViewController.swift"
- "LabKitBrowseCategoryFeedItem_"
- "LabKitSidebarFeedItem_"
- "[%{public}s] Onboarding generation has started for onboarding completion state %s"
- "[%{public}s] Submitting these changes: %s"
- "[%{public}s] Unable to compute desired difference for commit: %s"
- "[%{public}s]: returning pipeline for sourceProfile %{public}s"
- "heart.circle.fill"
- "name configuration "
```
