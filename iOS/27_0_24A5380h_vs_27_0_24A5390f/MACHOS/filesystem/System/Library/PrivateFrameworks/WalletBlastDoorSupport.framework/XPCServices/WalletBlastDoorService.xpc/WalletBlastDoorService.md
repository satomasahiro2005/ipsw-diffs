## WalletBlastDoorService

> `/System/Library/PrivateFrameworks/WalletBlastDoorSupport.framework/XPCServices/WalletBlastDoorService.xpc/WalletBlastDoorService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8290` | `0x178dc` | **`+0xf64c`** |
| `__TEXT.__auth_stubs` | `0xb50` | `0x1b20` | **`+0xfd0`** |
| `__DATA_CONST.__auth_got` | `0x5b0` | `0xd98` | **`+0x7e8`** |
| `__TEXT.__eh_frame` | `0x190` | `0x770` | **`+0x5e0`** |
| `__DATA_CONST.__got` | `0xd8` | `0x428` | **`+0x350`** |
| `__TEXT.__oslogstring` | `—` | `0x32d` | **`+0x32d`** |
| `__TEXT.__swift5_typeref` | `0x144` | `0x339` | **`+0x1f5`** |
| `__TEXT.__cstring` | `0x48` | `0x22b` | **`+0x1e3`** |
| `__DATA.__data` | `0x180` | `0x300` | **`+0x180`** |
| `__TEXT.__const` | `0x242` | `0x3a0` | **`+0x15e`** |
| `__TEXT.__unwind_info` | `0x160` | `0x298` | **`+0x138`** |
| `__DATA_CONST.__auth_ptr` | `0xd0` | `0x200` | **`+0x130`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-325.100.1.0.0
+327.100.2.0.0

+  - /usr/lib/swift/libswift_StringProcessing.dylib

-  Functions: 75
-  Symbols:   85
-  CStrings:  4
+  Functions: 135
+  Symbols:   99
+  CStrings:  28
Symbols:
+ __os_log_impl
+ _objc_release_x27
+ _os_log_type_enabled
+ _swift_bridgeObjectRelease_n
+ _swift_dynamicCastClass
+ _swift_errorRelease
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_once
+ _swift_retain_x27
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRelease_n
+ _swift_unknownObjectRetain
CStrings:
+ "Discarding barcode because its message encoding is too long"
+ "Discarding barcode because its message is too long"
+ "Discarding order provider because its dark tracking logo name is too long"
+ "Discarding order provider because its light tracking logo name is too long"
+ "Discarding pickup fulfillment because its identifier is too long"
+ "Discarding return because its identifier is too long"
+ "Discarding shipping fulfillment because its identifier is too long"
+ "Discarding webServiceURL and authenticationToken because the authenticationToken is too long"
+ "Discarding webServiceURL and authenticationToken because the webServiceURL has an invalid scheme"
+ "Discarding webServiceURL and authenticationToken because the webServiceURL has no scheme"
+ "WalletOrderContent"
+ "changeNotifications"
+ "changeNotificationsInvalid"
+ "com.apple.BlastDoor"
+ "com.apple.BlastDoor.WalletOrderContent"
+ "fulfillmentInvalid"
+ "fulfillments.pickup.status"
+ "fulfillments.shipping.shippingType"
+ "fulfillments.shipping.status"
+ "orderContentInvalid"
+ "payment.transactions.status"
+ "payment.transactions.type"
+ "shippingTypeInvalid"
+ "transactionTypeInvalid"
```
