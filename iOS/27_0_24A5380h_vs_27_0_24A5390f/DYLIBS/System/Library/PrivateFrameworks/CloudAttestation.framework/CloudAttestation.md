## CloudAttestation

> `/System/Library/PrivateFrameworks/CloudAttestation.framework/CloudAttestation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__eh_frame` | `0xaa38` | `0xa988` | **`-0xb0`** |
| `__TEXT.__text` | `0x13ccd0` | `0x13cc30` | **`-0xa0`** |
| `__TEXT.__oslogstring` | `0x3198` | `0x3208` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x4f88` | `0x4f60` | **`-0x28`** |
| `__TEXT.__swift5_reflstr` | `0x3123` | `0x3143` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x2c52` | `0x2c72` | **`+0x20`** |
| `__DATA.__common` | `0x280` | `0x298` | **`+0x18`** |
| `__DATA.__data` | `0x2978` | `0x2990` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x3b60` | `0x3b78` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x508` | `0x4f4` | **`-0x14`** |
| `__TEXT.__const` | `0x1daf8` | `0x1dae8` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x340` | `0x338` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x380` | `0x37c` | **`-0x4`** |

### Other Changes

```diff

-323.0.1.0.0
+323.0.6.0.0

-  Functions: 7027
-  Symbols:   2389
-  CStrings:  369
+  Functions: 7025
+  Symbols:   2390
+  CStrings:  371
Symbols:
+ _get_witness_table 16CloudAttestation13PolicyBuilderV05TupleC0Vy_AEy_AA04X509C0V_AC08OptionalC0Vy_AEy_AA023CertificateTransparencyC0V_QPGGAC011ConditionalC0Oy_AEy_AA014SEPAttestationC0V_QPGARGAA08APTicketC0VAA09LocalBootC0VAA08SEPImageC0VAA07CryptexC0VAA012SecureConfigC0VAA0iC0VAA010KeyOptionsC0VAIy_AEy_AA06FusingC0V_QPGGAA010DeviceModeC0VAA010DarwinInitC0VAA011RoutingHintC0VAA015EnsembleMembersC0VQPG_AIy_AEy_AA014ProxiedReleaseC0V_QPGGAIy_AEy_AA011EnvironmentC0V_QPGGQPGAA0bC0HPyHC
+ _symbolic _____Sg 16CloudAttestation0B13PolicyContextV
+ _symbolic _____y_AAy____________y_AAy_______QPGG_____y_AAy_______QPGAIG___________________________________ACy_AAy_______QPGG____________________QPG_ACy_AAy_______QPGGACy_AAy_______QPGGQPG 16CloudAttestation13PolicyBuilderV05TupleC0V AA04X509C0V AC08OptionalC0V AA023CertificateTransparencyC0V AC011ConditionalC0O AA014SEPAttestationC0V AA08APTicketC0V AA09LocalBootC0V AA08SEPImageC0V AA07CryptexC0V AA012SecureConfigC0V AA0iC0V AA010KeyOptionsC0V AA06FusingC0V AA010DeviceModeC0V AA010DarwinInitC0V AA011RoutingHintC0V AA015EnsembleMembersC0V AA014ProxiedReleaseC0V AA011EnvironmentC0V
+ _symbolic _____y____________y_AAy_______QPGG_____y_AAy_______QPGAIG___________________________________ACy_AAy_______QPGG____________________QPG_ACy_AAy_______QPGGACy_AAy_______QPGGt 16CloudAttestation13PolicyBuilderV05TupleC0V AA04X509C0V AC08OptionalC0V AA023CertificateTransparencyC0V AC011ConditionalC0O AA014SEPAttestationC0V AA08APTicketC0V AA09LocalBootC0V AA08SEPImageC0V AA07CryptexC0V AA012SecureConfigC0V AA0iC0V AA010KeyOptionsC0V AA06FusingC0V AA010DeviceModeC0V AA010DarwinInitC0V AA011RoutingHintC0V AA015EnsembleMembersC0V AA014ProxiedReleaseC0V AA011EnvironmentC0V
- _get_witness_table 16CloudAttestation13PolicyBuilderV05TupleC0Vy_AEy_AA04X509C0V_AC08OptionalC0Vy_AEy_AA023CertificateTransparencyC0V_QPGGAC011ConditionalC0Oy_AEy_AA014SEPAttestationC0V_QPGARGAA08APTicketC0VAA09LocalBootC0VAA08SEPImageC0VAA07CryptexC0VAA012SecureConfigC0VAA0iC0VAA010KeyOptionsC0VAIy_AEy_AA06FusingC0V_QPGGAA010DeviceModeC0VAA010DarwinInitC0VAA011RoutingHintC0VAA015EnsembleMembersC0VQPG_AIy_AEy_AA014ProxiedReleaseC0V_QPGGAA011EnvironmentC0VQPGAA0bC0HPyHC
- _symbolic _____y_AAy____________y_AAy_______QPGG_____y_AAy_______QPGAIG___________________________________ACy_AAy_______QPGG____________________QPG_ACy_AAy_______QPGG_____QPG 16CloudAttestation13PolicyBuilderV05TupleC0V AA04X509C0V AC08OptionalC0V AA023CertificateTransparencyC0V AC011ConditionalC0O AA014SEPAttestationC0V AA08APTicketC0V AA09LocalBootC0V AA08SEPImageC0V AA07CryptexC0V AA012SecureConfigC0V AA0iC0V AA010KeyOptionsC0V AA06FusingC0V AA010DeviceModeC0V AA010DarwinInitC0V AA011RoutingHintC0V AA015EnsembleMembersC0V AA014ProxiedReleaseC0V AA011EnvironmentC0V
- _symbolic _____y____________y_AAy_______QPGG_____y_AAy_______QPGAIG___________________________________ACy_AAy_______QPGG____________________QPG_ACy_AAy_______QPGG_____t 16CloudAttestation13PolicyBuilderV05TupleC0V AA04X509C0V AC08OptionalC0V AA023CertificateTransparencyC0V AC011ConditionalC0O AA014SEPAttestationC0V AA08APTicketC0V AA09LocalBootC0V AA08SEPImageC0V AA07CryptexC0V AA012SecureConfigC0V AA0iC0V AA010KeyOptionsC0V AA06FusingC0V AA010DeviceModeC0V AA010DarwinInitC0V AA011RoutingHintC0V AA015EnsembleMembersC0V AA014ProxiedReleaseC0V AA011EnvironmentC0V
CStrings:
+ "Invalid environment string from CFPrefs: %s"
+ "Invalid environment string from SecureConfig: %s"
```
