## Rapport

> `/System/Library/PrivateFrameworks/Rapport.framework/Rapport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd9624` | `0xddf34` | **`+0x4910`** |
| `__TEXT.__oslogstring` | `0x242d` | `0x26fd` | **`+0x2d0`** |
| `__TEXT.__const` | `0x3f68` | `0x41b8` | **`+0x250`** |
| `__AUTH_CONST.__const` | `0x2658` | `0x27c0` | **`+0x168`** |
| `__TEXT.__cstring` | `0x144ac` | `0x145fc` | **`+0x150`** |
| `__AUTH_CONST.__objc_const` | `0x112f8` | `0x113e8` | **`+0xf0`** |
| `__TEXT.__swift5_capture` | `0x890` | `0x950` | **`+0xc0`** |
| `__TEXT.__objc_methlist` | `0x9f48` | `0x9fe0` | **`+0x98`** |
| `__AUTH.__objc_data` | `0x1280` | `0x1300` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0xbd5` | `0xc4f` | **`+0x7a`** |
| `__DATA_CONST.__objc_selrefs` | `0x44e0` | `0x4558` | **`+0x78`** |
| `__AUTH_CONST.__cfstring` | `0x60a0` | `0x6100` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0x1140` | `0x1178` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x2ed0` | `0x2f00` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x27e8` | `0x2810` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0xd94` | `0xdbc` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x91c` | `0x93c` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x240` | `0x258` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x14c4` | `0x14d8` | **`+0x14`** |
| `__DATA.__data` | `0x20d8` | `0x20e8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x4d0` | `0x4e0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xb28` | `0xb34` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x2c8` | `0x2d0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x10f4` | `0x10f8` | **`+0x4`** |

### Other Changes

```diff

-751.100.2.0.0
+751.200.31.0.0

-  Functions: 5746
-  Symbols:   6761
-  CStrings:  3009
+  Functions: 5785
+  Symbols:   6793
+  CStrings:  3030
Symbols:
+ +[RPNWTXTUtils statusFlagsForEndpoint:]
+ +[RPNWTXTUtils statusFlagsForTXTRecord:]
+ +[RPNWTXTUtils updateStatusFlags:onEndpoint:operation:]
+ +[RPNWTXTUtils updateStatusFlags:onTXTRecord:operation:]
+ -[RPClient endpointContextForService:trustCircles:completion:]
+ -[RPClient updateEndpointAttributes:forService:usingContext:completion:]
+ -[RPConnection _identityDaemonGetPairingIdentityFromHomeWithAccessory:completion:]
+ -[RPConnection _requestIDIsHighVolume:messageIsChatty:]
+ -[RPSiriSession _triggerInfoRequest]
+ -[RPSiriSession setTriggerDurationMs:]
+ -[RPSiriSession setTwoShotFeedbackDelaySec:]
+ -[RPSiriSession triggerDurationMs]
+ -[RPSiriSession twoShotFeedbackDelaySec]
+ GCC_except_table280
+ GCC_except_table73
+ GCC_except_table92
+ _OBJC_CLASS_$_NSScanner
+ _OBJC_CLASS_$_RPNWTXTUtils
+ _OBJC_IVAR_$_RPSiriSession._triggerDurationMs
+ _OBJC_IVAR_$_RPSiriSession._twoShotFeedbackDelaySec
+ _OBJC_METACLASS_$_RPNWTXTUtils
+ __OBJC_$_CLASS_METHODS_RPNWTXTUtils
+ __OBJC_CLASS_RO_$_RPNWTXTUtils
+ __OBJC_METACLASS_RO_$_RPNWTXTUtils
+ ___40+[RPNWTXTUtils statusFlagsForTXTRecord:]_block_invoke
+ ___62-[RPClient endpointContextForService:trustCircles:completion:]_block_invoke
+ ___72-[RPClient updateEndpointAttributes:forService:usingContext:completion:]_block_invoke
+ ___block_descriptor_40_e8_32r_e19_B36?0r*8i16r*20Q28lr32l8
+ ___swift_closure_destructor.142Tm
+ ___swift_closure_destructor.154Tm
+ ___swift_closure_destructor.186Tm
+ ___swift_closure_destructor.253Tm
+ _nw_endpoint_copy_txt_record
+ _nw_endpoint_set_txt_record
+ _nw_txt_record_access_key
+ _nw_txt_record_create_dictionary
+ _nw_txt_record_set_key
+ _swift_deletedMethodError
+ _swift_retain_x28
+ _symbolic So10RPIdentityC
+ _symbolic So10RPIdentityCSgIeghg_
+ _symbolic So16CUPairingSessionCSgXw
+ _symbolic So16CUPairingSessionCSgXwz_Xx
+ _symbolic yySo10RPIdentityCSgYbccSg
- -[RPConnection _requestIDLogLevel:chatty:]
- GCC_except_table278
- GCC_except_table39
- GCC_except_table68
- GCC_except_table70
- GCC_except_table72
- GCC_except_table91
- _OBJC_IVAR_$_RPConnection._identityVerified
- ___swift_closure_destructor.143Tm
- ___swift_closure_destructor.175Tm
- ___swift_closure_destructor.242Tm
- ___swift_closure_destructor.250Tm
CStrings:
+ "-[RPClient endpointContextForService:trustCircles:completion:]"
+ "-[RPClient updateEndpointAttributes:forService:usingContext:completion:]"
+ "B36@?0r*8i16r*20Q28"
+ "Failed to resolve client HomeKit pairing identity for %s: %@"
+ "Identity daemon not available"
+ "PairVerify activate client"
+ "PairVerify activate client: session no longer current, ignoring"
+ "PairVerify client identity resolution result nil, will use default"
+ "PairVerify client identity resolution: session no longer current, ignoring"
+ "PairVerify client ignoring resolved identity %@, handler already set"
+ "PairVerify client will use resolved identity %@"
+ "PairVerify prepare client: AT %{public}s, CF %{public}s, FL %{public}s, PWT %{public}s"
+ "PairVerify will resolve client identity before activation"
+ "Requesting endpoint context for %@ with %#ll{flags}\n"
+ "Resolving client HomeKit pairing identity for %s"
+ "StatusFlags"
+ "Successfully resolved client HomeKit pairing identity for %s to %@"
+ "Unable to resolve client HomeKit pairing identity for %s"
+ "Updating endpoint %@ for %@ with context (%lu bytes)\n"
+ "_vtDurMs"
+ "_vtTwoShotSec"
+ "tutool"
- "PairVerify start client: AT %{public}s, CF %{public}s, FL %{public}s, PWT %{public}s"
```
