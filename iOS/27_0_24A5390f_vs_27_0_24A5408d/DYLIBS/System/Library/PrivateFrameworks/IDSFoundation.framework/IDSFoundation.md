## IDSFoundation

> `/System/Library/PrivateFrameworks/IDSFoundation.framework/IDSFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ebbf4` | `0x4ed8f4` | **`+0x1d00`** |
| `__TEXT.__cstring` | `0x3499d` | `0x34c6d` | **`+0x2d0`** |
| `__AUTH_CONST.__objc_const` | `0x3ea40` | `0x3eca8` | **`+0x268`** |
| `__AUTH_CONST.__cfstring` | `0x2cb80` | `0x2cd80` | **`+0x200`** |
| `__TEXT.__ustring` | `0xc` | `0x188` | **`+0x17c`** |
| `__TEXT.__oslogstring` | `0x2b92a` | `0x2ba9a` | **`+0x170`** |
| `__AUTH.__objc_data` | `0xa598` | `0xa6d8` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0x1ba8c` | `0x1bbc4` | **`+0x138`** |
| `__TEXT.__constg_swiftt` | `0xc798` | `0xc85c` | **`+0xc4`** |
| `__DATA.__data` | `0xf258` | `0xf2e8` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0xb0a0` | `0xb120` | **`+0x80`** |
| `__TEXT.__const` | `0x3f720` | `0x3f790` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x14360` | `0x143c8` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x75c8` | `0x7620` | **`+0x58`** |
| `__TEXT.__gcc_except_tab` | `0xbb14` | `0xbb58` | **`+0x44`** |
| `__TEXT.__swift5_fieldmd` | `0xb674` | `0xb6b4` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0xb67e` | `0xb6b4` | **`+0x36`** |
| `__AUTH.__data` | `0xb0a8` | `0xb0d8` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x1a0a0` | `0x1a0c0` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x6b36` | `0x6b56` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x28a0` | `0x28b8` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x384` | `0x398` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x12b0` | `0x12b8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xea8` | `0xeb0` | **`+0x8`** |

### Other Changes

```diff

-2000.100.2.2.1
+2003.100.1.0.0

-  Functions: 31643
-  Symbols:   5088
-  CStrings:  8370
+  Functions: 31703
+  Symbols:   5093
+  CStrings:  8389
Symbols:
+ _IDSMessageContextLocalTraceIdentifierKey
+ _IDSMessageTraceIDKey
+ _IDSRegistrationPropertySupportsDedicatedChannelBaseFilterOverrideOpportunistic
+ _OBJC_CLASS_$_IDSDeregistrationDailyMetric
+ _OBJC_METACLASS_$_IDSDeregistrationDailyMetric
CStrings:
+ "%@ (idx %u)"
+ "(none)"
+ "(unnamed)"
+ "<%@: %p verifierResult: %@, ticket: %@, accountKey: %@, queryResponseTime: %@, verificationDate: %@>, ktOptInStatus: %@"
+ "DatagramChannelHBHSecretLogging"
+ "GL getInterfaceFamily"
+ "HBH secret logging: sessionID = %@, participantID = %llu, relaySessionKey = %@, salt = %@, hbhEncKey = %@, hbhDecKey = %@"
+ "IDSFoundation.IDSDeregistrationDailyMetric"
+ "IDSMessageContextLocalTraceIdentifierKey"
+ "IDSMessageTraceID"
+ "IDSSendParametersTraceID"
+ "Remote App Intents"
+ "VerificationDate"
+ "_postProcessQUICAllocbindResponse: HBH keys already derived (in deriveAES128CTRKeys); keeping them for %@."
+ "_supportsDedicatedChannelBaseFilterOverrideOpportunistic"
+ "com.apple.private.alloy.remoteappintents"
+ "deriveAES128CTRKeys: IDSLinkHBHDeriveHKDFSha256Keys failed."
+ "filter out utun interface [if:%s family:%u subfamily:%u type:%d], useDefaultInterfaceOnly:%@"
+ "supports-dedicated-channel-base-filter-override-opportunistic"
+ "── %@ (idx %u) %@ ──\n  addr:      %@\n  netmask:   %@\n  external:  %@\n  delegated: %@\n  flags:     AWDL:%@ Cellular:%@ Temp:%@ CompanionLink:%@ Wired:%@ Expensive:%@ Constrained:%@ clat46:%@"
- "<%@: %p verifierResult: %@, ticket: %@, accountKey: %@, queryResponseTime: %@>, ktOptInStatus: %@"
```
