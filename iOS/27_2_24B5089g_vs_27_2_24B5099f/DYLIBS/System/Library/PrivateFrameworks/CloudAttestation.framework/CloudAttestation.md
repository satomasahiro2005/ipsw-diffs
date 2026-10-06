## CloudAttestation

> `/System/Library/PrivateFrameworks/CloudAttestation.framework/CloudAttestation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14246c` | `0x144c84` | **`+0x2818`** |
| `__DATA.__bss` | `0x14f80` | `0x15680` | **`+0x700`** |
| `__TEXT.__const` | `0x1e4d2` | `0x1e900` | **`+0x42e`** |
| `__TEXT.__oslogstring` | `0x3198` | `0x34b8` | **`+0x320`** |
| `__TEXT.__eh_frame` | `0xa958` | `0xab90` | **`+0x238`** |
| `__AUTH_CONST.__const` | `0x7df8` | `0x7fd0` | **`+0x1d8`** |
| `__TEXT.__unwind_info` | `0x5340` | `0x5468` | **`+0x128`** |
| `__TEXT.__swift5_fieldmd` | `0x3be8` | `0x3c9c` | **`+0xb4`** |
| `__TEXT.__swift5_typeref` | `0x2d80` | `0x2cd6` | **`-0xaa`** |
| `__DATA.__data` | `0x2980` | `0x2a10` | **`+0x90`** |
| `__AUTH.__data` | `0x100` | `0x188` | **`+0x88`** |
| `__TEXT.__constg_swiftt` | `0x2f30` | `0x2f90` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x31c3` | `0x3223` | **`+0x60`** |
| `__TEXT.__swift5_assocty` | `0x668` | `0x6b0` | **`+0x48`** |
| `__TEXT.__swift5_proto` | `0xc94` | `0xccc` | **`+0x38`** |
| `__TEXT.__cstring` | `0x25f4` | `0x25c4` | **`-0x30`** |
| `__TEXT.__swift_as_cont` | `0x4cc` | `0x4e8` | **`+0x1c`** |
| `__DATA_DIRTY.__data` | `0x49a8` | `0x49b8` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x328` | `0x338` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x448` | `0x454` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x36c` | `0x378` | **`+0xc`** |

### Other Changes

