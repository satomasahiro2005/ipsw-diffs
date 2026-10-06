## SiriCalendarUI

> `/System/Library/PrivateFrameworks/SiriCalendarUI.framework/SiriCalendarUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27c38` | `0x26fd0` | **`-0xc68`** |
| `__DATA.__bss` | `0x1338` | `0x11b8` | **`-0x180`** |
| `__TEXT.__const` | `0x1d38` | `0x1c58` | **`-0xe0`** |
| `__TEXT.__oslogstring` | `0x2a5` | `0x1f5` | **`-0xb0`** |
| `__AUTH_CONST.__const` | `0xda0` | `0xd10` | **`-0x90`** |
| `__AUTH_CONST.__auth_got` | `0xc20` | `0xbd8` | **`-0x48`** |
| `__TEXT.__eh_frame` | `0x2c0` | `0x280` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x918` | `0x8e0` | **`-0x38`** |
| `__TEXT.__swift5_reflstr` | `0x755` | `0x725` | **`-0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x724` | `0x6fc` | **`-0x28`** |
| `__DATA.__data` | `0xdb0` | `0xd90` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x834` | `0x818` | **`-0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x80` | `0x68` | **`-0x18`** |
| `__TEXT.__swift5_typeref` | `0x2adb` | `0x2ac5` | **`-0x16`** |
| `__TEXT.__swift5_proto` | `0x98` | `0x8c` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x530` | `0x528` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x88` | `0x84` | **`-0x4`** |

### Other Changes

```diff

-3600.18.5.0.0
+3600.18.9.1.1

-  Functions: 1051
-  Symbols:   604
-  CStrings:  25
+  Functions: 1025
+  Symbols:   598
+  CStrings:  22
Symbols:
- ___swift_memcpy0_1
- _associated conformance 14SiriCalendarUI27EventListCellViewModelErrorOSHAASQ
- _swift_allocError
- _swift_willThrow
- _symbolic _____ 14SiriCalendarUI27EventListCellViewModelErrorO
- _symbolic _____Sg 13CalendarUIKit19EKEventModelWrapperV
CStrings:
+ "[RenderableEvent] No eventModel available; rendering from snippet data (pre-hydration miss) — deliberately not fetching on the render thread"
+ "[RenderableEvent] Using snippet data to make event cell model"
- "[RenderableEvent] No eventModel available, fetching via eventIdentifier on the render thread"
- "[RenderableEvent] Using event store to make event cell model"
- "[Snippet.Event] Could not create event cell model"
- "[Snippet.Event] Initializing EventListCellViewModel with concrete event"
- "[Snippet.Event] Initializing EventListCellViewModel with draft event"
```
