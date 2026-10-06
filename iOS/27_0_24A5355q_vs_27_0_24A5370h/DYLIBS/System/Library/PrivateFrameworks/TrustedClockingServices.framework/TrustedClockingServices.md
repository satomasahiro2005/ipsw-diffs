## TrustedClockingServices

> `/System/Library/PrivateFrameworks/TrustedClockingServices.framework/TrustedClockingServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1fac` | `0x1c2c` | **`-0x380`** |
| `__AUTH_CONST.__cfstring` | `0x4a0` | `0x320` | **`-0x180`** |
| `__TEXT.__text` | `0x112e0` | `0x11268` | **`-0x78`** |
| `__TEXT.__objc_methlist` | `0x784` | `0x73c` | **`-0x48`** |
| `__TEXT.__eh_frame` | `0x650` | `0x688` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x4c0` | `0x488` | **`-0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x300` | `0x2e0` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x680` | `0x690` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x1b70` | `0x1b60` | **`-0x10`** |
| `__TEXT.__const` | `0xae8` | `0xaf8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x750` | `0x740` | **`-0x10`** |
| `__TEXT.__swift5_typeref` | `0x291` | `0x29b` | **`+0xa`** |
| `__DATA.__data` | `0x280` | `0x288` | **`+0x8`** |

### Other Changes

```diff

-87.1.31.0.0
+92.30.0.0.0

-  Functions: 608
-  Symbols:   762
-  CStrings:  144
+  Functions: 605
+  Symbols:   761
+  CStrings:  132
Symbols:
+ GCC_except_table21
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__110unique_ptrIN10applesauce5iokit7details26io_notificationport_holderENS_14default_deleteIS4_EEE5resetB9fqe220106EPS4_
+ __ZNSt3__110unique_ptrINS_5tupleIJN5caulk6thread10attributesEZ70-[TrustedClockingRealtimeThread initWithWorkload:realtimeConstraints:]E3$_0NS1_IJEEEEEENS_14default_deleteIS7_EEED1B9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220106Em
+ __ZNSt3__120__optional_copy_baseINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEELb0EEC2B9fqe220106ERKS7_
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__123__optional_storage_baseINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEELb0EE16__construct_fromB9fqe220106IRKNS_20__optional_copy_baseIS6_Lb0EEEEEvOT_
+ __ZNSt3__16vectorIhNS_9allocatorIhEEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__18optionalINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEEaSB9fqe220106IRA27_KcLi0EEERS7_OT_
+ _swift_allocError
+ _swift_unexpectedError
+ _symbolic _____ySiG s23_ContiguousArrayStorageC
- -[TrustedClockingClient callStartKernelWorkloop:]
- -[TrustedClockingClient callStopKernelWorkloop:]
- -[TrustedClockingManager startKernelWorkloop:]
- -[TrustedClockingManager stopKernelWorkloop:]
- GCC_except_table23
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__110unique_ptrIN10applesauce5iokit7details26io_notificationport_holderENS_14default_deleteIS4_EEE5resetB9fqe220100EPS4_
- __ZNSt3__110unique_ptrINS_5tupleIJN5caulk6thread10attributesEZ70-[TrustedClockingRealtimeThread initWithWorkload:realtimeConstraints:]E3$_0NS1_IJEEEEEENS_14default_deleteIS7_EEED1B9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE22__init_internal_bufferB9fqe220100Em
- __ZNSt3__120__optional_copy_baseINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEELb0EEC2B9fqe220100ERKS7_
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__123__optional_storage_baseINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEELb0EE16__construct_fromB9fqe220100IRKNS_20__optional_copy_baseIS6_Lb0EEEEEvOT_
- __ZNSt3__16vectorIhNS_9allocatorIhEEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__18optionalINS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEEEaSB9fqe220100IRA27_KcLi0EEERS7_OT_
CStrings:
- "TrustedClockingClient: ERROR - Missing required entitlement to send start signal to kernel workloop"
- "TrustedClockingClient: ERROR - Missing required entitlement to send stop signal to kernel workloop"
- "TrustedClockingClient: Failed to send start signal to kernel workloop: 0x%x"
- "TrustedClockingClient: Failed to send stop signal to kernel workloop: 0x%x"
- "TrustedClockingClient: Kernel workloop start signal sent successfully"
- "TrustedClockingClient: Kernel workloop stop signal sent successfully"
- "TrustedClockingClient: Signaling kernel workloop to start with use case ID %u"
- "TrustedClockingClient: Signaling kernel workloop to stop"
- "TrustedClockingManager: Failed to signal kernel workloop to start with use case ID %u"
- "TrustedClockingManager: Failed to signal kernel workloop to stop"
- "TrustedClockingManager: Signaling kernel workloop to start"
- "TrustedClockingManager: Signaling kernel workloop to stop"
```
