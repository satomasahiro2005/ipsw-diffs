## libBasebandManagerICE.dylib

> `/usr/lib/libBasebandManagerICE.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28ff40` | `0x29b18c` | **`+0xb24c`** |
| `__TEXT.__gcc_except_tab` | `0x3c038` | `0x3d134` | **`+0x10fc`** |
| `__TEXT.__cstring` | `0x8ae2` | `0x8e5a` | **`+0x378`** |
| `__TEXT.__oslogstring` | `0x102fb` | `0x10524` | **`+0x229`** |
| `__TEXT.__unwind_info` | `0xb160` | `0xb2e0` | **`+0x180`** |
| `__TEXT.__const` | `0x148c0` | `0x149d0` | **`+0x110`** |
| `__DATA_CONST.__const` | `0x2238` | `0x22b8` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x11698` | `0x11708` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0x1c38` | `0x1c90` | **`+0x58`** |
| `__DATA_DIRTY.__data` | `0x5e0` | `0x638` | **`+0x58`** |
| `__DATA.__data` | `0x604` | `0x658` | **`+0x54`** |
| `__AUTH_CONST.__cfstring` | `0xb20` | `0xb60` | **`+0x40`** |
| `__DATA.__common` | `0x9` | `0x49` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x2350` | `0x2380` | **`+0x30`** |
| `__DATA_DIRTY.__bss` | `0x16a2` | `0x16d2` | **`+0x30`** |
| `__TEXT.__init_offsets` | `0x168` | `0x17c` | **`+0x14`** |
| `__DATA_CONST.__weak_got` | `0x158` | `0x168` | **`+0x10`** |
| `__DATA_DIRTY.__common` | `0xd0` | `0xd8` | **`+0x8`** |

### Other Changes

```diff

-1585.0.0.0.0
+1594.0.0.0.0

