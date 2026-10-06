## libCommCenterBase.dylib

> `/System/Library/Frameworks/CoreTelephony.framework/Support/libCommCenterBase.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd3718` | `0xd3060` | **`-0x6b8`** |
| `__TEXT.__cstring` | `0x14af1` | `0x148df` | **`-0x212`** |
| `__TEXT.__oslogstring` | `0x2849` | `0x26f1` | **`-0x158`** |
| `__DATA_CONST.__const` | `0x7700` | `0x7658` | **`-0xa8`** |
| `__AUTH_CONST.__const` | `0x143b8` | `0x14380` | **`-0x38`** |
| `__TEXT.__gcc_except_tab` | `0x13e44` | `0x13e24` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0xc48` | `0xc38` | **`-0x10`** |
| `__TEXT.__const` | `0xce50` | `0xce40` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x4e88` | `0x4e80` | **`-0x8`** |

### Other Changes

```diff

-13496.3.0.0.0
+13498.0.0.0.0

-  Symbols:   9438
-  CStrings:  4501
+  Symbols:   9435
+  CStrings:  4467
Symbols:
+ ___TUAssertTrigger
- _TelephonyUtilIsOversteerEnabled
- __ZNK3xpc6object9to_stringEv
- __ZZ29cellularInterfaceNameForIndexiE24kOversteerInterfaceNames
- __os_log_debug_impl
Functions:
~ __ZN10subscriber9isSimDeadENS_8SimStateE : 88 -> 64
~ __ZN10subscriber12isSimPresentENS_8SimStateE : 88 -> 64
~ __Z25PersonalityIdFromSlotIdExRKNSt3__110shared_ptrIK8RegistryEEN10subscriber7SimSlotE : 1012 -> 688
~ __ZNK13DisplayStatus9dumpStateEPKN3ctu11OsLogLoggerE : 172 -> 4
~ __ZN13CSIPDPManager20getInterfaceNameByIdEiRNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE : 124 -> 88
~ __ZN19SignalStrengthModel11handleInputENSt3__110shared_ptrIK6InputsEE : 424 -> 248
~ __ZN16HelperRestServer17handleRestMessageERKNSt3__110shared_ptrIN3ctu22RestResourceConnectionEEEN3xpc4dictE : 680 -> 532
~ __ZN16HelperRestServer26handleRestMessageWithReplyERKNSt3__110shared_ptrIN3ctu22RestResourceConnectionEEEN3xpc4dictENS0_8functionIFvNS7_6objectEEEE : 780 -> 624
~ __ZN16HelperRestServer23handleDroppedConnectionERKNSt3__110shared_ptrIN3ctu22RestResourceConnectionEEEN3xpc6objectE : 432 -> 352
~ __Z34getActiveFakePositiveInterfaceName18DataConnectionType : 88 -> 28
~ __Z17getGsm7TableIndexN3sms12TextEncodingE : 88 -> 64
~ __ZNK20FeatureConfiguration40isFakingSuccessfulBasebandRequestEnabledEv : 4 -> 8
~ __ZN10subscriber21isSimInTransientStateENS_8SimStateE : 88 -> 64
~ __ZN10subscriber11isSimAbsentENS_8SimStateE : 88 -> 64
~ __ZN10subscriber13isSimInsertedENS_8SimStateE : 88 -> 64
~ __ZN10subscriber15isSimUnreadableENS_8SimStateE : 88 -> 64
~ __ZN10subscriber10isSimReadyENS_8SimStateE : 88 -> 64
~ __ZN10subscriber12isSimSettledENS_8SimStateE : 88 -> 64
~ __ZN10subscriber11isSimLockedENS_8SimStateE : 88 -> 64
~ __ZN10subscriber18isSimReadyOrLockedENS_8SimStateE : 88 -> 64
~ __ZN10subscriber23isSimPermanentlyBlockedENS_8SimStateE : 88 -> 64
~ __ZN10subscriber20isSimPresentAndValidENS_8SimStateE : 88 -> 64
~ __ZNK12BasicSimInfo22isEmptyEsimCapableCardEv : 116 -> 92
~ __ZN12OTASPService20sendOTASPSuccessToUIEv : 516 -> 448
~ __ZN10LineParser15parseFromStreamEPKN3ctu11OsLogLoggerERNSt3__113basic_istreamIcNS4_11char_traitsIcEEEENS4_8functionIFvRKNS4_12basic_stringIcS7_NS4_9allocatorIcEEEEEEE : 2356 -> 2284
~ __Z18isXLAT464InterfacePKc : 184 -> 168
~ __Z20getCLAT46IPv6AddressPKcRjPhRS0_ : 608 -> 588
~ __ZN9DataUtils27loadPlistFromBundleResourceEPKN3ctu11OsLogLoggerEPKc : 460 -> 396
CStrings:
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreTelephony/CSI/Source/Common/SmsPduEncoder.cpp"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CoreTelephony/CommCenter/CommCenterCommandDrivers/Sim/SubscriberDefinitions.cpp"
- "Assertion failure: ( %s ), in file %s, line: %d"
- "DisplayStatus [isOn=%{bool}d, isLocked=%{bool}d, isCoversheetActive=%{bool}d, isPasscodeSet=%{bool}d, isEffectivelyLocked=%{bool}d]"
- "Getting main bundle"
- "Input(%s) = %f"
- "Parsed %zu lines successfully"
- "Personality Info: %s - %s"
- "Sending OTASP success dialogue to UI"
- "ThumperID: %s, info: %p"
- "[conn %p] Connection closed."
- "[conn %p] Got REST message: %s"
- "feth0"
- "feth1"
- "feth10"
- "feth11"
- "feth12"
- "feth13"
- "feth14"
- "feth15"
- "feth16"
- "feth17"
- "feth18"
- "feth19"
- "feth2"
- "feth20"
- "feth3"
- "feth4"
- "feth5"
- "feth6"
- "feth7"
- "feth8"
- "feth9"
- "not active"
```
