## IDSFoundation

> `/System/Library/PrivateFrameworks/IDSFoundation.framework/IDSFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x500fa0` | `0x502048` | **`+0x10a8`** |
| `__AUTH_CONST.__cfstring` | `0x2d4c0` | `0x2d680` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x35c1d` | `0x35dad` | **`+0x190`** |
| `__AUTH_CONST.__objc_const` | `0x3f0d8` | `0x3f250` | **`+0x178`** |
| `__TEXT.__oslogstring` | `0x2cf7a` | `0x2d0ba` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x1bf64` | `0x1bfdc` | **`+0x78`** |
| `__AUTH_CONST.__const` | `0x1ab58` | `0x1abb8` | **`+0x60`** |
| `__AUTH.__objc_data` | `0xa468` | `0xa4b8` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x1530` | `0x1570` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xb310` | `0xb350` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x147e0` | `0x14818` | **`+0x38`** |
| `__AUTH_CONST.__objc_intobj` | `0xc48` | `0xc78` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x16784` | `0x167b4` | **`+0x30`** |
| `__DATA.__bss` | `0x67c00` | `0x67c20` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x28f8` | `0x2914` | **`+0x1c`** |
| `__DATA_CONST.__const` | `0x76d0` | `0x76e8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x2a60` | `0x2a68` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x12c0` | `0x12c8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xb30` | `0xb38` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x100` | `0x108` | **`+0x8`** |

### Other Changes

```diff

-2003.200.44.0.0
+2003.200.61.0.0

+  - /usr/lib/libtailspin.dylib

-  Functions: 32051
-  Symbols:   5113
-  CStrings:  8493
+  Functions: 32071
+  Symbols:   5129
+  CStrings:  8514
Symbols:
+ _IDSGroupSessionInEndpointContextDataKey
+ _IDSGroupSessionInviteDeclineReasonKey
+ _IDSSessionRemoteDestinationSameAccountKey
+ _OBJC_CLASS_$_IDSTailspinCapture
+ _OBJC_METACLASS_$_IDSTailspinCapture
+ _TSPDumpOptions_CollectAriadnePlists
+ _TSPDumpOptions_CollectOsLogs
+ _TSPDumpOptions_CollectOsSignposts
+ _TSPDumpOptions_CollectTrials
+ _TSPDumpOptions_MinTraceBufferDurationSec
+ _TSPDumpOptions_ReasonString
+ _TSPDumpOptions_ScrubOutput
+ _TSPDumpOptions_Symbolicate
+ _TSPDumpOptions_TargetPID
+ _os_unfair_lock_trylock
+ _tailspin_dump_output_with_options_sync
CStrings:
+ "%@_%@.tailspin"
+ ".tailspin"
+ "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789"
+ "B"
+ "IDS detected issue with %@"
+ "IDSTailspinCapture: dump failed for %{public}@ after %.2fs"
+ "IDSTailspinCapture: failed to create %{public}@: %{errno}d. Suppressing further open failures."
+ "IDSTailspinCapture: saved %{public}@ in %.2fs"
+ "IDSTailspinCapture: unable to create %{public}@: %{public}@"
+ "IDSTailspinCapture: unable to remove %{public}@: %{public}@"
+ "IDSTailspinCaptureEnabled"
+ "IDSTailspinCaptureMinRestSeconds"
+ "Library/IdentityServices/Tailspins"
+ "Notes Voicenotes"
+ "com.apple.private.alloy.notes.voicenotes"
+ "en_US_POSIX"
+ "gs-invite-decline-reason-key"
+ "ids.tailspin"
+ "in-endpoint-context-data-key"
+ "remote-destination-same-account"
+ "yyyyMMdd_HHmmss"
```
