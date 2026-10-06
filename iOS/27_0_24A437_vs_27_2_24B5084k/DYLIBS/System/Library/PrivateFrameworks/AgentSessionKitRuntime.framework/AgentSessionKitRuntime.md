## AgentSessionKitRuntime

> `/System/Library/PrivateFrameworks/AgentSessionKitRuntime.framework/AgentSessionKitRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x263af0` | `0x2c868c` | **`+0x64b9c`** |
| `__TEXT.__const` | `0x2101c` | `0x2ab2c` | **`+0x9b10`** |
| `__DATA.__bss` | `0x16390` | `0x1e010` | **`+0x7c80`** |
| `__AUTH_CONST.__objc_const` | `0xd530` | `0x11908` | **`+0x43d8`** |
| `__TEXT.__eh_frame` | `0x15660` | `0x181e8` | **`+0x2b88`** |
| `__AUTH.__data` | `0x6548` | `0x8f28` | **`+0x29e0`** |
| `__TEXT.__unwind_info` | `0xb2d8` | `0xd8a0` | **`+0x25c8`** |
| `__TEXT.__swift5_reflstr` | `0x792a` | `0x9e1a` | **`+0x24f0`** |
| `__TEXT.__swift5_fieldmd` | `0x60b8` | `0x7be4` | **`+0x1b2c`** |
| `__TEXT.__swift5_typeref` | `0x86df` | `0xa157` | **`+0x1a78`** |
| `__DATA.__data` | `0x4618` | `0x57f8` | **`+0x11e0`** |
| `__TEXT.__constg_swiftt` | `0x47b4` | `0x58b8` | **`+0x1104`** |
| `__AUTH.__objc_data` | `0x2010` | `0x2d30` | **`+0xd20`** |
| `__AUTH_CONST.__const` | `0x8be0` | `0x9748` | **`+0xb68`** |
| `__TEXT.__swift5_assocty` | `0x1630` | `0x1e10` | **`+0x7e0`** |
| `__TEXT.__swift5_proto` | `0xbcc` | `0xf40` | **`+0x374`** |
| `__DATA_DIRTY.__data` | `0x3d98` | `0x3a68` | **`-0x330`** |
| `__TEXT.__swift5_capture` | `0x26a0` | `0x28f8` | **`+0x258`** |
| `__TEXT.__swift5_types` | `0x518` | `0x684` | **`+0x16c`** |
| `__DATA_CONST.__objc_classlist` | `0x420` | `0x568` | **`+0x148`** |
| `__DATA_CONST.__got` | `0x14d8` | `0x15c0` | **`+0xe8`** |
| `__DATA.__common` | `0x230` | `0x2f8` | **`+0xc8`** |
| `__TEXT.__oslogstring` | `0x9623` | `0x96c3` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x228e` | `0x21fe` | **`-0x90`** |
| `__AUTH_CONST.__auth_got` | `0x25d0` | `0x2580` | **`-0x50`** |
| `__TEXT.__swift_as_cont` | `0x87c` | `0x84c` | **`-0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x808` | `0x7e8` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x720` | `0x738` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x140` | `0x154` | **`+0x14`** |
| `__DATA_CONST.__objc_protolist` | `0x68` | `0x58` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x354` | `0x348` | **`-0xc`** |
| `__TEXT.__swift_as_ret` | `0x358` | `0x34c` | **`-0xc`** |
| `__DATA_CONST.__objc_protorefs` | `0x40` | `0x38` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x2c` | `0x30` | **`+0x4`** |

### Other Changes

```diff

-291.6.0.5.102
+297.6.0.5.0

+  - /System/Library/PrivateFrameworks/GenerativeModelsFoundation.framework/GenerativeModelsFoundation

-  - /System/Library/PrivateFrameworks/MobileKeyBag.framework/MobileKeyBag

-  Functions: 17798
-  Symbols:   314
-  CStrings:  788
+  Functions: 21614
+  Symbols:   308
+  CStrings:  785
Symbols:
- _MKBDeviceUnlockedSinceBoot
- _OBJC_CLASS_$_NSArray
- _dispatch_semaphore_create
- _notify_cancel
- _notify_register_dispatch
- _os_transaction_create
CStrings:
+ "Ensured agent media photo library exists"
+ "Skipping agent media photo library: enhanced Siri is unavailable"
+ "compactSession: session deleted mid-compaction, skipping local reconcile session=%{public}s"
+ "compaction: failed to read mergeable value for %{public}s: %{public}@"
+ "local database has %{public}ld session zones; skipping CloudKit zone discovery"
+ "quota exceeded: holding off sends for %{public}fs (backoff level %{public}ld)"
+ "restored quota hold-off: %{public}fs remaining (backoff level %{public}ld)"
+ "sync-metadata membership check failed for %{public}ld zones: %{public}@"
+ "turn ordering returned %{public}ld of %{public}ld event ids, using canonical order"
+ "turn ordering returned %{public}ld of %{public}ld events, using canonical order"
+ "v29ToV30: moved sync blobs for %{public}ld session(s)"
+ "verifyingSessionScope: dropping event %{public}s — userTurnId matched but belongs to session %{public}s, not the requested %{public}s"
- "Cascade ledger: seed failed for event %{public}s: %@"
- "Cascade ledger: seed failed for session %{public}s: %@"
- "FirstUnlockGate: notify_register_dispatch failed (%{public}u); firing handlers inline"
- "FirstUnlockGate: received first_unlock notification, draining all the waiting handlers"
- "awaitFirstUnlock()"
- "cascade full set donation completed, marker set"
- "com.apple.GenerativeFunctions.agentstored.firstUnlockGate"
- "com.apple.mobile.keybagd.first_unlock"
- "full set donation complete for sessions and events"
- "full set donation failed: %@"
- "full set donation gate timed out after 5 minutes, unblocking donation queue"
- "full set donation seeded ledger with %{public}ld sessions, %{public}ld events"
- "performing one time full set donation of cascade"
- "quota exceeded — holding off sends for %{public}fs (backoff level %{public}ld)"
- "restored %{public}ld session zones from local database"
```
