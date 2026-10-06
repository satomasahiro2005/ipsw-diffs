## ThreadNetwork

> `/System/Library/Frameworks/ThreadNetwork.framework/ThreadNetwork`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x160c` | `0x1689` | **`+0x7d`** |
| `__TEXT.__text` | `0xe7b8` | `0xe82c` | **`+0x74`** |
| `__DATA_CONST.__const` | `0x468` | `0x440` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0x800` | `0x820` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0xa8a` | `0xa7b` | **`-0xf`** |
| `__TEXT.__unwind_info` | `0x3a0` | `0x3a8` | **`+0x8`** |

### Other Changes

```diff

-431.0.2.0.0
+434.0.1.0.0

-  Symbols:   679
+  Symbols:   678
Symbols:
+ -[THClient enableCredentialSharingModeInternallyWithExtendedPANId:completion:]
+ -[THClient enableCredentialSharingModeWithExtendedPANId:completion:]
+ ___68-[THClient enableCredentialSharingModeWithExtendedPANId:completion:]_block_invoke
+ ___78-[THClient enableCredentialSharingModeInternallyWithExtendedPANId:completion:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e17_v16?0"NSError"8ls32l8s40l8
- -[THClient enableCredentialSharingMode:]
- -[THClient enableCredentialSharingModeInternally:]
- ___40-[THClient enableCredentialSharingMode:]_block_invoke
- ___50-[THClient enableCredentialSharingModeInternally:]_block_invoke
- ___block_descriptor_40_e8_32bs_e30_v24?0"NSString"8"NSError"16ls32l8
- ___block_descriptor_48_e8_32s40bs_e30_v24?0"NSString"8"NSError"16ls40l8s32l8
Functions:
~ ___129-[THClient retrieveListOfPreferredNetworkEntriesInternally:ipV4NwSignature:ipv6NwSignature:wifiSSID:showCurrentEntry:completion:]_block_invoke : 1564 -> 1556
~ -[THClient enableCredentialSharingModeInternally:] -> -[THClient enableCredentialSharingModeInternallyWithExtendedPANId:completion:] : 392 -> 468
~ ___50-[THClient enableCredentialSharingModeInternally:]_block_invoke -> ___78-[THClient enableCredentialSharingModeInternallyWithExtendedPANId:completion:]_block_invoke : 116 -> 112
~ ___50-[THClient enableCredentialSharingModeInternally:]_block_invoke.143 -> ___78-[THClient enableCredentialSharingModeInternallyWithExtendedPANId:completion:]_block_invoke.146 : 220 -> 188
~ -[THClient startThreadBRScanInternally:] : 368 -> 372
~ ___35-[THClient retrieveAllCredentials:]_block_invoke : 1092 -> 1088
~ ___41-[THClient retrieveAllActiveCredentials:]_block_invoke : 1092 -> 1088
~ -[THClient enableCredentialSharingMode:] -> -[THClient enableCredentialSharingModeWithExtendedPANId:completion:] : 392 -> 512
~ ___40-[THClient enableCredentialSharingMode:]_block_invoke -> ___68-[THClient enableCredentialSharingModeWithExtendedPANId:completion:]_block_invoke : 140 -> 136
~ ___40-[THClient enableCredentialSharingMode:]_block_invoke.150 -> ___68-[THClient enableCredentialSharingModeWithExtendedPANId:completion:]_block_invoke.152 : 248 -> 220
CStrings:
+ "-[THClient enableCredentialSharingModeInternallyWithExtendedPANId:completion:]"
+ "-[THClient enableCredentialSharingModeInternallyWithExtendedPANId:completion:]_block_invoke"
+ "-[THClient enableCredentialSharingModeWithExtendedPANId:completion:]"
+ "-[THClient enableCredentialSharingModeWithExtendedPANId:completion:]_block_invoke"
+ "Client: %s:%d - Credential Sharing Mode error: %@"
+ "Invalid input parameter: xpanId is required"
- "-[THClient enableCredentialSharingMode:]"
- "-[THClient enableCredentialSharingMode:]_block_invoke"
- "-[THClient enableCredentialSharingModeInternally:]"
- "-[THClient enableCredentialSharingModeInternally:]_block_invoke"
- "Client: %s:%d - Credential Sharing Mode adminCode: %@, error: %@"
- "v24@?0@\"NSString\"8@\"NSError\"16"
```
