## libTelephonyUtilDynamic.dylib

> `/usr/lib/libTelephonyUtilDynamic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x857e0` | `0x84c74` | **`-0xb6c`** |
| `__TEXT.__oslogstring` | `0x21c6` | `0x1d36` | **`-0x490`** |
| `__TEXT.__cstring` | `0x368f` | `0x3604` | **`-0x8b`** |
| `__AUTH_CONST.__cfstring` | `0x6e0` | `0x660` | **`-0x80`** |
| `__TEXT.__gcc_except_tab` | `0x8b58` | `0x8b0c` | **`-0x4c`** |
| `__DATA_CONST.__got` | `0x308` | `0x2f0` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x44d8` | `0x44c0` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0xc70` | `0xc60` | **`-0x10`** |

### Other Changes

```diff

-  Functions: 3366
-  Symbols:   5241
-  CStrings:  730
+  Functions: 3363
+  Symbols:   5236
+  CStrings:  707
Symbols:
+ GCC_except_table115
+ GCC_except_table134
+ _sTelephonyHardwareConfig
- _CFTypeToCString
- _CFUserNotificationCreate
- __ZN3ctu2cf6insertIPK10__CFStringS4_EEbP14__CFDictionaryT_T0_PK13__CFAllocator
- _kCFUserNotificationAlertHeaderKey
- _kCFUserNotificationAlertMessageKey
- _kCFUserNotificationDefaultButtonTitleKey
- _os_parse_boot_arg_string
- _performMGQueryReturnsString
CStrings:
- "/private/var/wireless/Library/Preferences/com.apple.telephony.overrides.plist"
- "BasebandChipset"
- "Did not find a hardware model override string"
- "Did not override hardware model string based on NVRAM boot args"
- "Failed to convert retrieved CFStringRef to UTF-8 C-string"
- "Failed to convert type returned by MobileGestalt to a C-string."
- "Failed to get baseband chipset from MobileGestalt and cache was empty; proceeding with unknown radio"
- "Failed to perform MobileGestalt query"
- "Failed to set Telephony hardware model info according to hardware model override string '%s'"
- "Failed while trying to query MobileGestalt"
- "HardwareModelString"
- "Invalid parameter"
- "OK"
- "Overrode and cached baseband chipset to enum value %d"
- "Passed buf of length %ld is not long enough for string of size %ld (incl. null terminator)"
- "Read baseband chipset %s from MobileGestalt"
- "Successfully overrode hardware model string to %s based on NVRAM boot args"
- "Successfully read %s to buffer from MobileGestalt"
- "Successfully set Telephony hardware model info according to hardware model override string '%s'"
- "Using cached baseband chipset enum value %d, originally from MobileGestalt"
- "Value %s from MobileGestalt does not match any supported baseband chipset; proceeding with unknown radio"
- "Value provided has type id %lu; it is not a CFString"
- "telephony-hw-override"
```
