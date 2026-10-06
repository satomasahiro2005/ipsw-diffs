## securityd

> `/usr/libexec/securityd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26ccb4` | `0x26cad8` | **`-0x1dc`** |
| `__DATA_CONST.__cfstring` | `0x1c520` | `0x1c540` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1d9c0` | `0x1d9a0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x22791` | `0x227a6` | **`+0x15`** |
| `__TEXT.__objc_methname` | `0x2e68f` | `0x2e67f` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x2feb3` | `0x2feaa` | **`-0x9`** |
| `__DATA.__objc_selrefs` | `0x98a8` | `0x98a0` | **`-0x8`** |
| `__DATA_CONST.__const` | `0x149b8` | `0x149c0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x15ea0` | `0x15e98` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x6a70` | `0x6a68` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0xa074` | `0xa078` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-62460.2.2.0.0
+62460.2.3.0.0

-  Functions: 9918
+  Functions: 9917
CStrings:
+ "Couldn't verify signature of TLKShare (%@) without tlkOwnershipProof as part of dataForSigning; trying again with tlkOwnershipProof"
+ "PhotoRevocationCheck"
+ "verifySignature:verifyingPeer:acceptSigWithProof:error:"
+ "verifySignature:verifyingPeer:ckrecord:acceptSigWithProof:error:"
- "Couldn't verify signature of TLKShare (%@) that includes tlkOwnershipProof as part of dataForSigning; trying again without tlkOwnershipProof"
- "dataForSigning"
- "verifySignature:verifyingPeer:acceptProoflessSig:error:"
- "verifySignature:verifyingPeer:ckrecord:acceptProoflessSig:error:"
```
