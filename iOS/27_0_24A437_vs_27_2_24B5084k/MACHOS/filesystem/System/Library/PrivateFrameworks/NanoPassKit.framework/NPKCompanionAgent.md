## NPKCompanionAgent

> `/System/Library/PrivateFrameworks/NanoPassKit.framework/NPKCompanionAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x425b4` | `0x42df4` | **`+0x840`** |
| `__TEXT.__oslogstring` | `0x9c0c` | `0x9e4c` | **`+0x240`** |
| `__TEXT.__objc_methname` | `0xc547` | `0xc725` | **`+0x1de`** |
| `__TEXT.__objc_stubs` | `0x7c60` | `0x7e00` | **`+0x1a0`** |
| `__TEXT.__objc_methlist` | `0x3580` | `0x35f8` | **`+0x78`** |
| `__DATA.__objc_selrefs` | `0x28c8` | `0x2928` | **`+0x60`** |
| `__DATA.__objc_const` | `0x5c20` | `0x5c60` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x3606` | `0x3629` | **`+0x23`** |
| `__TEXT.__auth_stubs` | `0xd70` | `0xd90` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xe78` | `0xe98` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x6c8` | `0x6d8` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1054` | `0x1060` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x1bc` | `0x1c4` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x6e8` | `0x6f0` | **`+0x8`** |
| `__TEXT.__cstring` | `0x28ba` | `0x28bc` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1347.0.0.0.0
+1353.0.0.0.0

-  Functions: 1155
-  Symbols:   450
-  CStrings:  2746
+  Functions: 1164
+  Symbols:   453
+  CStrings:  2766
Symbols:
+ _NPKPaymentWebServiceBackgroundContextPathForDevice
+ _NPKPeerPaymentAccountPathForDevice
+ _NPKPeerPaymentWebServiceContextPathForDevice
+ _NPKStorePathForPaymentPassWithUniqueIDForDevice
+ _OBJC_CLASS_$_NPKPassSignatureValidationCache
- _NPKHomeDirectoryPath
- _NPKStorePathForPaymentPassWithUniqueID
CStrings:
+ "@\"NPKPassSignatureValidationCache\""
+ "Error: Not creating pass sync service: no initialized device"
+ "Notice: No peer payment account path (no active paired device); skipping peer payment account lookup."
+ "Notice: No peer payment account path (no active paired device); skipping peer payment account write."
+ "Notice: [BarcodeEvent] No pending transactions cache path (no active paired device); skipping archive."
+ "Notice: [BarcodeEvent] No pending transactions cache path (no active paired device); skipping fetch."
+ "Warning: No secure element identifiers available; not requesting associated data for pass with uniqueID: %@"
+ "_paymentWebServiceBackgroundContextPath"
+ "_paymentWebServiceBackgroundContextPathForDevice:"
+ "_paymentWebServiceContextPath"
+ "_paymentWebServiceContextPathForDevice:"
+ "_peerPaymentAccountPath"
+ "_peerPaymentAccountPathForDevice:"
+ "_peerPaymentWebServiceContextPath"
+ "_peerPaymentWebServiceContextPathForDevice:"
+ "_signatureValidationCache"
+ "initWithCompanionPaymentPassDatabase:pairedDevice:"
+ "initWithDevice:"
+ "initWithPassSyncEngineRole:pairedDevice:"
+ "initWithPasses:device:signatureValidationCache:"
+ "invalidatePassWithUniqueID:"
- "initWithPassSyncEngineRole:"
```
