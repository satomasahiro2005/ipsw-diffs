## findmydeviced

> `/usr/libexec/findmydeviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4d565c` | `0x4de348` | **`+0x8cec`** |
| `__TEXT.__eh_frame` | `0x25adc` | `0x261f4` | **`+0x718`** |
| `__TEXT.__oslogstring` | `0x1c9c9` | `0x1cbe9` | **`+0x220`** |
| `__TEXT.__unwind_info` | `0xf948` | `0xfb58` | **`+0x210`** |
| `__DATA.__objc_const` | `0x1e858` | `0x1e9b0` | **`+0x158`** |
| `__DATA.__bss` | `0x28b70` | `0x28a70` | **`-0x100`** |
| `__TEXT.__objc_methname` | `0x20389` | `0x20449` | **`+0xc0`** |
| `__TEXT.__objc_stubs` | `0x189e0` | `0x18a60` | **`+0x80`** |
| `__DATA.__data` | `0xacf0` | `0xad68` | **`+0x78`** |
| `__DATA_CONST.__const` | `0x1d720` | `0x1d790` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x108cc` | `0x1093c` | **`+0x70`** |
| `__TEXT.__const` | `0x46416` | `0x463b6` | **`-0x60`** |
| `__TEXT.__swift_as_cont` | `0x1f94` | `0x1fe8` | **`+0x54`** |
| `__DATA.__objc_data` | `0x5520` | `0x5570` | **`+0x50`** |
| `__TEXT.__swift_as_ret` | `0x13a0` | `0x13e8` | **`+0x48`** |
| `__TEXT.__auth_stubs` | `0x4d40` | `0x4d80` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0x2a16` | `0x2a56` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x3ddc` | `0x3e1c` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x1cd0` | `0x1d10` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x560e` | `0x563e` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x7138` | `0x7160` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x26b0` | `0x26d0` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0xd14` | `0xd30` | **`+0x1c`** |
| `__TEXT.__constg_swiftt` | `0x5978` | `0x5990` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x6c8c` | `0x6ca4` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x1e10` | `0x1e18` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1b60` | `0x1b68` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x8e8` | `0x8f0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x2a8` | `0x2b0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x580` | `0x588` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x13f4` | `0x13ec` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x4d24` | `0x4d1c` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x1150` | `0x1154` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-482.30.6.14.8
+482.30.6.14.20

-  Functions: 16215
-  Symbols:   2694
-  CStrings:  10306
+  Functions: 16287
+  Symbols:   2699
+  CStrings:  10329
Symbols:
+ _$s14FindMyCloudKit0cD9ChangeSetV5ErrorO19deleteWithNewRecordyA2EmFWC
+ _$s14FindMyCloudKit0cD9ChangeSetV5ErrorOMa
+ _$s15FindMyBluetooth10PeripheralC11isConnectedSbvgTj
+ _$sSh11descriptionSSvg
+ _swift_release_x3
CStrings:
+ "#nvram - Skipping clear for key %@, already absent"
+ "%@ clearAllState: preserveLock=%d"
+ "%s accessory record %{public}s already removed; treating unpair as complete"
+ "@\"<FMDNVRAMWritePrimitives>\""
+ "@\"NSData\"24@0:8@\"NSString\"16"
+ "Bluetooth not ready for proactive key rotation: %{public}@"
+ "Cancelled indication monitoring for peripheral: %{public}s"
+ "Cancelled operation: %s"
+ "FMDNVRAMIOKitWritePrimitives"
+ "FMDNVRAMWritePrimitives"
+ "Failed to check connection for %{private,mask.hash}s: %{public}@"
+ "Failed to store connect event for accessory %{public}s, error: %@"
+ "PencilAutoPairing: %{public}s; awaiting initiatePairing from client for accessory: %{public}s"
+ "Proactively rotating key for already-connected %{private,mask.hash}s"
+ "T@\"<FMDNVRAMWritePrimitives>\",&,N,V_writePrimitives"
+ "Terminated indication monitoring for peripheral: %{public}s"
+ "Terminated operation: %s"
+ "_writePrimitives"
+ "connectedAccessories updated: %{public}s"
+ "dataForKey:"
+ "i32@0:8@\"NSString\"16@\"NSData\"24"
+ "i32@0:8@16@24"
+ "initWithWritePrimitives:"
+ "saveDataForKey:value:"
+ "setWritePrimitives:"
+ "writePrimitives"
- "#nvram - Error retrieving data value from nvrm. result code %d"
- "%@ clearAllState: Preserving PFLock activationLockInfo (maskedAppleID, activationLockStatus, fmLockType)"
- "PencilAutoPairing: notPaired; awaiting initiatePairing from client for accessory: %{public}s"
```
