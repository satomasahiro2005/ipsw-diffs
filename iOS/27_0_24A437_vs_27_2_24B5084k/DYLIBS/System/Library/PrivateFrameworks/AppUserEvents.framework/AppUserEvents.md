## AppUserEvents

> `/System/Library/PrivateFrameworks/AppUserEvents.framework/AppUserEvents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34b74` | `0x388d0` | **`+0x3d5c`** |
| `__TEXT.__eh_frame` | `0x2150` | `0x2558` | **`+0x408`** |
| `__DATA.__bss` | `0x3710` | `0x3a10` | **`+0x300`** |
| `__TEXT.__const` | `0x3208` | `0x3418` | **`+0x210`** |
| `__AUTH_CONST.__const` | `0x25a0` | `0x26c8` | **`+0x128`** |
| `__TEXT.__swift5_typeref` | `0xf1f` | `0x1013` | **`+0xf4`** |
| `__TEXT.__unwind_info` | `0xf70` | `0x1060` | **`+0xf0`** |
| `__TEXT.__constg_swiftt` | `0x1674` | `0x175c` | **`+0xe8`** |
| `__TEXT.__swift5_fieldmd` | `0xe7c` | `0xeec` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0xc78` | `0xcc0` | **`+0x48`** |
| `__DATA.__data` | `0x16e0` | `0x1720` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x428` | `0x468` | **`+0x40`** |
| `__TEXT.__swift5_proto` | `0x27c` | `0x2a4` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x924` | `0x944` | **`+0x20`** |
| `__AUTH.__data` | `0x6b8` | `0x6c8` | **`+0x10`** |
| `__TEXT.__cstring` | `0xb2a` | `0xb3a` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x581` | `0x591` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x3c` | `0x48` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x118` | `0x11c` | **`+0x4`** |

### Other Changes

```diff

-10.0.0.0.0
+11.0.0.0.0

-  Functions: 1252
-  Symbols:   581
-  CStrings:  81
+  Functions: 1299
+  Symbols:   593
+  CStrings:  83
Symbols:
+ ___swift_allocate_boxed_opaque_existential_1Tm
+ ___swift_deallocate_boxed_opaque_existential_0
+ ___swift_memcpy33_8
+ ___unnamed_17
+ ___unnamed_18
+ _symbolic $s13AppUserEvents0B15EventSupplementP
+ _symbolic $s13AppUserEvents16_SQLLiteralRange33_E4D167AB3ED1F72A211C3A17817C6B32LLP
+ _symbolic $s13AppUserEvents19_SQLRangeExpression33_E4D167AB3ED1F72A211C3A17817C6B32LLP
+ _symbolic 5Event_____Qz 13AppUserEvents0B15EventSupplementP
+ _symbolic 6Output_____Qy0_ 10Foundation19PredicateExpressionP
+ _symbolic 6Output_____Qy_ 10Foundation19PredicateExpressionP
+ _symbolic S2S______SayxGtYbKc 10Foundation12DateIntervalV
+ _symbolic SbSg
+ _symbolic _____ 13AppUserEvents12_SQLFragment33_E4D167AB3ED1F72A211C3A17817C6B32LLV
+ _symbolic q_
+ _type_layout_string 13AppUserEvents12_SQLFragment33_E4D167AB3ED1F72A211C3A17817C6B32LLV
- ___unnamed_8
- ___unnamed_9
- _symbolic 7ElementSTQz
- _symbolic ySS______SayxGtYbKc 10Foundation12DateIntervalV
CStrings:
+ "Closing event write stream, id=%{public}s"
+ "Did save session, id=%{public}s"
+ "Did save session, id=%{public}s, persisted=%{public}s"
+ "Failed to save session, id=%{public}s, error=%{public}@"
+ "Opening event write stream, id=%{public}s"
+ "Skipping persistence of empty session, id=%{public}s"
+ "Submitting event to write stream, event=%{public}s, id=%{public}s"
+ "Will save session, eventCount=%ld, id=%{public}s"
+ "op value "
- "Closing event write stream, identifier=%{public}s"
- "Did save session, identifier=%{public}s"
- "Failed to save session, identifier=%{public}s, error=%{public}@"
- "Opening event write stream, identifier=%{public}s"
- "Skipping persistence of empty session, identifier=%{public}s"
- "Submitting event to write stream, event=%{public}s, identifier=%{public}s"
- "Will save session, eventCount=%ld, identifier=%{public}s"
```
