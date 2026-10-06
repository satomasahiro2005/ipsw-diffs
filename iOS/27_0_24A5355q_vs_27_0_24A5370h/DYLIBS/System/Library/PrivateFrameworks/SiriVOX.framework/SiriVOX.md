## SiriVOX

> `/System/Library/PrivateFrameworks/SiriVOX.framework/SiriVOX`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x83b58` | `0x84098` | **`+0x540`** |
| `__TEXT.__oslogstring` | `0x881e` | `0x89be` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x117d7` | `0x1184e` | **`+0x77`** |
| `__AUTH_CONST.__objc_const` | `0x134f8` | `0x13558` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x8a80` | `0x8ae0` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x3cf8` | `0x3d30` | **`+0x38`** |
| `__AUTH_CONST.__objc_intobj` | `0xe28` | `0xe58` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x54c` | `0x57c` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x2388` | `0x23b0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x5fc0` | `0x5fe0` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0xc48` | `0xc28` | **`-0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x960` | `0x980` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x2c00` | `0x2be8` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x6d0` | `0x6d8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xc94` | `0xc9c` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x778` | `0x770` | **`-0x8`** |

### Other Changes

```diff

-3600.46.3.0.0
+3600.52.2.0.0

+  - /System/Library/PrivateFrameworks/Rapport.framework/Rapport

-  Functions: 3127
-  Symbols:   6648
-  CStrings:  2244
+  Functions: 3134
+  Symbols:   6657
+  CStrings:  2252
Symbols:
+ -[SVXSession _cancelSuspendedEndpointerSafetyTimeout]
+ -[SVXSession _scheduleSuspendedEndpointerSafetyTimeoutIfNeeded]
+ -[SVXSession _suspendedEndpointerSafetyTimeoutFired]
+ -[SVXSession hasSuspendedEndpointerSafetyTimeout]
+ -[SVXSessionManager _invalidateCurrentSessionSync]
+ -[SVXSessionManager odeonActivityBroadcaster]
+ -[SVXSessionManager odeonPerformer]
+ GCC_except_table1669
+ GCC_except_table1675
+ GCC_except_table1676
+ GCC_except_table1805
+ GCC_except_table1807
+ GCC_except_table1915
+ GCC_except_table2075
+ GCC_except_table2208
+ GCC_except_table2329
+ GCC_except_table2345
+ GCC_except_table2464
+ GCC_except_table2468
+ GCC_except_table2470
+ GCC_except_table2473
+ GCC_except_table2775
+ GCC_except_table2930
+ GCC_except_table3005
+ _OBJC_CLASS_$_DeviceSelectionSiriSessionSignal
+ _OBJC_CLASS_$_DeviceSelectionTriggerSignal
+ _OBJC_IVAR_$_SVXSession._suspendedEndpointerSafetyTimer
+ _OBJC_IVAR_$_SVXSessionManager._lastSessionBecameActiveTimestamp
+ ___63-[SVXSession _scheduleSuspendedEndpointerSafetyTimeoutIfNeeded]_block_invoke
+ ___63-[SVXSession _scheduleSuspendedEndpointerSafetyTimeoutIfNeeded]_block_invoke_2
+ ___block_descriptor_56_e8_32s40s48bs_e8_v16?0q8ls32l8s40l8s48l8
+ _mach_continuous_time
- -[SVXSessionManager _sendActivationTriggerToDeviceSelection:]
- GCC_except_table1671
- GCC_except_table1677
- GCC_except_table1678
- GCC_except_table1806
- GCC_except_table1809
- GCC_except_table1914
- GCC_except_table2074
- GCC_except_table2207
- GCC_except_table2328
- GCC_except_table2343
- GCC_except_table2461
- GCC_except_table2463
- GCC_except_table2466
- GCC_except_table2768
- GCC_except_table2923
- GCC_except_table2998
- _OBJC_CLASS_$_DeviceSelectionContext
- _OBJC_CLASS_$_DeviceSelectionSignalDonation
- _OBJC_CLASS_$_DeviceSelectionTriggerSource
- ___61-[SVXSessionManager _sendActivationTriggerToDeviceSelection:]_block_invoke
- ___block_descriptor_48_e8_32bs_e5_v8?0ls32l8
- ___block_descriptor_48_e8_32s40bs_e8_v16?0q8ls32l8s40l8
CStrings:
+ "%s #deviceSelection Donating signals: session start and trigger type(%@), isConnectedToCarPlay %d, isSiriDisplayed %d, isSiriSpeaking %d"
+ "%s Cancelling suspended endpointer safety timeout"
+ "%s Endpointer suspended without active button hold, scheduling safety timeout (%.0fs)"
+ "%s Session stuck active for %.0fs (>%.0fs), forcing context clear"
+ "%s Suspended endpointer safety timeout fired but endpointer no longer suspended, ignoring"
+ "%s Suspended endpointer safety timeout fired but speech request already ended, ignoring"
+ "%s Suspended endpointer safety timeout fired, forcing automatic endpointing"
+ "%s Trampoline session: forwarding activation without entering activity state machine."
+ "-[SVXSession _cancelSuspendedEndpointerSafetyTimeout]"
+ "-[SVXSession _scheduleSuspendedEndpointerSafetyTimeoutIfNeeded]"
+ "-[SVXSession _suspendedEndpointerSafetyTimeoutFired]"
+ "-[SVXSessionManager _performedDeviceSelectionWithRequestInfo:isVoiceTrigger:]"
+ "remote"
+ "\xf0\xe1"
- "%s #deviceSelection Donating activation with type(%@), isConnectedToCarPlay %d, isSiriDisplayed %d, isSiriSpeaking %d"
- "%s #deviceSelection Failed to donate Siri activation trigger source: %@"
- "%s #deviceSelection Successfully donated Siri activation trigger source."
- "-[SVXSessionManager _sendActivationTriggerToDeviceSelection:]"
- "-[SVXSessionManager _sendActivationTriggerToDeviceSelection:]_block_invoke"
- "\xf0\xd1"
```
