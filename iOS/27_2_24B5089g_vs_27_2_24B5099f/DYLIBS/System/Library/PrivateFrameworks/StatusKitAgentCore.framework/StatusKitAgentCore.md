## StatusKitAgentCore

> `/System/Library/PrivateFrameworks/StatusKitAgentCore.framework/StatusKitAgentCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x1f38` | `0x20c8` | **`+0x190`** |
| `__DATA.__bss` | `0x4280` | `0x4180` | **`-0x100`** |
| `__DATA_DIRTY.__bss` | `0x14d0` | `0x15d0` | **`+0x100`** |
| `__AUTH.__data` | `0x230` | `0x170` | **`-0xc0`** |
| `__DATA.__data` | `0x1c90` | `0x1bd0` | **`-0xc0`** |
| `__AUTH.__objc_data` | `0x1360` | `0x12f8` | **`-0x68`** |
| `__DATA_DIRTY.__objc_data` | `0x3ad0` | `0x3b38` | **`+0x68`** |
| `__TEXT.__eh_frame` | `0x9d98` | `0x9df0` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x19416` | `0x19466` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x5cd8` | `0x5cf8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xd88` | `0xd78` | **`-0x10`** |
| `__TEXT.__cstring` | `0x977c` | `0x978c` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1600` | `0x15f8` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x4498` | `0x44a0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xb110` | `0xb118` | **`+0x8`** |
| `__TEXT.__text` | `0x1be30c` | `0x1be304` | **`-0x8`** |

### Other Changes

```diff

-154.200.11.0.0
+154.200.31.0.0

-  Functions: 7790
-  Symbols:   14201
-  CStrings:  2611
+  Functions: 7794
+  Symbols:   14203
+  CStrings:  2612
Symbols:
+ -[SKAInvitationManager _isHandleInvited:onChannel:]
+ _$s10Foundation4DateV2geoiySbAC_ACtFZ
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
+ _$s11Distributed0A23TargetInvocationDecoderP18decodeNextArgumentqd__yKlFTj
+ _$sSMsSkRzrlE4sort2byySb7ElementSTQz_ADtKXE_tKFySryADGzKXEfU_s15ContiguousArrayVySSG_Tg5
+ _$ss10_NativeSetV6filteryAByxGSbxqd__YKXEqd__YKs5ErrorRd__lFADs13_UnsafeBitsetVqd__YKXEfU_So31SKADatabasePublishedLocalStatusC_s5NeverOTG5TA
+ _$ss13_UnsafeBitsetV027_withTemporaryUninitializedB09wordCount4bodyxSi_xABq_YKXEtq_YKs5ErrorR_r0_lFZxSryAB4WordVGq_YKXEfU_s10_NativeSetVy18StatusKitAgentCore16SKAStatusProfileCG_s5NeverOTg506$ss13_ab8V013withd36B08capacity4bodyxSi_xABq_YKXEtq_YKs5i9R_r0_lFZxx12_YKXEfU_s10_kl4Vy18mno6Core16qr5CG_s5S4OTG5ABq_xRi_zRi0_zRi__Ri0__r0_lyAqOIsgyrzr_Tf1nc_n06$ss10_kl29V6filteryAByxGSbxqd__YKXEqd__zi12Rd__lFADs13_ab14Vqd__YKXEfU_18mno6Core16qr4C_s5S4OTG5AOxSbq_Ri_zRi0_zRi__Ri0__r0_lyAnQIsgndzr_Tf1nc_n
+ _$ss13_UnsafeBitsetV027_withTemporaryUninitializedB09wordCount4bodyxSi_xABq_YKXEtq_YKs5ErrorR_r0_lFZxSryAB4WordVGq_YKXEfU_s10_NativeSetVySo31SKADatabasePublishedLocalStatusCG_s5NeverOTg506$ss13_ab8V013withd36B08capacity4bodyxSi_xABq_YKXEtq_YKs5i9R_r0_lFZxv12_YKXEfU_s10_kl6VySo31mnop5CG_s5Q4OTG5ABq_xRi_zRi0_zRi__Ri0__r0_lyApNIsgyrzr_Tf1nc_n
+ _$ss13_UnsafeBitsetV027_withTemporaryUninitializedB09wordCount4bodyxSi_xABq_YKXEtq_YKs5ErrorR_r0_lFZxSryAB4WordVGq_YKXEfU_s10_NativeSetVySo31SKADatabasePublishedLocalStatusCG_s5NeverOTg506$ss13_ab8V013withd36B08capacity4bodyxSi_xABq_YKXEtq_YKs5i9R_r0_lFZxv12_YKXEfU_s10_kl6VySo31mnop5CG_s5Q4OTG5ABq_xRi_zRi0_zRi__Ri0__r0_lyApNIsgyrzr_Tf1nc_n06$ss10_kl29V6filteryAByxGSbxqd__YKXEqd__xi12Rd__lFADs13_ab16Vqd__YKXEfU_So31mnop4C_s5Q4OTG5ANxSbq_Ri_zRi0_zRi__Ri0__r0_lyAmPIsgndzr_Tf1nc_n
- _$s14XPCDistributed9XPCSystemC17InvocationDecoderV18decodeNextArgumentxyKSeRzSERzlF
- _$sSL2leoiySbx_xtFZTj
- _$sSr15_stableSortImpl2byySbx_xtKXE_tKFSS_Tg5
- _$ss13_UnsafeBitsetV027_withTemporaryUninitializedB09wordCount4bodyxSi_xABq_YKXEtq_YKs5ErrorR_r0_lFZxSryAB4WordVGq_YKXEfU_s10_NativeSetVy18StatusKitAgentCore16SKAStatusProfileCG_s5NeverOTg506$ss10_kl33V6filteryAByxGSbxqd__YKXEqd__YKs5i12Rd__lFADs13_ab14Vqd__YKXEfU_18mno6Core16qr4C_s5S4OTG5AOxSbq_Ri_zRi0_zRi__Ri0__r0_lyAnQIsgndzr_Tf1nc_n
- _$ss13_UnsafeBitsetV027_withTemporaryUninitializedB09wordCount4bodyxSi_xABq_YKXEtq_YKs5ErrorR_r0_lFZxSryAB4WordVGq_YKXEfU_s10_NativeSetVySo31SKADatabasePublishedLocalStatusCG_s5NeverOTg506$ss10_kl33V6filteryAByxGSbxqd__YKXEqd__YKs5i12Rd__lFADs13_ab16Vqd__YKXEfU_So31mnop4C_s5Q4OTG5ANxSbq_Ri_zRi0_zRi__Ri0__r0_lyAmPIsgndzr_Tf1nc_n
- _swift_conformsToProtocol2
- _swift_release_x9
CStrings:
+ "Sender is not an invited user on our current channel %{public}@ - skipping reverse invite"
+ "presence-reverse-invite-adopter-enabled-V2"
- "presence-reverse-invite-adopter-enabled"
```
