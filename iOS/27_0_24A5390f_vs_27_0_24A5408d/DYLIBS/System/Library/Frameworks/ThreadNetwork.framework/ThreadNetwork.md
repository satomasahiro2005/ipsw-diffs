## ThreadNetwork

> `/System/Library/Frameworks/ThreadNetwork.framework/ThreadNetwork`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe890` | `0xda20` | **`-0xe70`** |
| `__TEXT.__objc_methlist` | `0xd58` | `0xdb8` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x7a8` | `0x7e8` | **`+0x40`** |
| `__TEXT.__cstring` | `0x16c2` | `0x16ed` | **`+0x2b`** |
| `__DATA_CONST.__const` | `0x440` | `0x468` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x3b0` | `0x388` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0x820` | `0x840` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x1b98` | `0x1bb0` | **`+0x18`** |

### Other Changes

```diff

-438.0.0.0.0
+442.0.0.0.0

-  Functions: 359
-  Symbols:   679
-  CStrings:  212
+  Functions: 366
+  Symbols:   687
+  CStrings:  213
Symbols:
+ -[THClient enableCredentialSharingModeForExtendedPANID:completion:]
+ -[THClient enableCredentialSharingModeInternallyForExtendedPANID:completion:]
+ -[THClient handleActiveNearbyNetworksResponse:error:isInternal:completion:]
+ -[THClient retrieveActiveCredentialsForNearbyNetworksInternallyWithCompletion:]
+ -[THClient retrieveActiveCredentialsForNearbyNetworksWithCompletion:]
+ -[THClient storeCredentialsForBorderAgentInternally:networkName:extendedPANId:activeOperationalDataSet:teamID:completion:]
+ -[THCredentials initWithActiveDataSetRecord:]
+ ___122-[THClient storeCredentialsForBorderAgentInternally:networkName:extendedPANId:activeOperationalDataSet:teamID:completion:]_block_invoke
+ ___67-[THClient enableCredentialSharingModeForExtendedPANID:completion:]_block_invoke
+ ___69-[THClient retrieveActiveCredentialsForNearbyNetworksWithCompletion:]_block_invoke
+ ___77-[THClient enableCredentialSharingModeInternallyForExtendedPANID:completion:]_block_invoke
+ ___79-[THClient retrieveActiveCredentialsForNearbyNetworksInternallyWithCompletion:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e27_v24?0"NSSet"8"NSError"16ls32l8s40l8
- -[THClient enableCredentialSharingModeInternallyWithExtendedPANId:completion:]
- -[THClient enableCredentialSharingModeWithExtendedPANId:completion:]
- ___115-[THClient storeCredentialsForBorderAgentInternally:networkName:extendedPANId:activeOperationalDataSet:completion:]_block_invoke
- ___68-[THClient enableCredentialSharingModeWithExtendedPANId:completion:]_block_invoke
- ___78-[THClient enableCredentialSharingModeInternallyWithExtendedPANId:completion:]_block_invoke
CStrings:
+ "-[THClient enableCredentialSharingModeForExtendedPANID:completion:]"
+ "-[THClient enableCredentialSharingModeForExtendedPANID:completion:]_block_invoke"
+ "-[THClient enableCredentialSharingModeInternallyForExtendedPANID:completion:]"
+ "-[THClient enableCredentialSharingModeInternallyForExtendedPANID:completion:]_block_invoke"
+ "Failed to retrieve nearby active record"
+ "Invalid input parameter: extendedPANID is required"
- "-[THClient enableCredentialSharingModeInternallyWithExtendedPANId:completion:]"
- "-[THClient enableCredentialSharingModeInternallyWithExtendedPANId:completion:]_block_invoke"
- "-[THClient enableCredentialSharingModeWithExtendedPANId:completion:]"
- "-[THClient enableCredentialSharingModeWithExtendedPANId:completion:]_block_invoke"
- "Invalid input parameter: xpanId is required"
```
