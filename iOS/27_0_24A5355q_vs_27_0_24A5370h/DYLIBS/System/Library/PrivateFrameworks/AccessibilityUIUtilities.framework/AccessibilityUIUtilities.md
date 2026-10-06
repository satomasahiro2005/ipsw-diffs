## AccessibilityUIUtilities

> `/System/Library/PrivateFrameworks/AccessibilityUIUtilities.framework/AccessibilityUIUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x610a4` | `0x61628` | **`+0x584`** |
| `__AUTH_CONST.__objc_const` | `0xa0d0` | `0xa150` | **`+0x80`** |
| `__DATA_CONST.__const` | `0xd60` | `0xdb0` | **`+0x50`** |
| `__TEXT.__cstring` | `0x5bb0` | `0x5b8e` | **`-0x22`** |
| `__AUTH_CONST.__cfstring` | `0x6940` | `0x6920` | **`-0x20`** |
| `__AUTH_CONST.__const` | `0xac0` | `0xaa0` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x639c` | `0x63b4` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1948` | `0x1960` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x568` | `0x578` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x5070` | `0x5080` | **`+0x10`** |

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0

-  - /System/Library/PrivateFrameworks/BluetoothManager.framework/BluetoothManager

-  - /System/Library/PrivateFrameworks/MobileBluetooth.framework/MobileBluetooth

-  - /System/Library/PrivateFrameworks/TelephonyUI.framework/TelephonyUI

-  Functions: 2390
-  Symbols:   4593
-  CStrings:  1060
+  Functions: 2397
+  Symbols:   4606
+  CStrings:  1058
Symbols:
+ +[AXUICaptionPreviewView captionImageBundle]
+ -[AXFavoritesEntryCell setSpecifier:]
+ -[AccessibilityAirPodSettingsController _refreshCaseTonesVolumeCache]
+ -[AccessibilityAirPodSettingsController _refreshToneVolumeCache]
+ -[AccessibilityAirPodSettingsController caseToneVolumeValueForAddress:]
+ -[AccessibilityAirPodSettingsController toneVolumeValueForAddress:]
+ GCC_except_table1133
+ GCC_except_table1134
+ GCC_except_table1230
+ GCC_except_table1380
+ GCC_except_table1494
+ GCC_except_table1605
+ GCC_except_table1802
+ GCC_except_table1803
+ GCC_except_table1804
+ GCC_except_table1824
+ GCC_except_table1832
+ GCC_except_table1845
+ GCC_except_table1855
+ GCC_except_table1880
+ GCC_except_table963
+ _AXUIAnyAvailableScreen
+ _OBJC_IVAR_$_AccessibilityAirPodSettingsController._cachedCaseTonesVolumeValue
+ _OBJC_IVAR_$_AccessibilityAirPodSettingsController._cachedDefaultCaseTonesVolumeValue
+ _OBJC_IVAR_$_AccessibilityAirPodSettingsController._cachedDefaultToneVolumeValue
+ _OBJC_IVAR_$_AccessibilityAirPodSettingsController._cachedToneVolumeValue
+ ___64-[AccessibilityAirPodSettingsController _refreshToneVolumeCache]_block_invoke
+ ___64-[AccessibilityAirPodSettingsController _refreshToneVolumeCache]_block_invoke_2
+ ___69-[AccessibilityAirPodSettingsController _refreshCaseTonesVolumeCache]_block_invoke
+ ___69-[AccessibilityAirPodSettingsController _refreshCaseTonesVolumeCache]_block_invoke_2
+ ___block_descriptor_48_e8_32s40w_e5_v8?0lw40l8s32l8
+ ___block_descriptor_56_e8_32w_e5_v8?0lw32l8
+ _dispatch_get_global_queue
- -[AXFavoritesEntryCell initWithStyle:reuseIdentifier:]
- -[AccessibilityAirPodSettingsController caseToneVolumeValue]
- -[AccessibilityAirPodSettingsController jumpToAVSettings:]
- -[AccessibilityAirPodSettingsController toneVolumeValue]
- GCC_except_table1130
- GCC_except_table1131
- GCC_except_table1228
- GCC_except_table1378
- GCC_except_table1492
- GCC_except_table1603
- GCC_except_table1794
- GCC_except_table1795
- GCC_except_table1796
- GCC_except_table1817
- GCC_except_table1825
- GCC_except_table1838
- GCC_except_table1841
- GCC_except_table1873
- GCC_except_table961
- _objc_retain_x28
CStrings:
+ "settings-navigation://com.apple.Settings.Bluetooth/HeadphoneDetail/HearingHealth/?identifier=%@&Selection=HEARING_PROTECTION_ID"
- "\t"
- "prefs:root=ACCESSIBILITY&path=AUDIO_VISUAL_TITLE"
- "settings-navigation://com.apple.Settings.Bluetooth/HeadphoneDetail/?identifier=%@&Selection=HEARING_PROTECTION_ID"
```
