## SEService

> `/System/Library/PrivateFrameworks/SEService.framework/SEService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1142f4` | `0x11ce80` | **`+0x8b8c`** |
| `__DATA.__bss` | `0x1c790` | `0x1ec10` | **`+0x2480`** |
| `__TEXT.__const` | `0x18930` | `0x19ca8` | **`+0x1378`** |
| `__AUTH_CONST.__const` | `0xa9f0` | `0xb660` | **`+0xc70`** |
| `__TEXT.__eh_frame` | `0x6700` | `0x6b04` | **`+0x404`** |
| `__TEXT.__swift5_fieldmd` | `0x3cec` | `0x4094` | **`+0x3a8`** |
| `__TEXT.__swift5_typeref` | `0x4430` | `0x47b3` | **`+0x383`** |
| `__TEXT.__constg_swiftt` | `0x3a0c` | `0x3d34` | **`+0x328`** |
| `__TEXT.__unwind_info` | `0x5380` | `0x5660` | **`+0x2e0`** |
| `__DATA.__data` | `0x3750` | `0x39a0` | **`+0x250`** |
| `__TEXT.__swift5_reflstr` | `0x1952` | `0x1b44` | **`+0x1f2`** |
| `__TEXT.__cstring` | `0x8e85` | `0x9075` | **`+0x1f0`** |
| `__TEXT.__swift5_proto` | `0x1400` | `0x152c` | **`+0x12c`** |
| `__AUTH_CONST.__objc_const` | `0x8428` | `0x84e8` | **`+0xc0`** |
| `__TEXT.__swift5_capture` | `0x1e4` | `0x294` | **`+0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b78` | `0x1c10` | **`+0x98`** |
| `__TEXT.__objc_methlist` | `0x3ccc` | `0x3d24` | **`+0x58`** |
| `__TEXT.__swift5_types` | `0x5c8` | `0x620` | **`+0x58`** |
| `__AUTH_CONST.__auth_got` | `0x1040` | `0x1070` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x2e57` | `0x2e87` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x2a48` | `0x2a28` | **`-0x20`** |
| `__DATA.__objc_ivar` | `0x394` | `0x3ac` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x378` | `0x390` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x258` | `0x26c` | **`+0x14`** |
| `__TEXT.__gcc_except_tab` | `0x1ab4` | `0x1aa8` | **`-0xc`** |
| `__TEXT.__swift5_mpenum` | `0xf4` | `0xfc` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x4` | `0xc` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x374` | `0x37c` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x140` | `0x144` | **`+0x4`** |

### Other Changes

```diff

-70.39.1.0.0
+71.7.0.0.0

