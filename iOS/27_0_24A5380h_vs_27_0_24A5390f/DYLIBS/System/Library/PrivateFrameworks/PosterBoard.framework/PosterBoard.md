## PosterBoard

> `/System/Library/PrivateFrameworks/PosterBoard.framework/PosterBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x272a9c` | `0x2742a4` | **`+0x1808`** |
| `__TEXT.__oslogstring` | `0x1db6a` | `0x1e04a` | **`+0x4e0`** |
| `__AUTH_CONST.__cfstring` | `0xc180` | `0xc300` | **`+0x180`** |
| `__AUTH_CONST.__objc_const` | `0x3d940` | `0x3daa0` | **`+0x160`** |
| `__TEXT.__cstring` | `0x143c5` | `0x144e5` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0xee5c` | `0xeee4` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0x9bc8` | `0x9c30` | **`+0x68`** |
| `__DATA.__objc_ivar` | `0x105c` | `0x1084` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x9230` | `0x9250` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x4604` | `0x4624` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x6c00` | `0x6c18` | **`+0x18`** |
| `__DATA.__bss` | `0x2f38` | `0x2f48` | **`+0x10`** |
| `__TEXT.__const` | `0x73d4` | `0x73e4` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2450` | `0x2458` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1da8` | `0x1db0` | **`+0x8`** |

### Other Changes

```diff

-347.102.0.0.0
+350.1.100.0.0

