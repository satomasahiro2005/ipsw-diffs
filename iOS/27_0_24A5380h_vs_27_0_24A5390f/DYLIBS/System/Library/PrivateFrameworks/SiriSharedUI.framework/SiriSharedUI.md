## SiriSharedUI

> `/System/Library/PrivateFrameworks/SiriSharedUI.framework/SiriSharedUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x165d04` | `0x167fc0` | **`+0x22bc`** |
| `__TEXT.__cstring` | `0x9aaa` | `0x9c3a` | **`+0x190`** |
| `__TEXT.__const` | `0x8df4` | `0x8eb4` | **`+0xc0`** |
| `__AUTH_CONST.__auth_got` | `0x23a8` | `0x2428` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x5f18` | `0x5f98` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x2c98` | `0x2cf8` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x4720` | `0x476c` | **`+0x4c`** |
| `__DATA_CONST.__objc_selrefs` | `0x5310` | `0x5358` | **`+0x48`** |
| `__DATA_DIRTY.__objc_data` | `0xcc8` | `0xd08` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x889c` | `0x88dc` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x47d0` | `0x4810` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0xf408` | `0xf438` | **`+0x30`** |
| `__DATA.__data` | `0x58a0` | `0x58d0` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x36c6` | `0x36f6` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x135a2` | `0x135d2` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x16d8` | `0x1700` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x26fc` | `0x2724` | **`+0x28`** |
| `__TEXT.__swift5_builtin` | `0x104` | `0x118` | **`+0x14`** |
| `__AUTH.__objc_data` | `0x4878` | `0x4868` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0x23c` | `0x240` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xf8` | `0xfc` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xac` | `0xb0` | **`+0x4`** |

### Other Changes

```diff

-3600.55.26.0.0
+3600.55.30.0.0

-  Functions: 7433
-  Symbols:   5362
-  CStrings:  1030
+  Functions: 7459
+  Symbols:   5373
+  CStrings:  1039
Symbols:
+ +[SiriSharedUIReplayUtilityWrapper startReplayCaptureToPath:]
+ +[SiriSharedUIReplayUtilityWrapper stopReplayCapture]
+ _OBJC_CLASS_$_NSFileHandle
+ ___swift_closure_destructor.117Tm
+ ___swift_closure_destructor.138Tm
+ ___swift_memcpy4_4
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _symbolic _____ So16os_unfair_lock_sV
+ _symbolic _____ s6UInt32V
+ _symbolic ______p 10Foundation15ContiguousBytesP
+ _symbolic _____y_____SgG 2os21OSAllocatedUnfairLockV 18SiriSuggestionsAPI0eF6FacadeC
+ _symbolic _____y_____Sg_____G s13ManagedBufferCsRi__rlE 18SiriSuggestionsAPI0cD6FacadeC So16os_unfair_lock_sV
+ _type_layout_string So16os_unfair_lock_sV
- ___swift_closure_destructor.114Tm
- ___swift_closure_destructor.133Tm
- _symbolic _____Sg 18SiriSuggestionsAPI0aB6FacadeC
CStrings:
+ "#Replay: startReplayCapture -> "
+ "#Replay: stopReplayCapture archived to "
+ ". Note: the auto-record pref is also ON, "
+ "Capture already in progress — ignoring startReplayCapture"
+ "No named capture in progress"
+ "This command records to "
+ "so Siri is additionally capturing files to the auto-record folder.\n"
+ "startReplayCapture(filePath:)"
+ "stopReplayCapture()"
```
