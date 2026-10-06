## EventKit

> `/System/Library/Frameworks/EventKit.framework/EventKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a1510` | `0x1a1644` | **`+0x134`** |
| `__DATA_CONST.__objc_selrefs` | `0xae58` | `0xae60` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x15a6c` | `0x15a74` | **`+0x8`** |

### Other Changes

```diff

-1970.0.0.0.0
+1973.0.0.0.0

-  Functions: 10665
-  Symbols:   13229
+  Functions: 10666
+  Symbols:   13231
Symbols:
+ -[EKEvent locationTitleExcludingConferenceRooms]
+ GCC_except_table351
+ GCC_except_table397
+ GCC_except_table400
+ GCC_except_table435
+ GCC_except_table440
+ GCC_except_table542
- GCC_except_table350
- GCC_except_table399
- GCC_except_table434
- GCC_except_table439
- GCC_except_table470
Functions:
~ -[EKCalendarItem filterAttendeesPendingDeletion:] : 348 -> 412
+ -[EKEvent locationTitleExcludingConferenceRooms]
```
