## ScreenTimeAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/ScreenTimeAppIntentsExtension.appex/ScreenTimeAppIntentsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10a1c` | `0x121f4` | **`+0x17d8`** |
| `__DATA.__bss` | `0x2a50` | `0x2e60` | **`+0x410`** |
| `__TEXT.__cstring` | `0x1869` | `0x1c39` | **`+0x3d0`** |
| `__TEXT.__const` | `0x1bf8` | `0x1ec8` | **`+0x2d0`** |
| `__DATA_CONST.__const` | `0x7e8` | `0x908` | **`+0x120`** |
| `__TEXT.__eh_frame` | `0x4c8` | `0x5d8` | **`+0x110`** |
| `__DATA_CONST.__auth_ptr` | `0x668` | `0x760` | **`+0xf8`** |
| `__TEXT.__swift5_reflstr` | `0x423` | `0x513` | **`+0xf0`** |
| `__DATA.__data` | `0x7e8` | `0x8b8` | **`+0xd0`** |
| `__TEXT.__auth_stubs` | `0xe70` | `0xf40` | **`+0xd0`** |
| `__TEXT.__swift5_fieldmd` | `0x254` | `0x308` | **`+0xb4`** |
| `__TEXT.__unwind_info` | `0x620` | `0x6c0` | **`+0xa0`** |
| `__TEXT.__swift5_assocty` | `0x290` | `0x300` | **`+0x70`** |
| `__DATA_CONST.__auth_got` | `0x740` | `0x7a8` | **`+0x68`** |
| `__TEXT.__constg_swiftt` | `0x348` | `0x3b0` | **`+0x68`** |
| `__TEXT.__swift5_typeref` | `0xa4d` | `0xab1` | **`+0x64`** |
| `__DATA_CONST.__got` | `0x1f0` | `0x218` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `0x2c` | `0x54` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x150` | `0x170` | **`+0x20`** |
| `__DATA.__common` | `0x98` | `0x80` | **`-0x18`** |
| `__TEXT.__swift_as_cont` | `0x30` | `0x44` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x28` | `0x3c` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x3c` | `0x48` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-645.1.100.0.0
+649.0.0.0.0

-  Functions: 486
+  Functions: 538

-  CStrings:  124
+  CStrings:  141
Symbols:
+ _swift_release_x24
- __swiftEmptyDictionarySingleton
CStrings:
+ "APPS_AND_WEBSITES"
+ "App & website activity"
+ "COMMUNICATION_LIMITS"
+ "COMMUNICATION_SAFETY"
+ "CONTENT_AND_PRIVACY"
+ "Description text for the Device Usage control"
+ "Description text for the control that opens the Apps & Websites pane"
+ "Description text for the control that opens the Manage Screen Time pane"
+ "Description text for the control that opens the Schedule pane"
+ "Description text for the control that opens the Time Allowances pane"
+ "Manage Screen Time"
+ "SCREEN_TIME_SUMMARY"
+ "This is the control on the Screen Time settings pane that shows app and website activity for your device."
+ "This is the control that links to the Apps & Websites pane on the Screen Time settings pane. This pane is where you can set limits and restrictions for apps and websites."
+ "This is the control that links to the Manage Screen Time pane on the Screen Time settings pane. This pane is where you can change your Screen Time passcode or turn Screen Time off."
+ "This is the control that links to the Schedule pane on the Screen Time settings pane. This pane helps you schedule time away from the screen."
+ "This is the control that links to the Time Allowances pane on the Screen Time settings pane. This pane is where you can set how much time can be spent in categories of apps and websites."
+ "Time away from the screen"
+ "Turn off Screen Time"
+ "Website restrictions"
+ "appsAndWebsites"
+ "deviceUsage"
+ "manageScreenTime"
+ "schedule"
+ "timeAllowances"
- "settings-navigation://com.apple.Settings.ScreenTime/ALWAYS_ALLOWED"
- "settings-navigation://com.apple.Settings.ScreenTime/APP_LIMITS"
- "settings-navigation://com.apple.Settings.ScreenTime/COMMUNICATION_LIMITS"
- "settings-navigation://com.apple.Settings.ScreenTime/COMMUNICATION_SAFETY"
- "settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY"
- "settings-navigation://com.apple.Settings.ScreenTime/DOWNTIME"
- "settings-navigation://com.apple.Settings.ScreenTime/EYE_DISTANCE"
- "settings-navigation://com.apple.Settings.ScreenTime/SCREEN_TIME_SUMMARY"
```
