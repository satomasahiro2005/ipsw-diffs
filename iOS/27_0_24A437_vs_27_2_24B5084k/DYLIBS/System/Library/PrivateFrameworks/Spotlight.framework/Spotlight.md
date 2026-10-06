## Spotlight

> `/System/Library/PrivateFrameworks/Spotlight.framework/Spotlight`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9bec0` | `0x9f968` | **`+0x3aa8`** |
| `__TEXT.__oslogstring` | `0x5608` | `0x5822` | **`+0x21a`** |
| `__TEXT.__eh_frame` | `0x1130` | `0x1200` | **`+0xd0`** |
| `__AUTH_CONST.__const` | `0x1400` | `0x1488` | **`+0x88`** |
| `__AUTH_CONST.__auth_got` | `0x12f0` | `0x1368` | **`+0x78`** |
| `__TEXT.__cstring` | `0x35cc` | `0x355c` | **`-0x70`** |
| `__TEXT.__const` | `0xe24` | `0xe74` | **`+0x50`** |
| `__DATA.__bss` | `0x8d0` | `0x910` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x17e8` | `0x1828` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x5564` | `0x5598` | **`+0x34`** |
| `__TEXT.__swift5_capture` | `0x3c8` | `0x3f4` | **`+0x2c`** |
| `__DATA_CONST.__got` | `0x18f0` | `0x1918` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x3000` | `0x2fe0` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0x7bc` | `0x7da` | **`+0x1e`** |
| `__AUTH_CONST.__objc_intobj` | `0x258` | `0x270` | **`+0x18`** |
| `__DATA.__data` | `0x750` | `0x768` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x414` | `0x3fc` | **`-0x18`** |
| `__AUTH_CONST.__objc_const` | `0x4710` | `0x4700` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2e40` | `0x2e50` | **`+0x10`** |
| `__DATA_DIRTY.__objc_data` | `0xe60` | `0xe50` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x334` | `0x324` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x298` | `0x28c` | **`-0xc`** |
| `__DATA_DIRTY.__data` | `0x2f0` | `0x2f8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x118` | `0x114` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x98` | `0x9c` | **`+0x4`** |

### Other Changes

```diff

-2459.105.0.0.0
+2465.1.2.0.0

-  Functions: 1714
-  Symbols:   3184
-  CStrings:  933
+  Functions: 1735
+  Symbols:   3201
+  CStrings:  937
Symbols:
+ -[SPClientSession dealloc]
+ _CFNotificationCenterRemoveObserver
+ _CFPreferencesSynchronize
+ _SSAppExclusionsEnabled
+ _SSGetDisabledAppSet
+ _SSGetDisabledBundleSet
+ _SSInvalidateAppExclusionsDisabledIDsCache
+ __OBJC_$_CLASS_METHODS_SPGenerativeSearchClient(Spotlight|Spotlight)
+ __OBJC_$_INSTANCE_METHODS_SPGenerativeSearchClient(Spotlight|Spotlight)
+ __SPTCCSiriAccessChangedCallback
+ ___27-[SPClientSession activate]_block_invoke_2
+ ____SPTCCSiriAccessChangedCallback_block_invoke
+ ___swift_closure_destructor.157Tm
+ ___swift_closure_destructorTm
+ ___swift_project_boxed_opaque_existential_1
+ _activate.sTCCObserverOnce
+ _kCFPreferencesAnyHost
+ _kCFPreferencesCurrentUser
+ _notify_cancel
+ _swift_beginAccess
+ _swift_endAccess
+ _swift_retain_x27
+ _symbolic _____y_____GSg 12HybridSearch15ComposableQueryV AA11MailContentV
+ _symbolic _____y_____y_____GG s23_ContiguousArrayStorageC 12HybridSearch15ComposableQueryV AC11MailContentV
- -[SPClientSession disabledBundleIds]
- _SPGetDisabledAppSet
- _SPGetDisabledBundleSet
- __INSTANCE_METHODS_SPGenerativeSearchClient
- __OBJC_$_CLASS_METHODS_SPGenerativeSearchClient(Spotlight)
- ___swift_closure_destructor.186Tm
- _symbolic _____ 12HybridSearch15RetrievalResultV
CStrings:
+ "App Shortcuts"
+ "Contact participant mail query [%s] cancelled during error handling"
+ "Contact participant mail query [%s] cancelled with CancellationError"
+ "Contact participant mail query [%s] could not attach participant filter, returning no results: %s"
+ "Contact participant mail query [%s] failed: %s"
+ "Contact participant mail query [%s] returned %ld results, tophitCount=%ld"
+ "Contact participant mail query [%s]: %ld/%ld results dropped — unsupported entity types filtered by wrapMailSearchResults"
+ "Contact participant mail query [%s]: no usable contact handles, returning no results"
+ "Executing contact participant mail query [%s]: emails=%ld names=%ld limit: %ld"
+ "SPGenerativeSearchClient"
+ "SPZKWQueryTask addApplicationResultsFromPredictionResponse"
+ "TU extraction query [%s]: hsClient is nil — cannot resolve source documents for %ld TU results"
+ "[qid=%lu][SPKGenerativeSearchMailQuery] Contact-entity query: emails=%lu names=%lu"
+ "[qid=%lu][SPKGenerativeSearchSiriTranscriptQuery] Disabled: contact-entity search excludes transcripts"
+ "_kMDItemThumbnailData"
+ "com.apple.spotlight.tcc.siriAccessChanged"
+ "contactParticipant emails=%ld names=%ld limit=%ld"
+ "mailClientAdapter is nil - cannot execute contact participant mail query"
+ "status=filterRejected"
+ "zkw has %lu apps"
- "Mail identifier retrieval (hardFilter) [%s] cancelled"
- "Mail identifier retrieval (hardFilter) [%s] cancelled during error handling"
- "Mail identifier retrieval (hardFilter) [%s] failed: %s"
- "Mail identifier retrieval (hardFilter) [%s] returned %ld results"
- "MailSearchClient.retrieveIdentifiers"
- "Retrieving mail identifiers (hardFilter) [%s]: '%{private}s' llmParses=%ld"
- "SPZKWQueryTask addApplicationResultsFromPredictionResponse with apps: %lu"
- "TU extraction query [%s]: gsClient is nil — cannot resolve source documents for %ld TU results"
- "[qid=%lu][%{public}@] Empty query string. Returning early."
- "com.apple.CloudDocs.MobileDocumentsFileProvider"
- "com.apple.CloudDocs.iCloudDriveFileProvider"
- "com.apple.CloudDocs.iCloudDriveFileProviderManaged"
- "com.apple.FileProvider.LocalStorage"
- "mailClientAdapter is nil - cannot retrieve mail identifiers"
- "userQueryString=%{private}s llmParses=%ld"
- "zkw has apps"
```
