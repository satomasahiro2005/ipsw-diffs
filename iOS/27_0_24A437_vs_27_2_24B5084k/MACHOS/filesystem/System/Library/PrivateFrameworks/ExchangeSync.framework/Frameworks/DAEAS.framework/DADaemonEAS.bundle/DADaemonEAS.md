## DADaemonEAS

> `/System/Library/PrivateFrameworks/ExchangeSync.framework/Frameworks/DAEAS.framework/DADaemonEAS.bundle/DADaemonEAS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x45f98` | `0x46fb8` | **`+0x1020`** |
| `__TEXT.__oslogstring` | `0x8c45` | `0x90c5` | **`+0x480`** |
| `__TEXT.__objc_methname` | `0x95a7` | `0x978f` | **`+0x1e8`** |
| `__TEXT.__objc_stubs` | `0x88a0` | `0x89e0` | **`+0x140`** |
| `__TEXT.__cstring` | `0x11bb` | `0x12ca` | **`+0x10f`** |
| `__DATA_CONST.__const` | `0x550` | `0x5c8` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x18e8` | `0x1960` | **`+0x78`** |
| `__DATA.__objc_selrefs` | `0x25a8` | `0x2608` | **`+0x60`** |
| `__DATA_CONST.__cfstring` | `0xf60` | `0xfc0` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0x1121` | `0x1165` | **`+0x44`** |
| `__TEXT.__unwind_info` | `0x6b8` | `0x6f8` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x1060` | `0x1090` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0xa44` | `0xa74` | **`+0x30`** |
| `__DATA.__objc_const` | `0x19e8` | `0x1a08` | **`+0x20`** |
| `__TEXT.__const` | `0x160` | `0x180` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x840` | `0x858` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x638` | `0x640` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xe4` | `0xe8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-2079.0.1.0.0
+2079.200.31.0.0

-  Functions: 539
-  Symbols:   529
-  CStrings:  2178
+  Functions: 553
+  Symbols:   534
+  CStrings:  2216
Symbols:
+ OBJC_IVAR_$_ASAccount._serverBackoffUntil
+ OBJC_IVAR_$_ASDaemonAccount._hasScheduledServerBackoffDrain
+ _CalCalendarIsAffectingAvailability
+ _CalCalendarSetIsAffectingAvailability
+ _arc4random_uniform
CStrings:
+ "#AccountID: %{public}@ ServerBackoffDrain: window ended, resuming sync and push"
+ "#EASTraffic #AccountID: %{public}@ Server throttle extended (%{public}@) to %.0fs, until %{public}@"
+ "#EASTraffic #AccountID: %{public}@ Server throttled us (%{public}@); backing off %.0fs, until %{public}@"
+ "%s.%@"
+ "%{public}s"
+ "-[ASAgent(FolderContentsSync) _fireWaitingFolderItemSyncRequestsLimit:]"
+ "503"
+ "Deferring the ping XPC refire from %llds to %llds; account is in a server-throttle backoff."
+ "Draining held folder syncs after server backoff; probing with one folder before releasing the rest."
+ "Dropping folder item sync request %@; its dataclass isn't item-synced here."
+ "Holding folder item sync requests; server has throttled us. They will drain when the backoff window ends."
+ "Not arming a ping timer during a server-throttle backoff; deferring the ping XPC refire past the window instead."
+ "Not going to ping; account is in a server-throttle backoff. Deferring the ping XPC refire past the window instead of dropping the reissue."
+ "Ping hit a server throttle; not reissuing or reconnecting until backoff drains."
+ "PingDelayXPC: Skipping XPC state %u for '%{public}@'"
+ "ServerBackoffDrain: Unregister XPC activity"
+ "ServerBackoffDrain: Unregister XPC activity (backoff cleared)"
+ "ServerBackoffDrain: XPC activity state %u (not run); awaiting RUN"
+ "ServerBackoffDrain: registered XPC activity in %.0fs (+%llds jitter)"
+ "ServerBackoffDrain: window extended, rescheduling in %.0fs"
+ "_asyncUnregisterXPCActivity:logMessage:"
+ "_fireWaitingFolderItemSyncRequestsLimit:"
+ "_hasScheduledServerBackoffDrain"
+ "_pingDelayActivityIdentifier"
+ "_registerOneShotXPCActivityWithIdentifier:delay:firedHandler:registeredLog:"
+ "_resetServerBackoffStateLocked"
+ "_serverBackoffDrainActivityIdentifier"
+ "_serverBackoffDrainFired"
+ "clearServerBackoff"
+ "com.apple.dataaccess.exchangeactivesync.EASServerThrottled"
+ "com.apple.exchangesyncd.serverbackoffdrain"
+ "isInServerBackoff"
+ "recordServerThrottleTelemetryForNewWindow:reason:delaySeconds:until:"
+ "resumeSyncRequestsAfterServerBackoff"
+ "scheduleServerBackoffDrainAfter:"
+ "v16@?0q8"
+ "v24@0:8d16"
+ "v32@0:8@16r*24"
+ "v44@0:8B16@20d28@36"
+ "v48@0:8@16q24@?32@?40"
- "-[ASAgent(FolderContentsSync) _fireWaitingFolderItemSyncRequests]"
- "PingDelayXPC: Skipping XPC state state %u for '%{public}s'"
```
