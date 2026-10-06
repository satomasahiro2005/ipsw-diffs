## softposreaderd

> `/usr/libexec/softposreaderd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x88340` | `0x708d0` | **`-0x17a70`** |
| `__TEXT.__text` | `0x423c64` | `0x41cb58` | **`-0x710c`** |
| `__TEXT.__oslogstring` | `0xce4e` | `0xd12e` | **`+0x2e0`** |
| `__TEXT.__cstring` | `0x119ab` | `0x11b7b` | **`+0x1d0`** |
| `__DATA_CONST.__const` | `0x182d0` | `0x18198` | **`-0x138`** |
| `__TEXT.__eh_frame` | `0xca8c` | `0xcb80` | **`+0xf4`** |
| `__TEXT.__objc_methname` | `0x42cd` | `0x425d` | **`-0x70`** |
| `__TEXT.__unwind_info` | `0x4e40` | `0x4e78` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x4290` | `0x42c0` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x795c` | `0x7984` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x2150` | `0x2168` | **`+0x18`** |
| `__DATA.__bss` | `0x15ce0` | `0x15cf0` | **`+0x10`** |
| `__DATA.__data` | `0xc7e8` | `0xc7f8` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x3b0` | `0x3bc` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0xe40` | `0xe48` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xde0` | `0xde8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x188` | `0x18c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x188` | `0x18c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-50.33.0.0.0
+51.4.0.0.0

-  Functions: 6163
-  Symbols:   1688
-  CStrings:  3582
+  Functions: 6169
+  Symbols:   1692
+  CStrings:  3606
Symbols:
+ _SPRConfigurationStatusIsNFCAvailable
+ _swift_task_deinitOnExecutor
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
CStrings:
+ " exceeds store size "
+ "%s.%s: no controllerInfo; assuming antenna present"
+ "Could not deserialize pinBlob to JSON"
+ "Could not deserialize trxBlob to JSON"
+ "Could not parse cipherBlob"
+ "Could not prepare signer"
+ "Could not remove batch: %@, repairing store."
+ "Error preparing signer: %@"
+ "Error repairing store when remove batch failed: %@"
+ "Failed to store boot UUID: %s"
+ "Failed to store completeAttestation: %@"
+ "Failed to store logDeletion: %@"
+ "Monitor store is unexpected size after removing batch. Got: "
+ "NFC antenna not present on this device"
+ "NFC antenna not supported on this device"
+ "Store cleared"
+ "batch reference "
+ "completeAttestation stored"
+ "controllerInfo"
+ "deviceClass"
+ "didPostPINEvent"
+ "hasAntenna"
+ "isAntennaPresent"
+ "logDeletion stored"
+ "monitoring-logs.tmp"
+ "pinBlob is empty"
+ "pinBlob is not a JSON object"
+ "readerBlobSigner certificate expires before time required: %ld seconds. Begin renewal."
+ "softposreaderd/UnifiedReaderPINController.swift"
+ "trxBlob is empty"
+ "trxBlob is not a JSON object"
- "Could not remove batch: %@"
- "Remove all events failed: "
- "URLForDirectory:inDomain:appropriateForURL:create:error:"
- "_itemReplacementDirectory"
- "cannot delete itemReplacementDirectory"
- "failed to create itemReplacementDirectory"
- "truncateAtOffset:error:"
```
