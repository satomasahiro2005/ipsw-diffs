## VideoIntelligence

> `/System/Library/PrivateFrameworks/VideoIntelligence.framework/VideoIntelligence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12d650` | `0x189dbc` | **`+0x5c76c`** |
| `__DATA.__bss` | `0x14fa0` | `0x1b1b0` | **`+0x6210`** |
| `__TEXT.__const` | `0xc820` | `0xf8f8` | **`+0x30d8`** |
| `__AUTH_CONST.__const` | `0x6b38` | `0x99c0` | **`+0x2e88`** |
| `__TEXT.__eh_frame` | `0x6ad8` | `0x8b38` | **`+0x2060`** |
| `__TEXT.__oslogstring` | `0x2fde` | `0x48f4` | **`+0x1916`** |
| `__TEXT.__constg_swiftt` | `0x31e4` | `0x42bc` | **`+0x10d8`** |
| `__TEXT.__swift5_typeref` | `0x3e26` | `0x4ec8` | **`+0x10a2`** |
| `__AUTH.__data` | `0x1ea0` | `0x2f20` | **`+0x1080`** |
| `__TEXT.__unwind_info` | `0x3190` | `0x4080` | **`+0xef0`** |
| `__DATA.__data` | `0x2818` | `0x3610` | **`+0xdf8`** |
| `__TEXT.__swift5_fieldmd` | `0x28dc` | `0x346c` | **`+0xb90`** |
| `__AUTH_CONST.__objc_const` | `0x1b20` | `0x23d8` | **`+0x8b8`** |
| `__TEXT.__swift5_reflstr` | `0x21a2` | `0x2a52` | **`+0x8b0`** |
| `__TEXT.__swift5_assocty` | `0x940` | `0xfc0` | **`+0x680`** |
| `__TEXT.__swift5_capture` | `0xc70` | `0x11c8` | **`+0x558`** |
| `__TEXT.__cstring` | `0x3886` | `0x3d06` | **`+0x480`** |
| `__TEXT.__swift5_proto` | `0xaec` | `0xe04` | **`+0x318`** |
| `__AUTH_CONST.__auth_got` | `0x1238` | `0x13c0` | **`+0x188`** |
| `__TEXT.__swift_as_cont` | `0x488` | `0x600` | **`+0x178`** |
| `__TEXT.__swift5_types` | `0x378` | `0x490` | **`+0x118`** |
| `__TEXT.__swift_as_ret` | `0x23c` | `0x314` | **`+0xd8`** |
| `__DATA_CONST.__got` | `0x658` | `0x720` | **`+0xc8`** |
| `__TEXT.__swift_as_entry` | `0x1c8` | `0x28c` | **`+0xc4`** |
| `__DATA.__common` | `0x72` | `0xe2` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x3b0` | `0x400` | **`+0x50`** |
| `__DATA_CONST.__objc_classlist` | `0xa0` | `0xe0` | **`+0x40`** |
| `__TEXT.__swift5_protos` | `0x88` | `0xc0` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x378` | `0x398` | **`+0x20`** |
| `__TEXT.__swift5_mpenum` | `0x64` | `0x50` | **`-0x14`** |
| `__DATA_CONST.__const` | `0x3b8` | `0x3c8` | **`+0x10`** |
| `__TEXT.__swift5_types2` | `0x4` | `0x8` | **`+0x4`** |

### Other Changes

