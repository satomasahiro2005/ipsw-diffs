## DifferentialPrivacy

> `/System/Library/PrivateFrameworks/DifferentialPrivacy.framework/DifferentialPrivacy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x44b3c` | `0x47630` | **`+0x2af4`** |
| `__TEXT.__cstring` | `0x3d6c` | `0x402c` | **`+0x2c0`** |
| `__AUTH_CONST.__cfstring` | `0x37c0` | `0x3960` | **`+0x1a0`** |
| `__AUTH_CONST.__auth_got` | `0x800` | `0x8c8` | **`+0xc8`** |
| `__TEXT.__ustring` | `—` | `0x96` | **`+0x96`** |
| `__AUTH_CONST.__objc_const` | `0x7460` | `0x73d0` | **`-0x90`** |
| `__TEXT.__gcc_except_tab` | `0xa44` | `0xaac` | **`+0x68`** |
| `__AUTH.__objc_data` | `0x1288` | `0x1238` | **`-0x50`** |
| `__DATA_CONST.__got` | `0x5e0` | `0x620` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x3d8` | `0x410` | **`+0x38`** |
| `__TEXT.__oslogstring` | `0x2ea6` | `0x2ed9` | **`+0x33`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d08` | `0x1d38` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x10b8` | `0x10e8` | **`+0x30`** |
| `__DATA.__data` | `0x9c8` | `0x9e0` | **`+0x18`** |
| `__TEXT.__const` | `0x7d8` | `0x7e8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x398c` | `0x399c` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1070` | `0x1078` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x340` | `0x338` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1f0` | `0x1e8` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x2a4` | `0x2ac` | **`+0x8`** |

### Other Changes

```diff

-778.0.0.0.6
+786.0.0.0.5

+  - /System/Library/Frameworks/CryptoKit.framework/CryptoKit

