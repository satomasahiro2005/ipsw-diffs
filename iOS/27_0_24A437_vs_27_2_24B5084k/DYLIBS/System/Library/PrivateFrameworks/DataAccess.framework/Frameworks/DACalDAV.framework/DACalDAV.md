## DACalDAV

> `/System/Library/PrivateFrameworks/DataAccess.framework/Frameworks/DACalDAV.framework/DACalDAV`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36b4c` | `0x36c3c` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0x24e0` | `0x2520` | **`+0x40`** |
| `__TEXT.__cstring` | `0x16f0` | `0x1709` | **`+0x19`** |
| `__AUTH_CONST.__objc_const` | `0x8c50` | `0x8c60` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x45bc` | `0x45cc` | **`+0x10`** |
| `__DATA_CONST.__const` | `0xa20` | `0xa28` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x7d0` | `0x7d8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2818` | `0x2820` | **`+0x8`** |

### Other Changes

```diff

-2708.0.0.0.0
+2708.1.5.0.0

-  Functions: 1092
-  Symbols:   2543
-  CStrings:  654
+  Functions: 1093
+  Symbols:   2546
+  CStrings:  656
Symbols:
+ -[MobileCalDAVAccount telemetryServerType]
+ GCC_except_table100
+ GCC_except_table104
+ GCC_except_table107
+ GCC_except_table121
+ GCC_except_table123
+ GCC_except_table86
+ _kCalDAVAppleInternalServerType
+ _kiCloudCalDAVServerType
- GCC_except_table103
- GCC_except_table106
- GCC_except_table120
- GCC_except_table122
- GCC_except_table85
- GCC_except_table99
Functions:
+ -[MobileCalDAVAccount telemetryServerType]
~ ___86-[MobileCalDAVPrincipal completeWithError:httpMethod:latency:task:responseStatusCode:]_block_invoke : 388 -> 372
~ -[MobileCalDAVCalendar putAction:completedWithError:] : 972 -> 992
CStrings:
+ ".apple.com"
+ "AppleInternal"
```
