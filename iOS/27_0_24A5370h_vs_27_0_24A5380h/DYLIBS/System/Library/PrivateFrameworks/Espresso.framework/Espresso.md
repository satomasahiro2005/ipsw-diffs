## Espresso

> `/System/Library/PrivateFrameworks/Espresso.framework/Espresso`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd19bd0` | `0xd1bacc` | **`+0x1efc`** |
| `__TEXT.__oslogstring` | `0x7b2a` | `0x8a69` | **`+0xf3f`** |
| `__TEXT.__gcc_except_tab` | `0xce2f8` | `0xce758` | **`+0x460`** |
| `__TEXT.__cstring` | `0x54021` | `0x53eb1` | **`-0x170`** |
| `__TEXT.__unwind_info` | `0x2c4f8` | `0x2c5b8` | **`+0xc0`** |
| `__DATA.__bss` | `0x6790` | `0x6770` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x2b8` | `0x2d8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xa80` | `0xa98` | **`+0x18`** |

### Other Changes

```diff

-3600.52.1.0.0
+3600.52.2.0.0

-  Functions: 34654
-  Symbols:   54426
-  CStrings:  10394
+  Functions: 34701
+  Symbols:   54429
+  CStrings:  10449
Symbols:
+ __ZN4E5RT14E5CompilerImpl27PurgeE5BundlesForInputModelINSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEEEvRKT_
+ __ZN4E5RT14E5CompilerImpl7CompileINSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEEEENS2_10unique_ptrINS_14ProgramLibraryENS2_14default_deleteISA_EEEERKT_RKNS_17E5CompilerOptionsE
+ __ZNK4E5RT14E5CompilerImpl12GetModelLockERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEE
+ __ZNSt3__15tupleIJbNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_10unique_ptrIN4E5RT14ProgramLibraryENS_14default_deleteIS9_EEEEEED1Ev
- __ZNSt3__15tupleIJbNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_10unique_ptrIN4E5RT14ProgramLibraryENS_14default_deleteIS9_EEEEEED2Ev
CStrings:
+ "3600.52.2"
+ "Closed ANEDevice = 0x%lx\n"
+ "Created E5BundleCache at %s\n"
+ "Customized E5 bundle location \n"
+ "Detected ANE Inference overflow during async execution."
+ "Detected ANE Inference overflow."
+ "Detected call to mapIOSurfacesWithModel on VM run. Ignore return result as this API is not supported on VM."
+ "Detected rank mistmatch between E5 and EIR. Input = %s, E5 rank = %s, EIR rank = %s. Skipped checking shape mistmatch."
+ "Detected shape mistmatch between E5 and EIR. Input = %s, dim = %s, E5 = %s, EIR = %s. EIR will be reshaped to match E5 shape."
+ "E5BundleCache IsNewCompileRequired: input=%s forceRecompile=True\n"
+ "E5BundleCache Lookup: input=%s output=%s exists=%d\n"
+ "E5BundleCache exists at %s\n"
+ "E5BundleCacheManager: GlobalCacheDirectory %s\n"
+ "E5BundleCacheManager: is root user\n"
+ "E5BundleCacheManager::MarkAsMobileOwned: path = %s\n"
+ "E5BundleCacheManager::MarkAsMobileOwned: path = %s. Unable to query grp for mobile.\n"
+ "E5BundleCacheManager::MarkAsMobileOwned: path = %s. Unable to query pwd for mobile.\n"
+ "E5BundleCacheManager::MarkAsMobileOwnedRecursive: path = %s failed with errno = %i \n"
+ "E5CompilerImpl:: processInfo is nil.\n"
+ "E5CompilerImpl::Compile acquiring global lock input=%s\n"
+ "E5CompilerImpl::Compile acquiring per-model lock input=%s\n"
+ "E5CompilerImpl::Compile fast-path cache hit input=%s\n"
+ "E5CompilerImpl::Compile(MIL, !CreateProtectedAssets) acquiring global lock input=%s\n"
+ "E5CompilerImpl::Compile(MIL, !CreateProtectedAssets) acquiring per-model lock input=%s\n"
+ "E5CompilerImpl::Compile(MIL, !CreateProtectedAssets) fast-path cache hit input=%s\n"
+ "E5CompilerImpl::Compile(MIL, CreateProtectedAssets) acquiring global lock input=%s\n"
+ "E5CompilerImpl::Compile(MIL, CreateProtectedAssets) acquiring per-model lock input=%s\n"
+ "E5CompilerImpl::Compile(MIL, CreateProtectedAssets) fast-path cache hit input=%s\n"
+ "E5CompilerImpl::CompileInternal::performCompilation input=%s output=%s tmp-output=%s\n"
+ "E5CompilerImpl::CompileInternal::performCompilation renamed %s to %s\n"
+ "E5CompilerImpl::GetModelLock key=%s stripe=%zu\n"
+ "E5CompilerImpl::IsNewCompileRequired acquiring per-model lock input=%s\n"
+ "E5CompilerImpl::PurgeE5BundlesForInputModel acquiring per-model lock input=%s\n"
+ "E5CompilerImpl::PurgeE5BundlesForInputModel(MIL) acquiring per-model locks milFastHash=%s milHash=%s\n"
+ "E5MLExecutionStreamSyncTelemetry"
+ "Espresso.e5ml.trace: serializing IO ports to tmp dir: %s"
+ "Loaded ANE Model at path = %s with programHandle = 0x%llx\n"
+ "Loaded ANE Model with cacheURLIdentifier = %s with programHandle = 0x%llx\n"
+ "Loading E5 compiled for platform = 0x%llx on platform = 0x%llx."
+ "Loading a shared resource. URI = %s \n"
+ "MPSGraph op: E5 Input shape is unknown for input/inOut = %s. Skipping input validation and reshape as part of PrepareOpForEncode()."
+ "MPSGraph op: Skipping output tensor validation for output = %s"
+ "Mapped pre-wire allocations for ANEDevice = 0x%lx programHandle = 0x%llx # buffers = %d\n"
+ "Opened ANEDevice = 0x%lx for programHandle = 0x%llx, aneId = %d \n"
+ "Process holds E5 bundle sharing entitlement.\n"
+ "Profiling Callback invoked. Reported Duration = %f ms\n"
+ "Purging tmp bundle at %s"
+ "RequestID=%{signpost.description:attribute}sGPUResourceCommitDuration=%{signpost.description:attribute}f"
+ "ResetStream() : No ops in stream."
+ "Unable to set compute_unit_mask"
+ "Unloaded ANE JIT Model at path = %s \n"
+ "Unloaded ANE Model at path = %s with programHandle = 0x%llx\n"
+ "Unmapped pre-wire allocations for ANEDevice 0x%lx programHandle 0x%llx # buffers = %d\n"
+ "Warning: Failed to create E5SegmentIO directory: %s"
+ "e5rt"
+ "remove_all() of path = %s failed with error code = %d\n"
- "3600.52.1"
```
