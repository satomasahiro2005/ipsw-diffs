## CloudAttestation

> `/System/Library/PrivateFrameworks/CloudAttestation.framework/CloudAttestation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13ab94` | `0x13cd18` | **`+0x2184`** |
| `__TEXT.__oslogstring` | `0x2d38` | `0x3198` | **`+0x460`** |
| `__TEXT.__eh_frame` | `0xa788` | `0xaa38` | **`+0x2b0`** |
| `__TEXT.__cstring` | `0x1f04` | `0x2074` | **`+0x170`** |
| `__TEXT.__unwind_info` | `0x4f10` | `0x4f80` | **`+0x70`** |
| `__TEXT.__const` | `0x1daa0` | `0x1daf8` | **`+0x58`** |
| `__TEXT.__swift_as_cont` | `0x4e4` | `0x508` | **`+0x24`** |
| `__DATA.__common` | `0x268` | `0x280` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1370` | `0x1380` | **`+0x10`** |
| `__AUTH_CONST.__const` | `0x7de8` | `0x7df8` | **`+0x10`** |
| `__DATA.__data` | `0x2a10` | `0x2a20` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1060` | `0x1070` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x168` | `0x178` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x3113` | `0x3123` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x370` | `0x380` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x330` | `0x340` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x3b54` | `0x3b60` | **`+0xc`** |

### Other Changes

```diff

-317.0.0.0.1
+323.0.1.0.0

-  Functions: 7007
-  Symbols:   2387
-  CStrings:  350
+  Functions: 7028
+  Symbols:   2390
+  CStrings:  369
Symbols:
+ _NSURLAuthenticationMethodClientCertificate
+ ___swift_closure_destructor.20Tm
+ ___swift_project_boxed_opaque_existential_1Tm
+ __oidSmtpUTF8Mailbox
+ _oidSmtpUTF8Mailbox
+ _swift_retain_x11
- ___swift_closure_destructor.18Tm
- ___swift_destroy_boxed_opaque_existential_3Tm
- ___swift_project_boxed_opaque_existential_3Tm
CStrings:
+ "Attached CT Proofs for: %{public}s"
+ "Attestation creation failed: %{public}@"
+ "Certificate DeviceIdentity %{public}s != %{public}s"
+ "Consistency proof cache hit from=%{public}s to=%{public}s"
+ "Consistency proof cache miss from=%{public}s to=%{public}s, fetching"
+ "Digest the inclusion proof is for (%{public}s) does not match the expected digest (%{public}s)"
+ "Evaluating if proxy attestation should recycle, release=%{public}s"
+ "Fetching CT proofs for: %{public}s"
+ "INTEGER encoded with constructed encoding"
+ "INTEGER encoded with top bit set!"
+ "INTEGER encoded with zero bytes"
+ "INTEGER not encoded in fewest number of octets"
+ "Inclusion proof cache hit for digest=%{public}s revision=%{public}s"
+ "Inclusion proof cache miss for digest=%{public}s revision=%{public}s, fetching"
+ "Invalid byte for ASN1Bool"
+ "Invalid content for ASN1Bool"
+ "Leaf type of proxy inclusion proof does not match compute node inclusion proof (proxyNodeType=%{public}s, computeNodeType=%{public}s)"
+ "Observed Cryptex Lockdown State: %{bool,public}d"
+ "PCC.ProxyNodeAttestor"
+ "Proxy attestation bundle is missing transparency proofs for leaf type %{public}s"
+ "Proxy attestation does not need to recycle proxyNodeRevision=%{public}llu targetRevision=%{public}llu"
+ "Recycling because proxy node revision is older than target proxyNodeRevision=%{public}llu targetRevision=%{public}llu"
+ "Recycling for tree roll (certificate)"
+ "Recycling for tree roll (release)"
+ "Release sha256:%{public}s is covered by proxy node attestation"
+ "Revisions for certificate: proxyNode=%{public}s, recentCertificate=%{public}s"
+ "Revisions for release: proxyNode=%{public}s, recentRelease=%{public}s"
+ "SecTrust verification failed: %{public}@"
+ "SwiftASN1Internal/ASN1Boolean.swift"
+ "SwiftASN1Internal/ASN1Integer.swift"
+ "Tree heads in consistency proof do not match inclusion proof tree heads (computeNodeInclusionProof=%{public}s, consistencyProofStart=%{public}s, consistencyProofEnd=%{public}s, proxyNodeInclusionProof=%{public}s)"
+ "Verifying transitive inclusion of digest=%{public}s leafType=%{public}s computeNodeRevision=%{public}s proxyNodeRevision=%{public}s"
+ "failed to issue DCRT: %{public}@"
- "Attached CT Proofs for: %s"
- "AttestationBundle passed validation for public key: %s"
- "AttestationBundle validation failed: %@"
- "Certificate DeviceIdentity %s != %s"
- "Digest the inclusion proof is for (%{public}s) does not match the expected digest (%{public}s"
- "Fetching CT proofs for: %s"
- "Leaf type of proxy inclusion proof does not match compute node inclusion proof"
- "Observed Cryptex Lockdown State: %{bool}d"
- "Proxy attestation bundle is missing transparency proofs"
- "SecTrust verification failed: %@"
- "Tree heads in consistency proof do not match inclusion proof tree heads (Compute node inclusion proof: %s, Consistency proof start: %s, Consistency proof end: %s, Proxy node inclusion proof: %s"
- "attestation creation failed: %@"
- "failed to issue DCRT: %@"
- "release sha256:%s is covered by proxy node attestation"
```
