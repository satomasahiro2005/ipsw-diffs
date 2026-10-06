## HomeKitDaemonShared

> `/System/Library/PrivateFrameworks/HomeKitDaemonShared.framework/HomeKitDaemonShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaee8` | `0xc3e4` | **`+0x14fc`** |
| `__AUTH_CONST.__const` | `0x130` | `0x288` | **`+0x158`** |
| `__AUTH_CONST.__auth_got` | `0x350` | `0x460` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x1925` | `0x19ef` | **`+0xca`** |
| `__DATA.__data` | `0x5d8` | `0x678` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x768` | `0x7b8` | **`+0x50`** |
| `__TEXT.__const` | `0x2d0` | `0x320` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x2a0` | `0x2f0` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x71` | `0xbf` | **`+0x4e`** |
| `__DATA_CONST.__got` | `0x178` | `0x1a8` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x1910` | `0x1930` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x84` | `0xa0` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0xbec` | `0xc04` | **`+0x18`** |
| `__TEXT.__cstring` | `0x519` | `0x52b` | **`+0x12`** |
| `__DATA_CONST.__objc_protolist` | `0x80` | `0x90` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x90` | `0xa0` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xc` | `0x10` | **`+0x4`** |

### Other Changes

```diff

-1484.2.0.0.0
+1490.2.0.1.1

-  Functions: 252
-  Symbols:   583
-  CStrings:  164
+  Functions: 286
+  Symbols:   629
+  CStrings:  169
Symbols:
+ _NSCocoaErrorDomain
+ _OBJC_CLASS_$_NSXPCConnection
+ _OBJC_CLASS_$_NSXPCInterface
+ __Block_copy
+ __Block_release
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HMDNFCTagXPCProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HMDNFCTagXPCProtocol
+ __OBJC_$_PROTOCOL_REFS_HMDNFCTagXPCProtocol
+ __OBJC_LABEL_PROTOCOL_$_HMDNFCTagXPCProtocol
+ __OBJC_PROTOCOL_$_HMDNFCTagXPCProtocol
+ ___swift_allocate_value_buffer
+ ___swift_closure_destructor
+ ___swift_destroy_boxed_opaque_existential_0
+ ___swift_memcpy0_1
+ ___swift_project_value_buffer
+ __swiftEmptyArrayStorage
+ __swiftImmortalRefCount
+ __swift_stdlib_malloc_size
+ _block_copy_helper
+ _block_descriptor
+ _block_destroy_helper
+ _flat unique So20HMDNFCTagXPCProtocol_p
+ _malloc_size
+ _memcpy
+ _memmove
+ _swift_allocObject
+ _swift_deallocObject
+ _swift_dynamicCast
+ _swift_errorRetain
+ _swift_getErrorValue
+ _swift_getObjCClassMetadata
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_once
+ _swift_release_x20
+ _swift_release_x22
+ _swift_retain_x2
+ _swift_retain_x20
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRelease_n
+ _swift_unknownObjectRetain
+ _symbolic So15NSXPCConnectionC
+ _symbolic _____ 19HomeKitDaemonShared15NFCTagForwarderO
+ _symbolic ______p So20HMDNFCTagXPCProtocolP
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
CStrings:
+ "Failed to obtain XPC remote proxy"
+ "XPC error forwarding NFC tag: %{public}s"
+ "XPC to homed rejected (NSCocoaErrorDomain 4099 — entitlement mismatch)."
+ "homed reply error: %{public}s"
+ "nfc.tag.forwarder"
```
