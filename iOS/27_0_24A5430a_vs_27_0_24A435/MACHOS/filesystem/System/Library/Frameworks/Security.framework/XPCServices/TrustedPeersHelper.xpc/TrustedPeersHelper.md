## TrustedPeersHelper

> `/System/Library/Frameworks/Security.framework/XPCServices/TrustedPeersHelper.xpc/TrustedPeersHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2acff0` | `0x2ad1e0` | **`+0x1f0`** |
| `__TEXT.__objc_stubs` | `0x61c0` | `0x61a0` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x92c1` | `0x92b1` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0xe064` | `0xe05b` | **`-0x9`** |
| `__DATA.__objc_selrefs` | `0x1f18` | `0x1f10` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x2944` | `0x293c` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x5008` | `0x5000` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-62460.2.2.0.0
+62460.2.3.0.0

-  Functions: 8948
+  Functions: 8947

-  CStrings:  3259
+  CStrings:  3258
CStrings:
+ "Couldn't verify signature of TLKShare (%@) without tlkOwnershipProof as part of dataForSigning; trying again with tlkOwnershipProof"
+ "verifySignature:verifyingPeer:ckrecord:acceptSigWithProof:error:"
- "Couldn't verify signature of TLKShare (%@) that includes tlkOwnershipProof as part of dataForSigning; trying again without tlkOwnershipProof"
- "dataForSigning:"
- "verifySignature:verifyingPeer:ckrecord:acceptProoflessSig:error:"
```
