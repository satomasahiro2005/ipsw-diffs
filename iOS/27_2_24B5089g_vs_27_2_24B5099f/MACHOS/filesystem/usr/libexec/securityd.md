## securityd

> `/usr/libexec/securityd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26dd24` | `0x26eb54` | **`+0xe30`** |
| `__TEXT.__objc_methname` | `0x2e77f` | `0x2e916` | **`+0x197`** |
| `__TEXT.__objc_stubs` | `0x1da60` | `0x1db60` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x14a28` | `0x14ab8` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x15ec0` | `0x15f30` | **`+0x70`** |
| `__TEXT.__cstring` | `0x22bde` | `0x22c4d` | **`+0x6f`** |
| `__DATA.__objc_const` | `0x23d18` | `0x23d80` | **`+0x68`** |
| `__DATA.__objc_selrefs` | `0x98d8` | `0x9918` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x2ff32` | `0x2ff6b` | **`+0x39`** |
| `__TEXT.__unwind_info` | `0x6a78` | `0x6aa8` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0xb0cf` | `0xb0f7` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x1c760` | `0x1c780` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x1aec` | `0x1af4` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xa124` | `0xa12c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
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
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-62460.40.56.502.1
+62460.40.74.0.0

-  Functions: 9922
+  Functions: 9934

-  CStrings:  16443
+  CStrings:  16459
CStrings:
+ "-[CuttlefishXPCWrapper notifyPeerTrustEstablishedWithSpecificUser:reply:]_block_invoke"
+ "@\"CKKSLocalResetOperation\""
+ "@?24@0:8@?16"
+ "B32@0:8^@16q24"
+ "T@\"CKKSLocalResetOperation\",&,V_lastLocalResetOperation"
+ "T@\"OTMetricsSessionData\",&,V_watchedFlowSessionMetrics"
+ "_lastLocalResetOperation"
+ "_watchedFlowSessionMetrics"
+ "claimWatchedFlowSessionMetrics"
+ "lastLocalResetOperation"
+ "notifyPeerTrustEstablishedWithSpecificUser:reply:"
+ "octagon: failed to notify TPH of trust establishment: %@"
+ "releaseWatchedFlowSessionMetrics:"
+ "setLastLocalResetOperation:"
+ "setWatchedFlowSessionMetrics:"
+ "watchedFlowSessionMetrics"
+ "wrapReplyReleasingWatchedFlowSessionMetrics:"
- "v32@0:8^@16q24"
```
