## ABMHelper

> `/System/Library/PrivateFrameworks/ABMHelper.framework/ABMHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cb514` | `0x1d0bc0` | **`+0x56ac`** |
| `__TEXT.__gcc_except_tab` | `0x210fc` | `0x21a2c` | **`+0x930`** |
| `__TEXT.__cstring` | `0x85c7` | `0x8911` | **`+0x34a`** |
| `__TEXT.__oslogstring` | `0xdb32` | `0xdca9` | **`+0x177`** |
| `__TEXT.__unwind_info` | `0x7010` | `0x7158` | **`+0x148`** |
| `__TEXT.__const` | `0x7100` | `0x7220` | **`+0x120`** |
| `__DATA.__data` | `0x3c8` | `0x468` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x940` | `0x9c0` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x9160` | `0x91b0` | **`+0x50`** |
| `__DATA_DIRTY.__common` | `0xf4` | `0x134` | **`+0x40`** |
| `__DATA.__bss` | `0x8` | `0x20` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0xb08` | `0xb20` | **`+0x18`** |
| `__DATA_CONST.__weak_got` | `0xa8` | `0xb8` | **`+0x10`** |
| `__TEXT.__init_offsets` | `0x160` | `0x16c` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x570` | `0x578` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x228` | `0x230` | **`+0x8`** |

### Other Changes

```diff

-1585.0.0.0.0
+1594.0.0.0.0

-  Functions: 4299
-  Symbols:   6773
-  CStrings:  2766
+  Functions: 4320
+  Symbols:   6808
+  CStrings:  2800
Symbols:
+ _CFUserNotificationCancel
+ _CFUserNotificationDisplayNotice
+ _TelephonyBasebandWatchdogStartWithStackshot
+ __GLOBAL__sub_I_Utils.cpp
+ __ZGVN3ctu9SingletonI21CapabilitiesOverridesS1_NS_23PthreadMutexGuardPolicyIS1_EEE9sInstanceE
+ __ZN12capabilities3abs27kKeySupportsCMHandDetectionE
+ __ZN17KernelPCIABPTrace25disableKernelTraceBuffersEv
+ __ZN3ctu23PthreadMutexGuardPolicyI21CapabilitiesOverridesED1Ev
+ __ZN3ctu2cf6insertIPK10__CFStringS4_EEbP14__CFDictionaryT_T0_PK13__CFAllocator
+ __ZN3ctu9SingletonI21CapabilitiesOverridesS1_NS_23PthreadMutexGuardPolicyIS1_EEE9sInstanceE
+ __ZN4util12getNvramDataEb
+ __ZN4util12setNvramDataENSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE
+ __ZN4util13removeBootArgERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEES8_
+ __ZN4util14trimWhitespaceERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE
+ __ZN4util21insertOrUpdateBootArgERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEES8_
+ __ZN4util23boot_args_regex_patternE
+ __ZN4util24getBootArgsFromNvramDataENSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE
+ __ZN4util8nvramKeyE
+ __ZN4util9nvramPathE
+ __ZN7support2uiL17gNotificationLockE
+ __ZN7support2uiL9isAllowedEv
+ __ZNKSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEE13__get_deleterERKSt9type_info
+ __ZNSt3__110shared_ptrI21CapabilitiesOverridesED2B9fqe220106Ev
+ __ZNSt3__110unique_ptrI21CapabilitiesOverridesNS_14default_deleteIS1_EEED2B9fqe220106Ev
+ __ZNSt3__115basic_stringbufIcNS_11char_traitsIcEENS_9allocatorIcEEEC2B9fqe220106ERKNS_12basic_stringIcS2_S4_EEj
+ __ZNSt3__118basic_stringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220106ERKNS_12basic_stringIcS2_S4_EEj
+ __ZNSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEE16__on_zero_sharedEv
+ __ZNSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEE21__on_zero_shared_weakEv
+ __ZNSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEED0Ev
+ __ZNSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEED1Ev
+ __ZTINSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEEE
+ __ZTSNSt3__110shared_ptrI21CapabilitiesOverridesE27__shared_ptr_default_deleteIS1_S1_EE
+ __ZTSNSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEEE
+ __ZTVNSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEEE
+ __ZZN7support2ui23displayUserNotificationERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEES9_bdE8sHistory
CStrings:
+ "%s %s"
+ "/var/wireless/Library/Preferences/com.apple.AppleBasebandManager.plist"
+ "Baseband DIAG DMC Integrity Match"
+ "Baseband Logging Mode has been changed"
+ "Capability %s returning overridden value"
+ "Cellular Problem"
+ "Cellular Radar Notifications Disabled"
+ "Cellular Sysdiagnose Complete"
+ "DIAG Mode changed"
+ "DIAG Service Error"
+ "Disable kernel trace buffers returned [0x%x]"
+ "ETB Configuration"
+ "Enable kernel trace buffers returned [0x%x]"
+ "Failed to create kernel trace object to disable kernel trace buffers"
+ "Failed to start kernel trace interface to disable kernel trace buffers"
+ "Integrity check for DMC file found an issue. Please file a radar under Purple ETL"
+ "Mode has changed. Please, reboot the device"
+ "NvramItems"
+ "OK"
+ "Resetting the baseband to apply your change"
+ "Restart the device before continuing to use DIAG trace"
+ "Restart the device before continuing to use the baseband trace"
+ "Showing notification: %s"
+ "To control notifications please go to:\n\nSettings > Carrier Settings > Baseband Manager > Logging Settings > Radar Notifications"
+ "boot-args='"
+ "boot-args='([^']*)'"
+ "com.apple.telephony.capabilities"
+ "error=%d, responseFlags=0x%lx"
+ "failed"
+ "getNvramData %s"
+ "got data %s"
+ "kernel.pci.bin.disable"
+ "setNvramData %s"
+ "succeeded"
```
