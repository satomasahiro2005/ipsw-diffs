## RemindersUICore

> `/System/Library/PrivateFrameworks/RemindersUICore.framework/RemindersUICore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb8d9d8` | `0xb93428` | **`+0x5a50`** |
| `__TEXT.__oslogstring` | `0x18fa7` | `0x19167` | **`+0x1c0`** |
| `__DATA_DIRTY.__bss` | `0x7bc0` | `0x7cc0` | **`+0x100`** |
| `__TEXT.__eh_frame` | `0x158c4` | `0x15974` | **`+0xb0`** |
| `__AUTH.__data` | `0x17930` | `0x179d0` | **`+0xa0`** |
| `__DATA_DIRTY.__data` | `0x13e18` | `0x13ea0` | **`+0x88`** |
| `__DATA.__bss` | `0x28610` | `0x28590` | **`-0x80`** |
| `__TEXT.__const` | `0x41614` | `0x41694` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x4ea60` | `0x4eac8` | **`+0x68`** |
| `__AUTH.__objc_data` | `0xa5e8` | `0xa590` | **`-0x58`** |
| `__DATA_DIRTY.__objc_data` | `0x4f90` | `0x4fe0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1cd78` | `0x1cdc8` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x22484` | `0x224cc` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0x2b8c8` | `0x2b888` | **`-0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x1b458` | `0x1b490` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x293be` | `0x293f4` | **`+0x36`** |
| `__DATA.__data` | `0x11228` | `0x111f8` | **`-0x30`** |
| `__TEXT.__swift5_capture` | `0xdc44` | `0xdc68` | **`+0x24`** |
| `__TEXT.__cstring` | `0x28210` | `0x28230` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1a50d` | `0x1a4ed` | **`-0x20`** |
| `__TEXT.__swift_as_ret` | `0x590` | `0x5a0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x5e38` | `0x5e40` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1e00` | `0x1e08` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xac8` | `0xad0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x4e4` | `0x4ec` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x23ac` | `0x23b0` | **`+0x4`** |

### Other Changes

```diff

-4076.0.0.0.0
+4077.0.0.0.0

-  Functions: 48995
-  Symbols:   13218
-  CStrings:  4454
+  Functions: 49029
+  Symbols:   13222
+  CStrings:  4460
Symbols:
+ _symbolic _____ 15RemindersUICore27TTRMagicComposeDueDateStateV8ResolvedV
+ _symbolic _____ 15RemindersUICore27TTRMagicComposeDueDateStateV8ResolvedV6ActionO
+ _symbolic _____4date_Sb8isAllDay_____Sg8timeZonet 10Foundation4DateV AA8TimeZoneV
+ _symbolic ______AAt 15RemindersUICore27TTRMagicComposeDueDateStateV8ResolvedV6ActionO
CStrings:
+ ", hasDueDateUpdate:"
+ "[MagicCompose] Scheduling backward pass with %ld update(s)"
+ "[MagicCompose] Starting backward pass with %ld update(s), dayWasUserSet: %{bool}d, timeWasUserSet: %{bool}d)"
+ "[MagicCompose] TTRMagicComposePromptUpdating: detected all-day change with date: %s"
+ "[MagicCompose] TTRMagicComposePromptUpdating: detected assignee change: %{private}s"
+ "[MagicCompose] TTRMagicComposePromptUpdating: detected assignee removed: %{private}s"
+ "[MagicCompose] TTRMagicComposePromptUpdating: detected due date change: %s"
+ "[MagicCompose] TTRMagicComposePromptUpdating: detected due date removed"
+ "[MagicCompose] TTRMagicComposePromptUpdating: detected recurrence rule change: %s"
+ "[MagicCompose] TTRMagicComposePromptUpdating: detected recurrence rule removed"
+ "[MagicCompose] TTRMagicComposePromptUpdating: detected spatial trigger change: %s"
+ "[MagicCompose] TTRMagicComposePromptUpdating: detected spatial trigger removed"
+ "[MagicCompose] TTRMagicComposePromptUpdating: detected time zone change: %s"
+ "[MagicCompose] Timezone-only reconversion produced nil date; no change applied"
+ "[MagicCompose] Wall-clock conversion produced nil date; falling back to raw absolute date"
+ "[MagicCompose] backward pass skipped — forward pass in progress"
- "[MagicCompose] Performing backward pass with %ld update(s), dayWasUserSet: %{bool}d, timeWasUserSet: %{bool}d)"
- "[MagicCompose] TTRMagicComposePromptUpdating: due date removed"
- "[MagicCompose] TTRMagicComposePromptUpdating: recurrence rule removed"
- "[MagicCompose] TTRMagicComposePromptUpdating: remove old assignee with name: %{private}s"
- "[MagicCompose] TTRMagicComposePromptUpdating: spatial trigger removed"
- "[MagicCompose] TTRMagicComposePromptUpdating: update due date with date: %s"
- "[MagicCompose] TTRMagicComposePromptUpdating: update new assignee with name: %{private}s"
- "[MagicCompose] TTRMagicComposePromptUpdating: update recurrence rule with rule: %s"
- "[MagicCompose] TTRMagicComposePromptUpdating: update spatial trigger with: %s"
- "[MagicCompose] TTRMagicComposePromptUpdating: update time zone with: %s"
```
