## CallsAppUI

> `/System/Library/PrivateFrameworks/CallsAppUI.framework/CallsAppUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x102500` | `0x104f04` | **`+0x2a04`** |
| `__DATA.__bss` | `0x26c8` | `0x2648` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x2c80` | `0x2d00` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x5c18` | `0x5c90` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0x1944` | `0x19a4` | **`+0x60`** |
| `__DATA.__data` | `0x2cd8` | `0x2d28` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x3d40` | `0x3d80` | **`+0x40`** |
| `__DATA_DIRTY.__data` | `0x4520` | `0x44f0` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0xe934` | `0xe95e` | **`+0x2a`** |
| `__TEXT.__swift5_capture` | `0x2244` | `0x2268` | **`+0x24`** |
| `__AUTH_CONST.__auth_got` | `0x2b20` | `0x2b40` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x81a8` | `0x81c8` | **`+0x20`** |
| `__TEXT.__const` | `0x8b14` | `0x8af4` | **`-0x20`** |
| `__TEXT.__cstring` | `0x1c1b` | `0x1bfb` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x2b1c` | `0x2b3c` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x3720` | `0x3738` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1678` | `0x1688` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2330` | `0x233c` | **`+0xc`** |
| `__DATA.__common` | `0x188` | `0x190` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x41a4` | `0x41ac` | **`+0x8`** |

### Other Changes

```diff

-156.200.70.2.2
+156.200.88.2.3

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 5069
-  Symbols:   2320
+  Functions: 5087
+  Symbols:   2325
Symbols:
+ ___swift_closure_destructor.105Tm
+ ___swift_closure_destructor.158Tm
+ ___swift_closure_destructor.74Tm
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_release_x12
+ _symbolic Shy_____G 10Foundation4UUIDV
+ _symbolic _____yShy_____GG 15Synchronization5MutexVAARi_zrlE 10Foundation4UUIDV
+ _symbolic _____y_____G s11_SetStorageC 10Foundation4UUIDV
- ___swift_closure_destructor.111Tm
- ___swift_closure_destructor.149Tm
- ___swift_closure_destructor.65Tm
- ___swift_closure_destructor.82Tm
CStrings:
+ "Not reporting message with recordUUID %s as %{public}s because a report is already in flight"
+ "VOICEMAIL_REPORT_SPAM_CARRIER_MESSAGE"
+ "VOICEMAIL_UNMARK_SPAM"
+ "checkmark.bubble.fill"
- "BLOCKED_VOICEMAILS"
- "VOICEMAIL_BLOCK_AND_REPORT_SPAM_MESSAGE"
- "VOICEMAIL_REPORT_NOT_SPAM"
- "hand.thumbsup.fill"
```
