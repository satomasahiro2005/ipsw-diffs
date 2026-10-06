## AppManagedFeaturesDemoExtension

> `/System/Library/ExtensionKit/Extensions/AppManagedFeaturesDemoExtension.appex/AppManagedFeaturesDemoExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1514` | `0x3bb4` | **`+0x26a0`** |
| `__TEXT.__eh_frame` | `0xf8` | `0x388` | **`+0x290`** |
| `__TEXT.__auth_stubs` | `0x2d0` | `0x4f0` | **`+0x220`** |
| `__TEXT.__oslogstring` | `0x7e` | `0x1ae` | **`+0x130`** |
| `__DATA_CONST.__auth_got` | `0x168` | `0x280` | **`+0x118`** |
| `__TEXT.__unwind_info` | `0xe8` | `0x1b0` | **`+0xc8`** |
| `__TEXT.__objc_stubs` | `—` | `0xc0` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x90` | `0x130` | **`+0xa0`** |
| `__TEXT.__const` | `0x11a` | `0x1aa` | **`+0x90`** |
| `__TEXT.__objc_methname` | `—` | `0x6e` | **`+0x6e`** |
| `__DATA_CONST.__const` | `0x90` | `0xe0` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x20` | `0x68` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x69` | `0x9f` | **`+0x36`** |
| `__DATA.__objc_selrefs` | `—` | `0x30` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `—` | `0x30` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0xc` | `0x38` | **`+0x2c`** |
| `__TEXT.__swift_as_ret` | `0xc` | `0x28` | **`+0x1c`** |
| `__DATA.__data` | `0xa0` | `0xb8` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x78` | `0x90` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x18` | `0x30` | **`+0x18`** |

### Same-size Content Changes

- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-46.0.7.0.0
+46.0.15.0.0

-  Functions: 37
-  Symbols:   58
-  CStrings:  6
+  Functions: 73
+  Symbols:   79
+  CStrings:  23
Symbols:
+ _OBJC_CLASS_$_NSJSONSerialization
+ _OBJC_CLASS_$_NSURLSession
+ _OBJC_CLASS_$_NSUserDefaults
+ ___chkstk_darwin
+ ___stack_chk_fail
+ ___stack_chk_guard
+ __swift_stdlib_bridgeErrorToNSError
+ _objc_msgSend
+ _objc_opt_self
+ _objc_release
+ _objc_release_x25
+ _objc_release_x26
+ _objc_retain_x8
+ _swift_deallocObject
+ _swift_errorRelease
+ _swift_errorRetain
+ _swift_release_x8
+ _swift_retain
+ _swift_task_create
+ _swift_unknownObjectRelease
+ _swift_willThrow
CStrings:
+ "Invalid workload URL: %{public}s"
+ "JSONObjectWithData:options:error:"
+ "Network request failed (round=%ld, task=%ld): %{public}@"
+ "Network workload complete: totalBytesDownloaded=%{public}ld"
+ "Network workload starting: url=%{public}s, iterations=%ld, concurrency=%ld"
+ "NetworkWorkloadConcurrency"
+ "NetworkWorkloadEnabled"
+ "NetworkWorkloadIterations"
+ "NetworkWorkloadURL"
+ "Workload round %ld/%ld"
+ "boolForKey:"
+ "hash sentinel"
+ "https://apple.com"
+ "integerForKey:"
+ "sharedSession"
+ "standardUserDefaults"
+ "stringForKey:"
```
