## AppleGameControllerPersonality

> `/System/Library/Extensions/AppleGameControllerPersonality.kext/AppleGameControllerPersonality`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1de0` | `0x26a4` | **`+0x8c4`** |
| `__DATA_CONST.__const` | `0x1388` | `0x1b20` | **`+0x798`** |
| `__TEXT.__os_log` | `0xc0` | `0x17e` | **`+0xbe`** |
| `__TEXT.__cstring` | `0x24b` | `0x2dc` | **`+0x91`** |
| `__DATA_CONST.__kalloc_type` | `0xc0` | `0x100` | **`+0x40`** |
| `__DATA.__common` | `0x88` | `0xb0` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x70` | `0x80` | **`+0x10`** |
| `__TEXT_EXEC.__auth_stubs` | `0x140` | `0x150` | **`+0x10`** |
| `__DATA.__bss` | `0x10` | `0x18` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xa0` | `0xa8` | **`+0x8`** |
| `__DATA_CONST.__mod_init_func` | `0x18` | `0x20` | **`+0x8`** |
| `__DATA_CONST.__mod_term_func` | `0x18` | `0x20` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`

### Other Changes

```diff

-14.0.21.0.0
-  Functions: 57
-  Symbols:   362
-  CStrings:  29
+14.0.24.0.0
+  Functions: 77
+  Symbols:   395
+  CStrings:  38
Symbols:
+ _GLOBAL__sub_I_SteamControllerUserEventDriver.cpp
+ __ZL34SteamControllerUserEventDriver_ktv
+ __ZN15OSMetaClassBase9_ptmf2ptfEPKS_MS_FvvE
+ __ZN30SteamControllerUserEventDriver10gMetaClassE
+ __ZN30SteamControllerUserEventDriver10superClassE
+ __ZN30SteamControllerUserEventDriver11handleStartEP9IOService
+ __ZN30SteamControllerUserEventDriver17handleInputReportEyjPvm
+ __ZN30SteamControllerUserEventDriver21handleInterruptReportEyP18IOMemoryDescriptor15IOHIDReportTypej
+ __ZN30SteamControllerUserEventDriver21handleInterruptReportEyP18IOMemoryDescriptor15IOHIDReportTypej_vfpthunk_
+ __ZN30SteamControllerUserEventDriver5probeEP9IOServicePi
+ __ZN30SteamControllerUserEventDriver9MetaClassC1Ev
+ __ZN30SteamControllerUserEventDriver9MetaClassC2Ev
+ __ZN30SteamControllerUserEventDriver9MetaClassD0Ev
+ __ZN30SteamControllerUserEventDriver9MetaClassD1Ev
+ __ZN30SteamControllerUserEventDriver9metaClassE
+ __ZN30SteamControllerUserEventDriverC1EPK11OSMetaClass
+ __ZN30SteamControllerUserEventDriverC1Ev
+ __ZN30SteamControllerUserEventDriverC2EPK11OSMetaClass
+ __ZN30SteamControllerUserEventDriverC2Ev
+ __ZN30SteamControllerUserEventDriverD0Ev
+ __ZN30SteamControllerUserEventDriverD1Ev
+ __ZN30SteamControllerUserEventDriverD2Ev
+ __ZN30SteamControllerUserEventDriverdlEPvm
+ __ZN30SteamControllerUserEventDrivernwEm
+ __ZNK30SteamControllerUserEventDriver12getMetaClassEv
+ __ZNK30SteamControllerUserEventDriver9MetaClass5allocEv
+ __ZTV15IORegistryEntry
+ __ZTV30SteamControllerUserEventDriver
+ __ZTVN30SteamControllerUserEventDriver9MetaClassE
+ __ZZN30SteamControllerUserEventDriver11handleStartEP9IOServiceE11_os_log_fmt
+ __ZZN30SteamControllerUserEventDriver17handleInputReportEyjPvmE11_os_log_fmt
+ __ZZN30SteamControllerUserEventDriver17handleInputReportEyjPvmE11_os_log_fmt_0
+ _gIOServicePlane
CStrings:
+ "121111121222121211111112112"
+ "GCIOMatchVirtual"
+ "RegisterService"
+ "SteamControllerUserEventDriver"
+ "SteamControllerUserEventDriver connected; registering service"
+ "SteamControllerUserEventDriver disconnected; terminating"
+ "SteamControllerUserEventDriver::handleStart(<IOHIDInterface %#010llx>)"
+ "bInterfaceNumber"
+ "site.SteamControllerUserEventDriver"
```