-  Functions: 7231
-  Symbols:   4703
-  CStrings:  1355
+  Functions: 7511
+  Symbols:   4816
+  CStrings:  1368
Symbols:
+ -[SESNFCAppSettingsContext bundle:hasEntitlement:]
+ -[SESNFCAppSettingsContext eligibilityForKind:service:]
+ -[SESNFCAppSettingsContext fireOnChange]
+ -[SESNFCAppSettingsContext initWithBundleId:onChange:tccAccessProvider:installedProvider:entitlementProvider:eligibilityProvider:defaultsSuiteName:]
+ -[SESNFCAppSettingsContext isBundleInstalled:allowPlaceholder:]
+ -[SESNFCAppSettingsContext liveEntitlementRecordForBundleId:]
+ -[SESNFCAppSettingsContext reconcile]
+ -[SESNFCAppSettingsContext tccAccessForService:bundleId:]
+ _OBJC_IVAR_$_SESNFCAppSettingsContext._eligibilityProvider
+ _OBJC_IVAR_$_SESNFCAppSettingsContext._entitlementProvider
+ _OBJC_IVAR_$_SESNFCAppSettingsContext._entitlementRecordCache
+ _OBJC_IVAR_$_SESNFCAppSettingsContext._entitlementRecordCacheBundleId
+ _OBJC_IVAR_$_SESNFCAppSettingsContext._installedProvider
+ _OBJC_IVAR_$_SESNFCAppSettingsContext._tccAccessProvider
+ ___40-[SESNFCAppSettingsContext fireOnChange]_block_invoke
+ ___swift_closure_destructorTm
+ ___swift_memcpy104_8
+ __dispatch_main_q
+ _associated conformance 9SEService12SESAppRecordV17InstallationStateOSHAASQ
+ _associated conformance 9SEService12SESAppRecordVSHAASQ
+ _associated conformance 9SEService13SERXPCRequestO29ReportCanFitFailureCodingKeys33_BD9D643E27EDCCF6A3C446974E43D3FDLLOSHAASQ
+ _associated conformance 9SEService13SERXPCRequestO29ReportCanFitFailureCodingKeys33_BD9D643E27EDCCF6A3C446974E43D3FDLLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 9SEService13SERXPCRequestO29ReportCanFitFailureCodingKeys33_BD9D643E27EDCCF6A3C446974E43D3FDLLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 9SEService14CredentialTypeO12DiscriminantOSHAASQ
+ _associated conformance 9SEService20AppMigrationInternalO10XPCRequestV10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOSHAASQ
+ _associated conformance 9SEService20AppMigrationInternalO10XPCRequestV10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO10XPCRequestV10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO11XPCResponseO10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOSHAASQ
+ _associated conformance 9SEService20AppMigrationInternalO11XPCResponseO10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO11XPCResponseO10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO11XPCResponseO15ErrorCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOSHAASQ
+ _associated conformance 9SEService20AppMigrationInternalO11XPCResponseO15ErrorCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO11XPCResponseO15ErrorCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO11XPCResponseO18MigratedCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO11XPCResponseO18MigratedCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO03XpcF10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOSHAASQ
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO03XpcF10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO03XpcF10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0I3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO0C16FailedCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOSHAASQ
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO0C16FailedCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO0C16FailedCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0I3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO0C20InProgressCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0J3KeyAAs23CustomStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO0C20InProgressCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0J3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO0D10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOSHAASQ
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO0D10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO0D10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOSHAASQ
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO10Foundation09LocalizedF0AAs0F0
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO21NotEntitledCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0J3KeyAAs23CustomStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO21NotEntitledCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0J3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO23SerializationCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOSHAASQ
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO23SerializationCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0I3KeyAAs23CustomStringConvertible
+ _associated conformance 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO23SerializationCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLOs0I3KeyAAs28CustomDebugStringConvertible
+ _get_enum_tag_for_layout_string 9SEService20AppMigrationInternalO11XPCResponseO
+ _get_enum_tag_for_layout_string 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO
+ _swift_retain_x23
+ _symbolic $s9SEService12TCCProvidingP
+ _symbolic $s9SEService14LSAppProvidingP
+ _symbolic SDy__________G 9SEService10TCCContextC10TCCServiceO AC9TCCAccessO
+ _symbolic _____ 9SEService12SESAppRecordV
+ _symbolic _____ 9SEService12SESAppRecordV17InstallationStateO
+ _symbolic _____ 9SEService13LSAppProviderV
+ _symbolic _____ 9SEService13SERXPCRequestO29ReportCanFitFailureCodingKeys33_BD9D643E27EDCCF6A3C446974E43D3FDLLO
+ _symbolic _____ 9SEService14CredentialTypeO12DiscriminantO
+ _symbolic _____ 9SEService18AppMigrationClientO
+ _symbolic _____ 9SEService20AppMigrationInternalO
+ _symbolic _____ 9SEService20AppMigrationInternalO10XPCRequestV
+ _symbolic _____ 9SEService20AppMigrationInternalO10XPCRequestV10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____ 9SEService20AppMigrationInternalO11XPCResponseO
+ _symbolic _____ 9SEService20AppMigrationInternalO11XPCResponseO10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____ 9SEService20AppMigrationInternalO11XPCResponseO15ErrorCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____ 9SEService20AppMigrationInternalO11XPCResponseO18MigratedCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____ 9SEService20AppMigrationInternalO5TypesO
+ _symbolic _____ 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO
+ _symbolic _____ 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO03XpcF10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____ 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO0C16FailedCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____ 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO0C20InProgressCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____ 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO0D10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____ 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____ 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO21NotEntitledCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____ 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO23SerializationCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____6reason______14credentialTypet 9SEService10SESnapshotC12CanFitResultO13FailureReasonV AA14CredentialTypeO12DiscriminantO
+ _symbolic _____Sg 9SEService12SESAppRecordV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 9SEService13SERXPCRequestO29ReportCanFitFailureCodingKeys33_BD9D643E27EDCCF6A3C446974E43D3FDLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 9SEService20AppMigrationInternalO10XPCRequestV10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 9SEService20AppMigrationInternalO11XPCResponseO10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 9SEService20AppMigrationInternalO11XPCResponseO15ErrorCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 9SEService20AppMigrationInternalO11XPCResponseO18MigratedCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO03XpcI10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO0F16FailedCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO0F20InProgressCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO0G10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO21NotEntitledCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO23SerializationCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 9SEService13SERXPCRequestO29ReportCanFitFailureCodingKeys33_BD9D643E27EDCCF6A3C446974E43D3FDLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 9SEService20AppMigrationInternalO10XPCRequestV10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 9SEService20AppMigrationInternalO11XPCResponseO10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 9SEService20AppMigrationInternalO11XPCResponseO15ErrorCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 9SEService20AppMigrationInternalO11XPCResponseO18MigratedCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO03XpcI10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO0F16FailedCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO0F20InProgressCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO0G10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO10CodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO21NotEntitledCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO23SerializationCodingKeys33_C352F89A29641555C860C1DB4D8FA3FFLLO
+ _symbolic _____y__________G s18_DictionaryStorageC 9SEService10TCCContextC10TCCServiceO AE9TCCAccessO
+ _type_layout_string 9SEService12SESAppRecordV
+ _type_layout_string 9SEService20AppMigrationInternalO10XPCRequestV
+ _type_layout_string 9SEService20AppMigrationInternalO11XPCResponseO
+ _type_layout_string 9SEService20AppMigrationInternalO5TypesO9ErrorCodeO
- -[SESNFCAppSettingsContext reconcileWithRecord:]
CStrings:
+ "An app migration is already in progress"
+ "App migration XPC error: "
+ "App migration encountered an internal error: "
+ "App migration failed to serialize/deserialize a message: "
+ "App migration failed: "
+ "AppMigrationXPCRequest "
+ "Bundle ID %@ does not correspond to an installed record"
+ "Client is not entitled to perform app migration"
+ "SERXPCClient: Failed to send fire-and-forget request: %@"
+ "SERXPCClient: Sending fire-and-forget request %s"
+ "com.apple.seserviced.private.appmigration"
+ "destinationBundleId"
+ "migrationInProgress"
+ "os_eligibility_get_domain_answer returned error code %d"
+ "reason credentialType "
+ "reportCanFitFailure"
- "Bundle ID %@ does not correspond to a record or error encountered %@"
- "Default Contactless App Configurable returned error code %d"
- "Default Contactless App Usable returned error code %d"
```
