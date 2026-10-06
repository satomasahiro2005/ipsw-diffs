## WebContentRestrictionsUI

> `/Applications/WebContentRestrictionsUI.app/WebContentRestrictionsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x3aa` | `0x49a` | **`+0xf0`** |
| `__TEXT.__text` | `0x6948` | `0x69fc` | **`+0xb4`** |
| `__DATA_CONST.__cfstring` | `0x360` | `0x3e0` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0xdaf` | `0xe1a` | **`+0x6b`** |
| `__TEXT.__objc_methtype` | `0x364` | `0x384` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xfa0` | `0xfc0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x564` | `0x580` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x4e0` | `0x4f8` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x7a0` | `0x7b0` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x218` | `0x20c` | **`-0xc`** |
| `__DATA.__objc_const` | `0x960` | `0x968` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x3e0` | `0x3e8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-63.0.0.0.0
+64.0.0.0.0

-  Functions: 160
-  Symbols:   207
-  CStrings:  271
+  Functions: 161
+  Symbols:   208
+  CStrings:  280
Symbols:
+ _NSSelectorFromString
CStrings:
+ "LSApplicationWorkspace"
+ "defaultWorkspace"
+ "openScreenTimeSettingsUseLegacyURL:withCompletion:"
+ "openSensitiveURL:withOptions:"
+ "performSelector:"
+ "performSelector:withObject:withObject:"
+ "prefs:root=SCREEN_TIME&path=CONTENT_PRIVACY/CONTENT_RESTRICTIONS/WEB_CONTENT"
+ "settings-navigation://com.apple.Settings.ScreenTime/APPS_AND_WEBSITES/APP_PERMISSIONS/WEB_CONTENT"
+ "v28@0:8B16@?20"
+ "v28@0:8B16@?<v@?@\"NSError\">20"
- "blocked"
```
