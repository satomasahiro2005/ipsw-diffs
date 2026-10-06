## maild

> `/System/Library/PrivateFrameworks/EmailDaemon.framework/maild`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x152748` | `0x152e14` | **`+0x6cc`** |
| `__TEXT.__gcc_except_tab` | `0x1962c` | `0x19718` | **`+0xec`** |
| `__TEXT.__objc_methname` | `0x1cef5` | `0x1cfd5` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0xaffe` | `0xb0ce` | **`+0xd0`** |
| `__TEXT.__objc_stubs` | `0x164e0` | `0x165a0` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x6f38` | `0x6f78` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x7008` | `0x7038` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xae24` | `0xae54` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xe5f8` | `0xe620` | **`+0x28`** |
| `__TEXT.__cstring` | `0x8df8` | `0x8e08` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
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
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3901.200.41.0.0
+3901.200.66.2.1

-  Functions: 5874
+  Functions: 5880

-  CStrings:  7516
+  CStrings:  7526
CStrings:
+ "Delivery did not commit (status %ld), keeping source draft"
+ "Message %@ permanently failed delivery, but no Drafts mailbox is available to move it to"
+ "Message %@ permanently failed delivery, moving to Drafts"
+ "_moveToDraftsAfterPermanentlyFailedDelivery:inOutbox:forAccount:"
+ "_removeSourceDraftForOutgoingMessage:"
+ "_removeSourceDraftForOutgoingMessage:deliveryStatus:"
+ "deleteDraftsInMailboxID:documentID:previousDraftObjectID:"
+ "sourceAutosaveID"
+ "sourceDraftObjectID"
+ "v16@?0@\"EMMessage\"8"
```
