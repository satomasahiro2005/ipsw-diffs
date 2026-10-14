## SpringBoard

> `/System/Library/AccessibilityBundles/SpringBoard.axbundle/SpringBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3a7d0` | `0x3aba8` | **`+0x3d8`** |
| `__TEXT.__oslogstring` | `0xa3b` | `0xd4d` | **`+0x312`** |
| `__TEXT.__cstring` | `0xa686` | `0xa3f2` | **`-0x294`** |
| `__AUTH_CONST.__cfstring` | `0xbc80` | `0xbb40` | **`-0x140`** |
| `__TEXT.__objc_methlist` | `0x4d1c` | `0x4d4c` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xdf0` | `0xe18` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2638` | `0x2650` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1368` | `0x1380` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0xb40` | `0xb2c` | **`-0x14`** |
| `__TEXT.__const` | `0xe0` | `0xe8` | **`+0x8`** |

### Other Changes

```diff

-3050.3.5.0.0
+3050.3.8.0.0

-  Functions: 1619
-  Symbols:   3855
-  CStrings:  1670
+  Functions: 1624
+  Symbols:   3860
+  CStrings:  1674
Symbols:
+ -[SBFluidSwitcherItemContainerAccessibility _axSwitcherViewController]
+ -[SBFluidSwitcherViewControllerAccessibility _axAppExposeBundleIdentifier]
+ -[SBFluidSwitcherViewControllerAccessibility _axAppLayoutIsPlaceableInDeck:]
+ -[SBFluidSwitcherViewControllerAccessibility _axReachableAppLayouts]
+ GCC_except_table1123
+ GCC_except_table1143
+ GCC_except_table1150
+ GCC_except_table1154
+ GCC_except_table1158
+ GCC_except_table1161
+ GCC_except_table1165
+ GCC_except_table1321
+ GCC_except_table1328
+ GCC_except_table1332
+ GCC_except_table1359
+ GCC_except_table1368
+ GCC_except_table1371
+ GCC_except_table1390
+ GCC_except_table1396
+ GCC_except_table1398
+ GCC_except_table1407
+ GCC_except_table1413
+ GCC_except_table1424
+ GCC_except_table1426
+ GCC_except_table1550
+ GCC_except_table1604
+ GCC_except_table756
+ GCC_except_table758
+ GCC_except_table779
+ GCC_except_table781
+ GCC_except_table799
+ GCC_except_table821
+ GCC_except_table828
+ GCC_except_table971
+ GCC_except_table973
+ ___68-[SBFluidSwitcherViewControllerAccessibility _axReachableAppLayouts]_block_invoke
+ ___block_descriptor_40_e8_32s_e15_B32?08Q16^B24ls32l8
- GCC_except_table1118
- GCC_except_table1138
- GCC_except_table1145
- GCC_except_table1149
- GCC_except_table1153
- GCC_except_table1156
- GCC_except_table1160
- GCC_except_table1316
- GCC_except_table1323
- GCC_except_table1327
- GCC_except_table1354
- GCC_except_table1358
- GCC_except_table1366
- GCC_except_table1385
- GCC_except_table1391
- GCC_except_table1393
- GCC_except_table1397
- GCC_except_table1408
- GCC_except_table1419
- GCC_except_table1421
- GCC_except_table1545
- GCC_except_table1599
- GCC_except_table755
- GCC_except_table757
- GCC_except_table778
- GCC_except_table780
- GCC_except_table796
- GCC_except_table816
- GCC_except_table823
- GCC_except_table966
- GCC_except_table968
- __AXLogWithFacility
CStrings:
+ "Applying screen curtain change to %d"
+ "Could not check in as: %{public}s"
+ "Lock button: returning SBBacklightActionNone, awake behind screen curtain"
+ "SBVOT: failed to read entitlements for caller (pid=%d): %{public}@"
+ "Screen curtain changed to %d while asleep, applying on next wake"
+ "VoiceOverTouch is back... (%d)"
+ "app.has.multiple.windows"
+ "show.all.shelf.apps"
- "Could not check in as: %s\n"
- "SBVOT: failed to read entitlements for caller (pid=%d): %@"
- "SBVOT: skipping screen curtain apply for enabled=%d because system is sleeping; will not be resynced on wake"
- "VoiceOverTouch is back... (%d)\n"
```
