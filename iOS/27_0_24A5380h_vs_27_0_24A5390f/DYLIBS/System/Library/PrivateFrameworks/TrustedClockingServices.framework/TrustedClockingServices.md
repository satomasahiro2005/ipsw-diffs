## TrustedClockingServices

> `/System/Library/PrivateFrameworks/TrustedClockingServices.framework/TrustedClockingServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11268` | `0x11688` | **`+0x420`** |
| `__AUTH_CONST.__objc_const` | `0x1b60` | `0x1bf0` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x480` | `0x510` | **`+0x90`** |
| `__TEXT.__cstring` | `0x1c2c` | `0x1cac` | **`+0x80`** |
| `__AUTH.__objc_data` | `0x498` | `0x4e8` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x320` | `0x360` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x488` | `0x4c8` | **`+0x40`** |
| `__TEXT.__const` | `0xaf8` | `0xb28` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x73c` | `0x76c` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x740` | `0x768` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x138` | `0x150` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e0` | `0x2f8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x690` | `0x6a0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xb0` | `0xb8` | **`+0x8`** |

### Other Changes

```diff

-93.1.0.0.0
+95.0.0.0.0

-  Functions: 605
-  Symbols:   761
-  CStrings:  132
+  Functions: 610
+  Symbols:   780
+  CStrings:  134
Symbols:
+ +[TrustedClockingThreadPriorityResolver specForThreadConfig:routingConfig:]
+ -[TrustedClockingManager createThreadForUseCaseID:]
+ -[TrustedClockingThread .cxx_construct]
+ -[TrustedClockingThread .cxx_destruct]
+ -[TrustedClockingThread initWithWorkload:attributes:]
+ -[TrustedClockingThread initWithWorkload:qosClass:]
+ -[TrustedClockingThread initWithWorkload:realtimeConstraints:]
+ -[TrustedClockingThreadFactory createThreadForUseCaseID:workload:]
+ GCC_except_table13
+ GCC_except_table20
+ _OBJC_CLASS_$_TrustedClockingThread
+ _OBJC_CLASS_$_TrustedClockingThreadPriorityResolver
+ _OBJC_IVAR_$_TrustedClockingThread._thread
+ _OBJC_IVAR_$_TrustedClockingThread._workload
+ _OBJC_METACLASS_$_TrustedClockingThread
+ _OBJC_METACLASS_$_TrustedClockingThreadPriorityResolver
+ __OBJC_$_CLASS_METHODS_TrustedClockingThreadPriorityResolver
+ __OBJC_$_INSTANCE_METHODS_TrustedClockingThread
+ __OBJC_$_INSTANCE_VARIABLES_TrustedClockingThread
+ __OBJC_$_PROP_LIST_TrustedClockingThread
+ __OBJC_$_PROTOCOL_REFS_TrustedClockingThreadProtocol
+ __OBJC_CLASS_PROTOCOLS_$_TrustedClockingThread
+ __OBJC_CLASS_RO_$_TrustedClockingThread
+ __OBJC_CLASS_RO_$_TrustedClockingThreadPriorityResolver
+ __OBJC_LABEL_PROTOCOL_$_TrustedClockingThreadProtocol
+ __OBJC_METACLASS_RO_$_TrustedClockingThread
+ __OBJC_METACLASS_RO_$_TrustedClockingThreadPriorityResolver
+ __OBJC_PROTOCOL_$_TrustedClockingThreadProtocol
+ __ZL14kThreadConfigs
+ __ZL15kRoutingConfigs
+ __ZL24kRoutingDevices_MockTest
+ __ZL27kRoutingDevices_ConvCapture
+ __ZL27kRoutingDevices_Siri2ndPass
+ __ZN5caulk12thread_proxyINSt3__15tupleIJNS_6thread10attributesEZ53-[TrustedClockingThread initWithWorkload:attributes:]E3$_0NS2_IJEEEEEEEEPvS8_
+ __ZNSt18bad_variant_accessD1Ev
+ __ZNSt3__110unique_ptrINS_5tupleIJN5caulk6thread10attributesEZ53-[TrustedClockingThread initWithWorkload:attributes:]E3$_0NS1_IJEEEEEENS_14default_deleteIS7_EEED1B9fqe220106Ev
+ __ZNSt3__126__throw_bad_variant_accessB9fqe220106Ev
+ __ZNSt3__18optionalINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEEaSB9fqe220106IRA38_KcLi0EEERS7_OT_
+ __ZNSt9exceptionD2Ev
+ __ZTISt18bad_variant_access
+ __ZTVSt18bad_variant_access
+ ___51-[TrustedClockingManager createThreadForUseCaseID:]_block_invoke
+ _objc_retain_x21
+ _objc_retain_x3
- -[TrustedClockingManager createRealtimeThread:sampleRate:useCaseID:]
- -[TrustedClockingRealtimeThread .cxx_construct]
- -[TrustedClockingRealtimeThread .cxx_destruct]
- -[TrustedClockingRealtimeThread initWithWorkload:realtimeConstraints:]
- -[TrustedClockingThreadFactory createRealtimeThread:frameSize:workload:]
- GCC_except_table16
- GCC_except_table18
- _OBJC_CLASS_$_TrustedClockingRealtimeThread
- _OBJC_IVAR_$_TrustedClockingRealtimeThread._thread
- _OBJC_IVAR_$_TrustedClockingRealtimeThread._workload
- _OBJC_METACLASS_$_TrustedClockingRealtimeThread
- __OBJC_$_INSTANCE_METHODS_TrustedClockingRealtimeThread
- __OBJC_$_INSTANCE_VARIABLES_TrustedClockingRealtimeThread
- __OBJC_$_PROP_LIST_TrustedClockingRealtimeThread
- __OBJC_$_PROTOCOL_REFS_TrustedClockingRealtimeThreadProtocol
- __OBJC_CLASS_PROTOCOLS_$_TrustedClockingRealtimeThread
- __OBJC_CLASS_RO_$_TrustedClockingRealtimeThread
- __OBJC_LABEL_PROTOCOL_$_TrustedClockingRealtimeThreadProtocol
- __OBJC_METACLASS_RO_$_TrustedClockingRealtimeThread
- __OBJC_PROTOCOL_$_TrustedClockingRealtimeThreadProtocol
- __ZN5caulk12thread_proxyINSt3__15tupleIJNS_6thread10attributesEZ70-[TrustedClockingRealtimeThread initWithWorkload:realtimeConstraints:]E3$_0NS2_IJEEEEEEEEPvS8_
- __ZNSt3__110unique_ptrINS_5tupleIJN5caulk6thread10attributesEZ70-[TrustedClockingRealtimeThread initWithWorkload:realtimeConstraints:]E3$_0NS1_IJEEEEEENS_14default_deleteIS7_EEED1B9fqe220106Ev
- __ZNSt3__18optionalINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEEaSB9fqe220106IRA27_KcLi0EEERS7_OT_
- ___68-[TrustedClockingManager createRealtimeThread:sampleRate:useCaseID:]_block_invoke
- _objc_retain_x4
CStrings:
+ "TrustedClockingThread::initWithWorkload: Exception: %s"
+ "TrustedClockingThreadFactory: No config found for useCaseID %u"
+ "TrustedClockingThreadFactory: useCaseID %u -> qos class %u"
+ "TrustedClockingThreadFactory: useCaseID %u -> realtime period=%u quantum=%u constraint=%u"
+ "com.apple.trustedclocking.audiothread"
- "TrustedClockingRealtimeThread::initWithWorkload: Exception: %s"
- "TrustedClockingRealtimeThread::initWithWorkload: Launching trusted clocking real time thread."
- "trusted_clocking_rt_thread"
```
