## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.im4p/exclave_sharedcache`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xee2354` | `0xed86c4` | **`-0x9c90`** |
| `__DATA.__data` | `0x5cda8` | `0x5c988` | **`-0x420`** |
| `__TEXT.__cstring` | `0xb24e1` | `0xb20c1` | **`-0x420`** |
| `__TEXT.__constg_swiftt` | `0x73604` | `0x732dc` | **`-0x328`** |
| `__TEXT.__oslogstring` | `0x72c5` | `0x7085` | **`-0x240`** |
| `__TEXT.__eh_frame` | `0x82ea0` | `0x82c6c` | **`-0x234`** |
| `__TEXT.__swift5_typeref` | `0x31736` | `0x31506` | **`-0x230`** |
| `__DATA.__ENDPOINTS` | `0x1b9c2` | `0x1bbd0` | **`+0x20e`** |
| `__TEXT.__swift5_fieldmd` | `0x7b4e8` | `0x7b3a0` | **`-0x148`** |
| `__DATA.__const` | `0x13dd50` | `0x13dca8` | **`-0xa8`** |
| `__PDATA.__bss` | `0xba48` | `0xbae8` | **`+0xa0`** |
| `__DATA.__bss` | `0x24ff0` | `0x24f70` | **`-0x80`** |
| `__TEXT.__const` | `0x1ee374` | `0x1ee2f4` | **`-0x80`** |
| `__TEXT.__swift_as_cont` | `0x2f00` | `0x2f58` | **`+0x58`** |
| `__TEXT.__swift5_reflstr` | `0x4bad8` | `0x4ba88` | **`-0x50`** |
| `__TEXT.__swift5_assocty` | `0xfec8` | `0xfe80` | **`-0x48`** |
| `__DATA.__common` | `0x4931` | `0x4901` | **`-0x30`** |
| `__DATA.__auth_ptr` | `0x7e68` | `0x7e40` | **`-0x28`** |
| `__TEXT.__swift_as_ret` | `0x1860` | `0x1880` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0xc070` | `0xc054` | **`-0x1c`** |
| `__TEXT.__swift_as_entry` | `0x1658` | `0x1670` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x7940` | `0x792c` | **`-0x14`** |
| `__PDATA.__const` | `0x6800` | `0x6810` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x14c8` | `0x14c0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__TIGHTBEAM`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__got`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__DATA.__thread_vars`
- `__PDATA.__auth_ptr`
- `__PDATA.__data`
- `__PDATA.__mod_init_func`
- `__PDATA.__shared_cache`
- `__TEXT.__chain_fixups`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_types2`

### Other Changes

