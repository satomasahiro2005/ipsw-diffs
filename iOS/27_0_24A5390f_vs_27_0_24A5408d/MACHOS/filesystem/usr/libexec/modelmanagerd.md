## modelmanagerd

> `/usr/libexec/modelmanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b4d3c` | `0x1b9fd8` | **`+0x529c`** |
| `__DATA_CONST.__const` | `0x8260` | `0x88a8` | **`+0x648`** |
| `__TEXT.__oslogstring` | `0x9e99` | `0xa269` | **`+0x3d0`** |
| `__TEXT.__swift5_capture` | `0x24d4` | `0x2758` | **`+0x284`** |
| `__TEXT.__eh_frame` | `0x164ec` | `0x16744` | **`+0x258`** |
| `__TEXT.__unwind_info` | `0x6cc0` | `0x6af0` | **`-0x1d0`** |
| `__TEXT.__const` | `0x67d6` | `0x6836` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x1933` | `0x1993` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x25c3` | `0x2623` | **`+0x60`** |
| `__DATA.__data` | `0x6398` | `0x63f0` | **`+0x58`** |
| `__TEXT.__auth_stubs` | `0x3e40` | `0x3e90` | **`+0x50`** |
| `__DATA.__objc_const` | `0x43f0` | `0x4430` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x2d64` | `0x2da4` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x2879` | `0x28b3` | **`+0x3a`** |
| `__DATA_CONST.__auth_got` | `0x1f28` | `0x1f50` | **`+0x28`** |
| `__DATA_CONST.__got` | `0xf40` | `0xf60` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x1218` | `0x1234` | **`+0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0x21b4` | `0x21cc` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0xd50` | `0xd58` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xacc` | `0xad0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-703.0.21.502.1
+703.0.33.0.0

