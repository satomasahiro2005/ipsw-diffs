## CoreTelephonyDiagnosticExtension

> `/System/Library/Frameworks/CoreTelephony.framework/PlugIns/CoreTelephonyDiagnosticExtension.appex/CoreTelephonyDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c4` | `0x8e0` | **`+0x61c`** |
| `__TEXT.__oslogstring` | `0x67` | `0x1ed` | **`+0x186`** |
| `__TEXT.__cstring` | `0x68` | `0x179` | **`+0x111`** |
| `__TEXT.__objc_stubs` | `0xe0` | `0x180` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x58` | `0xe4` | **`+0x8c`** |
| `__DATA_CONST.__cfstring` | `0x40` | `0xc0` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0xc8` | `0x131` | **`+0x69`** |
| `__TEXT.__objc_methlist` | `0x2c` | `0x5c` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x78` | `0xa8` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x48` | `0x70` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x40` | `0x38` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`

### Other Changes

```diff

-13466.3.0.0.0
+13473.1.0.0.0

-  Functions: 3
-  Symbols:   32
-  CStrings:  19
+  Functions: 7
+  Symbols:   31
+  CStrings:  36
Symbols:
+ _OBJC_CLASS_$_NSMutableArray
+ _objc_release_x22
+ _objc_release_x24
+ _objc_release_x25
+ _objc_release_x26
- _OBJC_CLASS_$_NSArray
- ___stack_chk_fail
- ___stack_chk_guard
- _objc_release_x23
- _objc_retain_x2
- _objc_retain_x8
Functions:
~ sub_100000cb0 : 340 -> 356
CStrings:
+ "/var/wireless/Library/LASD"
+ "/var/wireless/Library/Preferences/com.apple.commcenter.plist"
+ "/var/wireless/Library/Preferences/no_backup/com.apple.commcenter.app.wea.alerts.plist"
+ "/var/wireless/Library/Preferences/no_backup/com.apple.commcenter.app.wea.notification.expiry.plist"
+ "Attempting to attach CommCenter preferences, sensitive collection %s"
+ "Attempting to attach LASD directory, sensitive collection %s"
+ "Attempting to attach WEA alerts plist, sensitive collection %s"
+ "Attempting to attach WEA notification expiry plist, sensitive collection %s"
+ "CommCenter preferences path: %@"
+ "LASD directory path: %@"
+ "WEA alerts plist path: %@"
+ "WEA notification expiry plist path: %@"
+ "addObject:"
+ "array"
+ "commcenterPreferencesAttachment:"
+ "lasdDirectoryAttachment:"
+ "weaAlertsAttachment:"
+ "weaNotificationExpiryAttachment:"
- "arrayWithObjects:count:"
```
