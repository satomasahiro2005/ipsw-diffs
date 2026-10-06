## CTFollowUpExtension

> `/System/Library/Frameworks/CoreTelephony.framework/PlugIns/CTFollowUpExtension.appex/CTFollowUpExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bd0` | `0x1924` | **`-0x2ac`** |
| `__DATA_CONST.__cfstring` | `0x5c0` | `0x4e0` | **`-0xe0`** |
| `__TEXT.__cstring` | `0x517` | `0x43e` | **`-0xd9`** |
| `__TEXT.__objc_methname` | `0x594` | `0x4f4` | **`-0xa0`** |
| `__TEXT.__objc_stubs` | `0x660` | `0x5e0` | **`-0x80`** |
| `__TEXT.__oslogstring` | `0x222` | `0x1d9` | **`-0x49`** |
| `__DATA.__objc_selrefs` | `0x1a8` | `0x188` | **`-0x20`** |
| `__DATA_CONST.__got` | `0xb0` | `0xa0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xa0` | `0x90` | **`-0x10`** |
| `__TEXT.__objc_methtype` | `0x6a` | `0x5c` | **`-0xe`** |
| `__TEXT.__objc_methlist` | `0x74` | `0x68` | **`-0xc`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`

### Other Changes

```diff

-13466.3.0.0.0
+13473.1.0.0.0

-  Functions: 16
-  Symbols:   68
-  CStrings:  122
+  Functions: 15
+  Symbols:   66
+  CStrings:  109
Symbols:
- _OBJC_CLASS_$_NSCharacterSet
- _OBJC_CLASS_$_NSString
CStrings:
+ "Followup did open QS enrollment resumption prefs url %@ with success %d error %@"
+ "com.followup.qs-enrollment-dismiss"
+ "com.followup.qs-enrollment-resumption"
+ "handleQuickSwitchEnrollmentResumption:"
+ "settings-navigation://com.apple.Settings.Cellular/MOBILE_DATA_SETTINGS/ADD_CELLULAR_PLAN"
- ""
- "DeviceModel"
- "Followup did open QS enrollment prefs url %@ with success %d error %@"
- "Followup did open QS websheet incomplete info prefs url %@ with success %d error %@"
- "PhoneNumber"
- "URLQueryAllowedCharacterSet"
- "com.followup.qs-enrollment"
- "com.followup.qs-no-wifi"
- "com.followup.qs-websheet-incomplete-info"
- "handleQuickSwitchEnrollmentItem:sliding:"
- "handleQuickSwitchWebsheetIncompleteInfoItem:selectedAction:"
- "no"
- "prefs:root=MOBILE_DATA_SETTINGS_ID&path=CELLULAR&client=com.apple.CommCenter&type=quickSwitch&flow=enroll&sliding=%@"
- "prefs:root=MOBILE_DATA_SETTINGS_ID&path=CELLULAR&client=com.apple.CommCenter&type=quickSwitch&flow=followUp&phoneNumber=%@&deviceModel=%@"
- "stringByAddingPercentEncodingWithAllowedCharacters:"
- "stringWithFormat:"
- "v28@0:8@16B24"
- "yes"
```
