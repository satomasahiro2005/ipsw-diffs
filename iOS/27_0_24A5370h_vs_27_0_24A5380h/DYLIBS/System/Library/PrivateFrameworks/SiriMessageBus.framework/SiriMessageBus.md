## SiriMessageBus

> `/System/Library/PrivateFrameworks/SiriMessageBus.framework/SiriMessageBus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x107f10` | `0x10a540` | **`+0x2630`** |
| `__DATA_DIRTY.__data` | `0x26d8` | `0x2e38` | **`+0x760`** |
| `__TEXT.__unwind_info` | `0x3a60` | `0x3f68` | **`+0x508`** |
| `__AUTH.__data` | `0xa08` | `0x5a0` | **`-0x468`** |
| `__DATA.__data` | `0x1398` | `0x1158` | **`-0x240`** |
| `__TEXT.__oslogstring` | `0x8d13` | `0x8ea3` | **`+0x190`** |
| `__TEXT.__eh_frame` | `0x96b8` | `0x9840` | **`+0x188`** |
| `__AUTH_CONST.__const` | `0x63c8` | `0x64c0` | **`+0xf8`** |
| `__TEXT.__const` | `0x5420` | `0x54f0` | **`+0xd0`** |
| `__DATA.__bss` | `0x2d10` | `0x2c90` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0xa00` | `0xa80` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x18f0` | `0x1954` | **`+0x64`** |
| `__TEXT.__swift5_typeref` | `0x2235` | `0x2299` | **`+0x64`** |
| `__AUTH.__objc_data` | `0x170` | `0x120` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x5b0` | `0x600` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x2618` | `0x2658` | **`+0x40`** |
| `__DATA.__common` | `0x40` | `0x20` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x18cf` | `0x18ef` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xee0` | `0xef8` | **`+0x18`** |
| `__DATA_DIRTY.__common` | `0x1c0` | `0x1d8` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x750` | `0x764` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x2c4` | `0x2d8` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x44c` | `0x460` | **`+0x14`** |
| `__TEXT.__swift5_fieldmd` | `0x134c` | `0x1358` | **`+0xc`** |
| `__TEXT.__constg_swiftt` | `0x231c` | `0x2324` | **`+0x8`** |

### Other Changes

```diff

-3600.54.6.0.0
+3600.54.13.0.0

+  - /System/Library/Frameworks/IOSurface.framework/IOSurface

-  Functions: 5901
-  Symbols:   1843
-  CStrings:  775
+  Functions: 5967
+  Symbols:   1847
+  CStrings:  780
Symbols:
+ _OBJC_CLASS_$_IOSurface
+ ___swift_closure_destructor.384Tm
+ _symbolic SS3key______5valuet 22IntelligenceFlowShared16CodableIOSurfaceV
+ _symbolic _____Sg 22IntelligenceFlowShared17InvocationContextV
+ _symbolic ______p 14SiriMessageBus29IntelligenceFlowProxyProtocolP
+ _symbolic _____ySSSo9IOSurfaceCG s17_NativeDictionaryV
+ _symbolic _____yqd__GSgXw 14SiriMessageBus33IntelligenceFlowGestureControllerC
+ _symbolic _____yqd__GSgXwz_x_qd_______RzADRd__r__lXX 14SiriMessageBus33IntelligenceFlowGestureControllerC AA0defG6TraitsP
+ _symbolic ytSg
+ _symbolic ytSgIeAgHr_
- ___swift_closure_destructor.387Tm
- _get_type_metadata 15Synchronization5MutexVy14SiriMessageBus29IntelligenceFlowProxyProtocol_pSgG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic G1R1_
- _symbolic _____yqd__G 14SiriMessageBus33IntelligenceFlowGestureControllerC
- _symbolic _____yx_qd__G 14SiriMessageBus33IntelligenceFlowGestureControllerC0F8Observer33_209F065FD1C278E5208B2B4CC198DEE2LLC
CStrings:
+ "[SerialAceExecutor]: Session invalidated. Skipping SystemResponseRendered."
+ "[SerialAceExecutor]: Task cancelled. Skipping handleAceCommandResult."
+ "[SerialAceExecutor]: Task cancelled. Skipping post-submit operations."
+ "[SerialAceExecutor]: Task cancelled. Skipping sendGeneratedSnippetResponse."
+ "[VCC-surface] SRD wire-decode key=%{public}s FAILED to recover IOSurface"
```
