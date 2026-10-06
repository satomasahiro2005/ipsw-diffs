## DifferentialPrivacy

> `/System/Library/PrivateFrameworks/DifferentialPrivacy.framework/DifferentialPrivacy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x499d0` | `0x4ac88` | **`+0x12b8`** |
| `__DATA.__data` | `0x9f8` | `0x2e8` | **`-0x710`** |
| `__DATA_DIRTY.__data` | `0x1f0` | `0x900` | **`+0x710`** |
| `__AUTH_CONST.__objc_const` | `0x7490` | `0x77f8` | **`+0x368`** |
| `__DATA_DIRTY.__objc_data` | `0x22e8` | `0x2648` | **`+0x360`** |
| `__AUTH.__objc_data` | `0x360` | `0xa0` | **`-0x2c0`** |
| `__TEXT.__cstring` | `0x430c` | `0x45ac` | **`+0x2a0`** |
| `__AUTH_CONST.__cfstring` | `0x3ac0` | `0x3ba0` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x39d4` | `0x3a9c` | **`+0xc8`** |
| `__TEXT.__swift5_reflstr` | `0x3b7` | `0x427` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x2b5` | `0x315` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x508` | `0x548` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x400` | `0x430` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x338` | `0x360` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d50` | `0x1d78` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x620` | `0x640` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1128` | `0x1148` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x338` | `0x348` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x1e8` | `0x1f8` | **`+0x10`** |
| `__TEXT.__const` | `0x898` | `0x8a8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x8c8` | `0x8d0` | **`+0x8`** |

### Other Changes

```diff

-798.0.0.0.0
+800.0.0.0.0

-  Functions: 1743
-  Symbols:   2886
-  CStrings:  788
+  Functions: 1758
+  Symbols:   2928
+  CStrings:  800
Symbols:
+ -[_DPPreambleProofOneHotBlockBudgetAnalysis .cxx_destruct]
+ -[_DPPreambleProofOneHotBlockBudgetAnalysis blockSize]
+ -[_DPPreambleProofOneHotBlockBudgetAnalysis cohortAnalysis]
+ -[_DPPreambleProofOneHotBlockBudgetAnalysis cohortSigma]
+ -[_DPPreambleProofOneHotBlockBudgetAnalysis dimension]
+ -[_DPPreambleProofOneHotBlockBudgetAnalysis exceedApproximateDPBudget:error:]
+ -[_DPPreambleProofOneHotBlockBudgetAnalysis initWithCohortSigma:sigmaLocal:squaredL2Sensitivity:blockSize:dimension:minBatchSize:error:]
+ -[_DPPreambleProofOneHotBlockBudgetAnalysis initWithCohortSigma:sigmaLocal:squaredL2Sensitivity:blockSize:numKeptBlocks:dimension:minBatchSize:error:]
+ -[_DPPreambleProofOneHotBlockBudgetAnalysis minBatchSize]
+ -[_DPPreambleProofOneHotBlockBudgetAnalysis numKeptBlocks]
+ -[_DPPreambleProofOneHotBlockBudgetAnalysis numLeafNodes]
+ -[_DPPreambleProofOneHotBlockBudgetAnalysis paddedDimension]
+ -[_DPPreambleProofOneHotBlockBudgetAnalysis sigmaLocal]
+ -[_DPPreambleProofOneHotBlockBudgetAnalysis squaredL2Sensitivity]
+ -[_DPPreambleProofOneHotBlockBudgetAuditor initWithMetadata:plistParameters:error:]
+ _OBJC_CLASS_$__DPPreambleProofOneHotBlockBudgetAnalysis
+ _OBJC_CLASS_$__DPPreambleProofOneHotBlockBudgetAuditor
+ _OBJC_IVAR_$__DPPreambleProofOneHotBlockBudgetAnalysis._blockSize
+ _OBJC_IVAR_$__DPPreambleProofOneHotBlockBudgetAnalysis._cohortAnalysis
+ _OBJC_IVAR_$__DPPreambleProofOneHotBlockBudgetAnalysis._cohortSigma
+ _OBJC_IVAR_$__DPPreambleProofOneHotBlockBudgetAnalysis._dimension
+ _OBJC_IVAR_$__DPPreambleProofOneHotBlockBudgetAnalysis._minBatchSize
+ _OBJC_IVAR_$__DPPreambleProofOneHotBlockBudgetAnalysis._numKeptBlocks
+ _OBJC_IVAR_$__DPPreambleProofOneHotBlockBudgetAnalysis._numLeafNodes
+ _OBJC_IVAR_$__DPPreambleProofOneHotBlockBudgetAnalysis._paddedDimension
+ _OBJC_IVAR_$__DPPreambleProofOneHotBlockBudgetAnalysis._sigmaLocal
+ _OBJC_IVAR_$__DPPreambleProofOneHotBlockBudgetAnalysis._squaredL2Sensitivity
+ _OBJC_METACLASS_$__DPPreambleProofOneHotBlockBudgetAnalysis
+ _OBJC_METACLASS_$__DPPreambleProofOneHotBlockBudgetAuditor
+ __OBJC_$_INSTANCE_METHODS__DPPreambleProofOneHotBlockBudgetAnalysis
+ __OBJC_$_INSTANCE_METHODS__DPPreambleProofOneHotBlockBudgetAuditor
+ __OBJC_$_INSTANCE_VARIABLES__DPPreambleProofOneHotBlockBudgetAnalysis
+ __OBJC_$_PROP_LIST__DPPreambleProofOneHotBlockBudgetAnalysis
+ __OBJC_CLASS_PROTOCOLS_$__DPPreambleProofOneHotBlockBudgetAnalysis
+ __OBJC_CLASS_RO_$__DPPreambleProofOneHotBlockBudgetAnalysis
+ __OBJC_CLASS_RO_$__DPPreambleProofOneHotBlockBudgetAuditor
+ __OBJC_METACLASS_RO_$__DPPreambleProofOneHotBlockBudgetAnalysis
+ __OBJC_METACLASS_RO_$__DPPreambleProofOneHotBlockBudgetAuditor
+ _symbolic Sd10noiseSigma_Sd5limitt
+ _symbolic Sd5value_Sd5limitt
+ _symbolic Si11measurement_t
+ _symbolic _____13scalingFactor_AA5limitt s6UInt64V
CStrings:
+ " exceeds integer range limit "
+ " exceeds maximum allowed integer limit "
+ " exceeds safe headroom limit "
+ " is negative, index must be >= 0."
+ "Failed to initialize one-hot-block budget analysis from metadata parameters:"
+ "Noise standard deviation "
+ "blockSize must not be zero."
+ "cohortSigma must be finite, not NAN, and greater than 0.0."
+ "numKeptBlocks must not be zero."
+ "samplesNeeded < 1: fewer than one client would add noise per block."
+ "sigmaLocal = %.17g and minBatchSize = %u achieve actualCohortSigma = %.17g which is lower than the target cohortSigma = %.17g when sampling rate is 100%%."
+ "sigmaLocal must be finite, not NAN, and greater than 0.0."
```