-  Functions: 9074
-  Symbols:   1696
-  CStrings:  1215
+  Functions: 9156
+  Symbols:   1706
+  CStrings:  1224
Symbols:
+ _$s20ModelManagerServices10RequestKeyV12subrequestIDs6UInt32Vvg
+ _$s20ModelManagerServices37InferenceProviderRequestConfigurationV12subrequestIDs6UInt32Vvg
+ _$s20ModelManagerServices37InferenceProviderRequestConfigurationV12subrequestIDs6UInt32Vvs
+ _$s26AppleIntelligenceReporting0aB14InferenceEventV9subsystem17sessionIdentifier04stepH0017invocationRequestH006clientkH0012modelManagerkH06errors07useCaseH0013additionalUseQ11Identifiers015requestorBundleH0010onBehalfOfvH0017inferenceProviderH015requestPriority05assetvH06assets8metadata11spanContext9timestamp18monotonicTimestampACSS_10Foundation4UUIDVSgSSSgAA14UUIDIdentifierVSgA2ZSayAA0aB5Error_pGAA0absQ0VSgSayA6_GA_A_A_AA0K8PriorityOSgA_SayAA0aB5AssetVGAA0abC8MetadataOSgAA0abC11SpanContextVSgAW4DateVSg0B15PlatformLibrary18MonotonicTimestampVSgtcfC
+ _$s26AppleIntelligenceReporting0aB14InferenceEventVMa
+ _$s26AppleIntelligenceReporting15RequestPriorityO10backgroundyA2CmFWC
+ _$s26AppleIntelligenceReporting15RequestPriorityO10foregroundyA2CmFWC
+ _$s26AppleIntelligenceReporting15RequestPriorityO13userInitiatedyA2CmFWC
+ _$s26AppleIntelligenceReporting15RequestPriorityO7unknownyA2CmFWC
+ _$s26AppleIntelligenceReporting15RequestPriorityOMa
+ _$s26AppleIntelligenceReporting15RequestPriorityOMn
- _$s26AppleIntelligenceReporting0aB14InferenceEventV9subsystem17sessionIdentifier04stepH0017invocationRequestH006clientkH0012modelManagerkH06errors07useCaseH0013additionalUseQ11Identifiers015requestorBundleH0010onBehalfOfvH0017inferenceProviderH005assetvH06assets8metadata11spanContext9timestamp18monotonicTimestamp19underlyingErrorCode21underlyingErrorDomain15routingDecisionACSS_10Foundation4UUIDVSgSSSgAA14UUIDIdentifierVSgA0_A0_SayAA0aB5Error_pGAA0absQ0VSgSayA8_GA1_A1_A1_A1_SayAA0aB5AssetVGAA0abC8MetadataOSgAA0abC11SpanContextVSgAY4DateVSg0B15PlatformLibrary18MonotonicTimestampVSgSiSgA1_A1_tcfC
CStrings:
+ "Adding new request for stream %s, starting from subrequest %u"
+ "Concatenating clientdata from stream %s subrequest %u onto batch (starting subrequest %u) currently accumulating for that stream"
+ "Creating new inputStreamRequests entry for %s, triggered by subrequest %u"
+ "ExecuteRequestNow called for an inputStreamRequest %s subrequest %u, but missing required information"
+ "Finished request %s subrequest %u (Session: %s)"
+ "Incorrect Input streaming request state for group %s, subrequest %u"
+ "InferenceProvider await endOfStream (%s : %u) finished"
+ "InferenceProvider awaiting endOfStream (%s : %u) on %s"
+ "InferenceProvider inputStreamEnded (%s) failed with %s"
+ "InferenceProvider requestInputStreamInference (%s : %u) executing on %s"
+ "InferenceProvider requestInputStreamInference (%s : %u) finished"
+ "Input stream %s subrequest %u (dispatched count %u) was locked to inference provider instance %d but the current instance is %s; aborting with %@ rather than resuming on a fresh instance"
+ "Missing input stream request info for %s subrequest %u"
+ "Received request %s subrequest %u (Session: %s)"
+ "Removing %s from inputStreamRequests dictionary after subrequest %u"
+ "Resetting currentRequest for input streaming group %s, subrequest %u"
+ "Resolved %s for bundle %s with entitlement enforcement; override %s grants access only for exempt use cases (exempt=%{bool}d)."
+ "Resolved %s via unentitled use-case list for bundle %s (exempt=%{bool}d)."
+ "Responding to input stream subrequest: %s subrequest %u"
+ "Responding to request: %s subrequest %u with ModelManagerError %@"
+ "Responding to request: %s subrequest %u with error %@"
+ "addingPending: %s subrequest %u missing from inputStreamRequests"
+ "bundleIdentifiers: %{public, signpost.description=attribute,public}s,\nuseCaseIdentifier: %{public, signpost.description=attribute,public}s,\nonBehalfOfPID: %{public, signpost.description=attribute,public}d,\ncreatedByPID: %{public, signpost.description=attribute,public}d,\ncontainsSensitiveData: %{public, signpost.description=attribute,public}s,\nuuid: %{public, signpost.description=attribute,public}s"
+ "dispatchedToInferenceProviderCount"
+ "lockedInferenceProviderInstanceID"
+ "requestInputStreamInference (%s : %u) called for exited extension"
+ "xpcdispatcher: Request TaskCancellation handler, id: %s subrequest %u."
- "Adding new request for %s"
- "Concatenating clientdata from %s to %s"
- "Creating new inputStreamRequests entry for %s"
- "ExecuteRequestNow called for an inputStreamRequest, but missing required information"
- "Incorrect Input streaming request state for group %s"
- "InferenceProvider await endOfStream (%s) finished"
- "InferenceProvider awaiting endOfStream (%s) on %s"
- "InferenceProvider requestInputStreamInference (%s) executing on %s"
- "InferenceProvider requestInputStreamInference (%s) failed with %s"
- "InferenceProvider requestInputStreamInference (%s) finished"
- "Missing input stream request info"
- "Removing %s from inputStreamRequests dictionary"
- "Resetting currentRequest for input streaming group %s"
- "Resolved %s with entitlement override %s for bundle %s."
- "Responding to input stream subrequest: %s"
- "addingPending: %s missing from inputStreamRequests"
- "bundeIdentifiers: %{public, signpost.description=attribute,public}s,\nuseCaseIdentifier: %{public, signpost.description=attribute,public}s,\nonBehalfOfPID: %{public, signpost.description=attribute,public}d,\ncreatedByPID: %{public, signpost.description=attribute,public}d,\ncontainsSensitiveData: %{public, signpost.description=attribute,public}s,\nuuid: %{public, signpost.description=attribute,public}s"
- "requestInputStreamInference (%s) called for exited extension"
```
