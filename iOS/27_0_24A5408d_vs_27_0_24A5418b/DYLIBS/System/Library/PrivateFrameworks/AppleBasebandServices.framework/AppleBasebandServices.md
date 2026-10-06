## AppleBasebandServices

> `/System/Library/PrivateFrameworks/AppleBasebandServices.framework/AppleBasebandServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b08c` | `0x1a768` | **`-0x924`** |
| `__TEXT.__gcc_except_tab` | `0x107c` | `0xd7c` | **`-0x300`** |
| `__TEXT.__const` | `0x638` | `0x560` | **`-0xd8`** |
| `__TEXT.__unwind_info` | `0x660` | `0x5d8` | **`-0x88`** |
| `__AUTH_CONST.__const` | `0x7d0` | `0x780` | **`-0x50`** |
| `__DATA.__data` | `0xd8` | `0x88` | **`-0x50`** |
| `__TEXT.__cstring` | `0x317` | `0x2e3` | **`-0x34`** |
| `__TEXT.__oslogstring` | `0x25f` | `0x236` | **`-0x29`** |
| `__AUTH_CONST.__cfstring` | `0x20` | `—` | **`-0x20`** |
| `__DATA_CONST.__weak_got` | `0x20` | `0x10` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x8` | `—` | **`-0x8`** |
| `__TEXT.__init_offsets` | `0x4` | `—` | **`-0x4`** |

### Other Changes

```diff

-  Functions: 263
-  Symbols:   627
-  CStrings:  65
+  Functions: 255
+  Symbols:   586
+  CStrings:  62
Symbols:
- GCC_except_table10
- GCC_except_table23
- GCC_except_table24
- GCC_except_table25
- GCC_except_table27
- GCC_except_table3
- GCC_except_table31
- GCC_except_table32
- GCC_except_table5
- _CFBooleanGetTypeID
- _CFGetTypeID
- _CFRelease
- _TelephonyBasebandWatchdogStartWithStackshot
- _TelephonyBasebandWatchdogStop
- __ZGVN3ctu9SingletonI21CapabilitiesOverridesS1_NS_23PthreadMutexGuardPolicyIS1_EEE9sInstanceE
- __ZN12capabilities3abs27kKeySupportsCMHandDetectionE
- __ZN3ctu23PthreadMutexGuardPolicyI21CapabilitiesOverridesED1Ev
- __ZN3ctu2cf12MakeCFStringC1EPKc
- __ZN3ctu2cf12MakeCFStringD1Ev
- __ZN3ctu2cf13plist_adapterC1EPK10__CFStringS4_
- __ZN3ctu2cf13plist_adapterD1Ev
- __ZN3ctu2cf6assignERbPK11__CFBoolean
- __ZN3ctu9SingletonI21CapabilitiesOverridesS1_NS_23PthreadMutexGuardPolicyIS1_EEE9sInstanceE
- __ZNKSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEE13__get_deleterERKSt9type_info
- __ZNSt3__110shared_ptrI21CapabilitiesOverridesED2B9fqe220106Ev
- __ZNSt3__110unique_ptrI21CapabilitiesOverridesNS_14default_deleteIS1_EEED2B9fqe220106Ev
- __ZNSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEE16__on_zero_sharedEv
- __ZNSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEE21__on_zero_shared_weakEv
- __ZNSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEED0Ev
- __ZNSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEED1Ev
- __ZTINSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEEE
- __ZTSNSt3__110shared_ptrI21CapabilitiesOverridesE27__shared_ptr_default_deleteIS1_S1_EE
- __ZTSNSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEEE
- __ZTVNSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEEE
- ___CFConstantStringClassReference
- ___cxa_atexit
- ___cxx_global_var_init
- __os_log_debug_impl
- _kCFPreferencesCurrentUser
- _pthread_mutex_lock
- _pthread_mutex_unlock
CStrings:
- "Capability %s returning overridden value"
- "Watchdog timed out"
- "com.apple.telephony.capabilities"
```