-  Functions: 1701
-  Symbols:   2870
-  CStrings:  761
+  Functions: 1720
+  Symbols:   2876
+  CStrings:  776
Symbols:
+ +[_DPSymmetricRAPPORWithOHE analysisFittingTargetADP:batchSize:numCompositions:maxLocalEpsilon:error:]
+ -[_DPPreambleBudgetAnalysis cohortSigma]
+ -[_DPPreambleBudgetAnalysis initWithBlockSize:numSuperBlocks:dimension:paddedDimension:cohortSigma:error:]
+ -[_DPPreambleBudgetAnalysis minSigmaForDPGuarantee:numBlocks:error:]
+ -[_DPPreambleBudgetAnalysis paddedDimension]
+ -[_DPPreambleBudgetAuditor initWithMetadata:plistParameters:error:]
+ -[_DPPreambleProofRandomizer randomizeBitValue:metadata:key:error:]
+ -[_DPPreambleRandomizer delegateRandomizer]
+ -[_DPPreambleRandomizer shouldUsePreambleProofWithMetadata:]
+ -[_DPPrio3SumVectorRandomizer metadataByBackfillingDPConfigDefaults:defaultNumCompositions:error:]
+ -[_DPSymmetricRAPPORBudgetAuditor initWithMetadata:plistParameters:enforceMaxADP:error:]
+ -[_DPSymmetricRAPPORWithOHE initWithBatchSize:localEpsilon:numCompositions:error:]
+ -[_DPSymmetricRAPPORWithOHE numCompositions]
+ _OBJC_CLASS_$__DPPreambleBudgetAuditor
+ _OBJC_IVAR_$__DPPreambleBudgetAnalysis._cohortSigma
+ _OBJC_IVAR_$__DPPreambleBudgetAnalysis._paddedDimension
+ _OBJC_IVAR_$__DPSymmetricRAPPORWithOHE._numCompositions
+ _OBJC_METACLASS_$__DPPreambleBudgetAuditor
+ __OBJC_$_INSTANCE_METHODS__DPPreambleBudgetAuditor
+ __OBJC_CLASS_RO_$__DPPreambleBudgetAuditor
+ __OBJC_METACLASS_RO_$__DPPreambleBudgetAuditor
+ ___106-[_DPPreambleBudgetAnalysis initWithBlockSize:numSuperBlocks:dimension:paddedDimension:cohortSigma:error:]_block_invoke
+ ___swift_destroy_boxed_opaque_existential_1
+ ___swift_project_boxed_opaque_existential_1
+ _initWithBlockSize:numSuperBlocks:dimension:paddedDimension:cohortSigma:error:.onceToken
+ _kDPMetadataDediscoTaskConfigDPConfigNumCompositions
+ _swift_retain_x20
+ _swift_retain_x21
+ _swift_retain_x22
+ _swift_retain_x23
+ _swift_willThrowTypedImpl
+ _symbolic ______p 10Foundation15ContiguousBytesP
- +[_DPBudgetAuditor containValidDPConfigInMetadata:error:]
- -[_DPPreambleBudgetAnalysis dimensionAfterTransform]
- -[_DPPreambleBudgetAnalysis initWithBlockSize:dimension:numSuperBlocks:sigma:error:]
- -[_DPPreambleBudgetAnalysis minSigmaForDPGuarantee:error:]
- -[_DPPreambleBudgetAnalysis numBlocks]
- -[_DPPreambleBudgetAnalysis sigma]
- -[_DPPreambleProofRandomizer randomizeBitValue:metadata:error:]
- -[_DPSymmetricRAPPORBudgetAuditor initWithMetadata:plistParameters:error:]
- -[_DPSymmetricRAPPORInternalBuildBudgetAuditor initWithMetadata:plistParameters:error:]
- -[_DPSymmetricRAPPORLegacyBudgetAuditor initWithMetadata:plistParameters:error:]
- -[_DPSymmetricRAPPORWithOHE initWithBatchSize:localEpsilon:error:]
- _OBJC_CLASS_$__DPSymmetricRAPPORInternalBuildBudgetAuditor
- _OBJC_CLASS_$__DPSymmetricRAPPORLegacyBudgetAuditor
- _OBJC_IVAR_$__DPPreambleBudgetAnalysis._dimensionAfterTransform
- _OBJC_IVAR_$__DPPreambleBudgetAnalysis._numBlocks
- _OBJC_IVAR_$__DPPreambleBudgetAnalysis._sigma
- _OBJC_METACLASS_$__DPSymmetricRAPPORInternalBuildBudgetAuditor
- _OBJC_METACLASS_$__DPSymmetricRAPPORLegacyBudgetAuditor
- __OBJC_$_INSTANCE_METHODS__DPSymmetricRAPPORInternalBuildBudgetAuditor
- __OBJC_$_INSTANCE_METHODS__DPSymmetricRAPPORLegacyBudgetAuditor
- __OBJC_CLASS_RO_$__DPSymmetricRAPPORInternalBuildBudgetAuditor
- __OBJC_CLASS_RO_$__DPSymmetricRAPPORLegacyBudgetAuditor
- __OBJC_METACLASS_RO_$__DPSymmetricRAPPORInternalBuildBudgetAuditor
- __OBJC_METACLASS_RO_$__DPSymmetricRAPPORLegacyBudgetAuditor
- ___84-[_DPPreambleBudgetAnalysis initWithBlockSize:dimension:numSuperBlocks:sigma:error:]_block_invoke
- _initWithBlockSize:dimension:numSuperBlocks:sigma:error:.onceToken
CStrings:
+ "%@ must be a dictionary, got %@"
+ "Bit vector at index %lu has %u set ones, exceeding %@ (%u)."
+ "DP budget parameters (%@, %@, %@) in %@.%@ must be specified together or omitted together."
+ "DifferentialPrivacyExecutionStage - executionStage: %lu, taskId: %{public}@, count: %lu, errorDomain: %{public}@, errorCode: %ld"
+ "Failed to create PreambleProof delegate randomizer"
+ "Failed to initialize preamble budget analysis from metadata parameters:"
+ "Forwarding Preamble to PreambleProof delegate"
+ "Malformed metadata entry %@"
+ "Malformed metadata: %@"
+ "Malformed parameter (%@) in metadata DPConfig, expected an array."
+ "Malformed parameter (%@) in metadata PreambleParameters expected a number."
+ "Malformed parameter (%@) in metadata VDAFConfig, expected a number."
+ "Missing required parameter (%@.%@.%@) in metadata."
+ "No local epsilon ≤ %f fits target %@ for batchSize=%u, numCompositions=%u."
+ "No preamble parameters found in metadata for padded dimension %u."
+ "NumCompositions"
+ "Number of compositions must be greater than 0."
+ "Precomputed minSigma bound %f exceeds cohortSigma %f"
+ "Skipping vector at index %lu: %@"
+ "Symmetric RAPPOR budget auditor uses min batch size = %d, local epsilon = %f, numCompositions = %d"
+ "cohortSigma must be finite, non NaN, and positive."
- "Precomputed minSigma bound %f exceeds Sigma %f"
- "Symmetric RAPPOR budget auditor uses min batch size = %d, local epsilon = %f"
- "Symmetric RAPPOR internal build budget auditor uses min batch size = %d, local epsilon = %f"
- "Symmetric RAPPOR legacy budget auditor uses min batch size = %d, local epsilon = %f"
- "Unable to infer DP budget auditor from donation metadata, using default symmetric RAPPOR legacy auditor."
- "sigma must be finite, non NaN, and positive."
```
