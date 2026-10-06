## Nexus

> `/System/Library/PrivateFrameworks/Nexus.framework/Nexus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10c68c` | `0x111910` | **`+0x5284`** |
| `__DATA.__bss` | `0x12ad0` | `0x13450` | **`+0x980`** |
| `__TEXT.__const` | `0xba68` | `0xc0e8` | **`+0x680`** |
| `__AUTH_CONST.__const` | `0x95f8` | `0x9860` | **`+0x268`** |
| `__TEXT.__swift5_fieldmd` | `0x2b80` | `0x2cd0` | **`+0x150`** |
| `__TEXT.__eh_frame` | `0x7d08` | `0x7e20` | **`+0x118`** |
| `__DATA.__data` | `0x25a0` | `0x2490` | **`-0x110`** |
| `__TEXT.__swift5_reflstr` | `0x21b3` | `0x22a3` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x3940` | `0x3a28` | **`+0xe8`** |
| `__TEXT.__oslogstring` | `0x3650` | `0x3730` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x3148` | `0x3218` | **`+0xd0`** |
| `__TEXT.__swift5_assocty` | `0x600` | `0x6c0` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x1f3c` | `0x1f90` | **`+0x54`** |
| `__TEXT.__swift5_proto` | `0x978` | `0x9c4` | **`+0x4c`** |
| `__TEXT.__swift5_typeref` | `0x30a4` | `0x30ee` | **`+0x4a`** |
| `__DATA_CONST.__objc_protolist` | `0x40` | `0x20` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0x508` | `0x520` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1478` | `0x1468` | **`-0x10`** |
| `__AUTH_CONST.__objc_const` | `0x20a0` | `0x2090` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x280` | `0x290` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x20` | `0x10` | **`-0x10`** |
| `__TEXT.__swift5_mpenum` | `0x118` | `0x128` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x1dc4` | `0x1dd0` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x2bc` | `0x2c8` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x214` | `0x220` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x224` | `0x22c` | **`+0x8`** |

### Other Changes

```diff

-900.25.0.0.0
+900.37.0.0.0

-  Functions: 4856
-  Symbols:   1466
-  CStrings:  755
+  Functions: 4975
+  Symbols:   1473
+  CStrings:  769
Symbols:
+ ___swift_closure_destructor.221Tm
+ ___swift_closure_destructor.305Tm
+ ___swift_memcpy41_8
+ ___swift_memcpy64_8
+ _associated conformance 5Nexus22NXProximityServiceDataO014CompanionSetupD0V10OtherFlagsVs10SetAlgebraAASQ
+ _associated conformance 5Nexus22NXProximityServiceDataO014CompanionSetupD0V10OtherFlagsVs10SetAlgebraAAs25ExpressibleByArrayLiteral
+ _associated conformance 5Nexus22NXProximityServiceDataO014CompanionSetupD0V10OtherFlagsVs9OptionSetAASY
+ _associated conformance 5Nexus22NXProximityServiceDataO014CompanionSetupD0V10OtherFlagsVs9OptionSetAAs0J7Algebra
+ _associated conformance 5Nexus22NXProximityServiceDataO014CompanionSetupD0V6ActionOSHAASQ
+ _associated conformance 5Nexus22NXProximityServiceDataO014CompanionSetupD0V6ActionOs12CaseIterableAA8AllCasessAHP_Sl
+ _associated conformance 5Nexus9NXSessionC16MessageKeyNumberOSHAASQ
+ _symbolic Say_____G 5Nexus22NXProximityServiceDataO014CompanionSetupD0V6ActionO
+ _symbolic _____ 5Nexus22NXProximityServiceDataO014CompanionSetupD0V10OtherFlagsV
+ _symbolic _____ 5Nexus22NXProximityServiceDataO014CompanionSetupD0V6ActionO
+ _symbolic _____ 5Nexus9NXSessionC16MessageKeyNumberO
+ _symbolic _____Sg 14CoreUtilsSwift7CUTimerC
+ _symbolic _____Sg 5Nexus22NXProximityServiceDataO014CompanionSetupD0V6ActionO
+ _symbolic _____ySiSbG s18_DictionaryStorageC
+ _symbolic _____y_____G 14CoreUtilsSwift12CUOmitCodingV 5Nexus12NXConnectionC
+ _type_layout_string 5Nexus16NXHandlerOptionsV
+ _xpc_copy_entitlement_for_token
+ _xpc_dictionary_get_bool
- _OBJC_CLASS_$_OS_dispatch_source
- __OBJC_$_PROTOCOL_REFS_OS_dispatch_source
- __OBJC_$_PROTOCOL_REFS_OS_dispatch_source_timer
- __OBJC_LABEL_PROTOCOL_$_OS_dispatch_source
- __OBJC_LABEL_PROTOCOL_$_OS_dispatch_source_timer
- __OBJC_PROTOCOL_$_OS_dispatch_source
- __OBJC_PROTOCOL_$_OS_dispatch_source_timer
- ___swift_closure_destructor.214Tm
- ___swift_closure_destructor.298Tm
- ___swift_memcpy24_8
- ___swift_memcpy49_8
- ___swift_memcpy97_8
- _flat unique So24OS_dispatch_source_timer_p
- _symbolic Say_____G So18OS_dispatch_sourceC8DispatchE10TimerFlagsV
- _symbolic ______pSg So24OS_dispatch_source_timerP
CStrings:
+ "### Activate failed: clientID=%llu, endpoint=%s, error=%@"
+ "### Invalidate failed: clientID=%llu, endpoint=%s, error=%@"
+ "### Send request failed: requestName=%s, clientID=%llu, error=%@"
+ "### Send request start failed: requestName=%s, clientID=%llu, error=%@"
+ "### Try password failed: clientID=%llu, error=%@"
+ "AuthTag bad size: actual="
+ "Finish with no file URL"
+ "LECAHap"
+ "LECAHapLow"
+ "LECATmap"
+ "LECATmapLow"
+ "[%s] ### received unencrypted frame after security established"
+ "[%s] request dropped (test): xid=%s, name=%s"
+ "[%s] request retry exhausted: xid=%{public}s, name=%{public}s, retries=%ld"
+ "[%s] request retry: xid=%{public}s, name=%{public}s, attempt=%ld"
+ "action"
+ "authTag"
+ "color"
+ "dropRequestCount="
+ "flags"
+ "maxSize must be positive"
+ "model"
+ "otherFlags"
+ "requests"
+ "setUpRecognition"
+ "setupID"
- "### Activate failed: clientID=%llu), endpoint=%s, error=%s"
- "### Activate failed: clientID=%llu, endpoint=%s, error=%s"
- "### Invalidate failed: clientID=%llu, endpoint=%s, error=%s"
- "### Send request failed: requestName=%s, clientID=%llu, error=%s"
- "### Send request start failed: requestName=%s, clientID=%llu, error=%s"
- "Finish with file URL"
- "LECA1"
- "LECA2"
- "LECA3"
- "LECA4"
- "[%s] AWDL delay connect workaround"
- "requestNames"
```
