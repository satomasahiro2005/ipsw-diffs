## DifferentialPrivacy

> `/System/Library/PrivateFrameworks/DifferentialPrivacy.framework/DifferentialPrivacy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4763c` | `0x499c0` | **`+0x2384`** |
| `__TEXT.__cstring` | `0x402c` | `0x430c` | **`+0x2e0`** |
| `__AUTH_CONST.__cfstring` | `0x3960` | `0x3ac0` | **`+0x160`** |
| `__TEXT.__eh_frame` | `0x410` | `0x508` | **`+0xf8`** |
| `__TEXT.__oslogstring` | `0x2ed9` | `0x2faa` | **`+0xd1`** |
| `__AUTH_CONST.__objc_const` | `0x73d0` | `0x7490` | **`+0xc0`** |
| `__TEXT.__const` | `0x7e8` | `0x898` | **`+0xb0`** |
| `__AUTH_CONST.__const` | `0x740` | `0x7d0` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x390` | `0x400` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x347` | `0x3b7` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x10e8` | `0x1130` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x399c` | `0x39d4` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x1078` | `0x1098` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x318` | `0x334` | **`+0x1c`** |
| `__DATA.__data` | `0x9e0` | `0x9f8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d38` | `0x1d50` | **`+0x18`** |
| `__DATA_DIRTY.__objc_data` | `0x22d8` | `0x22e8` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x2ac` | `0x2b5` | **`+0x9`** |
| `__AUTH_CONST.__auth_got` | `0x8c0` | `0x8c8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x330` | `0x338` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x44` | `0x48` | **`+0x4`** |

### Other Changes

```diff

-791.0.0.0.1
+793.0.0.0.3

-  Functions: 1720
-  Symbols:   2875
-  CStrings:  776
+  Functions: 1743
+  Symbols:   2886
+  CStrings:  788
Symbols:
+ -[_DPHistogramWithAggregatorDiscreteGaussian initWithSigma:squaredL2Sensitivity:rappor:error:]
+ -[_DPPreambleBudgetAnalysis initWithBlockSize:numSuperBlocks:dimension:paddedDimension:cohortSigma:sigmaLocal:minBatchSize:error:]
+ -[_DPPreambleBudgetAnalysis minBatchSize]
+ -[_DPPreambleBudgetAnalysis sigmaLocal]
+ _OBJC_IVAR_$__DPPreambleBudgetAnalysis._minBatchSize
+ _OBJC_IVAR_$__DPPreambleBudgetAnalysis._sigmaLocal
+ ___130-[_DPPreambleBudgetAnalysis initWithBlockSize:numSuperBlocks:dimension:paddedDimension:cohortSigma:sigmaLocal:minBatchSize:error:]_block_invoke
+ _initWithBlockSize:numSuperBlocks:dimension:paddedDimension:cohortSigma:sigmaLocal:minBatchSize:error:.onceToken
+ _kDPMetadataDediscoTaskConfigDPConfigMechanismDiscreteGaussianWithZeroConcentratedDpAccountant
+ _kTokenFieldNotBefore
+ _lgamma
+ _symbolic SSm
+ _symbolic _____ 19DifferentialPrivacy43PreambleProofWithOneHotBlockEngineParameterV
+ _type_layout_string 19DifferentialPrivacy43PreambleProofWithOneHotBlockEngineParameterV
- -[_DPPreambleBudgetAnalysis initWithBlockSize:numSuperBlocks:dimension:paddedDimension:cohortSigma:error:]
- ___106-[_DPPreambleBudgetAnalysis initWithBlockSize:numSuperBlocks:dimension:paddedDimension:cohortSigma:error:]_block_invoke
- _initWithBlockSize:numSuperBlocks:dimension:paddedDimension:cohortSigma:error:.onceToken
CStrings:
+ "DistributedDiscreteGaussianWithZeroConcentratedDpAccountantForPreambleProof"
+ "Malformed parameter (%@) in metadata DPConfig expected a number."
+ "Malformed parameter (%@) in metadata PreambleParameters, expected a number."
+ "Malformed parameter (%@) in metadata taskConfig, expected a number."
+ "Precomputed minSigma bound %.17g exceeds cohortSigma %.17g"
+ "Unsupported DP mechanism (%@) in metadata DPConfig."
+ "delta %.17g exceeds target %.17g for Gaussian noise when numBlocks %u == numSuperBlocks %u"
+ "failureProb >= %.17g which exceeds maxFailureProb %.17g"
+ "minBatchSize must be positive."
+ "minSamplesNeeded %f > expectedNumSamples %f, i.e., Pr[Bin(minBatchSize, gamma) < minSamplesNeeded] exceeds 0.5"
+ "notBefore"
+ "sigmaLocal %.17g >= cohortSigma %.17g. In this case, for the preamble algorithm with random allocation accountant, every client will add enough noise to guarantee central DP for the coordinates it donates to."
+ "sigmaLocal = %.17g and minBatchSize = %u achieve actualCohortSigma = %.17g which is lower than the target cohortSigma = %.17g when sampling rate is 100%%"
+ "sigmaLocal must be finite, non NaN, and positive."
+ "squaredL2Sensitivity must be finite, not NAN, and greater than 0.0."
- "Malformed parameter (%@) in metadata PreambleParameters expected a number."
- "Precomputed minSigma bound %f exceeds cohortSigma %f"
- "delta %f exceeds minDelta bound %f for Gaussian noise when numBlocks %u == numSuperBlocks %u"
```
