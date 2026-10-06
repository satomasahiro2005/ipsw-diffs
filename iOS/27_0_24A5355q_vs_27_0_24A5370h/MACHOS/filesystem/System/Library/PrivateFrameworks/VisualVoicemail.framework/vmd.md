## vmd

> `/System/Library/PrivateFrameworks/VisualVoicemail.framework/vmd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb80b0` | `0xb97cc` | **`+0x171c`** |
| `__TEXT.__objc_methname` | `0x12351` | `0x1262f` | **`+0x2de`** |
| `__TEXT.__objc_stubs` | `0xdcc0` | `0xdf60` | **`+0x2a0`** |
| `__DATA.__objc_const` | `0x12108` | `0x123a0` | **`+0x298`** |
| `__TEXT.__oslogstring` | `0x15ac7` | `0x15d57` | **`+0x290`** |
| `__TEXT.__objc_methtype` | `0x32cf` | `0x34e0` | **`+0x211`** |
| `__TEXT.__gcc_except_tab` | `0xc750` | `0xc920` | **`+0x1d0`** |
| `__TEXT.__objc_methlist` | `0x7984` | `0x7b1c` | **`+0x198`** |
| `__TEXT.__unwind_info` | `0x3e90` | `0x3fa0` | **`+0x110`** |
| `__DATA.__objc_selrefs` | `0x4648` | `0x46f0` | **`+0xa8`** |
| `__TEXT.__cstring` | `0x471a` | `0x478a` | **`+0x70`** |
| `__DATA.__data` | `0x11c0` | `0x1220` | **`+0x60`** |
| `__DATA_CONST.__cfstring` | `0x5480` | `0x54e0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x3370` | `0x33c8` | **`+0x58`** |
| `__DATA.__objc_data` | `0x1cd0` | `0x1d20` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x1870` | `0x18b0` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x770` | `0x798` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0xc50` | `0xc70` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0xdea` | `0xe0a` | **`+0x20`** |
| `__DATA.__bss` | `0x610` | `0x620` | **`+0x10`** |
| `__TEXT.__const` | `0x512` | `0x522` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x2d8` | `0x2e0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x158` | `0x160` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x2b0` | `0x2b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-949.0.0.0.0
+952.0.0.0.0

-  Functions: 3480
-  Symbols:   706
-  CStrings:  5734
+  Functions: 3522
+  Symbols:   710
+  CStrings:  5795
Symbols:
+ __ZN3ctu12TimerService23createPeriodicTimerImplENSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEENS1_5tupleIJNS_8TimeTypeENS1_6chrono8durationIxNS1_5ratioILl1ELl1000000EEEEEEEE11qos_class_tU13block_pointerFvvE
+ __ZN3ctu20DispatchTimerService6createEv
+ __ZNK3ctu12TimerService19throwIfPeriodIsZeroERKNSt3__15tupleIJNS_8TimeTypeENS1_6chrono8durationIxNS1_5ratioILl1ELl1000000EEEEEEEE
+ __ZNSt3__16chrono12steady_clock3nowEv
CStrings:
+ "%s#I %s%sPeriodic polling timer expired, scheduling sync"
+ "%s#I %s%sStarting periodic polling timer with interval %lu min"
+ "%s#I %s%sStopping periodic polling timer"
+ "%s#I %s%sSync already in progress, skipping periodic poll"
+ "%s#I %s%sUpdating periodic polling, carrier bundle changed"
+ "%s#I %s%sUpdating periodic polling, mode=%s"
+ "%s#I %s%sUpdating periodic polling, subscribed=%s"
+ "%s#I %s%sVMPeriodicTimer %p created with delegate %p"
+ "%s#I %s%sVMPeriodicTimer %p deleted"
+ "%s#I %s%sVMPeriodicTimer %p started with interval %lu sec"
+ "%s#I %s%sVMPeriodicTimer %p stopped"
+ "%s#I %s%s[%c] Next retry interval (%lu s) >= polling time remaining (%lu s), polling will handle recovery"
+ "%s#I %s%s[%c] Scheduling delayed sync in %lu s, iteration %d"
+ "@\"<VMPeriodicTimerDelegate>\""
+ "@\"VMPeriodicTimer\""
+ "EnablePeriodicPolling"
+ "PeriodicPolling"
+ "PeriodicPollingInterval"
+ "T@\"<VMPeriodicTimerDelegate>\",W,N,V_delegate"
+ "T@\"VMPeriodicTimer\",&,N,V_periodicPollingTimer"
+ "TB,N,V_periodicPollingActive"
+ "TB,R,N,GisPeriodicPollingActive"
+ "TB,R,N,GisRunning"
+ "Td,R,N"
+ "VMPeriodicTimer"
+ "VMPeriodicTimerDelegate"
+ "_interval"
+ "_nextExpiryTime"
+ "_periodicPollingActive"
+ "_periodicPollingTimer"
+ "_timer"
+ "_timerService"
+ "carrierPeriodicPollingEnabled"
+ "carrierPeriodicPollingInterval"
+ "com.apple.voicemail.periodicPolling"
+ "handlePeriodicTimerExpired"
+ "initWithDelegate:queue:prefix:"
+ "interval"
+ "isPeriodicPollingActive"
+ "isRunning"
+ "periodicPollingActive"
+ "periodicPollingTimeRemaining"
+ "periodicPollingTimer"
+ "poll.tmr"
+ "resetTimer"
+ "running"
+ "setPeriodicPollingActive:"
+ "setPeriodicPollingTimer:"
+ "setTimer:interval:"
+ "startPeriodicPollingTimer:"
+ "startWithInterval:"
+ "stopPeriodicPollingTimer"
+ "timeRemaining"
+ "timerExpired"
+ "updateNextExpiryTime"
+ "updatePeriodicPolling"
+ "v32@0:8{unique_ptr<ctu::Timer, std::default_delete<ctu::Timer>>={?=^{Timer}}}16d24"
+ "{duration<long long, std::ratio<1>>=\"__rep_\"q}"
+ "{shared_ptr<ctu::DispatchTimerService>=\"__ptr_\"^{DispatchTimerService}\"__cntrl_\"^{__shared_weak_count}}"
+ "{time_point<std::chrono::steady_clock, std::chrono::duration<long long, std::ratio<1, 1000000000>>>=\"__d_\"{duration<long long, std::ratio<1, 1000000000>>=\"__rep_\"q}}"
+ "{unique_ptr<ctu::Timer, std::default_delete<ctu::Timer>>=\"\"{?=\"__ptr_\"^{Timer}}}"
+ "\x81"
- "%s#I %s%s[%c] Scheduling delayed sync in %u s, iteration %d"
```
