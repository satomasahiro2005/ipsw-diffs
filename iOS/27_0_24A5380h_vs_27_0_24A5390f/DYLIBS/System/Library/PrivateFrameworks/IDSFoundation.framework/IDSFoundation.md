## IDSFoundation

> `/System/Library/PrivateFrameworks/IDSFoundation.framework/IDSFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e6b20` | `0x4ebbf4` | **`+0x50d4`** |
| `__DATA.__bss` | `0x65a60` | `0x66270` | **`+0x810`** |
| `__TEXT.__const` | `0x3f110` | `0x3f720` | **`+0x610`** |
| `__TEXT.__eh_frame` | `0x160d4` | `0x164a4` | **`+0x3d0`** |
| `__TEXT.__gcc_except_tab` | `0xb880` | `0xbb14` | **`+0x294`** |
| `__AUTH_CONST.__const` | `0x19e18` | `0x1a0a0` | **`+0x288`** |
| `__TEXT.__cstring` | `0x3477d` | `0x3499d` | **`+0x220`** |
| `__TEXT.__unwind_info` | `0x141e8` | `0x14360` | **`+0x178`** |
| `__AUTH_CONST.__cfstring` | `0x2ca40` | `0x2cb80` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0xb568` | `0xb67e` | **`+0x116`** |
| `__AUTH_CONST.__objc_const` | `0x3e938` | `0x3ea40` | **`+0x108`** |
| `__DATA.__data` | `0xf190` | `0xf258` | **`+0xc8`** |
| `__TEXT.__constg_swiftt` | `0xc6e0` | `0xc798` | **`+0xb8`** |
| `__DATA_CONST.__const` | `0x7518` | `0x75c8` | **`+0xb0`** |
| `__TEXT.__swift5_fieldmd` | `0xb5c8` | `0xb674` | **`+0xac`** |
| `__AUTH.__data` | `0xb000` | `0xb0a8` | **`+0xa8`** |
| `__TEXT.__oslogstring` | `0x2b88a` | `0x2b92a` | **`+0xa0`** |
| `__TEXT.__swift5_reflstr` | `0x6ab6` | `0x6b36` | **`+0x80`** |
| `__TEXT.__swift5_assocty` | `0x910` | `0x958` | **`+0x48`** |
| `__TEXT.__swift5_proto` | `0x339c` | `0x33dc` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x29f0` | `0x2a28` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x1ba5c` | `0x1ba8c` | **`+0x30`** |
| `__TEXT.__swift5_acfuncs` | `0x1a4` | `0x1cc` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x5dc` | `0x600` | **`+0x24`** |
| `__DATA_CONST.__got` | `0x14e0` | `0x1500` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xb088` | `0xb0a0` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x394` | `0x3ac` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x31c` | `0x330` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0xe98` | `0xea8` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x12a8` | `0x12b0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x289c` | `0x28a0` | **`+0x4`** |

### Other Changes

```diff

-1998.100.2.0.0
+2000.100.2.2.1

-  Functions: 31551
-  Symbols:   5086
-  CStrings:  8352
+  Functions: 31643
+  Symbols:   5088
+  CStrings:  8370
Symbols:
+ _IDSGroupSessionCapabilityTerminateAutomatically
+ _OBJC_CLASS_$_OS_dispatch_queue_serial
CStrings:
+ "%-3s connection %@ [C%llu%@] (%s)"
+ "%-3s connection [C%llu%@] (%s)"
+ "%02hhx"
+ "%@ P2P QPod TLE keys: %{sensitive}@"
+ "<IDSNWConnectionInfo C%llu isQUICPod=%@ qpod=%@>"
+ "<IDSNWQPodParameters role=%s clientCID=0x%08x serverCID=0x%08x clientSecret=%@ serverSecret=%@>"
+ "<none>"
+ "Server"
+ "avcPlain"
+ "com.apple.ids.primary-queue-actor"
+ "logP2PTLEKeys"
+ "mirageHandshake"
+ "participantData"
+ "participantInfo"
+ "skip stale allocbind timeout for %@, GL state [%s]."
+ "skip stale allocbind timeout for %@, generation %u != current %u."
+ "terminateAutomatically"
+ "updateOutgoingBlob(sessionID:blob:)"
```