```diff

-1777.40.23.502.2
-  Functions: 53151
+1777.40.28.0.2
+  Functions: 53102

-  CStrings:  16561
+  CStrings:  16512
CStrings:
+ " bytes for clientCode "
+ " for clientCode "
+ " opted into prefers-waiting-through-sleep; option accepted but not yet implemented"
+ "%s(%zu): failed to delete delta scratch RO span slot"
+ "%s(%zu): failed to delete delta scratch RO temp cap"
+ "%s(%zu): failed to map frame into delta scratch RO span"
+ "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Sat Sep 12 05:10:17 PDT 2026; root:AppleImage4_exclavecore-374~18509/ExclaveImage4/RELEASE_ARM64E"
+ "ANEExclave version: ANEExclave_exclavecore-13.101.1"
+ "B16@?0^{vas_core_span={?=CQQCCCCC^vQ}iC[3C]{?=^?^?^?}^vQQ^{vas_core_vas}^{vas_core_span}^{vas_core_span}Q^{vas_segment}{spanmap_struct=b2b4b22b36}{_liblibc_mtx=[16C]}B{?=^{vas_core_span}^^{vas_core_span}}{spanmap_struct=b2b4b22b36}}8"
+ "Build Date: Sat Sep 12 04:43:50 PDT 2026"
+ "Creating new repository for clientCode "
+ "Deferred power on for ANEEngine from "
+ "Detected file size "
+ "ExclaveOS Image4 Framework Version 7.0.0: Sat Sep 12 05:10:17 PDT 2026; root:AppleImage4_exclavecore-374~18509/ExclaveImage4/RELEASE_ARM64E"
+ "Repository loaded for clientCode "
+ "Resuming ANEEngine to service existing clients from "
+ "Save for clientCode "
+ "Tue Sep 15 12:41:23 PDT 2026"
+ "Unexpected L4_Error: %s(%zu) err='L4_Cap_Delete(scratch->ro_span_slot)'"
+ "Unexpected L4_Error: %s(%zu) err='L4_Cap_Delete(scratch->ro_temp_slot)'"
+ "Unexpected L4_Error: %s(%zu) err='_map_this_frame_readonly(scratch->ro_span, (uintptr_t)ro_words, scratch->ro_temp_slot)'"
+ "[VAS abort in function %s at line %d] [%s] could not allocate fixup span for fault handler\n"
+ "[VAS abort in function %s at line %d] [true: (%s)] Could not depopulate temp span (drop): %s (0x%04hx)\n\n"
+ "[VAS abort in function %s at line %d] [true: (%s)] _delta_page_against_original returned unexpected result(%p)\n"
+ "_delta_page_against_original"
+ "applyFixups: rebase failed for %#lx (region %zd)"
+ "applyFixups: region %zd has NULL fixup_metadata_pointer"
+ "clientSessionHint(client:model:args:) Cycles: "
+ "clientSetPowerHint(client:model:keepPowered:) Cycles: "
+ "com.apple.securepairing.frequent"
+ "delta_output != fault->write_buffer"
+ "vas_return_code(drop_depop) != VAS_SUCCESS"
- ", iopsOverride: "
- ", preferedEncoding: "
- "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Fri Sep  4 01:28:14 PDT 2026; root:AppleImage4_exclavecore-374~18270/ExclaveImage4/RELEASE_ARM64E"
- "ANEExclave version: ANEExclave_exclavecore-13.100.8"
- "All domain keys are up to date"
- "Attempt to serialize IOPDomainKey without peerPubKey"
- "Attempt to serialize IOPDomainKey without serializedRefKey"
- "B16@?0^{vas_core_span={?=CQQCCCCC^vQ}iC[3C]{?=^?^?}^vQQ^{vas_core_vas}^{vas_core_span}^{vas_core_span}Q^{vas_segment}{spanmap_struct=b2b4b22b36}{_liblibc_mtx=[16C]}B{?=^{vas_core_span}^^{vas_core_span}}{spanmap_struct=b2b4b22b36}}8"
- "Build Date: Wed Sep  9 20:44:59 PDT 2026"
- "Can't read iop type from stream"
- "Can't read peerPubKey"
- "Can't serialize AKSRefKey: "
- "Could not update a public key for domain: %u"
- "Deferred power on for ANEEngine"
- "Dropping unsoported public key type: %u"
- "ExclaveOS Image4 Framework Version 7.0.0: Fri Sep  4 01:28:14 PDT 2026; root:AppleImage4_exclavecore-374~18270/ExclaveImage4/RELEASE_ARM64E"
- "Failed to read domain key"
- "Failed to read domain key count"
- "Failed to read iop domain keys"
- "Fri Sep 11 21:06:35 PDT 2026"
- "Record does not contain domain keys"
- "Requested iop keys: "
- "Resuming ANEEngine to service existing clients"
- "SPR not found for peerId "
- "Saving the client repository failed"
- "SecurePairingCoreComponent/SecurePairingCore+Domain.swift"
- "Skipping unsupported IOP key type: %u"
- "Skipping unsupported IOP type: %u"
- "Stored domain keys contain unknow IOP type: %u"
- "TransferDataStream attempt to receive data in finished state"
- "TransferDataStream attempt to send data in finished state"
- "Unexpected iop type code "
- "Update domain keys, missing keys: "
- "Updating provided keys based on peer response"
- "Will provide keys for IOPs: "
- "cancelDomainPairing threw an unexpected error type"
- "extractPublicKeys(from: "
- "extractPublicKeys(from:)"
- "extracted public keys for domains: "
- "generateDomainKeys()"
- "generateKey(for: "
- "generateKey(for:)"
- "got key material: "
- "handleDomainKeys -> "
- "handleDomainKeys threw an unexpected error type"
- "handleDomainKeys(pairingId: "
- "handleDomainKeys(pairingId:bytes:)"
- "handleDomainKeysAck -> "
- "handleDomainKeysAck threw an unexpected error type"
- "handleDomainKeysAck(pairingId: "
- "handleDomainKeysAck(pairingId:bytes:)"
- "handleMissingKeyTypes(peerIds: "
- "handleMissingKeyTypesAck -> "
- "handleMissingKeyTypesAck(pairingId: "
- "handleMissingKeyTypesAck(pairingId:bytes:)"
- "handleMissingKeyTypesCont -> "
- "handleMissingKeyTypesCont(pairingId: "
- "handleMissingKeyTypesCont(pairingId:bytes:)"
- "handleMissingKeys -> "
- "handleMissingKeys(bytes: "
- "handleMissingKeys(context:bytes:)"
- "handleStartKeyTransfer - no iops set to context before key transfer"
- "handleStartKeyTransfer -> "
- "handleStartKeyTransfer threw an unexpected error type"
- "handleStartKeyTransfer(pairingId: "
- "handleStartKeyTransfer(pairingId:)"
- "invalid rawValue for TransferEncoding: "
- "no payload should be here"
- "setProvidedKeys(_:merge:)"
- "startDomainPairing -> "
- "startDomainPairing(clientClass:peerId:tag:encoding:iopsOverride:bytes:)"
- "startDomainPairing(clientClass:peerId:tag:preferedEncoding:iopsOverride:)"
- "startDomainPairing(peerIds: "
- "storeDomainKeys()"
- "storing new keys for domains: "
- "storing original keys for domains: "
- "unexpected payload size: %ld"
- "updateDomainKeys(iopsOverride: "
- "updateDomainKeys(iopsOverride:)"
- "updatePublicKeys(_:)"
- "updatePublicKeys(from:) count = "
```
