## UserDomainConceptsSupport

> `/System/Library/PrivateFrameworks/UserDomainConceptsSupport.framework/UserDomainConceptsSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x134d4` | `0x14210` | **`+0xd3c`** |
| `__TEXT.__oslogstring` | `0x3d` | `0x13c` | **`+0xff`** |
| `__TEXT.__cstring` | `0x211` | `0x291` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x630` | `0x698` | **`+0x68`** |
| `__TEXT.__swift5_reflstr` | `0x1c2` | `0x222` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x2b8` | `0x304` | **`+0x4c`** |
| `__TEXT.__constg_swiftt` | `0x2e4` | `0x308` | **`+0x24`** |
| `__TEXT.__const` | `0x592` | `0x5b2` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x690` | `0x6a8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x508` | `0x520` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x618` | `0x628` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x4b6` | `0x4c0` | **`+0xa`** |
| `__TEXT.__swift_as_cont` | `0x54` | `0x5c` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x310` | `0x314` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x24` | `0x28` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x34` | `0x38` | **`+0x4`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 420
-  Symbols:   291
-  CStrings:  14
+  Functions: 425
+  Symbols:   293
+  CStrings:  18
Symbols:
+ _symbolic Si
+ _symbolic _____ 25UserDomainConceptsSupport18ListConceptManagerC13ReloadTrigger33_068A1837F8ED68C018A2C8D9742CDD66LLO
CStrings:
+ "%{public}s reload publish dropped, commit store write in flight (trigger=%{public}s reloadId=%{public}s epoch=%{public}llu)"
+ "%{public}s scheduling reload trigger=%{public}s reloadId=%{public}s epoch=%{public}llu persistsInFlight=%{public}ld"
+ "ListConceptManager: persistsInFlight underflow — increment/decrement pairing is broken"
+ "protectedDataAvailable"
```
