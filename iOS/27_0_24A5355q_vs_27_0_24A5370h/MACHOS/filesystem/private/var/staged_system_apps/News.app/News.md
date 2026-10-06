## News

> `/private/var/staged_system_apps/News.app/News`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6198c` | `0x6171c` | **`-0x270`** |
| `__DATA_CONST.__cfstring` | `0x3800` | `0x37c0` | **`-0x40`** |
| `__TEXT.__objc_methname` | `0x1785e` | `0x1787e` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xe280` | `0xe2a0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x898` | `0x8b4` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x77dc` | `0x77c4` | **`-0x18`** |
| `__TEXT.__oslogstring` | `0x2f37` | `0x2f24` | **`-0x13`** |
| `__DATA.__bss` | `0x760` | `0x750` | **`-0x10`** |
| `__TEXT.__cstring` | `0x8a84` | `0x8a74` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1a88` | `0x1a98` | **`+0x10`** |
| `__DATA.__objc_const` | `0xd508` | `0xd500` | **`-0x8`** |
| `__DATA.__objc_selrefs` | `0x5410` | `0x5418` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xd00` | `0xd08` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5916.1.0.0.0
+5920.0.0.0.0

-  Functions: 2713
-  Symbols:   899
+  Functions: 2710
+  Symbols:   900
Symbols:
+ _FCBackgroundAppRefreshTaskIdentifier
+ _FCNewsInternalExtrasBundle
+ _OBJC_CLASS_$_TSBackgroundTasksBackgroundFetchScheduler
- _FCURLForAppleInternalLibraryBundlesDirectory
- _OBJC_CLASS_$_TSApplicationBackgroundFetchScheduler
CStrings:
+ "_performBackgroundFetchWithCompletionHandler:"
+ "_registerBackgroundFetchScheduler"
+ "app was awoken for fetching via background app refresh task"
+ "initWithApplication:taskIdentifier:"
+ "performBridgedBackgroundFetch:"
+ "prepareForUseWithFetchHandler:"
+ "v16@?0@?<v@?Q>8"
- "NewsInternalExtras"
- "app was awoken for fetching via application:performFetchWithCompletionHandler:"
- "bundle"
- "fc_setMinimumBackgroundFetchInterval:"
- "initWithPath:"
- "pathForResource:ofType:"
- "prepareForUseWithApplicationDelegate:"
```
