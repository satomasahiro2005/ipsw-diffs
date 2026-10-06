## AppleGameControllerPersonality

> `/System/Library/Extensions/AppleGameControllerPersonality.kext/AppleGameControllerPersonality`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1a64` | `0x1d94` | **`+0x330`** |
| `__DATA_CONST.__const` | `0x1510` | `0x1388` | **`-0x188`** |
| `__TEXT.__os_log` | `0x76` | `0xc0` | **`+0x4a`** |
| `__TEXT.__cstring` | `0x22b` | `0x235` | **`+0xa`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`

### Other Changes

```diff

-14.0.17.0.0
-  Functions: 58
-  Symbols:   364
-  CStrings:  29
+14.0.19.0.0
+  Functions: 57
+  Symbols:   362
+  CStrings:  28
Symbols:
+ _GLOBAL__sub_I_AppleGCIOHIDEventDriverPropertyMerger.cpp
+ _OUTLINED_FUNCTION_1
+ __ZL41AppleGCIOHIDEventDriverPropertyMerger_ktv
+ __ZN15IORegistryEntry18getRegistryEntryIDEv
+ __ZN17IOHIDEventService9metaClassE
+ __ZN37AppleGCIOHIDEventDriverPropertyMerger10gMetaClassE
+ __ZN37AppleGCIOHIDEventDriverPropertyMerger10superClassE
+ __ZN37AppleGCIOHIDEventDriverPropertyMerger5probeEP9IOServicePi
+ __ZN37AppleGCIOHIDEventDriverPropertyMerger9MetaClassC1Ev
+ __ZN37AppleGCIOHIDEventDriverPropertyMerger9MetaClassC2Ev
+ __ZN37AppleGCIOHIDEventDriverPropertyMerger9MetaClassD0Ev
+ __ZN37AppleGCIOHIDEventDriverPropertyMerger9MetaClassD1Ev
+ __ZN37AppleGCIOHIDEventDriverPropertyMerger9metaClassE
+ __ZN37AppleGCIOHIDEventDriverPropertyMergerC1EPK11OSMetaClass
+ __ZN37AppleGCIOHIDEventDriverPropertyMergerC1Ev
+ __ZN37AppleGCIOHIDEventDriverPropertyMergerC2EPK11OSMetaClass
+ __ZN37AppleGCIOHIDEventDriverPropertyMergerC2Ev
+ __ZN37AppleGCIOHIDEventDriverPropertyMergerD0Ev
+ __ZN37AppleGCIOHIDEventDriverPropertyMergerD1Ev
+ __ZN37AppleGCIOHIDEventDriverPropertyMergerD2Ev
+ __ZN37AppleGCIOHIDEventDriverPropertyMergerdlEPvm
+ __ZN37AppleGCIOHIDEventDriverPropertyMergernwEm
+ __ZNK37AppleGCIOHIDEventDriverPropertyMerger12getMetaClassEv
+ __ZNK37AppleGCIOHIDEventDriverPropertyMerger9MetaClass5allocEv
+ __ZTV37AppleGCIOHIDEventDriverPropertyMerger
+ __ZTVN37AppleGCIOHIDEventDriverPropertyMerger9MetaClassE
+ __ZZN25AppleGCHIDUserEventDriver11handleStartEP9IOServiceE11_os_log_fmt
+ __ZZN37AppleGCIOHIDEventDriverPropertyMerger5probeEP9IOServicePiE11_os_log_fmt
- _GLOBAL__sub_I_AppleGCHIDEventDummyService.cpp
- __ZL31AppleGCHIDEventDummyService_ktv
- __ZN27AppleGCHIDEventDummyService10gMetaClassE
- __ZN27AppleGCHIDEventDummyService10superClassE
- __ZN27AppleGCHIDEventDummyService11handleStartEP9IOService
- __ZN27AppleGCHIDEventDummyService11setPropertyEPK8OSSymbolP8OSObject
- __ZN27AppleGCHIDEventDummyService12didTerminateEP9IOServicejPb
- __ZN27AppleGCHIDEventDummyService5probeEP9IOServicePi
- __ZN27AppleGCHIDEventDummyService9MetaClassC1Ev
- __ZN27AppleGCHIDEventDummyService9MetaClassC2Ev
- __ZN27AppleGCHIDEventDummyService9MetaClassD0Ev
- __ZN27AppleGCHIDEventDummyService9MetaClassD1Ev
- __ZN27AppleGCHIDEventDummyService9metaClassE
- __ZN27AppleGCHIDEventDummyServiceC1EPK11OSMetaClass
- __ZN27AppleGCHIDEventDummyServiceC1Ev
- __ZN27AppleGCHIDEventDummyServiceC2EPK11OSMetaClass
- __ZN27AppleGCHIDEventDummyServiceC2Ev
- __ZN27AppleGCHIDEventDummyServiceD0Ev
- __ZN27AppleGCHIDEventDummyServiceD1Ev
- __ZN27AppleGCHIDEventDummyServiceD2Ev
- __ZN27AppleGCHIDEventDummyServicedlEPvm
- __ZN27AppleGCHIDEventDummyServicenwEm
- __ZNK27AppleGCHIDEventDummyService12getMetaClassEv
- __ZNK27AppleGCHIDEventDummyService9MetaClass5allocEv
- __ZTV27AppleGCHIDEventDummyService
- __ZTVN27AppleGCHIDEventDummyService9MetaClassE
- __ZZN27AppleGCHIDEventDummyService5probeEP9IOServicePiE11_os_log_fmt
- __ZZN27AppleGCHIDEventDummyService5probeEP9IOServicePiE11_os_log_fmt_0
- _kOSBooleanTrue
- _strlen
CStrings:
+ "AppleGCHIDUserEventDriver::handleStart(<IOHIDInterface %#010llx>)"
+ "AppleGCHIDUserEventDriver::probe(<IOHIDDevice %#010llx>)"
+ "AppleGCIOHIDEventDriverPropertyMerger"
+ "AppleGCIOHIDEventDriverPropertyMerger::probe(<IOHIDDevice %#010llx>)"
+ "Built-In"
+ "GameControllerCapabilities"
+ "GameControllerEligible"
+ "GameControllerSupport"
+ "GameControllerType"
+ "site.AppleGCIOHIDEventDriverPropertyMerger"
- "AppleGCHIDEventDummyService"
- "AppleGCHIDEventDummyService::probe()"
- "AppleGCHIDEventDummyService::probe() matched!"
- "AppleGCHIDUserEventDriver::probe()"
- "GameControllerSupportedHIDDevice"
- "GamepadHIDServiceSupport"
- "HIDRMOverride"
- "HIDServiceSupport"
- "Register"
- "com.apple."
- "site.AppleGCHIDEventDummyService"
```
