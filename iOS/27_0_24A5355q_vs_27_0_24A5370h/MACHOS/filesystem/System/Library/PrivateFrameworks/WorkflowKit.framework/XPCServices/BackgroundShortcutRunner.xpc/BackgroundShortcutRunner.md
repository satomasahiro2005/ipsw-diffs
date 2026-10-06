## BackgroundShortcutRunner

> `/System/Library/PrivateFrameworks/WorkflowKit.framework/XPCServices/BackgroundShortcutRunner.xpc/BackgroundShortcutRunner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7e370` | `0x87db0` | **`+0x9a40`** |
| `__TEXT.__eh_frame` | `0x4110` | `0x47f0` | **`+0x6e0`** |
| `__TEXT.__cstring` | `0xf02` | `0x13d6` | **`+0x4d4`** |
| `__TEXT.__oslogstring` | `0xc45` | `0x1088` | **`+0x443`** |
| `__TEXT.__unwind_info` | `0x1348` | `0x1498` | **`+0x150`** |
| `__TEXT.__auth_stubs` | `0x30f0` | `0x3220` | **`+0x130`** |
| `__TEXT.__const` | `0x1868` | `0x1980` | **`+0x118`** |
| `__TEXT.__swift5_typeref` | `0xe2f` | `0xf35` | **`+0x106`** |
| `__TEXT.__objc_methname` | `0x25bf` | `0x266f` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0x1f60` | `0x2000` | **`+0xa0`** |
| `__DATA_CONST.__auth_got` | `0x1888` | `0x1920` | **`+0x98`** |
| `__DATA.__data` | `0x1280` | `0x12f0` | **`+0x70`** |
| `__DATA_CONST.__got` | `0xda0` | `0xe08` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x21a8` | `0x2208` | **`+0x60`** |
| `__TEXT.__swift_as_cont` | `0x2c0` | `0x308` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x9a0` | `0x9e4` | **`+0x44`** |
| `__DATA.__objc_selrefs` | `0xa18` | `0xa48` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x4b8` | `0x4e0` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x150` | `0x178` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `0xcc` | `0xf0` | **`+0x24`** |
| `__TEXT.__objc_methlist` | `0x62c` | `0x644` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x4dc` | `0x4f0` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x400` | `0x410` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x4cc` | `0x4bc` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0x6c` | `0x70` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`

### Other Changes

```diff

-5025.0.25.103.0
+5028.0.21.0.0

-  - /usr/lib/swift/libswiftCompression.dylib

-  Functions: 2673
-  Symbols:   367
-  CStrings:  617
+  Functions: 2710
+  Symbols:   365
+  CStrings:  688
Symbols:
+ _swift_retain_x22
- __swift_FORCE_LOAD_$_swiftCompression
- _objc_release_x13
- _objc_release_x9
CStrings:
+ "%s runToolWithInvocation: called without stepwise-execution entitlement, rejecting"
+ "-[WFIsolatedShortcutRunner runToolWithInvocation:]"
+ "Action indexing took %fs"
+ "Adding bundled and interchange actions for updated bundles"
+ "Bumping version"
+ "Bundle cache: %ld hits, %ld misses"
+ "Clearing existing data"
+ "Clearing unused data"
+ "Creating SiriKit actions for updated bundles"
+ "Creating all available AppIntents actions"
+ "Enumerating actions"
+ "Evaluating testing config"
+ "IndexActionContainers"
+ "IndexActionContainers.AccessorContainerQuery"
+ "IndexActionContainers.ContainerIndexerLookup"
+ "IndexTool.OutputType"
+ "IndexTool.ParameterAwait"
+ "IndexTool.ParameterLoop"
+ "IndexTool.Savepoint"
+ "IndexTool.SpotlightCheck"
+ "IndexTool.VisibilityFlags"
+ "IndexType.ContentItem"
+ "IndexType.IndexActionParameters"
+ "IndexType.Parameter"
+ "IndexType.PrewarmActionParameters"
+ "IndexType.PrewarmContentItems"
+ "Indexing FlowTools"
+ "Indexing actions"
+ "Indexing new triggers"
+ "Indexing seed state"
+ "Indexing types"
+ "Loading daemons + initializing indexers"
+ "Optimizing database"
+ "Preflight.Actions"
+ "Preflight.Actions.AppIntents"
+ "Preflight.Actions.Bundled"
+ "Preflight.Actions.PerBundle"
+ "Preflight.Actions.SiriKit"
+ "Preflight.LaunchServicesSnapshot"
+ "Preflight.LinkSnapshot"
+ "Reindex.BumpVersion"
+ "Reindex.ClearExistingData"
+ "Reindex.ClearUnusedData"
+ "Reindex.EffectiveChangeset"
+ "Reindex.EvaluateTestingConfig"
+ "Reindex.IndexActions"
+ "Reindex.IndexFlowTools"
+ "Reindex.IndexNewTriggers"
+ "Reindex.IndexSeedState"
+ "Reindex.IndexTypes"
+ "Reindex.LocalIndex"
+ "Reindex.Optimize"
+ "Reindex.Preflight"
+ "Reindex.Setup"
+ "Reindex.UpdateUnderspecifiedContainers"
+ "Resolving effective changeset"
+ "Taking Launch Services snapshot"
+ "Taking Link snapshot"
+ "Type indexing (params + content items) took %fs"
+ "Updating underspecified containers"
+ "allowStepwiseExecution"
+ "bundle=%{signpost.description:attribute}s"
+ "bundleCacheHitCount"
+ "bundleCacheMissCount"
+ "changeset=%{signpost.description:attribute}s"
+ "count=%{signpost.description:attribute}ld"
+ "hydrate options: displayRep.requiredImage=%s value=%s"
+ "hydrateEncodedRemoteHydrationRequest:completionBlock:"
+ "hydrateEncodedRemoteHydrationRequest:completionHandler:"
+ "process: BGSR"
+ "resetBundleCache"
+ "setCacheAllLocales:"
- "hydrateEntitiesWithIdentifiers:entityMetadata:context:completionHandler:"
```
