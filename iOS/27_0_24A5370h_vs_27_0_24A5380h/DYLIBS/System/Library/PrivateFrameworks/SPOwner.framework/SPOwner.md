## SPOwner

> `/System/Library/PrivateFrameworks/SPOwner.framework/SPOwner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x754f4` | `0x76bcc` | **`+0x16d8`** |
| `__AUTH.__objc_data` | `0x1690` | `0x48` | **`-0x1648`** |
| `__DATA_DIRTY.__objc_data` | `0x1450` | `0x2a98` | **`+0x1648`** |
| `__TEXT.__oslogstring` | `0x76c8` | `0x7ed8` | **`+0x810`** |
| `__AUTH_CONST.__objc_const` | `0x14048` | `0x14170` | **`+0x128`** |
| `__TEXT.__objc_methlist` | `0xba14` | `0xbb14` | **`+0x100`** |
| `__AUTH.__data` | `0xf0` | `—` | **`-0xf0`** |
| `__DATA_DIRTY.__data` | `0xb8` | `0x1a8` | **`+0xf0`** |
| `__TEXT.__gcc_except_tab` | `0x14d8` | `0x157c` | **`+0xa4`** |
| `__DATA_CONST.__objc_selrefs` | `0x3cf0` | `0x3d90` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x2130` | `0x21a8` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x26c8` | `0x2738` | **`+0x70`** |
| `__DATA_CONST.__got` | `0x5c8` | `0x5f8` | **`+0x30`** |
| `__TEXT.__const` | `0x588` | `0x5b8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x6a19` | `0x6a49` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0xc18` | `0xbf8` | **`-0x20`** |
| `__DATA.__objc_ivar` | `0xee4` | `0xefc` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x678` | `0x688` | **`+0x10`** |
| `__DATA.__bss` | `0x810` | `0x800` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x340` | `0x350` | **`+0x10`** |

### Other Changes

```diff

-448.30.6.7.2
+449.30.6.14.8

