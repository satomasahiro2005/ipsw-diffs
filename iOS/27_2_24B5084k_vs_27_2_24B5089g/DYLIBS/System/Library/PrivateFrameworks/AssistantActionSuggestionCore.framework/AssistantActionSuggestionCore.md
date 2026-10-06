## AssistantActionSuggestionCore

> `/System/Library/PrivateFrameworks/AssistantActionSuggestionCore.framework/AssistantActionSuggestionCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2351e4` | `0x2371c4` | **`+0x1fe0`** |
| `__DATA_DIRTY.__data` | `0x43e0` | `0x47a8` | **`+0x3c8`** |
| `__AUTH.__data` | `0xcc0` | `0xa38` | **`-0x288`** |
| `__TEXT.__oslogstring` | `0x785a` | `0x798a` | **`+0x130`** |
| `__DATA.__data` | `0x21a8` | `0x20a0` | **`-0x108`** |
| `__AUTH.__objc_data` | `0x2a8` | `0x208` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x940` | `0x9e0` | **`+0xa0`** |
| `__DATA.__bss` | `0xbd70` | `0xbcf0` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x16a0` | `0x1720` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x3430` | `0x3460` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x19c0` | `0x19f0` | **`+0x30`** |
| `__TEXT.__const` | `0xbc48` | `0xbc78` | **`+0x30`** |
| `__DATA.__common` | `0xa0` | `0x80` | **`-0x20`** |
| `__DATA_DIRTY.__common` | `0x180` | `0x1a0` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0xfa04` | `0xfa1c` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x890` | `0x898` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x3c9a` | `0x3ca2` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x50b0` | `0x50b8` | **`+0x8`** |

### Other Changes

```diff

-674.0.1.0.0
+675.0.2.0.0

-  Functions: 5020
-  Symbols:   2004
-  CStrings:  1189
+  Functions: 5027
+  Symbols:   2011
+  CStrings:  1192
Symbols:
+ _DDBinderDateDurationKey
+ _DDBinderDateKey
+ _DDBinderDateTimeKey
+ _DDBinderTimeDurationKey
+ _DDBinderTimeKey
+ _DDBinderTimeOffsetKey
+ _symbolic _____Sg 32AssistantActionSuggestionSupport16SelectionContextO17MessageIdentifierV
CStrings:
+ "Event gate: filtering out %ld events — conversation has no qualifying calendar event"
+ "Event gate: filtering out %ld events — no calendar-event entity in the last incoming message"
+ "Reminder gate: filtering out %ld reminders — no date-bearing due anchor in the conversation"
+ "Reminder gate: filtering out %ld reminders — no temporal entity in the last incoming message"
- "Filtering out %ld events — no calendar event detected in context text"
```