-  Functions: 10824
-  Symbols:   11046
-  CStrings:  3942
+  Functions: 10841
+  Symbols:   11074
+  CStrings:  3968
Symbols:
+ -[PBFLockScreenColorConfigurationCache _stateCaptureDescription]
+ -[PBFLockScreenColorConfigurationCache dealloc]
+ -[PBFLockScreenRoleCoordinator transactionDidCommitWithCollection:]
+ -[PBFLockScreenRoleCoordinator transactionDidFailWithError:]
+ -[PBFPosterSnapshotManager _lock_scheduleStartupRetryRekickWithDelay:]
+ -[PBFPosterSnapshotManager _test_installProviderTracker:pbfTracker:forRequest:enqueueAndKickoff:]
+ -[PBFPosterSnapshotManager initWithRuntimeAssertionProvider:modelCoordinatorProvider:extensionProvider:applicationStateMonitor:]
+ -[PBFPosterSnapshotPUIRequestTracker consumeStartupRetryIfAvailable]
+ -[PBFPosterSnapshotPUIRequestTracker startupRetriesRemaining]
+ -[PBFPosterSnapshotProviderTracker _lock_reclaimSnapshotterState:]
+ -[PBFPosterSnapshotProviderTracker availableInstanceCount]
+ -[PBFPosterSnapshotProviderTracker dequeueSnapshotterForPath:error:]
+ -[PBFPosterSnapshotProviderTracker initWithProvider:extension:extensionInstanceProvider:]
+ -[PBFPosterSnapshotProviderTracker liveInstanceCount]
+ -[PBFPosterSnapshotProviderTracker numberOfLiveSnapshotters]
+ -[PBFPosterSnapshotProviderTracker releaseSnapshotter:shouldTerminate:]
+ -[PBFPosterSnapshotProviderTracker snapshotterDidInvalidateScene:]
+ -[PBFPosterSnapshotProviderTracker terminateAndReclaimSnapshotterImmediately:]
+ _OBJC_CLASS_$_PFPosterExtensionInstanceProvider
+ _OBJC_IVAR_$_PBFLockScreenColorConfigurationCache._lock_generation
+ _OBJC_IVAR_$_PBFLockScreenColorConfigurationCache._lock_lastWrittenConfigurations
+ _OBJC_IVAR_$_PBFLockScreenColorConfigurationCache._stateCaptureHandle
+ _OBJC_IVAR_$_PBFPosterSnapshotManager._extensionInstanceProvider
+ _OBJC_IVAR_$_PBFPosterSnapshotManager._lock_puiRequestToSnapshotter
+ _OBJC_IVAR_$_PBFPosterSnapshotManager._lock_startupRetryRekickScheduled
+ _OBJC_IVAR_$_PBFPosterSnapshotPUIRequestTracker._lock_startupRetriesRemaining
+ _OBJC_IVAR_$_PBFPosterSnapshotProviderTracker._extension
+ _OBJC_IVAR_$_PBFPosterSnapshotProviderTracker._extensionInstanceProvider
+ _OBJC_IVAR_$_PBFPosterSnapshotProviderTracker._lock_liveSnapshotters
+ _OBJC_IVAR_$_PBFPosterSnapshotProviderTracker._lock_pendingTerminateVerdict
+ _OBJC_IVAR_$_PBFPosterSnapshotProviderTracker._lock_snapshotterInstances
+ _PBFErrorIsBenignNonCrash
+ _PBFLogSnapshotProviderTracker
+ _PBFLogSnapshotProviderTracker.__logObj
+ _PBFLogSnapshotProviderTracker.onceToken
+ _PFDispatchTimeAfterSeconds
+ ___58-[PBFLockScreenColorConfigurationCache initWithCachePath:]_block_invoke
+ ___58-[PBFLockScreenColorConfigurationCache initWithCachePath:]_block_invoke_2
+ ___70-[PBFPosterSnapshotManager _lock_scheduleStartupRetryRekickWithDelay:]_block_invoke
+ ___PBFLogSnapshotProviderTracker_block_invoke
- -[PBFLockScreenRoleCoordinator _updateColorConfigurationCacheWithCollection:]
- -[PBFPosterSnapshotManager initWithRuntimeAssertionProvider:modelCoordinatorProvider:applicationStateMonitor:]
- -[PBFPosterSnapshotProviderTracker alignmentKeys]
- -[PBFPosterSnapshotProviderTracker createSnapshotterForPath:error:]
- -[PBFPosterSnapshotProviderTracker initWithProvider:extensionProvider:]
- -[PBFPosterSnapshotProviderTracker releaseSnapshotter:]
- -[PBFPosterSnapshotProviderTracker removeSnapshotterForAlignmentKey:]
- -[PBFPosterSnapshotProviderTracker snapshotterDidInvalidateScene:shouldTerminate:]
- -[PBFPosterSnapshotProviderTracker snapshotterForAlignmentKey:]
- _OBJC_IVAR_$_PBFPosterSnapshotProviderTracker._extensionProvider
- _OBJC_IVAR_$_PBFPosterSnapshotProviderTracker._lock_snapshottersByAlignmentKey
- _PBFAlignmentKeyForPath
CStrings:
+ "  %@\n"
+ "(pooled, no reason)"
+ "N"
+ "PBFLockScreenColorConfigurationCache"
+ "PBFLockScreenColorConfigurationCache.m"
+ "PBFLockScreenColorConfigurationCache: failed to create cache directory: %{public}@"
+ "PBFPosterSnapshotManager"
+ "PUI request %{public}@ failed (%{public}@); terminating process and retrying (%lu attempts left)"
+ "SnapshotProviderTracker"
+ "Y"
+ "[%{public}@] canAcceptMoreSnapshotters:%lu -> liveInstances=%lu availableForReuse=%lu (snapshotters total=%lu pending=%lu) canAccept=%d"
+ "[%{public}@] dequeueSnapshotterForPath: %{public}@ %{public}@ instance (reason=%{public}@) -> liveInstances=%lu availableForReuse=%lu (snapshotters total=%lu pending=%lu)"
+ "[%{public}@] dequeueSnapshotterForPath: %{public}@ failed to acquire instance (reason=%{public}@): %{public}@"
+ "[%{public}@] releaseSnapshotter: snapshotter=%{public}@ shouldTerminate=%d marked pending-invalidation -> total=%lu pending=%lu (active=%lu)"
+ "[%{public}@] snapshotterDidInvalidateScene: EARLY-RETURN — snapshotter=%{public}@ not found in _lock_snapshottersPendingInvalidation (already invalidated, or never released?)"
+ "[%{public}@] snapshotterDidInvalidateScene: snapshotter=%{public}@ shouldTerminate=%d -> total=%lu pending=%lu (real teardown confirmed)"
+ "[%{public}@] terminateAndReclaimSnapshotterImmediately: snapshotter=%{public}@ -> total=%lu pending=%lu (no scene to wait for)"
+ "[%{public}@] terminateAndReclaimSnapshotterImmediately: snapshotter=%{public}@ already reclaimed — no-op"
+ "booted NEW"
+ "cancelRequests: invalidating orphaned snapshotter %{public}@ and reclaiming its instance"
+ "cancelRequests: releasing orphaned snapshotter %{public}@ for reuse"
+ "configs=%lu\n"
+ "createDir failed"
+ "epoch=%llu lastWrittenBytes=%lu pending=%lu valid=%@\n"
+ "kickoff: no instance for %{public}@ (%{public}@); retrying (%lu attempts left)"
+ "kickoff: no instance for %{public}@ after retries: %{public}@ — failing request"
+ "path=%@ exists=%@ size=%llu mtime=%@\n"
+ "raced invalidate (post-IO)"
+ "raced invalidate (pre-IO)"
+ "reused POOLED"
+ "\x91"
- "cancelRequests: No more active work for alignment key %{public}@, invalidating orphaned snapshotter"
- "cancelRequests: No more active work for alignment key %{public}@, releasing orphaned snapshotter for reuse"
- "cancelRequests: alignment key %{public}@ still in use by another active request, keeping snapshotter"
- "kickoff: Created snapshotter for alignment key %{public}@"
- "kickoff: Failed to create snapshotter for %{public}@: %{public}@"
```
