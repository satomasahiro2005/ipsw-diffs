## Rapport

> `/System/Library/PrivateFrameworks/Rapport.framework/Rapport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd96a8` | `0xd93f8` | **`-0x2b0`** |
| `__TEXT.__cstring` | `0x145dc` | `0x1449c` | **`-0x140`** |
| `__TEXT.__gcc_except_tab` | `0x1448` | `0x14c4` | **`+0x7c`** |
| `__TEXT.__swift5_capture` | `0x820` | `0x890` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x11298` | `0x112f8` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x2e70` | `0x2ec8` | **`+0x58`** |
| `__AUTH_CONST.__const` | `0x25e8` | `0x2638` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x2798` | `0x27e8` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0xb85` | `0xbd5` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x60c0` | `0x6080` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x9f08` | `0x9f38` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x1130` | `0x1140` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x44c8` | `0x44d8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x10ec` | `0x10f4` | **`+0x8`** |

### Other Changes

```diff

-745.100.4.0.0
+747.100.2.0.0

-  Functions: 5733
-  Symbols:   6738
-  CStrings:  3016
+  Functions: 5742
+  Symbols:   6757
+  CStrings:  3007
Symbols:
+ -[RPEventRegistration registrationID]
+ -[RPEventRegistration setRegistrationID:]
+ -[RPRequestRegistration registrationID]
+ -[RPRequestRegistration setRegistrationID:]
+ GCC_except_table278
+ GCC_except_table39
+ GCC_except_table68
+ GCC_except_table70
+ GCC_except_table72
+ GCC_except_table91
+ _OBJC_IVAR_$_RPEventRegistration._registrationID
+ _OBJC_IVAR_$_RPRequestRegistration._registrationID
+ ___block_descriptor_40_e8_32w_e5_v8?0lw32l8
+ ___block_descriptor_48_e8_32s40w_e5_v8?0lw40l8s32l8
+ ___swift_closure_destructor.113Tm
+ ___swift_closure_destructor.242Tm
+ ___swift_closure_destructor.250Tm
+ _swift_retain_x21
+ _swift_retain_x27
+ _symbolic So12RPConnectionCSgXw
+ _symbolic So12RPConnectionCSgXwz_Xx
+ _symbolic So14CUWriteRequestCSgXw
+ _symbolic So14CUWriteRequestCSgXwz_Xx
- -[RPConnection logConnectionInformation:options:]
- ___swift_closure_destructor.236Tm
- ___swift_closure_destructor.249Tm
- _symbolic So14CUWriteRequestC
CStrings:
+ "_pairVerifyAuthType"
- "%@ Using IP transport over wireless or wired ethernet"
- "%@ Using P2P transport over BLE"
- "%@ Using P2P transport over WiFi"
- "%@ Using unknown transport"
- "-[RPConnection logConnectionInformation:options:]"
- "AudioAccessory1,"
- "AudioAccessory5,"
- "AudioAccessory6,"
- "Received msgID '%@' from %@ with %s\n"
- "Received msgID '%@', XID 0x%X, %d keys, from %@\n"
```
