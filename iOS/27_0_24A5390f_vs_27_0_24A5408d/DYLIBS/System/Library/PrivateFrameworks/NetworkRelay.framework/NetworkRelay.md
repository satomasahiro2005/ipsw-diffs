## NetworkRelay

> `/System/Library/PrivateFrameworks/NetworkRelay.framework/NetworkRelay`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x79568` | `0x7b824` | **`+0x22bc`** |
| `__TEXT.__cstring` | `0x10178` | `0x104d4` | **`+0x35c`** |
| `__AUTH_CONST.__cfstring` | `0x5140` | `0x51e0` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x5170` | `0x5200` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x1f64` | `0x1fc4` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xd18` | `0xd70` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x10b8` | `0x10e0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x9f8` | `0xa10` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x554` | `0x560` | **`+0xc`** |
| `__DATA.__bss` | `0x268` | `0x270` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0xf8` | `0xf0` | **`-0x8`** |

### Other Changes

```diff

-914.0.22.0.1
+914.0.34.0.4

-  Functions: 1048
-  Symbols:   2265
-  CStrings:  1974
+  Functions: 1064
+  Symbols:   2287
+  CStrings:  1997
Symbols:
+ -[NRDeviceInfo deviceType]
+ -[NRDeviceInfo isEnabled]
+ -[NRDeviceInfo isRegistered]
+ -[NRDeviceInfo setDeviceType:]
+ -[NRDeviceInfo setIsEnabled:]
+ -[NRDeviceInfo setIsRegistered:]
+ -[NRDeviceManager copyAllDevicesWithQueue:completionBlock:]
+ -[NRDeviceManager unregisterMesh:queue:completionBlock:]
+ GCC_except_table456
+ GCC_except_table467
+ GCC_except_table703
+ GCC_except_table711
+ GCC_except_table716
+ GCC_except_table720
+ GCC_except_table730
+ GCC_except_table734
+ GCC_except_table738
+ GCC_except_table742
+ GCC_except_table765
+ GCC_except_table768
+ GCC_except_table772
+ GCC_except_table781
+ GCC_except_table783
+ GCC_except_table785
+ GCC_except_table788
+ GCC_except_table790
+ GCC_except_table846
+ GCC_except_table848
+ GCC_except_table863
+ _NRDeviceManagerErrorMeshIdentifierKey
+ _OBJC_IVAR_$_NRDeviceInfo._deviceType
+ _OBJC_IVAR_$_NRDeviceInfo._isEnabled
+ _OBJC_IVAR_$_NRDeviceInfo._isRegistered
+ ___34-[NRDeviceManager unregisterMesh:]_block_invoke
+ ___56-[NRDeviceManager unregisterMesh:queue:completionBlock:]_block_invoke
+ ___76-[NRDeviceManager registerMesh:operationalProperties:queue:completionBlock:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e33_v16?0"NSObject<OS_xpc_object>"8ls40l8s32l8
+ ___block_descriptor_48_e8_32s40bs_e34_v32?0q8"NSString"16"NSString"24ls32l8s40l8
+ ___nrXPCCopyAllDevices_block_invoke
+ ___nrXPCRegisterMesh_block_invoke_2
+ ___nrXPCSendAsyncMeshResult_block_invoke
+ _nrXPCCopyAllDevices
+ _nrXPCEntitlementMeshMonitor_block_invoke_2.sNRXPCConnection
+ _nrXPCKeyAllDevices
+ _nrXPCRegisterMesh
+ _nrXPCUnregisterMesh
- GCC_except_table450
- GCC_except_table461
- GCC_except_table697
- GCC_except_table705
- GCC_except_table710
- GCC_except_table714
- GCC_except_table718
- GCC_except_table728
- GCC_except_table732
- GCC_except_table736
- GCC_except_table759
- GCC_except_table762
- GCC_except_table766
- GCC_except_table771
- GCC_except_table773
- GCC_except_table775
- GCC_except_table782
- GCC_except_table784
- GCC_except_table835
- GCC_except_table837
- GCC_except_table852
- _nrXPCEntitlementMeshMonitor_block_invoke.sNRXPCConnection
- _nrXPCKeyPersistentMesh
- _nrXPCSetPersistentMesh
CStrings:
+ " type:%@ %sregistered %sabled"
+ "%s called with null meshIdentifier"
+ "%s%.30s:%-4d Failed to register mesh %@: %@"
+ "%s%.30s:%-4d Failed to unregister mesh %@: %@"
+ "%s%.30s:%-4d Registered mesh %@"
+ "%s%.30s:%-4d Unregistered mesh %@"
+ "-[NRDeviceManager copyAllDevicesWithQueue:completionBlock:]"
+ "-[NRDeviceManager registerMesh:operationalProperties:queue:completionBlock:]_block_invoke"
+ "-[NRDeviceManager unregisterMesh:]_block_invoke"
+ "-[NRDeviceManager unregisterMesh:queue:completionBlock:]"
+ "-[NRDeviceManager unregisterMesh:queue:completionBlock:]_block_invoke"
+ "AllDevices"
+ "CopyAllDevices"
+ "Failed to deserialize all devices: %@"
+ "Missing all devices data in XPC response"
+ "NRDeviceManagerErrorMeshIdentifierKey"
+ "RegisterMesh"
+ "UnregisterMesh"
+ "isEnabled"
+ "nrXPCCopyAllDevices"
+ "nrXPCCopyAllDevices_block_invoke"
+ "nrXPCRegisterMesh"
+ "nrXPCSendAsyncMeshResult"
+ "nrXPCSendAsyncMeshResult_block_invoke"
+ "nrXPCUnregisterMesh"
+ "v32@?0q8@\"NSString\"16@\"NSString\"24"
- "PersistentMesh"
- "SetPersistentMesh"
- "nrXPCSetPersistentMesh"
```
