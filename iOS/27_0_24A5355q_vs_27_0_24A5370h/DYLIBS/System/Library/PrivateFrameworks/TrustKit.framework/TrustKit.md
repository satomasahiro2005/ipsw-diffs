## TrustKit

> `/System/Library/PrivateFrameworks/TrustKit.framework/TrustKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c528` | `0x3bb2c` | **`-0x9fc`** |
| `__TEXT.__eh_frame` | `0x2bf8` | `0x2a94` | **`-0x164`** |
| `__AUTH_CONST.__const` | `0x3290` | `0x31c8` | **`-0xc8`** |
| `__TEXT.__swift5_reflstr` | `0x14b5` | `0x1425` | **`-0x90`** |
| `__DATA.__bss` | `0x4f00` | `0x4f80` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x204` | `0x184` | **`-0x80`** |
| `__TEXT.__unwind_info` | `0x14f8` | `0x1480` | **`-0x78`** |
| `__TEXT.__constg_swiftt` | `0x1c10` | `0x1c80` | **`+0x70`** |
| `__TEXT.__cstring` | `0x2a39` | `0x2aa9` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x1014` | `0xfcc` | **`-0x48`** |
| `__TEXT.__swift_as_cont` | `0x2c8` | `0x288` | **`-0x40`** |
| `__AUTH_CONST.__objc_const` | `0x2150` | `0x2170` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x1b04` | `0x1b20` | **`+0x1c`** |
| `__TEXT.__const` | `0x4638` | `0x4628` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0xd4` | `0xc8` | **`-0xc`** |
| `__TEXT.__swift_as_ret` | `0x110` | `0x104` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0xa08` | `0xa00` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x2e4` | `0x2e8` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x6c` | `0x70` | **`+0x4`** |

### Other Changes

```diff

-89.0.0.0.0
+92.0.0.0.0

-  Functions: 1586
-  Symbols:   822
-  CStrings:  230
+  Functions: 1558
+  Symbols:   817
+  CStrings:  231
Symbols:
+ ___swift_closure_destructor.65Tm
+ _symbolic $s8TrustKit22DaemonAnalyticsManagerC7BMEventP
+ _symbolic Sb______pIeghHrzo_ s5ErrorP
+ _symbolic ShySSG
+ _symbolic ___________pIeghHrzo_ 8TrustKit20TKDecisioningServiceC23TKSpamDecisioningOutputV s5ErrorP
+ _symbolic _____yypG s23_ContiguousArrayStorageC
+ _symbolic yt______pIeghHrzo_ s5ErrorP
- ___swift_closure_destructor.72Tm
- _swift_retain_n
- _swift_retain_x23
- _swift_retain_x8
- _symbolic ShySSGSg
- _symbolic _____SgSg 8TrustKit18AttestationManagerC
- _symbolic x______pIegHrzo_z_Sb_lXX s5ErrorP
- _symbolic x______pIegHrzo_z_______lXX s5ErrorP 8TrustKit20TKDecisioningServiceC23TKSpamDecisioningOutputV
- _symbolic x______pIegHrzo_z_yt_lXX s5ErrorP
- _symbolic x______pRi_zRi0_zlySbIsegHrzo_ s5ErrorP
- _symbolic x______pRi_zRi0_zly_____IsegHrzo_ s5ErrorP 8TrustKit20TKDecisioningServiceC23TKSpamDecisioningOutputV
- _symbolic x______pRi_zRi0_zlyytIsegHrzo_ s5ErrorP
CStrings:
+ "Invalid report content. { missingField=message-text }"
+ "Skipping message text validation for message type. { messsageType="
- "Invalid type and content."
```
