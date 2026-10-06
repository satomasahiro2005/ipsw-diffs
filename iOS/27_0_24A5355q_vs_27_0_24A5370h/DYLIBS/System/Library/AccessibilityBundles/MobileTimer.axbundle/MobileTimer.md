## MobileTimer

> `/System/Library/AccessibilityBundles/MobileTimer.axbundle/MobileTimer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8bb0` | `0x8c0c` | **`+0x5c`** |
| `__AUTH_CONST.__cfstring` | `0x24e0` | `0x2520` | **`+0x40`** |
| `__TEXT.__cstring` | `0x177d` | `0x17ae` | **`+0x31`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  CStrings:  319
+  CStrings:  321
Symbols:
+ ___block_descriptor_48_e8_32s40w_e15_"NSString"8?0ls32l8w40l8
- ___block_descriptor_56_e8_32s40s48w_e15_"NSString"8?0lw48l8s32l8s40l8
Functions:
~ +[MTAAlarmCollectionViewCellAccessibility _accessibilityPerformValidations:] : 304 -> 332
~ -[MTAAlarmTableViewCellAccessibility _axSetDetailLabelForAlarm:] : 292 -> 228
~ ___64-[MTAAlarmTableViewCellAccessibility _axSetDetailLabelForAlarm:]_block_invoke : 236 -> 372
~ -[MTAAlarmTableViewControllerAccessibility _axSetDetailLabelsForVisibleCells] : 1064 -> 1060
~ -[MTAWorldClockMapViewAccessibility _accessibilityHitTest:withEvent:] : 500 -> 496
CStrings:
+ "detailLabel"
+ "timeLabel, nameLabel, upcomingDateLabel, repeatLabel, soundLabel"
+ "upcomingDateLabel"
- "timeLabel, nameLabel, repeatLabel, soundLabel"
```
