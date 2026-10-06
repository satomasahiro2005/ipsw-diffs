## IOAccessoryManager

> `/System/Library/CoreAccessories/PlugIns/Transports/IOAccessoryManager.transport/IOAccessoryManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0xbb84` | `0xbc14` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x4ce0` | `0x4d10` | **`+0x30`** |
| `__TEXT.__text` | `0x5d0cc` | `0x5d0a0` | **`-0x2c`** |
| `__TEXT.__unwind_info` | `0xe78` | `0xea0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x4540` | `0x4560` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2f4c` | `0x2f64` | **`+0x18`** |
| `__DATA_CONST.__const` | `0xec8` | `0xed8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1ee8` | `0x1ef8` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x8d0` | `0x8dc` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x468` | `0x46c` | **`+0x4`** |
| `__TEXT.__cstring` | `0x5fab` | `0x5faa` | **`-0x1`** |

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1

-  Functions: 1943
-  Symbols:   2830
+  Functions: 1941
+  Symbols:   2832
Symbols:
+ -[ACCTransportIOAccessoryAuthCP deferredAuthChallenge]
+ -[ACCTransportIOAccessoryAuthCP setDeferredAuthChallenge:]
+ -[ACCTransportIOAccessorySharedManager _connectionWithUUIDHasActiveEndpoint:]
+ _ACCUserDefaultsKey_PretendWirelessCTAMatch
+ _OBJC_IVAR_$_ACCTransportIOAccessoryAuthCP._deferredAuthChallenge
+ _kCFACCUserDefaultsKey_PretendWirelessCTAMatch
- -[ACCTransportIOAccessorySharedManager _managerForConnectionUUIDHasActiveEndpoint:]
- _OUTLINED_FUNCTION_68
- _OUTLINED_FUNCTION_69
- _OUTLINED_FUNCTION_70
CStrings:
+ "%s: connectionUUID %@ has %lu endpoint(s) %@ but no manager — orphans, ready for destroy"
+ "%s: connectionUUID %@ has %lu remaining endpoint(s) %@, none owned by a live port or manager — ready for destroy (orphans cascade)"
+ "%s: connectionUUID %@ has 0 endpoints, ready for destroy"
+ "%s: endpoint %@ on connection %@ is still claimed by live port (class %@)"
+ "-[ACCTransportIOAccessorySharedManager _connectionWithUUIDHasActiveEndpoint:]"
+ "ERROR: Failed to register for notifications from AppleAuthCP ioService:%04X, fail status:%04X\n"
+ "PretendWirelessCTAMatch"
- "ACMCredential - ACMCredentialDataPKITokenValidated"
- "ACMCredential - ACMCredentialDataPKITokenValidated2"
- "ERROR: Failed to register for notifactions from AppleAuthCP ioService:%04X, fail status:%04X\n"
- "found IOAccessoryConfigStream with active endpointUUID %@"
- "found IOAccessoryEA with active endpointUUID %@"
- "found IOAccessoryOOBPairing with active endpointUUID %@"
- "found IOAccessoryPort with active endpointUUID %@"
```