```diff

-323.40.9.502.1
+323.40.14.0.1

-  Functions: 7339
-  Symbols:   2428
-  CStrings:  396
+  Functions: 7429
+  Symbols:   2441
+  CStrings:  408
Symbols:
+ ___swift_get_extra_inhabitant_index.65Tm
+ ___swift_memcpy203_8
+ ___swift_store_extra_inhabitant_index.66Tm
+ ___unnamed_12
+ _aks_attest_context_get_blob
+ _associated conformance 16CloudAttestation07PrivateA23Compute_ReleaseMetadataV9ReferenceV21InternalSwiftProtobuf26_MessageImplementationBaseAASH
+ _associated conformance 16CloudAttestation07PrivateA23Compute_ReleaseMetadataV9ReferenceV21InternalSwiftProtobuf26_MessageImplementationBaseAaF0K0
+ _associated conformance 16CloudAttestation07PrivateA23Compute_ReleaseMetadataV9ReferenceV21InternalSwiftProtobuf7MessageAAs28CustomDebugStringConvertible
+ _associated conformance 16CloudAttestation07PrivateA23Compute_ReleaseMetadataV9ReferenceVSHAASQ
+ _associated conformance 16CloudAttestation16ATReleaseTypeTLSOSHAASQ
+ _associated conformance 16CloudAttestation3PCCO17ProxyNodeAttestorV16TransparencyTypeOSHAASQ
+ _associated conformance 16CloudAttestation3PCCO17ProxyNodeAttestorV16TransparencyTypeOs12CaseIterableAA8AllCasessAHP_Sl
+ _get_witness_table 16CloudAttestation13PolicyBuilderV05TupleC0Vy_AC08OptionalC0Vy_AEy_AA014ProxiedReleaseC0V_QPGG_AGy_AEy_AA011EnvironmentC0V_QPGGQPGAA0bC0HPyHC
+ _symbolic Say_____G 16CloudAttestation07PrivateA23Compute_ReleaseMetadataV9ReferenceV
+ _symbolic Say_____G 16CloudAttestation3PCCO17ProxyNodeAttestorV16TransparencyTypeO
+ _symbolic _____ 16CloudAttestation07PrivateA23Compute_ReleaseMetadataV9ReferenceV
+ _symbolic _____ 16CloudAttestation16ATReleaseTypeTLSO
+ _symbolic _____ 16CloudAttestation3PCCO17ProxyNodeAttestorV16TransparencyTypeO
+ _symbolic ___________p 16CloudAttestation29TransparencyConsistencyProverP AA0cE0P
+ _symbolic _____y______y_AAy_______QPGG_ABy_AAy_______QPGGQPG 16CloudAttestation13PolicyBuilderV05TupleC0V AC08OptionalC0V AA014ProxiedReleaseC0V AA011EnvironmentC0V
+ _symbolic _____y______y_______QPGG_AAy_ABy_______QPGGt 16CloudAttestation13PolicyBuilderV08OptionalC0V AC05TupleC0V AA014ProxiedReleaseC0V AA011EnvironmentC0V
- ___swift_memcpy204_8
- ___unnamed_11
- _get_witness_table 16CloudAttestation13PolicyBuilderV05TupleC0Vy_AEy_AA04X509C0V_AC08OptionalC0Vy_AEy_AA023CertificateTransparencyC0V_QPGGAC011ConditionalC0Oy_AEy_AA014SEPAttestationC0V_QPGARGAA08APTicketC0VAA09LocalBootC0VAA08SEPImageC0VAA07CryptexC0VAA012SecureConfigC0VAA0iC0VAA010KeyOptionsC0VAIy_AEy_AA06FusingC0V_QPGGAA010DeviceModeC0VAA010DarwinInitC0VAA011RoutingHintC0VAA015EnsembleMembersC0VQPG_AIy_AEy_AA014ProxiedReleaseC0V_QPGGAIy_AEy_AA011EnvironmentC0V_QPGGQPGAA0bC0HPyHC
- _swift_dynamicCastObjCClassUnconditional
- _symbolic ________________p 16CloudAttestation29TransparencyConsistencyProverP AA0cE0P AA0C8VerifierP
- _symbolic _____m 16CloudAttestation3PCCO20ComputeNodeValidatorV
- _symbolic _____y_AAy____________y_AAy_______QPGG_____y_AAy_______QPGAIG___________________________________ACy_AAy_______QPGG____________________QPG_ACy_AAy_______QPGGACy_AAy_______QPGGQPG 16CloudAttestation13PolicyBuilderV05TupleC0V AA04X509C0V AC08OptionalC0V AA023CertificateTransparencyC0V AC011ConditionalC0O AA014SEPAttestationC0V AA08APTicketC0V AA09LocalBootC0V AA08SEPImageC0V AA07CryptexC0V AA012SecureConfigC0V AA0iC0V AA010KeyOptionsC0V AA06FusingC0V AA010DeviceModeC0V AA010DarwinInitC0V AA011RoutingHintC0V AA015EnsembleMembersC0V AA014ProxiedReleaseC0V AA011EnvironmentC0V
- _symbolic _____y____________y_AAy_______QPGG_____y_AAy_______QPGAIG___________________________________ACy_AAy_______QPGG____________________QPG_ACy_AAy_______QPGGACy_AAy_______QPGGt 16CloudAttestation13PolicyBuilderV05TupleC0V AA04X509C0V AC08OptionalC0V AA023CertificateTransparencyC0V AC011ConditionalC0O AA014SEPAttestationC0V AA08APTicketC0V AA09LocalBootC0V AA08SEPImageC0V AA07CryptexC0V AA012SecureConfigC0V AA0iC0V AA010KeyOptionsC0V AA06FusingC0V AA010DeviceModeC0V AA010DarwinInitC0V AA011RoutingHintC0V AA015EnsembleMembersC0V AA014ProxiedReleaseC0V AA011EnvironmentC0V
CStrings:
+ "CertificateTransparencyPolicy failed with error: %{public}@"
+ "CertificateTransparencyPolicy succeeded with expiry: %{public}s"
+ "Evaluating if proxy attestation should recycle for %{public}s, digest=%{public}s"
+ "Failed to fetch CT proofs, but failing open because \"certificateTransparencyFetchFailClosed\" is false: %{public}@"
+ "Failed to insert proof into cache: %{public}@"
+ "OSK is missing pka_flag_use_seal_data_ap"
+ "PKA.SealDataA does not match RequestData.SealDataA"
+ "PKA.SealDataB does not match RequestData.SealDataB"
+ "Proxy attestation does not need to recycle (%{public}s) proxyNodeRevision=%{public}llu targetRevision=%{public}llu"
+ "Proxy attestation has no %{public}s transparency proofs, not recycling"
+ "Recycling because proxy node revision is older than target (%{public}s) proxyNodeRevision=%{public}llu targetRevision=%{public}llu"
+ "Recycling for tree roll (%{public}s)"
+ "Request to transparency server %{public}s failed: %{public}@"
+ "Revisions for %{public}s: proxyNode=%{public}s, recent=%{public}s"
+ "Transparency server %{public}s responded with status %{public}ld"
+ "Transparency server %{public}s returned a non-HTTP response"
+ "Transparency server returned %{public}ld proofs for %{public}ld digests"
+ "Transparency server returned an empty inclusion proof"
+ "Transparency server returned status %{public}s for consistency proof request"
+ "Transparency server returned status %{public}s for inclusion proof batch request"
+ "Transparency server returned status %{public}s for inclusion proof request"
+ "Unable to obtain Narrative credential: %{public}@"
+ "certificate"
+ "failed to get osk blob"
+ "release"
- "Bundle AppData failed integrity check: (digest:%{public}s != nonce:%{public}s"
- "Bundle AppData is non-empty, but attestation contains no nonce"
- "CertificateTransparencyPolicy failed with error: %@"
- "CertificateTransparencyPolicy succeeded with expiry: %s"
- "Evaluating if proxy attestation should recycle, release=%{public}s"
- "Failed to fetch CT proofs, but failing open because \"certificateTransparencyFetchFailClosed\" is false"
- "Proxy attestation does not need to recycle proxyNodeRevision=%{public}llu targetRevision=%{public}llu"
- "Recycling because proxy node revision is older than target proxyNodeRevision=%{public}llu targetRevision=%{public}llu"
- "Recycling for tree roll (certificate)"
- "Recycling for tree roll (release)"
- "Revisions for certificate: proxyNode=%{public}s, recentCertificate=%{public}s"
- "Revisions for release: proxyNode=%{public}s, recentRelease=%{public}s"
- "certificateTransparencyShouldRecycleProxyAttestation"
```