-  Functions: 7140
-  Symbols:   12452
-  CStrings:  2942
+  Functions: 7167
+  Symbols:   12507
+  CStrings:  2988
Symbols:
+ GCC_except_table282
+ GCC_except_table316
+ GCC_except_table328
+ GCC_except_table333
+ GCC_except_table337
+ GCC_except_table345
+ GCC_except_table347
+ GCC_except_table349
+ GCC_except_table351
+ GCC_except_table366
+ GCC_except_table370
+ GCC_except_table371
+ GCC_except_table380
+ _CFUserNotificationDisplayNotice
+ _TelephonyBasebandWatchdogStartWithStackshot
+ _TelephonyRadiosGetHardwareConfig
+ _TelephonyUtilTriggerNMI
+ _TelephonyUtilWriteStackshot
+ __GLOBAL__sub_I_Utils.cpp
+ __ZGVN3ctu9SingletonI21CapabilitiesOverridesS1_NS_23PthreadMutexGuardPolicyIS1_EEE9sInstanceE
+ __ZN12capabilities3abs17shouldBlockResetsEv
+ __ZN12capabilities3abs26shouldPanicOnBasebandResetEv
+ __ZN12capabilities3abs27kKeySupportsCMHandDetectionE
+ __ZN12capabilities3abs39shouldTriggerStackshotOnShutdownTimeoutEv
+ __ZN3abm27kCommandBasebandBootArgsAddE
+ __ZN3abm27kCommandBasebandBootArgsGetE
+ __ZN3abm28kKeyBasebandBootArgsArgumentE
+ __ZN3abm29kKeyBasebandBootArgsGetResultE
+ __ZN3abm30kCommandBasebandBootArgsDeleteE
+ __ZN3ctu23PthreadMutexGuardPolicyI21CapabilitiesOverridesED1Ev
+ __ZN3ctu2cf11CFSharedRefIK14__CFDictionaryEC2ERKNS0_7_RetainIS3_EE
+ __ZN3ctu2cf6insertIPK10__CFStringS4_EEbP14__CFDictionaryT_T0_PK13__CFAllocator
+ __ZN3ctu5power7manager20simulateNotificationEjb
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
+ __ZNK12TelephonyXPC6Result8describeEv
+ __ZNK3ctu14SharedLockableI10SharedDataE12execute_syncIZNS1_13setPreferenceIP14__CFDictionaryEEbRKNSt3__112basic_stringIcNS7_11char_traitsIcEENS7_9allocatorIcEEEET_EUlvE_EENS7_5decayIDTclfp_EEE4typeEOSG_
+ __ZNKSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEE13__get_deleterERKSt9type_info
+ __ZNSt3__110shared_ptrI21CapabilitiesOverridesED2B9fqe220106Ev
+ __ZNSt3__110shared_ptrIN3ctu5power7managerEED2B9fqe220106Ev
+ __ZNSt3__110unique_ptrI21CapabilitiesOverridesNS_14default_deleteIS1_EEED2B9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE5eraseEmm
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6insertEmPKcm
+ __ZNSt3__118basic_stringstreamIcNS_11char_traitsIcEENS_9allocatorIcEEEC1B9fqe220106ERKNS_12basic_stringIcS2_S4_EEj
+ __ZNSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEE16__on_zero_sharedEv
+ __ZNSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEE21__on_zero_shared_weakEv
+ __ZNSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEED0Ev
+ __ZNSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEED1Ev
+ __ZNSt3__16vectorImNS_9allocatorImEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorImNS_9allocatorImEEE24__emplace_back_slow_pathIJRKmEEEPmDpOT_
+ __ZNSt3__1eqB9fqe220106IcNS_11char_traitsIcEENS_9allocatorIcEEEEbRKNS_12basic_stringIT_T0_T1_EESB_
+ __ZTINSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEEE
+ __ZTSNSt3__110shared_ptrI21CapabilitiesOverridesE27__shared_ptr_default_deleteIS1_S1_EE
+ __ZTSNSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEEE
+ __ZTVNSt3__120__shared_ptr_pointerIP21CapabilitiesOverridesNS_10shared_ptrIS1_E27__shared_ptr_default_deleteIS1_S1_EENS_9allocatorIS1_EEEE
+ __ZZN9ABMServer10getProfileEvE11sABMProfile
+ __ZZN9ABMServer10getProfileEvE9onceToken
+ ____ZN9ABMServer10getProfileEv_block_invoke
- GCC_except_table286
- GCC_except_table291
- GCC_except_table319
- GCC_except_table330
- GCC_except_table332
- GCC_except_table334
- GCC_except_table336
- GCC_except_table350
- GCC_except_table363
- GCC_except_table367
- GCC_except_table377
- ___copy_helper_block_e8_32c35_ZTSNSt3__18weak_ptrI10BootModuleEE
- ___destroy_helper_block_e8_32c35_ZTSNSt3__18weak_ptrI10BootModuleEE
CStrings:
+ "    %s"
+ " Execute abmtool bb bootargs add %s"
+ " does not exist in file "
+ " does not exist or could not be read. Try creating the file or restarting the device and try again."
+ " does not exist, could not be read, or is missing the key NvramItems."
+ " does not have any bb boot-args to delete."
+ ", reason "
+ "-l 0xffffffff -v 99 -N"
+ "/var/wireless/Library/Preferences/com.apple.AppleBasebandManager.plist"
+ "AppleBasebandManager-AppleBasebandServices_Manager-1594"
+ "AppleBasebandServices_Manager-1594"
+ "Baseband Firmware Not Found"
+ "Baseband Hard-Reset: "
+ "Capability %s returning overridden value"
+ "Did you forget to check update baseband or set permissions if you used a custom build?"
+ "Enumerating HealthEvents to be written to disk:"
+ "Error: boot-arg "
+ "Error: failed to write new boot-args to "
+ "Error: file "
+ "Execute abmtool bb bootargs delete %s"
+ "Execute abmtool bb bootargs get %s"
+ "Got boot-args %s of length %lu"
+ "HealthEvents dictionary representation to be written to disk: %@"
+ "Incompatible Baseband firmware."
+ "NULL"
+ "NvramItems"
+ "OK"
+ "PANIC: %s"
+ "PanicString"
+ "SensingCAInfo: angle=%.1f (bucket %u), fdDist=%u, pitch=%u, roll=%u, facing=%u, case=%s"
+ "ServiceManager sleep timeout"
+ "ServiceManager wake timeout"
+ "Simulated notification: %s"
+ "Skipping repair status check"
+ "Triggering stackshot"
+ "Triggering stackshot  -- done"
+ "Triggering stackshot, goes with "
+ "Unexpected behavior may occur. Please upgrade to a newer firmware."
+ "Unsupported ABM profile, check your plist!"
+ "blocking reset until user signals"
+ "boot-args not found"
+ "boot-args='"
+ "boot-args=''"
+ "boot-args='([^']*)'"
+ "com.apple.telephony.capabilities"
+ "exists"
+ "getNvramData %s"
+ "got data %s"
+ "key not found\n"
+ "setNvramData %s"
- "-l 0xffffffff -v 0 -N"
- "AppleBasebandManager-AppleBasebandServices_Manager-1585"
- "AppleBasebandServices_Manager-1585"
- "SensingCAInfo: angle=%d, fdDist=%u, pitch=%u, roll=%u, facing=%u, case=%s"
```
