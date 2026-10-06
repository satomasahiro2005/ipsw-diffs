## modelmanagerd

> `/usr/libexec/modelmanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ba03c` | `0x1c4f34` | **`+0xaef8`** |
| `__TEXT.__eh_frame` | `0x16744` | `0x17174` | **`+0xa30`** |
| `__TEXT.__unwind_info` | `0x6af0` | `0x7100` | **`+0x610`** |
| `__TEXT.__oslogstring` | `0xa269` | `0xa539` | **`+0x2d0`** |
| `__DATA_CONST.__const` | `0x88a8` | `0x8ab8` | **`+0x210`** |
| `__DATA.__data` | `0x63f0` | `0x65f8` | **`+0x208`** |
| `__TEXT.__swift5_reflstr` | `0x2623` | `0x2763` | **`+0x140`** |
| `__TEXT.__const` | `0x6836` | `0x6956` | **`+0x120`** |
| `__TEXT.__objc_methname` | `0x1993` | `0x1ab3` | **`+0x120`** |
| `__DATA.__objc_const` | `0x4430` | `0x4540` | **`+0x110`** |
| `__TEXT.__constg_swiftt` | `0x2da4` | `0x2eb4` | **`+0x110`** |
| `__TEXT.__swift5_capture` | `0x2758` | `0x283c` | **`+0xe4`** |
| `__TEXT.__auth_stubs` | `0x3e80` | `0x3f50` | **`+0xd0`** |
| `__TEXT.__swift5_fieldmd` | `0x21cc` | `0x2274` | **`+0xa8`** |
| `__TEXT.__swift_as_cont` | `0x1234` | `0x12dc` | **`+0xa8`** |
| `__DATA.__objc_data` | `0x700` | `0x7a0` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x28b3` | `0x293b` | **`+0x88`** |
| `__TEXT.__cstring` | `0x1f50` | `0x1fd0` | **`+0x80`** |
| `__DATA_CONST.__auth_got` | `0x1f48` | `0x1fb0` | **`+0x68`** |
| `__TEXT.__swift_as_ret` | `0xad0` | `0xb34` | **`+0x64`** |
| `__DATA.__common` | `0x640` | `0x6a0` | **`+0x60`** |
| `__TEXT.__swift_as_entry` | `0x954` | `0x984` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0xd58` | `0xd78` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xf60` | `0xf70` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-703.0.33.0.0
+714.40.81.502.1

-  Functions: 9166
-  Symbols:   1705
-  CStrings:  1224
+  Functions: 9393
+  Symbols:   1722
+  CStrings:  1250
Symbols:
+ _$s12ModelCatalog11CostProfileV25transitionDelayMultiplierSivg
+ _$s20ModelManagerServices10ClientDataVSQAAMc
+ _$s20ModelManagerServices15RemoteDeviceSetV8rawValues6UInt32Vvg
+ _$s20ModelManagerServices15RemoteDeviceSetVSQAAMc
+ _$s20ModelManagerServices17ExclaveBundleInfoVMn
+ _$s20ModelManagerServices20PrewarmConfigurationV16requiredAssetIDs21excludedResourceTypes8metadata17requestClientData21propagateLoadFailuresACShySSGSg_AJSDyS2SGSgAA0nO0VSgSbtcfC
+ _$s20ModelManagerServices20PrewarmConfigurationV16requiredAssetIDs21excludedResourceTypes8metadata17requestClientData21propagateLoadFailuresACShySSGSg_AJSDyS2SGSgAA0nO0VSgSbtcfcfA3_
+ _$s20ModelManagerServices20PrewarmConfigurationV21propagateLoadFailuresSbvg
+ _$s20ModelManagerServices26InferenceProviderXPCSenderC28usedSinceLastHysteresisCheck15assetDescriptorSbAA0de5AssetM0V_tYaKFTjTu
+ _$s20ModelManagerServices35InferenceProviderPrewarmInformationV17requestClientDataAA0iJ0VSgvg
+ _$s20ModelManagerServices7SessionC8MetadataV14assetBundleURI9useCaseID13onBehalfOfPID06parentn2OnmnO017loggingIdentifier2id010sessionSetK025inferenceInterfaceVersion25customAssetConfigurations06clientD4Data13codeSignature22prefersImmediateUnloadAE10Foundation3URLV_SSs5Int32VSiSSAA14UUIDIdentifierVyACGAR4UUIDVAA0Y0VSayAA24CustomAssetConfigurationVGSgAA10ClientDataVSgAA13CodeSignatureOSbtcfC
+ _$s20ModelManagerServices7SessionC8MetadataV22prefersImmediateUnloadSbvg
+ _$s8Dispatch0A13WorkItemFlagsV10enforceQoSACvgZ
+ _$s8Dispatch0A3QoSV0B6SClassO8rawValueAESgSo11qos_class_ta_tcfC
+ _$s8Dispatch0A3QoSV0B6SClassOMn
+ _$s8Dispatch0A3QoSV8qosClass16relativePriorityA2C0B6SClassO_SitcfC
+ _$ss10SetAlgebraP12intersectionyxxFTj
+ _$ss10SetAlgebraP7isEmptySbvgTj
+ _$ss10SetAlgebraP8subtractyyxFTj
+ _$ss10SetAlgebraPxycfCTj
- _$s20ModelManagerServices20PrewarmConfigurationV16requiredAssetIDs21excludedResourceTypes8metadata17requestClientDataACShySSGSg_AISDyS2SGSgAA0nO0VSgtcfC
- _$s20ModelManagerServices7SessionC8MetadataV14assetBundleURI9useCaseID13onBehalfOfPID06parentn2OnmnO017loggingIdentifier2id010sessionSetK025inferenceInterfaceVersion25customAssetConfigurations06clientD4Data13codeSignatureAE10Foundation3URLV_SSs5Int32VSiSSAA14UUIDIdentifierVyACGAQ4UUIDVAA0Y0VSayAA24CustomAssetConfigurationVGSgAA10ClientDataVSgAA13CodeSignatureOtcfC
- _$s8Dispatch0A3QoSV0B6SClassO10backgroundyA2EmFWC
CStrings:
+ "Asset %s not used since last hysteresis check; proceeding with transition"
+ "Asset %s used since last hysteresis check; resetting window, skipping transition"
+ "Ending input stream %s for cancelled session %s"
+ "Failed to establish jetsam floor for %s: %@"
+ "Failed to query remote availability, treating as no remotes: %@"
+ "Failed to register wake notification: %u"
+ "Handling exclave load for asset %s"
+ "Hysteresis check failed for %s: %@; proceeding with transition"
+ "No connection available for %s"
+ "Not moving asset %s to dynamic mode: required by an asset in use by an execution group"
+ "Registered wake notification listener for %{public}s"
+ "Request made with unrecognized InferenceProvider %s"
+ "Resolved remote mode with available remotes: %u"
+ "TightbeamListener"
+ "availabilityQueryFailed"
+ "availableRemotes"
+ "bootstrapsInFlight"
+ "com.apple.modelmanager.exclaves.test.wake"
+ "endOfStreamSignalled"
+ "floorQueue"
+ "hostAvailable"
+ "internalRelayWakeToken"
+ "markAsActive(connection:)"
+ "markAsInactive skipped — connection still in use (bootstrap in flight or sibling loaded)"
+ "markAsInactive(connection:)"
+ "notifyOperationFailure: bundle=%s errorType=%s wrappedCase=%s"
+ "onAcquisitionError"
+ "onAssetDidLoad"
+ "sessionID"
+ "transitionDelayMultiplier"
+ "usedSinceLastHysteresisCheck executing on %s for %s"
+ "usedSinceLastHysteresisCheck failed with XPC Error %s; reporting not-used"
+ "usedSinceLastHysteresisCheck on %s returned %{bool}d"
+ "usedSinceLastHysteresisCheck: no sender for %s, reporting not-used"
- "Could not find inference provider connection for %s"
- "claimAssets attempted with unrecognized InferenceProvider %s"
- "forceLoadInModels attempted with unrecognized InferenceProvider %s"
- "getInferenceProvider returned nil for %s"
- "notifyOperationFailure: wrapped error type=%s, wrappedCase=%s"
- "prewarmAssets for %s attempted with unrecognized InferenceProvider %s"
- "request %s made with unrecognized InferenceProvider %s"
- "vm punchout request made with unrecognized InferenceProvider %s"
```
