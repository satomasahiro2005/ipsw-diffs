## PreviewsFoundationOS

> `/System/Library/PrivateFrameworks/PreviewsFoundationOS.framework/PreviewsFoundationOS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x149bac` | `0x14aaec` | **`+0xf40`** |
| `__TEXT.__cstring` | `0x528b` | `0x55a9` | **`+0x31e`** |
| `__DATA.__bss` | `0xdc10` | `0xdd90` | **`+0x180`** |
| `__AUTH_CONST.__const` | `0xff50` | `0x10078` | **`+0x128`** |
| `__TEXT.__unwind_info` | `0x5a80` | `0x5a10` | **`-0x70`** |
| `__TEXT.__eh_frame` | `0x8150` | `0x8104` | **`-0x4c`** |
| `__TEXT.__swift5_capture` | `0x3298` | `0x32d0` | **`+0x38`** |
| `__DATA.__data` | `0x6b60` | `0x6b90` | **`+0x30`** |
| `__TEXT.__const` | `0xffa4` | `0xffcc` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x5d13` | `0x5d21` | **`+0xe`** |
| `__TEXT.__swift5_proto` | `0x8a0` | `0x8ac` | **`+0xc`** |
| `__TEXT.__swift5_reflstr` | `0x2280` | `0x228c` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x1aa8` | `0x1ab0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x9a0` | `0x998` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x59f4` | `0x59fc` | **`+0x8`** |

### Other Changes

```diff

-24.0.45.1.0
+24.20.6.0.0

-  Functions: 8030
-  Symbols:   2419
-  CStrings:  431
+  Functions: 8058
+  Symbols:   2421
+  CStrings:  429
Symbols:
+ ___swift_closure_destructor.119Tm
+ ___swift_closure_destructor.150Tm
+ ___swift_closure_destructor.21Tm
+ ___swift_closure_destructor.32Tm
+ ___swift_closure_destructor.5Tm
+ ___swift_exist.box.addr_destructor.78Tm
+ _symbolic _____ySay______pGG s12LazySequenceV 20PreviewsFoundationOS18HumanReadableErrorP
- ___swift_closure_destructor.116Tm
- ___swift_closure_destructor.12Tm
- ___swift_closure_destructor.131Tm
- ___swift_closure_destructor.44Tm
- ___swift_exist.box.addr_destructor.75Tm
CStrings:
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Collections/ChunkStack.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Collections/OrderedDictionary.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Concurrency/AsyncObservableEvent.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Concurrency/AsyncStream+Sink.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Concurrency/CancelationToken.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Concurrency/Continuation.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Concurrency/FirstSuccess.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Concurrency/Invalidatable/ConcurrentInvalidatableCache.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Concurrency/Invalidatable/InvalidationHandle.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Concurrency/Invalidatable/IsolatedInvalidatableCache.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Concurrency/Task & Promise/IsolatedTask.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Concurrency/Task & Promise/Task+Promise.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Concurrency/Task & Promise/TaskRef.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/CrashReports/Errors/CrashReportError+ConditionInFileError.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/CrashReports/Errors/CrashReportError+DyldLibraryLoadCrashError.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/CrashReports/Errors/CrashReportError+IndexOutOfRangeError.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/CrashReports/Errors/CrashReportError+MissingEnvironmentObjectError.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/CrashReports/Errors/CrashReportError+UncaughtExceptionError.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/CrashReports/Symbolication/CrashLogSymbolicator.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Error Handling/UVExceptionHandling.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Event Stream/EventStream+Operators.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Event Stream/EventStream.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Event Stream/EventStreamObservable.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Future/Future Subclasses/FlatMapFuture.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Future/Future Subclasses/MapFuture.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Future/Future Subclasses/PromiseFuture.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Future/Future Subclasses/TimeoutFuture.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Future/Future Subclasses/TraverseFuture.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Future/Future Subclasses/ZipFuture.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Future/Future+Observation.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Future/Future.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Future/SerialQueue/FutureSerialQueue.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/QueryResolver/QueryManager.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/QueryResolver/ValueCombiner.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/Assertion.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/AssociatedObjectCache.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/AutoCancelling.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/BuildNumber.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/ConcurrentFutureCache.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/CountedSharedResourceStore.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/DelayedInvocation.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/Error+UVAdditions.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/ErrorParsingUtilities.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/FulfillOnce.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/IOPowerSource.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/Invalidatable.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/InvalidatableCache.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/ManagedResource.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/PropertyList.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/ResourceHub.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/SingleFireEvent.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/SynchronousAccessProviding.swift"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Utilities/UserDefaults.swift"
- "   Invalidated: "
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Assertion.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/AssociatedObjectCache.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/AsyncObservableEvent.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/AsyncStream+Sink.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/AutoCancelling.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/BuildNumber.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/CancelationToken.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/ChunkStack.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/ConcurrentFutureCache.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/ConcurrentInvalidatableCache.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Continuation.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/CountedSharedResourceStore.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/CrashLogSymbolicator.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/CrashReportError+ConditionInFileError.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/CrashReportError+DyldLibraryLoadCrashError.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/CrashReportError+IndexOutOfRangeError.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/CrashReportError+MissingEnvironmentObjectError.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/CrashReportError+UncaughtExceptionError.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/DelayedInvocation.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Error+UVAdditions.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/ErrorParsingUtilities.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/EventStream+Operators.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/EventStream.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/EventStreamObservable.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/FirstSuccess.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/FlatMapFuture.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/FulfillOnce.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Future+Observation.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Future.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/FutureSerialQueue.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/IOPowerSource.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Invalidatable.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/InvalidatableCache.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/InvalidationHandle.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/IsolatedInvalidatableCache.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/IsolatedTask.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/ManagedResource.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/MapFuture.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/OrderedDictionary.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/PromiseFuture.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/PropertyList.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/QueryManager.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/ResourceHub.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/SingleFireEvent.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/SynchronousAccessProviding.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/Task+Promise.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/TaskRef.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/TimeoutFuture.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/TraverseFuture.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/UVExceptionHandling.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/UserDefaults.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/ValueCombiner.swift"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/UITestingAgent/Shared/PreviewsFoundation/Sources/PreviewsFoundation/ZipFuture.swift"
- "Was unable to access defaults for "
```
