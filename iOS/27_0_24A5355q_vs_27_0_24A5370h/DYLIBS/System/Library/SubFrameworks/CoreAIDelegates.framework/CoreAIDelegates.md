## CoreAIDelegates

> `/System/Library/SubFrameworks/CoreAIDelegates.framework/CoreAIDelegates`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27834` | `0x2d990` | **`+0x615c`** |
| `__TEXT.__cstring` | `0x95d` | `0x11ad` | **`+0x850`** |
| `__TEXT.__eh_frame` | `0x1828` | `0x1600` | **`-0x228`** |
| `__DATA.__bss` | `0x2380` | `0x2280` | **`-0x100`** |
| `__AUTH_CONST.__auth_got` | `0xba8` | `0xc48` | **`+0xa0`** |
| `__TEXT.__swift5_reflstr` | `0x57d` | `0x5ef` | **`+0x72`** |
| `__TEXT.__swift5_capture` | `0x78` | `0x24` | **`-0x54`** |
| `__TEXT.__swift_as_cont` | `0xc4` | `0x78` | **`-0x4c`** |
| `__TEXT.__swift5_fieldmd` | `0x694` | `0x6dc` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x500` | `0x542` | **`+0x42`** |
| `__TEXT.__unwind_info` | `0x978` | `0x938` | **`-0x40`** |
| `__DATA.__data` | `0x5c0` | `0x5f8` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x270` | `0x2a8` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0x2270` | `0x2298` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `0x44` | `0x28` | **`-0x1c`** |
| `__TEXT.__swift_as_ret` | `0x40` | `0x28` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x78` | `0x88` | **`+0x10`** |
| `__AUTH.__data` | `0x328` | `0x330` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x120` | `0x118` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-3600.67.4.0.0
+3600.73.1.0.0

-  Functions: 755
+  Functions: 758

-  CStrings:  91
+  CStrings:  136
Symbols:
+ _fsync
+ _swift_release_x26
+ _swift_retain_x25
+ _swift_retain_x28
- _objc_retain_x25
- _swift_release_n
- _swift_retain_x27
- _swift_task_create
CStrings:
+ " after already removing invalid specialized asest at this location."
+ " at staging location: "
+ " expected to be empty after move, found: "
+ " failed: Asset does not resolve to the current cache"
+ " failed: Path resolves to lock-file directory"
+ " failed: Path resolves to staging directory"
+ " has been specialized into "
+ " is not a valid .aimodel or .aimodelc."
+ " supports architectures "
+ " — likely deleted concurrently"
+ "%{public}s"
+ ". Removing invalid asset before proceeding."
+ ": Invalid extension type (expected aimodelx)"
+ ": Item should be located within "
+ "A specialized asset already exists for "
+ "AIModel(contentsOf:options:) received a model already specialized in the cache. Loading asset from the cache."
+ "AIModel: compiled asset at "
+ "AIModel: sync/ staging directory unexpectedly absent after createDirectory at "
+ "AIModelCache for "
+ "AIModelCache.default"
+ "An invalid specialized asset was found for "
+ "COREAI_ENABLE_DEFAULT_PROFILER"
+ "Cannot move item at "
+ "Cleanup of old directories failed: Asset does not resolve to the current cache"
+ "Cleanup of old directories failed: Asset provided is invalid"
+ "Cleanup of old directories leading to "
+ "Deletion could not be completed, assets still in use"
+ "Derived delegate options: "
+ "Failed to barrier fsync directory: "
+ "Failed to delete requested cache entries: Asset at "
+ "Failed to determine tmp source directory, invalid destination provided: "
+ "Failed to fsync directory: "
+ "Failed to full fsync directory: "
+ "Failed to move asset at "
+ "Failed to open directory for fsync: "
+ "Failed to remove empty directories left-over in move from: "
+ "Failed to resolve bookmark data: "
+ "Failed to specialize model at "
+ "Invalid specialized asset exists for "
+ "Override delegate options: "
+ "Setting delegate options to: "
+ "Unable to determine Core AI architecture name for this device. Returning architectureName as \"unknown\""
+ "Unable to get key for model at "
+ "Unable to get key pinning entry "
+ "^(unknown|[A-Za-z]*\\d+[A-Z]\\d+[a-z]?\\d*[a-z]?)$"
+ "but the current device is "
+ "delegateOptionsOverride:"
+ "enableDefaultOSPreferredCompute:"
+ "h7p"
+ "linux"
+ "unsupported"
- "%s"
- ": asset does not exist"
- "CoreAIDelegates/AIModel+Architecture.swift"
- "Failed to delete asset at "
- "ODIE_ENABLE_DEFAULT_PROFILER"
- "Unable to determine the Core AI architecture name for this device."
```
