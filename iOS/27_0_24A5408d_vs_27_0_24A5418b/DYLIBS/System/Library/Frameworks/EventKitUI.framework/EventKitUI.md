## EventKitUI

> `/System/Library/Frameworks/EventKitUI.framework/EventKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f9aec` | `0x1f9ba4` | **`+0xb8`** |
| `__AUTH_CONST.__objc_const` | `0x31838` | `0x31868` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x2038c` | `0x2039c` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1c10` | `0x1c18` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xfbf0` | `0xfbf8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2594` | `0x2598` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1572.0.0.0.0
+1572.0.100.0.0

-  Functions: 12398
-  Symbols:   18520
+  Functions: 12399
+  Symbols:   18524
Symbols:
+ -[EKEventAttendeePicker searchResults]
+ GCC_except_table26
+ GCC_except_table45
+ GCC_except_table51
+ _OBJC_IVAR_$_EKEventAttendeePicker._lastFinishedSearchId
- GCC_except_table48
Functions:
~ -[EKEventAttendeePicker dealloc] : 152 -> 180
+ -[EKEventAttendeePicker searchResults]
~ -[EKEventAttendeePicker _hideSearchResultsViewAndCancelOutstandingSearches:] : 344 -> 368
~ ___44-[EKEventAttendeePicker finishedTaskWithID:]_block_invoke : 104 -> 112
~ -[EKEventAttendeePicker searchWithText:] : 348 -> 372
~ -[EKEventAttendeePicker searchForCorecipients] : 356 -> 380
~ -[EKEventAttendeePicker .cxx_destruct] : 460 -> 480
CStrings:
+ "\xf0\xf1"
- "\xf0\xe1"
```
