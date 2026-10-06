## AutoUnlockDaemon

> `/System/Library/PrivateFrameworks/AutoUnlockDaemon.framework/AutoUnlockDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c0f1c` | `0x1c19b0` | **`+0xa94`** |
| `__AUTH_CONST.__objc_const` | `0xca30` | `0xcc38` | **`+0x208`** |
| `__DATA.__bss` | `0x55a8` | `0x5428` | **`-0x180`** |
| `__AUTH.__data` | `0x6b18` | `0x6c78` | **`+0x160`** |
| `__AUTH_CONST.__const` | `0xcbc8` | `0xcb58` | **`-0x70`** |
| `__TEXT.__const` | `0xe6e8` | `0xe678` | **`-0x70`** |
| `__TEXT.__constg_swiftt` | `0x5da0` | `0x5e04` | **`+0x64`** |
| `__TEXT.__swift5_reflstr` | `0x39bf` | `0x3a11` | **`+0x52`** |
| `__DATA_DIRTY.__objc_data` | `0xaa0` | `0xae8` | **`+0x48`** |
| `__DATA.__data` | `0x2392` | `0x23c2` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x826a` | `0x829a` | **`+0x30`** |
| `__TEXT.__cstring` | `0x6fc2` | `0x6feb` | **`+0x29`** |
| `__TEXT.__objc_methlist` | `0x2bcc` | `0x2bf4` | **`+0x28`** |
| `__DATA_DIRTY.__data` | `0x1db8` | `0x1d98` | **`-0x20`** |
| `__TEXT.__eh_frame` | `0xaa98` | `0xaa78` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x14f0` | `0x1508` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x537c` | `0x5394` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x4552` | `0x456a` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0xed4` | `0xec8` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0x13c8` | `0x13d0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x238` | `0x240` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x50a8` | `0x50b0` | **`+0x8`** |

### Other Changes

```diff

-2118.10.4.2.3
+2122.10.2.2.1

-  Functions: 7839
-  Symbols:   3363
-  CStrings:  1432
+  Functions: 7834
+  Symbols:   3367
+  CStrings:  1431
Symbols:
+ -[SDAutoUnlockWiFiManager initForTestingWithQueue:niSession:wifiDevice:wifiStatusMonitor:]
+ -[SDAutoUnlockWiFiManager testForceFireAWDLBringUpTimer]
+ GCC_except_table115
+ GCC_except_table69
+ GCC_except_table73
+ GCC_except_table96
+ __DATA__TtC16AutoUnlockDaemon43SDAuthenticationTransportRapportNoInfraWiFi
+ __METACLASS_DATA__TtC16AutoUnlockDaemon43SDAuthenticationTransportRapportNoInfraWiFi
+ ___56-[SDAutoUnlockWiFiManager testForceFireAWDLBringUpTimer]_block_invoke
+ _swift_release_x14
+ _symbolic SSSgycSg
+ _symbolic _____ 16AutoUnlockDaemon43SDAuthenticationTransportRapportNoInfraWiFiC
+ _symbolic _____SgSDy_____ypGcSg 10Foundation4DataV So11CFStringRefa
- GCC_except_table112
- GCC_except_table68
- GCC_except_table72
- GCC_except_table95
- _OUTLINED_FUNCTION_68
- _OUTLINED_FUNCTION_69
- _OUTLINED_FUNCTION_70
- _associated conformance 16AutoUnlockDaemon19RapportFeatureFlagsOSHAASQ
- _symbolic _____ 16AutoUnlockDaemon19RapportFeatureFlagsO
CStrings:
+ "AutoUnlockDaemon.SDAuthenticationTransportRapportNoInfraWiFi"
+ "Failed to aks_validate_local_key. This may indicate the keys were migrated from a different device, keychain, or keybag"
+ "Failed to load LocalLTK from %s, error: %@"
+ "Failed to validate LocalLTK from %s, error: %@, will try to re-generate"
+ "rapportNoInfraWiFi"
- "ACMCredential - ACMCredentialDataPKITokenValidated"
- "ACMCredential - ACMCredentialDataPKITokenValidated2"
- "AlwaysOnBLEConnections"
- "Failed to aks_validate_local_key"
- "Pairing for siri is tied to Auto Unlock. Use SFAutoUnlockManager instead"
- "Rapport"
```