```diff

-32.3.0.0.0
+33.12.0.0.0

+  - /usr/lib/swift/libswiftAccelerate.dylib

-  Functions: 4091
-  Symbols:   405
-  CStrings:  512
+  Functions: 5389
+  Symbols:   428
+  CStrings:  635
Symbols:
+ _OBJC_CLASS_$_NSUserDefaults
+ _OBJC_CLASS_$_OS_dispatch_queue_serial
+ __swift_FORCE_LOAD_$_swiftAccelerate
+ _dispatch_activate
+ _dispatch_async
+ _dispatch_barrier_async
+ _dispatch_block_create_with_voucher
+ _dispatch_block_create_with_voucher_and_qos_class
+ _dispatch_workloop_create_inactive
+ _dispatch_workloop_set_os_workgroup
+ _dispatch_workloop_set_qos_class_floor
+ _notify_cancel
+ _notify_register_dispatch
+ _pthread_get_qos_class_np
+ _pthread_mach_thread_np
+ _pthread_self
+ _pthread_threadid_np
+ _swift_copyPOD
+ _swift_deletedAsyncMethodErrorTu
+ _swift_initStructMetadata
+ _swift_retain_x1
+ _swift_task_future_wait_throwing
+ _swift_unknownObjectRelease_n
+ _swift_unknownObjectRetain_n
+ _voucher_copy
- _OBJC_CLASS_$_OS_dispatch_queue_concurrent
- _OBJC_CLASS_$_OS_dispatch_workloop
CStrings:
+ " has unknown QoS"
+ ") with relative priority "
+ "1.0"
+ "11.0"
+ "3.0"
+ "3.3"
+ "5.0"
+ "6.0"
+ "7.0"
+ "AssetRegistry %s abandoning the resolution of %s: a result has already been delivered"
+ "AssetRegistry %s discarding cached resolutions: a source changed what it can serve (was %{public}s, now %{public}s)"
+ "AssetRegistry %s discarding the failure of an abandoned resolution of %s: %@"
+ "AssetRegistry %s joining an in-flight assets resolution of %s"
+ "AssetRegistry %s joining an in-flight resolution of %s"
+ "AssetRegistry %s: %s contributes no key: %@"
+ "AssetRegistry %s: %s has lost its owning registry"
+ "AssetRegistry %s: no source served %s, reporting %@ after skipping %s"
+ "AssetRegistry %s: not caching %s, resolved before a provider refresh"
+ "AssetRegistry %s: not caching the assets for %s, %s"
+ "AssetRegistry %s: skipping %s, resolving error: %@"
+ "AssetRegistry %s: timed out waiting for the %s provider to finish resolving %s"
+ "I/O bindings have been previously committed, decommitting before binding"
+ "MobileAssetSupport"
+ "MobileAsset_WorkRateMETs"
+ "ModelAvailability(introduced: "
+ "Mulberry"
+ "Mulberry.WorkRateMETs"
+ "QoS"
+ "Threading"
+ "TransientError"
+ "Unexpected model: "
+ "VINDispatchAsync: failed to create block with QoS class 0x%x and relative priority %d"
+ "VideoIntelligence.VFM.Mulberry.OverriddenAdapters"
+ "VideoIntelligence.VFM.Mulberry.OverriddenFunctionName"
+ "VideoIntelligence.VFM.Mulberry.OverriddenModelPath"
+ "VideoIntelligence/MulberryInferenceProvider.swift"
+ "VideoIntelligence/MulberryModel.swift"
+ "WorkAttribution(0x"
+ "[AssetRegistrySource] [MA] [Catalog] starting download, QoS %{public}s, %{public}s"
+ "[AssetRegistrySource] [MA] [Download] startDownload, QoS %{public}s, %{public}s"
+ "[AssetRegistrySource] [MA] [Query] issuing query, QoS %{public}s, %{public}s"
+ "[AssetRegistrySource] [MA] _downloadAsset(), QoS %{public}s, %{public}s"
+ "[AssetRegistrySource] [MA] _ensureMetadataAssetDownloaded(), QoS %{public}s, %{public}s"
+ "[AssetRegistrySource] [MA] _findAssetAndRetry(), QoS %{public}s, %{public}s"
+ "[AssetRegistrySource] [MA] joining in-flight fetch, QoS %{public}s, effective QoS %{public}s"
+ "[AssetRegistrySource] [MA] joining in-flight resolution, QoS %{public}s, effective QoS %{public}s"
+ "[AssetRegistry] AssetRegistry %s resolve(), QoS %{public}s, %{public}s"
+ "[AssetRegistry] AssetRegistry %s resolveAssets(for:), QoS %{public}s, %{public}s"
+ "[MA] [Catalog] catalog change announces a download of ours, left for it to count"
+ "[MA] [Catalog] catalog change arrived after the source went away"
+ "[MA] [Catalog] could not observe catalog changes: notify status %u"
+ "[MA] [Catalog] could not stop observing catalog changes: notify status %u"
+ "[MA] [Catalog] counting the catalog change claimed by a download that failed, now generation %{public}s"
+ "[MA] [Catalog] mobileassetd replaced the catalog, now generation %{public}s"
+ "[MA] [Catalog] observing %{public}s"
+ "[MA] [Catalog] stopped observing catalog changes, token %d"
+ "[MA] [Download] cancelled before reaching MobileAsset: %s"
+ "[MA] [Download] cancelled downloading asset: %@"
+ "[MA] [Download] downloaded %s in %fs"
+ "[MA] [Download] downloaded but not refreshable: %s"
+ "[MA] [Download] downloading %s, progress: %@"
+ "[MA] [Download] failed to cancel: %@, %ld"
+ "[MA] [Download] failed: %@, %ld, %s"
+ "[MA] [Download] installed but refresh failed: %s"
+ "[MA] [Download] not starting, its client cancelled: %s"
+ "[MA] [Download] succeeded with an error attached: %@: %@"
+ "[MA] [Fetch] %s lost the publish race %ld times, giving up on this attempt"
+ "[MA] [Fetch] %s not local, state: %ld"
+ "[MA] [Metadata] %s: %@, reporting %@"
+ "[MA] [Metadata] %s: query %@, reporting %@"
+ "[MA] [Metadata] already downloaded: %s"
+ "[MA] [Metadata] asset download already in progress, consolidating..."
+ "[MA] [Metadata] asset is not local after download: %s, state: %ld"
+ "[MA] [Metadata] discarding assets found under catalog generation %{public}s, now %{public}s"
+ "[MA] [Metadata] no catalog refresh landed, querying installed assets instead: %@"
+ "[MA] [Metadata] not caching an asset found before a catalog refresh: %s"
+ "[MA] [Metadata] prior asset download completed, retrying..."
+ "[MA] [Query] a catalog landed while resolving an asset this device has not installed, asking again"
+ "[MA] [Query] a catalog landed while this query ran, leaving its freshness alone and keeping the wind-back"
+ "[MA] [Query] failed: result %ld, error: %@"
+ "[MA] [Query] failed: succeeded but reported an error: %@"
+ "[MA] [Query] found %s %s/%s in %fs"
+ "[MA] [Query] matched within allowed differences"
+ "[MA] [Query] no catalog landed for the retry, not asking the daemon again"
+ "[MA] [Query] no installed asset to prefer over the listed one, keeping %s"
+ "[MA] [Query] no locally installed asset among the results"
+ "[MA] [Query] no usable catalog, considering only locally installed assets"
+ "[MA] [Query] skipping asset missing AssetVersionInfo: %s"
+ "[MA] [Query] skipping asset missing BuildVersionTuple: %s"
+ "[MA] [Query] skipping asset missing BundleVersionTuple: %s"
+ "[MA] [Query] the catalog could not be refreshed, preferring the installed %s over the listed %s"
+ "[MA] [Query] the wind-back is already spent, leaving the freshness window to govern the next attempt"
+ "[MA] discarding assets built under catalog generation %{public}s, now %{public}s"
+ "[MA] ignoring a second completion for an already-retired operation"
+ "[MA] sharing an asset whose work is still in flight: %s"
+ "[Mulberry] MulberryInferenceProvider.prepare() called, %{public}s"
+ "[Mulberry] MulberryInferenceProvider.prepare(), QoS %{public}s, %{public}s"
+ "[Mulberry] MulberryInferenceProvider.run() called, %{public}s"
+ "[Mulberry] MulberryModel.fetching() task started, %{public}s"
+ "[Mulberry] MulberryModel.fetching(), QoS %{public}s, %{public}s"
+ "[Mulberry] MulberryModel.resolvingState() task started, %{public}s"
+ "[Mulberry] MulberryModel.resolvingState(), QoS %{public}s, %{public}s"
+ "[OVERRIDING] Ignoring inaccessible Mulberry adapter: %s: %s"
+ "[OVERRIDING] Ignoring inaccessible Mulberry model path: %s"
+ "[OVERRIDING] Mulberry adapter: %s: %s"
+ "[OVERRIDING] Mulberry function name: %s"
+ "[OVERRIDING] Mulberry model has been overridden via UserDefaults"
+ "[OVERRIDING] Mulberry model path: %s"
+ "[wrMETs] MA FF is disabled."
+ "[wrMETs] MA FF is enabled."
+ "abandoned the resolution of requirement: %s"
+ "angular_uncertainty"
+ "assetMetadata(for:compatibilityVersion:escalating:)"
+ "boosted work in progress, %{public}s"
+ "clamping out-of-range relative priority %{public}d to %{public}d"
+ "com.apple.MobileAsset.VideoIntelligence.ma.cached-metadata-updated"
+ "com.apple.VideoIntelligence."
+ "decommitting I/O bindings"
+ "dev_placeholder_out"
+ "discarding cached metadata: the source changed what it can serve (was %{public}s, now %{public}s)"
+ "done decommitting I/O bindings"
+ "dropping relative priority %{public}d attached to an unspecified QoS class"
+ "error decommitting I/O bindings"
+ "fetching(escalating:)"
+ "fetching(scheduling:)"
+ "has uncommitted I/O bindings"
+ "ignoring unsupported QoS class 0x%{public}x"
+ "invalidationKey: requires concrete implementation"
+ "joints_uncertainty"
+ "metadata is already being loaded with requirement: %s, joining the load in progress"
+ "not caching a metadata load failure answered before a provider refresh, %s: %@"
+ "not caching a resolution failure answered before a provider refresh, %s: %@"
+ "not caching a transient metadata load failure for requirement: %s, error: %@"
+ "not caching a transient resolution failure for requirement: %s, error: %@"
+ "not caching metadata loaded before a provider refresh, %s"
+ "pthread_get_qos_class_np(0x%{public}lx) failed: %d"
+ "pthread_threadid_np(0x%{public}lx) failed: %d"
+ "requirement depends on itself: %s, recursive requirement detected"
+ "resolution of requirement: %s was cancelled"
+ "resolvingState(escalating:)"
+ "resolvingState(scheduling:)"
+ "startResolving(requirement:escalating:completionHandler:): requires concrete implementation"
+ "unclassified error answered as transient; add a `TransientError` conformance to have it decided: %@"
+ "user-interactive"
+ "uvd_joints_variance"
- "AssetRegistry %s: all sources not available"
- "AssetRegistry %s: skipping mobile asset provider %s, due to resolving error %@"
- "AssetRegistry %s: timed out waiting for %s to finish resolving %s"
- "I/O bindings have been previously committed, decommiting before binding"
- "VideoIntelligence/AssetMetadataProviding.swift"
- "[MA] [Download] asset successfully downloaded: %s, elapsed time: %f"
- "[MA] [Download] cancelled downloading asset: %s"
- "[MA] [Download] downloading asset: %s, progress: %@"
- "[MA] [Download] failed to cancel downloading asset: %s, result: %ld"
- "[MA] [Download] failed to download asset: %s, error: %@"
- "[MA] [Metadata] asset already downloaded: %s"
- "[MA] [Query] failed: %@"
- "[MA] [Query] found asset: %@, bundle version: %s, build version: %s, elapsed time: %f"
- "[MA] [Query] skipping asset missing AssetVersionInfo: %@"
- "[MA] [Query] skipping asset missing BuildVersionTuple: %@"
- "[MA] [Query] skipping asset missing BundleVersionTuple: %@"
- "decommiting I/O bindings"
- "done decommiting I/O bindings"
- "error decommiting I/O bindings"
- "has uncommited I/O bindings"
- "ongoing resolution for requirement: %s, recursive requirement detected"
- "resolve(requirement:completionHandler:): requires concrete implementation"
```