-  Functions: 4359
-  Symbols:   7279
-  CStrings:  1543
+  Functions: 4390
+  Symbols:   7318
+  CStrings:  1570
Symbols:
+ -[SPBeaconManager simpleBeaconSubscribersInfoWithCompletion:]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface armDarwinReconnectObserver]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface armReconnectWatchdog_locked]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface buildSessionForServiceName:]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface cancelReconnectWatchdog]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface isSPDCurrentlyRunning]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface machServiceName]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface performProbeGatedRecoveryWithReason:]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface reconnectAttempt]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface reconnectGeneration]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface reconnectInProgress]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface reconnectWatchdogTimer]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface setReconnectAttempt:]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface setReconnectGeneration:]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface setReconnectInProgress:]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface setReconnectWatchdogTimer:]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface setStopped:]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface setSuppressNextInvalidation:]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface stopped]
+ -[SPBeaconManagerSimpleBeaconUpdateInterface suppressNextInvalidation]
+ GCC_except_table45
+ _OBJC_IVAR_$_SPBeaconManagerSimpleBeaconUpdateInterface._reconnectAttempt
+ _OBJC_IVAR_$_SPBeaconManagerSimpleBeaconUpdateInterface._reconnectGeneration
+ _OBJC_IVAR_$_SPBeaconManagerSimpleBeaconUpdateInterface._reconnectInProgress
+ _OBJC_IVAR_$_SPBeaconManagerSimpleBeaconUpdateInterface._reconnectWatchdogTimer
+ _OBJC_IVAR_$_SPBeaconManagerSimpleBeaconUpdateInterface._stopped
+ _OBJC_IVAR_$_SPBeaconManagerSimpleBeaconUpdateInterface._suppressNextInvalidation
+ ___61-[SPBeaconManager simpleBeaconSubscribersInfoWithCompletion:]_block_invoke
+ ___66-[SPBeaconManagerSimpleBeaconUpdateInterface invalidationHandler:]_block_invoke
+ ___72-[SPBeaconManagerSimpleBeaconUpdateInterface armDarwinReconnectObserver]_block_invoke
+ ___73-[SPBeaconManagerSimpleBeaconUpdateInterface armReconnectWatchdog_locked]_block_invoke
+ ___73-[SPBeaconManagerSimpleBeaconUpdateInterface buildSessionForServiceName:]_block_invoke
+ ___73-[SPBeaconManagerSimpleBeaconUpdateInterface buildSessionForServiceName:]_block_invoke_2
+ ___82-[SPBeaconManagerSimpleBeaconUpdateInterface performProbeGatedRecoveryWithReason:]_block_invoke
+ ___86-[SPBeaconManagerSimpleBeaconUpdateInterface stopUpdatingSimpleBeaconsWithCompletion:]_block_invoke_2
+ ___block_descriptor_48_e8_32w_e20_v20?0B8"NSError"12lw32l8
+ ___block_descriptor_56_e8_32s40r48r_e5_v8?0lr40l8s32l8r48l8
+ ___block_descriptor_57_e8_32s40s_e5_v8?0ls32l8s40l8
+ _bootstrap_look_up3
+ _bootstrap_port
+ _mach_port_deallocate
+ _mach_task_self_
- ___51-[SPBeaconManagerSimpleBeaconUpdateInterface proxy]_block_invoke
- ___51-[SPBeaconManagerSimpleBeaconUpdateInterface proxy]_block_invoke_2
- ___66-[SPBeaconManagerSimpleBeaconUpdateInterface interruptionHandler:]_block_invoke
CStrings:
+ "#sbreconnect completion-ignored-stale self=%{public}p stale=%{public}lu current=%{public}lu"
+ "#sbreconnect handleReconnection begin self=%{public}p"
+ "#sbreconnect handleReconnection retry-failed self=%{public}p attempt=%{public}lu error=%@ (arming observer + one-shot reprobe)"
+ "#sbreconnect handleReconnection retry-success self=%{public}p attempt=%{public}lu"
+ "#sbreconnect interrupt-noop self=%{public}p (session already nil — no recovery scheduled)"
+ "#sbreconnect interrupted self=%{public}p connection=%{public}@ hasDiffBlock=%{public}d sessionNonNil=%{public}d willArmObserver=%{public}d"
+ "#sbreconnect invalidated self=%{public}p connection=%{public}@ (probe-gated recovery)"
+ "#sbreconnect invalidated-after-stop self=%{public}p (no recovery scheduled)"
+ "#sbreconnect invalidation-during-reconnect cleared in-progress latch self=%{public}p attempt=%{public}lu"
+ "#sbreconnect invalidation-suppressed self=%{public}p connection=%{public}@ (framework-initiated)"
+ "#sbreconnect observer-rearmed-for-attempt self=%{public}p attempt=%{public}lu"
+ "#sbreconnect probe self=%{public}p result=alive"
+ "#sbreconnect probe self=%{public}p result=dormant kr=%{public}d"
+ "#sbreconnect reconnect-skipped-already-in-progress self=%{public}p (handleReconnection)"
+ "#sbreconnect reconnect-skipped-stopped self=%{public}p (handleReconnection)"
+ "#sbreconnect reconnect-watchdog-armed self=%{public}p attempt=%{public}lu delay=%{public}.1f"
+ "#sbreconnect reconnect-watchdog-fired self=%{public}p attempt=%{public}lu (clearing latch + probing)"
+ "#sbreconnect recovery-decision self=%{public}p reason=%{public}s branch=reconnect-now (SPD alive)"
+ "#sbreconnect recovery-decision self=%{public}p reason=%{public}s branch=wait-for-darwin (SPD dormant)"
+ "#sbreconnect remove-observers self=%{public}p (typically handleReconnection success or dealloc)"
+ "#sbreconnect session-rebuilt self=%{public}p attempt=%{public}lu"
+ "#sbreconnect session-start completion self=%{public}p success=%{public}d"
+ "#sbreconnect session-start completion self=%{public}p success=%{public}d error=%@"
+ "#sbreconnect session-start self=%{public}p contextClass=%{public}@ sendInitial=%{public}d"
+ "error-retry"
+ "interrupt"
+ "invalidate"
+ "watchdog"
- "Failed reconnecting to daemon after retry: %@."
```
