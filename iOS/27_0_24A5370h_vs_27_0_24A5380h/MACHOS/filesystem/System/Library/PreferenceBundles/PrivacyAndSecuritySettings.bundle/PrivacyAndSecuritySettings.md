## PrivacyAndSecuritySettings

> `/System/Library/PreferenceBundles/PrivacyAndSecuritySettings.bundle/PrivacyAndSecuritySettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b018` | `0x8d510` | **`+0x24f8`** |
| `__TEXT.__eh_frame` | `0x2bb4` | `0x2e14` | **`+0x260`** |
| `__DATA.__data` | `0x3c50` | `0x3dc8` | **`+0x178`** |
| `__TEXT.__const` | `0x7254` | `0x73b4` | **`+0x160`** |
| `__DATA_CONST.__const` | `0x37a8` | `0x38e8` | **`+0x140`** |
| `__DATA.__objc_const` | `0x2d60` | `0x2e88` | **`+0x128`** |
| `__TEXT.__auth_stubs` | `0x2b40` | `0x2c10` | **`+0xd0`** |
| `__TEXT.__objc_methname` | `0x1e85` | `0x1f45` | **`+0xc0`** |
| `__TEXT.__swift5_capture` | `0xaa8` | `0xb4c` | **`+0xa4`** |
| `__DATA.__objc_data` | `0x8d0` | `0x970` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x1e38` | `0x1ed0` | **`+0x98`** |
| `__TEXT.__swift5_reflstr` | `0x1b01` | `0x1b91` | **`+0x90`** |
| `__DATA.__bss` | `0x3a18` | `0x3a98` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x1674` | `0x16f0` | **`+0x7c`** |
| `__TEXT.__objc_classname` | `0xcaa` | `0xd1a` | **`+0x70`** |
| `__DATA_CONST.__auth_got` | `0x15b0` | `0x1618` | **`+0x68`** |
| `__TEXT.__cstring` | `0x4256` | `0x41f6` | **`-0x60`** |
| `__TEXT.__constg_swiftt` | `0x15f0` | `0x164c` | **`+0x5c`** |
| `__TEXT.__swift5_typeref` | `0x7e8a` | `0x7e30` | **`-0x5a`** |
| `__DATA_CONST.__auth_ptr` | `0xce0` | `0xd38` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0xb91` | `0xbe1` | **`+0x50`** |
| `__DATA_CONST.__got` | `0xb08` | `0xb38` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x1d8` | `0x1f4` | **`+0x1c`** |
| `__TEXT.__swift_as_entry` | `0xd8` | `0xe4` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0xa8` | `0xb4` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x138` | `0x140` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x230` | `0x234` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x15c` | `0x160` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-1262.0.0.0.0
+2027.0.2.0.0

+  - /System/Library/PrivateFrameworks/CoreODI.framework/CoreODI

-  Functions: 2477
+  Functions: 2514

-  CStrings:  855
+  CStrings:  866
CStrings:
+ "Risk Detection availability"
+ "Risk Detection consent state"
+ "TrustInsightsListItemModelProvider: createConsentManager failed: %@"
+ "_TtC26PrivacyAndSecuritySettingsP33_14FAD36673BFA52B4A0BD3ADB2C9ECDC36TrustInsightsListItemConsentDelegate"
+ "com.apple.odi.trustinsights"
+ "consentDelegate"
+ "consentManager"
+ "consentStateTask"
+ "continuation"
+ "isRiskDetectionEnabled"
+ "logger"
+ "shouldShow"
+ "stateUpdates"
- "Accessibility label for log navigation link"
- "Allow apps to request Apple’s Impersonation Risk Detection signals to help detect if your device or account show signs of an active scam."
```
