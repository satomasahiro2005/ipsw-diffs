## libBasebandCommandDriversARI.dylib

> `/usr/lib/libBasebandCommandDriversARI.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc1624` | `0xbd77c` | **`-0x3ea8`** |
| `__TEXT.__gcc_except_tab` | `0xe288` | `0xde9c` | **`-0x3ec`** |
| `__TEXT.__const` | `0x8580` | `0x84b0` | **`-0xd0`** |
| `__TEXT.__cstring` | `0x35f8` | `0x352d` | **`-0xcb`** |
| `__TEXT.__unwind_info` | `0x39f8` | `0x3938` | **`-0xc0`** |
| `__DATA.__data` | `0x220` | `0x1c0` | **`-0x60`** |
| `__AUTH_CONST.__const` | `0x7010` | `0x6fc0` | **`-0x50`** |
| `__DATA_DIRTY.__data` | `0xf0` | `0xa0` | **`-0x50`** |
| `__DATA.__common` | `0x40` | `—` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0x26ef` | `0x26bd` | **`-0x32`** |
| `__AUTH_CONST.__cfstring` | `0xa0` | `0x80` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x670` | `0x660` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x110` | `0x100` | **`-0x10`** |
| `__TEXT.__init_offsets` | `0x14` | `0x8` | **`-0xc`** |

### Other Changes

```diff

-  Functions: 2232
-  Symbols:   4722
-  CStrings:  864
+  Functions: 2209
+  Symbols:   4682
+  CStrings:  850
Symbols:
+ __ZN3ctu2cf11CFSharedRefIK10__CFStringED2Ev
- GCC_except_table237
- _CFBooleanGetTypeID
- _TelephonyBasebandWatchdogStartWithStackshot
- _TelephonyBasebandWatchdogStop
- __GLOBAL__sub_I_Utils.cpp
- __ZGVN3ctu9SingletonI13ABMPropertiesS1_NS_23PthreadMutexGuardPolicyIS1_EEE9sInstanceE
- __ZGVN3ctu9SingletonI21CapabilitiesOverridesS1_NS_23PthreadMutexGuardPolicyIS1_EEE9sInstanceE
- __ZN12capabilities3abs27kKeySupportsCMHandDetectionE
- __ZN3ctu23PthreadMutexGuardPolicyI13ABMPropertiesED1Ev
- __ZN3ctu23PthreadMutexGuardPolicyI21CapabilitiesOverridesED1Ev
- __ZN3ctu2cf13plist_adapter3setINSt3__112basic_stringIcNS3_11char_traitsIcEENS3_9allocatorIcEEEEEEbT_PK10__CFStringb
- __ZN3ctu2cf13plist_adapter3setINSt3__112basic_stringIcNS3_11char_traitsIcEENS3_9allocatorIcEEEEEEbT_PKcb
- __ZN3ctu2cf18ConvertToCFTypeRefD2Ev
- __ZN3ctu2cf6assignERNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEEPKv
- __ZN3ctu2cf6assignERbPK11__CFBoolean
- __ZN3ctu9SingletonI13ABMPropertiesS1_NS_23PthreadMutexGuardPolicyIS1_EEE9sInstanceE
- __ZN3ctu9SingletonI21CapabilitiesOverridesS1_NS_23PthreadMutexGuardPolicyIS1_EEE9sInstanceE
- __ZN4util12getNvramDataEb
- __ZN4util12setNvramDataENSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE
- __ZN4util13removeBootArgERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEES8_
- __ZN4util14trimWhitespaceERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE
- __ZN4util21insertOrUpdateBootArgERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEES8_
- __ZN4util23boot_args_regex_patternE
- __ZN4util24getBootArgsFromNvramDataENSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE
- __ZN4util8nvramKeyE
- __ZN4util9nvramPathE
- __ZN7support2fs10fileExistsERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEE
- __ZNKSt3__120__shared_ptr_pointerIP13ABMPropertiesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEE13__get_deleterERKSt9type_info
- __ZNSt3__110shared_ptrI13ABMPropertiesED1B9fqe220106Ev
- __ZNSt3__110unique_ptrI13ABMPropertiesNS_14default_deleteIS1_EEED2B9fqe220106Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6appendB9fqe220106IPKcLi0EEERS5_T_SA_
- __ZNSt3__118basic_stringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220106ERKNS_12basic_stringIcS2_S4_EEj
- __ZNSt3__118basic_stringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEED1Ev
- __ZNSt3__120__shared_ptr_pointerIP13ABMPropertiesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEE16__on_zero_sharedEv
- __ZNSt3__120__shared_ptr_pointerIP13ABMPropertiesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEE21__on_zero_shared_weakEv
- __ZNSt3__120__shared_ptr_pointerIP13ABMPropertiesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEED0Ev
- __ZNSt3__120__shared_ptr_pointerIP13ABMPropertiesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEED1Ev
- __ZTINSt3__120__shared_ptr_pointerIP13ABMPropertiesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEEE
- __ZTSNSt3__110shared_ptrI13ABMPropertiesE27__shared_ptr_default_deleteIS1_S1_EE
- __ZTSNSt3__120__shared_ptr_pointerIP13ABMPropertiesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEEE
- __ZTVNSt3__120__shared_ptr_pointerIP13ABMPropertiesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEEE
CStrings:
- "%s %s"
- "/var/wireless/Library/Preferences/com.apple.AppleBasebandManager.plist"
- "NvramItems"
- "Watchdog timed out"
- "boot-args='"
- "boot-args='([^']*)'"
- "com.apple.AppleBasebandManager"
- "does not exist"
- "exists"
- "failed"
- "getNvramData %s"
- "got data %s"
- "setNvramData %s"
- "succeeded"
```
