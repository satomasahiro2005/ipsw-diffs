## AppleIDSetupUI

> `/System/Library/PrivateFrameworks/AppleIDSetupUI.framework/AppleIDSetupUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x187868` | `0x189654` | **`+0x1dec`** |
| `__TEXT.__eh_frame` | `0xb0d8` | `0xb410` | **`+0x338`** |
| `__TEXT.__oslogstring` | `0xb6ad` | `0xb95d` | **`+0x2b0`** |
| `__AUTH_CONST.__objc_const` | `0x11928` | `0x11ac0` | **`+0x198`** |
| `__TEXT.__const` | `0xd7f4` | `0xd944` | **`+0x150`** |
| `__DATA.__bss` | `0x8168` | `0x8268` | **`+0x100`** |
| `__TEXT.__swift5_reflstr` | `0x3ec2` | `0x3fc2` | **`+0x100`** |
| `__AUTH.__data` | `0x3b20` | `0x3c10` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x56a0` | `0x5760` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x3588` | `0x3620` | **`+0x98`** |
| `__AUTH_CONST.__const` | `0xa920` | `0xa9b0` | **`+0x90`** |
| `__TEXT.__cstring` | `0x4e89` | `0x4f09` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x56a4` | `0x5704` | **`+0x60`** |
| `__TEXT.__swift_as_ret` | `0x424` | `0x454` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x8dc` | `0x908` | **`+0x2c`** |
| `__DATA.__data` | `0x5728` | `0x5708` | **`-0x20`** |
| `__TEXT.__swift_as_entry` | `0x458` | `0x474` | **`+0x1c`** |
| `__TEXT.__swift5_typeref` | `0xef16` | `0xef28` | **`+0x12`** |
| `__AUTH.__objc_data` | `0x5168` | `0x5158` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2520` | `0x2510` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x14f0` | `0x14e8` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x300` | `0x308` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x4b8` | `0x4c0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x3b0` | `0x3b8` | **`+0x8`** |

### Other Changes

```diff

-128.1.1.0.0
+129.125.3.0.0

-  Functions: 7233
-  Symbols:   3189
-  CStrings:  1281
+  Functions: 7268
+  Symbols:   3195
+  CStrings:  1289
Symbols:
+ __DATA__TtC14AppleIDSetupUI28AgeVerificationConfiguration
+ __IVARS__TtC14AppleIDSetupUI28AgeVerificationConfiguration
+ __METACLASS_DATA__TtC14AppleIDSetupUI28AgeVerificationConfiguration
+ _associated conformance 14AppleIDSetupUI19AgeVerificationModeOSHAASQ
+ _symbolic _____ 14AppleIDSetupUI19AgeVerificationModeO
+ _symbolic _____ 14AppleIDSetupUI28AgeVerificationConfigurationC
+ _symbolic _____Sg 14AppleIDSetupUI28AgeVerificationConfigurationC
+ _symbolic ______p 14AppleIDSetupUI16AKDeviceProtocolP
+ _symbolic ______pXp 14AppleIDSetupUI27AISSelfieFaceIDTaskProtocolP
+ _symbolic ______pXp 14AppleIDSetupUI36PASAgeVerificationControllerProtocolP
- _symbolic _____Sg 12AppleIDSetup19AgeAssuranceContextC
- _symbolic ______p 12AppleIDSetup25AISScreenTimeShimProtocolP
- _symbolic ______pSg 14AppleIDSetupUI27AISSelfieFaceIDTaskProtocolP
- _symbolic ______pXpSg 14AppleIDSetupUI36PASAgeVerificationControllerProtocolP
CStrings:
+ "AgeAssuranceFlowPresenter - background Face ID verification failed; applying WCF/CS - %@"
+ "AgeAssuranceFlowPresenter - background Face ID verification succeeded; account verified, no restrictions applied"
+ "AgeAssuranceFlowPresenter - background mode could not verify without UI; applying WCF/CS"
+ "AgeAssuranceFlowPresenter - background mode resolved a regulatory step; applying WCF/CS without presenting AVK UI"
+ "AgeAssuranceFlowPresenter - background mode: presenter unexpectedly nil"
+ "AgeVerificationPresenter - createWithAuthResponse called without authResponse"
+ "AgeVerificationPresenter.createRegulatoryStep - bag is nil, cannot build regulatory fallback step"
+ "AgeVerificationPresenter.prepareVerificationUI - background mode: re-throwing selfie failure to caller"
+ "Applied WCF/CS account restrictions in background - %{bool}d"
+ "Applying WCF/CS account restrictions in background"
+ "Failed to apply account restrictions in background with error: %@"
+ "WCF/CS restrictions reported not applied without an error"
+ "WCF/CS restrictions reported not applied without an error for no-account flow"
+ "WCF/CS restrictions were not applied"
- "AgeAssuranceFlowPresenter - restrictions-only flow detected, applying background restrictions"
- "Applying background restrictions for unverified adult via ScreenTime shim"
- "Applying restrictions for no-account scenario"
- "Failed to apply background restrictions with error: %@"
- "Successfully applied background restrictions"
- "Successfully applied restrictions for no-account scenario - %{bool}d"
```
