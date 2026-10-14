## TelephonyUtilities

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/TelephonyUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bd710` | `0x1bde7c` | **`+0x76c`** |
| `__TEXT.__cstring` | `0x14716` | `0x147c6` | **`+0xb0`** |
| `__TEXT.__objc_methlist` | `0x1bb30` | `0x1bbc0` | **`+0x90`** |
| `__DATA.__bss` | `0x84d0` | `0x8550` | **`+0x80`** |
| `__AUTH_CONST.__objc_const` | `0x2b6d0` | `0x2b748` | **`+0x78`** |
| `__AUTH_CONST.__cfstring` | `0x12900` | `0x12960` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x3918` | `0x3958` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xb900` | `0xb940` | **`+0x40`** |
| `__TEXT.__const` | `0x4b6c` | `0x4bac` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x7408` | `0x7440` | **`+0x38`** |
| `__TEXT.__oslogstring` | `0x14bea` | `0x14c0a` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1678` | `0x1688` | **`+0x10`** |
| `__DATA.__data` | `0x3f40` | `0x3f50` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x1443` | `0x144b` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x3d8` | `0x3dc` | **`+0x4`** |

### Other Changes

```diff

-1626.200.84.0.0
+1626.200.91.2.3

-  Functions: 12076
-  Symbols:   16279
-  CStrings:  4687
+  Functions: 12099
+  Symbols:   16292
+  CStrings:  4694
Symbols:
+ -[TUConfigurationProvider isJunkFilteringAvailable]
+ -[TUConfigurationProvider isSilenceJunkCallingUserPreferenceEnabled]
+ -[TUConfigurationProvider setSilenceJunkCallingUserPreferenceEnabled:]
+ -[TUFeatureFlags pebbleAudibleRingtonesEnabled]
+ -[TUFeatureFlags voicemailSpamArbitrationEnabled]
+ -[TUNeighborhoodActivityConduit validateGuestSessionInvitationFromIDSIdentifier:requireActiveConnection:completion:]
+ -[TUNeighborhoodActivityConduitXPCClient validateGuestSessionInvitationFromIDSIdentifier:requireActiveConnection:completion:]
+ -[TUUserConfiguration initForTestingWithDataSource:]
+ GCC_except_table209
+ _TUDisplayNickname
+ _TUIsFaceTimeAppInstalled
+ ___125-[TUNeighborhoodActivityConduitXPCClient validateGuestSessionInvitationFromIDSIdentifier:requireActiveConnection:completion:]_block_invoke
+ ___125-[TUNeighborhoodActivityConduitXPCClient validateGuestSessionInvitationFromIDSIdentifier:requireActiveConnection:completion:]_block_invoke_2
+ ___block_descriptor_57_e8_32s40s48bs_e5_v8?0ls32l8s48l8s40l8
+ _associated conformance 18TelephonyUtilities20TUInterpreterRequestC6ErrorsO10Foundation13CustomNSErrorAAs5Error
- GCC_except_table208
- GCC_except_table59
CStrings:
+ "ATVRemote1,5"
+ "Error validating launch: %@"
+ "PebbleAudibleRingtonesEnabled"
+ "Personal Content Is Not Allowed"
+ "The companion device disabled personal content for this device."
+ "perception"
+ "voicemailSpamArbitration"
```
