## MessagesSecurityPolicy

> `/System/Library/PrivateFrameworks/MessagesSecurityPolicy.framework/MessagesSecurityPolicy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x3a8` | `0x738` | **`+0x390`** |
| `__AUTH.__data` | `0x708` | `0x4c8` | **`-0x240`** |
| `__DATA.__data` | `0x498` | `0x388` | **`-0x110`** |
| `__TEXT.__oslogstring` | `0xfda` | `0xed7` | **`-0x103`** |
| `__AUTH.__objc_data` | `0x220` | `0x1d0` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x50` | `0xa0` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x1458` | `0x1418` | **`-0x40`** |
| `__TEXT.__swift5_reflstr` | `0x760` | `0x737` | **`-0x29`** |
| `__TEXT.__const` | `0x159e` | `0x157e` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x718` | `0x730` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x858` | `0x840` | **`-0x18`** |
| `__TEXT.__swift5_typeref` | `0xba4` | `0xb8c` | **`-0x18`** |
| `__TEXT.__swift5_capture` | `0x8b4` | `0x8c4` | **`+0x10`** |
| `__DATA.__common` | `0x8` | `—` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__text` | `0x1aa78` | `0x1aa80` | **`+0x8`** |

### Other Changes

```diff

-1483.100.10.2.4
+1486.100.5.2.1

-  Functions: 554
+  Functions: 545

-  CStrings:  118
+  CStrings:  117
Symbols:
+ ___swift_closure_destructor.2Tm
+ ___swift_memcpy48_8
+ _swift_release_x22
+ _swift_retain_x26
+ _swift_retain_x9
- ___swift_closure_destructor.5Tm
- ___swift_memcpy17_8
- ___swift_memcpy25_8
- ___swift_memcpy56_8
- _symbolic So17OS_dispatch_queueC
CStrings:
+ "Sender is me."
+ "The lenient policy rule set will be used for %s sender."
+ "The strict policy rule set will be used for %s sender, and %ld event."
+ "The strict policy rule set will be used for %s sender."
+ "The strict reparsing policy rule set will be used for %s sender and %ld event."
- "The lenient policy rule set will be used for %s  sender, isFromMe: %{bool}d, and %ld event."
- "The lenient policy rule set will be used for %s sender, isFromMe: %{bool}d"
- "The lenient policy rule set will be used for %s sender, isFromMe: %{bool}d."
- "The strict policy rule set will be used for %s sender, isFromMe: %{bool}d"
- "The strict policy rule set will be used for %s sender, isFromMe: %{bool}d, and %ld event."
- "The strict reparsing policy rule set will be used for %s sender, isFromMe: %{bool}d and %ld event."
```
