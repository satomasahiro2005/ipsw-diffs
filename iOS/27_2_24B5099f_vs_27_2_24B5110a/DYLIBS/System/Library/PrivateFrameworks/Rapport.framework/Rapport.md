## Rapport

> `/System/Library/PrivateFrameworks/Rapport.framework/Rapport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe02f8` | `0xe6494` | **`+0x619c`** |
| `__DATA.__bss` | `0x2e90` | `0x32a0` | **`+0x410`** |
| `__TEXT.__const` | `0x41a8` | `0x4458` | **`+0x2b0`** |
| `__TEXT.__oslogstring` | `0x26bd` | `0x289d` | **`+0x1e0`** |
| `__AUTH_CONST.__objc_const` | `0x11678` | `0x11808` | **`+0x190`** |
| `__AUTH_CONST.__const` | `0x27c0` | `0x2940` | **`+0x180`** |
| `__TEXT.__swift5_reflstr` | `0x93c` | `0xabc` | **`+0x180`** |
| `__DATA_DIRTY.__objc_data` | `0x2618` | `0x2768` | **`+0x150`** |
| `__TEXT.__constg_swiftt` | `0xdbc` | `0xf08` | **`+0x14c`** |
| `__TEXT.__cstring` | `0x14eac` | `0x14fec` | **`+0x140`** |
| `__TEXT.__objc_methlist` | `0xa1a8` | `0xa2d0` | **`+0x128`** |
| `__TEXT.__swift5_fieldmd` | `0xb34` | `0xc14` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x2f80` | `0x3058` | **`+0xd8`** |
| `__DATA_CONST.__objc_selrefs` | `0x4610` | `0x46d0` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x28d8` | `0x2960` | **`+0x88`** |
| `__AUTH_CONST.__cfstring` | `0x5f40` | `0x5fc0` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0xc4f` | `0xccd` | **`+0x7e`** |
| `__TEXT.__swift5_assocty` | `0x88` | `0x100` | **`+0x78`** |
| `__DATA.__data` | `0x678` | `0x6e8` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0x1190` | `0x11b0` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x144` | `0x164` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1518` | `0x1530` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x50` | `0x64` | **`+0x14`** |
| `__DATA.__objc_ivar` | `0x111c` | `0x1124` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x4e8` | `0x4f0` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x950` | `0x958` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xb0` | `0xb8` | **`+0x8`** |

### Other Changes

```diff

-751.200.74.0.0
+751.200.92.0.0

-  Functions: 5843
-  Symbols:   6872
-  CStrings:  3073
+  Functions: 5948
+  Symbols:   6913
+  CStrings:  3093
Symbols:
+ -[RPCompanionLinkDevice updateMultiUserDeviceWithPeer:]
+ -[RPConnection _accountOwnerCheckEnabled]
+ -[RPConnection _isAccountCheckedWithPeerModel:]
+ -[RPConnection _localDeviceClass]
+ -[RPConnection _multiUserDeviceWithIdentifier:]
+ -[RPConnection _peerUpdatedAfterTrustChange:]
+ -[RPConnection _sourceVersionFromString:]
+ -[RPConnection accountOwnerCheckApplies]
+ -[RPConnection localAccountUpdated]
+ -[RPConnection multiUserDevices]
+ -[RPConnection setMultiUserDevices:]
+ -[RPConnection verifyIdentityProof:accountAltDSID:]
+ -[RPConnection verifyMUHomeKitIdentityProof:identifier:accountAltDSID:completion:]
+ -[RPSiriSession setTriggeredPhrase:]
+ -[RPSiriSession triggeredPhrase]
+ GCC_except_table291
+ GCC_except_table72
+ GCC_except_table74
+ GCC_except_table76
+ GCC_except_table95
+ _OBJC_IVAR_$_RPConnection._multiUserDevices
+ _OBJC_IVAR_$_RPSiriSession._triggeredPhrase
+ _RPLinkIsAccountChecked
+ _RPOptionMultiUserDeviceID
+ _TextToSourceVersion
+ ___82-[RPConnection verifyMUHomeKitIdentityProof:identifier:accountAltDSID:completion:]_block_invoke
+ ___82-[RPConnection verifyMUHomeKitIdentityProof:identifier:accountAltDSID:completion:]_block_invoke_2
+ ___block_descriptor_65_e8_32s40s48bs56r_e25_v20?0B8"CUPairedPeer"12ls32l8s40l8r56l8s48l8
+ ___block_descriptor_88_e8_32s40s48s56s64s72bs80r_e23_v20?0B8"RPIdentity"12ls32l8s40l8s48l8s56l8s64l8r80l8s72l8
+ ___swift_closure_destructor.115Tm
+ ___swift_closure_destructor.144Tm
+ ___swift_closure_destructor.156Tm
+ ___swift_closure_destructor.188Tm
+ ___swift_closure_destructor.255Tm
+ __sepBackedIdentityEnabled.enabled
+ _associated conformance 7Rapport16RPConnectionCoreC17AccountOwnerCheckOSHAASQ
+ _associated conformance So21RPAccountOwnerSourcesVs10SetAlgebraSCSQ
+ _associated conformance So21RPAccountOwnerSourcesVs10SetAlgebraSCs25ExpressibleByArrayLiteral
+ _associated conformance So21RPAccountOwnerSourcesVs9OptionSetSCSY
+ _associated conformance So21RPAccountOwnerSourcesVs9OptionSetSCs0E7Algebra
+ _swift_bridgeObjectRetain_n
+ _symbolic $ss10SetAlgebraP
+ _symbolic $ss25ExpressibleByArrayLiteralP
+ _symbolic $ss9OptionSetP
+ _symbolic _____ 7Rapport16RPConnectionCoreC17AccountOwnerCheckO
+ _symbolic _____ So21RPAccountOwnerSourcesV
+ _symbolic _____Sg 7Rapport16RPConnectionCoreC17AccountOwnerCheckO
+ _type_layout_string So21RPAccountOwnerSourcesV
- GCC_except_table73
- GCC_except_table92
- ___swift_closure_destructor.113Tm
- ___swift_closure_destructor.142Tm
- ___swift_closure_destructor.154Tm
- ___swift_closure_destructor.186Tm
- ___swift_closure_destructor.253Tm
CStrings:
+ "### Account owner removed: peer reports another account, ours %{private,mask.hash}s, peer %{private,mask.hash}s, sources 0x%{public}s, model %{public}s, %{public}s"
+ "### Failed to obtain local account for multi-user HK verify\n"
+ "-[RPConnection verifyMUHomeKitIdentityProof:identifier:accountAltDSID:completion:]"
+ "Account owner kept: %{public}s, sources 0x%{public}s, model %{public}s, %{public}s"
+ "Account owner not checked: disabled, %{public}s"
+ "Account owner withheld: %{public}s, ours %{private,mask.hash}s, sources 0x%{public}s, model %{public}s, %{public}s"
+ "AccountOwnerCheck"
+ "SEPBackedIdentity"
+ "Send AltDSID update: %{public}s"
+ "_vtPhrase"
+ "disabled"
+ "exemptLink"
+ "iCrowd"
+ "legacyPeer"
+ "localUnknown"
+ "match"
+ "mismatch"
+ "missingFlag.MultiUser"
+ "multiUserDevID"
+ "peerUnknown"
```
