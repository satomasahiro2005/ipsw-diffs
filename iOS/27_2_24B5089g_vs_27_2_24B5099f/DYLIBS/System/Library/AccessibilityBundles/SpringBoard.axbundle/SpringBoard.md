## SpringBoard

> `/System/Library/AccessibilityBundles/SpringBoard.axbundle/SpringBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3a738` | `0x3a7d0` | **`+0x98`** |
| `__AUTH_CONST.__cfstring` | `0xbc20` | `0xbc80` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x9fb` | `0xa3b` | **`+0x40`** |
| `__TEXT.__cstring` | `0xa657` | `0xa686` | **`+0x2f`** |
| `__DATA_CONST.__const` | `0xe18` | `0xdf0` | **`-0x28`** |
| `__TEXT.__gcc_except_tab` | `0xb50` | `0xb40` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x4d0c` | `0x4d1c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2630` | `0x2638` | **`+0x8`** |
| `__TEXT.__const` | `0xe8` | `0xe0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1360` | `0x1368` | **`+0x8`** |

### Other Changes

```diff

-3050.3.1.0.0
+3050.3.5.0.0

-  CStrings:  1666
+  CStrings:  1670
Symbols:
+ -[SBLockScreenManagerAccessibility _axAuthenticationFailureAnnouncement:]
+ -[SpringBoardAccessibility _axAcquireOrientationDeferralAssertionForDisplayID:]
+ GCC_except_table1118
+ GCC_except_table1138
+ GCC_except_table1145
+ GCC_except_table1149
+ GCC_except_table1153
+ GCC_except_table1156
+ GCC_except_table1160
+ GCC_except_table1316
+ GCC_except_table1323
+ GCC_except_table1327
+ GCC_except_table1354
+ GCC_except_table1358
+ GCC_except_table1363
+ GCC_except_table1366
+ GCC_except_table1385
+ GCC_except_table1391
+ GCC_except_table1393
+ GCC_except_table1397
+ GCC_except_table816
+ GCC_except_table823
+ GCC_except_table966
+ GCC_except_table968
+ ___79-[SpringBoardAccessibility _axAcquireOrientationDeferralAssertionForDisplayID:]_block_invoke
- -[SBFluidSwitcherViewControllerAccessibility _axPostScreenChangeToFocusAppLayout:attempt:]
- GCC_except_table1119
- GCC_except_table1139
- GCC_except_table1146
- GCC_except_table1150
- GCC_except_table1154
- GCC_except_table1157
- GCC_except_table1161
- GCC_except_table1317
- GCC_except_table1324
- GCC_except_table1328
- GCC_except_table1355
- GCC_except_table1359
- GCC_except_table1364
- GCC_except_table1367
- GCC_except_table1386
- GCC_except_table1392
- GCC_except_table1394
- GCC_except_table814
- GCC_except_table818
- GCC_except_table825
- GCC_except_table967
- GCC_except_table969
- ___90-[SBFluidSwitcherViewControllerAccessibility _axPostScreenChangeToFocusAppLayout:attempt:]_block_invoke
- ___block_descriptor_56_e8_32s40w_e5_v8?0lw40l8s32l8
CStrings:
+ "Holding device orientation device-wide (requested displayID %u)"
+ "biometricLockout"
+ "displayID"
+ "enabled"
+ "lockscreen.press.home.to.unlock"
+ "lockscreen.swipe.up.to.unlock"
- "alr_requiresPreflight"
- "statusBarEdgeInOrientation:"
```
