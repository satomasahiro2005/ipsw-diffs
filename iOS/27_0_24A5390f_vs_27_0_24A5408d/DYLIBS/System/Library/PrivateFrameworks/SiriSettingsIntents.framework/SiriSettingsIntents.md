## SiriSettingsIntents

> `/System/Library/PrivateFrameworks/SiriSettingsIntents.framework/SiriSettingsIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x126224` | `0x12671c` | **`+0x4f8`** |
| `__TEXT.__eh_frame` | `0xd698` | `0xd768` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x1084f` | `0x1089f` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x5068` | `0x5030` | **`-0x38`** |
| `__DATA_DIRTY.__data` | `0x4520` | `0x4528` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x6b78` | `0x6b80` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xaa0` | `0xaa8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x92c` | `0x930` | **`+0x4`** |

### Other Changes

```diff

-3600.35.7.0.0
+3600.35.9.0.0

-  Functions: 7097
+  Functions: 7104

-  CStrings:  1314
+  CStrings:  1315
CStrings:
+ "settings-navigation://com.apple.Settings.Appearance"
+ "settings-navigation://com.apple.Settings.Focus/"
- "prefs:root=DO_NOT_DISTURB"
```
