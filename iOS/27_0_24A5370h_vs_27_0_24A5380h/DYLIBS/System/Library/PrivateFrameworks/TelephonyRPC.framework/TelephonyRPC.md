## TelephonyRPC

> `/System/Library/PrivateFrameworks/TelephonyRPC.framework/TelephonyRPC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ccd4` | `0x1cd00` | **`+0x2c`** |
| `__AUTH_CONST.__objc_const` | `0x1e80` | `0x1e60` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xc08` | `0xc18` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0xb43` | `0xb53` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x790` | `0x798` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xc4` | `0xc0` | **`-0x4`** |

### Other Changes

```diff

-1155.0.0.0.0
+1157.0.0.0.0

-  Symbols:   973
+  Symbols:   972
Symbols:
- _OBJC_IVAR_$_NPHVMSyncSessionManager._cancel
Functions:
~ -[NPHVMSyncSessionManager syncSession:enqueueChanges:error:] : 1276 -> 1280
~ -[NPHVMSyncSessionManager isCancelled] : 8 -> 12
~ -[VoicemailCompanionReplication handleSIGTERM] : 488 -> 524
CStrings:
+ "%s - exiting"
+ "%s - timed out waiting for sync to cancel; exiting anyway"
- "%s - done waiting"
- "%s - sync no longer in progress; exiting"
```
