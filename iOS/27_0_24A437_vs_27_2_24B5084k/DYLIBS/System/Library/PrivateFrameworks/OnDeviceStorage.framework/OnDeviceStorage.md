## OnDeviceStorage

> `/System/Library/PrivateFrameworks/OnDeviceStorage.framework/OnDeviceStorage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__eh_frame` | `0x2d60` | `0x3758` | **`+0x9f8`** |
| `__TEXT.__oslogstring` | `—` | `0x52f` | **`+0x52f`** |
| `__TEXT.__text` | `0x3573c` | `0x35bd8` | **`+0x49c`** |
| `__TEXT.__cstring` | `0x84c` | `0x49c` | **`-0x3b0`** |
| `__TEXT.__unwind_info` | `0xf68` | `0x11a0` | **`+0x238`** |
| `__TEXT.__const` | `0xd38` | `0xee0` | **`+0x1a8`** |
| `__AUTH_CONST.__const` | `0x568` | `0x658` | **`+0xf0`** |
| `__TEXT.__swift_as_cont` | `0x2e8` | `0x364` | **`+0x7c`** |
| `__TEXT.__swift_as_entry` | `0x120` | `0x19c` | **`+0x7c`** |
| `__TEXT.__swift_as_ret` | `0x11c` | `0x194` | **`+0x78`** |
| `__DATA.__data` | `0x320` | `0x380` | **`+0x60`** |
| `__AUTH.__objc_data` | `—` | `0x50` | **`+0x50`** |
| `__DATA_DIRTY.__data` | `0x640` | `0x600` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0x8f0` | `0x8b8` | **`-0x38`** |
| `__TEXT.__swift5_capture` | `0x1f0` | `0x1b8` | **`-0x38`** |
| `__DATA_DIRTY.__common` | `0x98` | `0x68` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0x72d` | `0x75b` | **`+0x2e`** |
| `__AUTH_CONST.__objc_const` | `0x398` | `0x370` | **`-0x28`** |
| `__DATA.__common` | `0x8` | `0x30` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x298` | `0x2b4` | **`+0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0x27c` | `0x288` | **`+0xc`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-3.0.59.0.0
+3.1.10.0.0

-  Functions: 625
-  Symbols:   291
-  CStrings:  57
+  Functions: 727
+  Symbols:   305
+  CStrings:  59
Symbols:
+ ___swift__destructor
+ ___swift_destroy_boxed_opaque_existential_1Tm
+ __os_log_impl
+ __swiftImmortalRefCount
+ _objc_release_x19
+ _objc_release_x20
+ _objc_release_x23
+ _objc_release_x26
+ _objc_release_x27
+ _objc_release_x28
+ _objc_retain_x25
+ _os_log_type_enabled
+ _swift_bridgeObjectRelease_n
+ _swift_release_n
+ _swift_release_x9
+ _swift_retain_n
+ _swift_retain_x19
+ _swift_retain_x23
+ _symbolic SDyS2SG
+ _symbolic SaySDyS2SGG
+ _symbolic ShySSG
+ _symbolic _____ 3XPC12XPCRichErrorV
+ _symbolic _____SgXw 15OnDeviceStorage06DaemonC7SessionC
+ _symbolic _____SgXwz_Xx 15OnDeviceStorage06DaemonC7SessionC
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
+ _symbolic ytSg
+ _symbolic ytSgIeAgHr_
- ___swift_allocate_boxed_opaque_existential_0
- ___swift_allocate_boxed_opaque_existential_0Tm
- ___swift_destroy_boxed_opaque_existential_1
- ___swift_exist.box.addr_destructor
- _objc_retain_x26
- _swift_getErrorValue
- _swift_release_x28
- _swift_retain
- _swift_retain_x28
- _swift_task_localValueGet
- _symbolic _____y_____G s23_ContiguousArrayStorageC 18OnDeviceFoundation10LogMessageV
- _symbolic _____y_____G s9TaskLocalC 18OnDeviceFoundation8OSLoggerV
- _symbolic _____y______pG s9TaskLocalC 18OnDeviceFoundation6LoggerP
CStrings:
+ "%{public}s"
+ "✨ Successfully opened connection: %{public}s"
+ "➕ The insert request has been processed in %{public}ld batches."
+ "🌐 %{public}s"
+ "📝 The upsert request has been processed in %{public}ld batches."
+ "📡 Creating XPC session for %{public}s"
+ "📡 Failed to send message to XPC service. (%{public}s)"
+ "📡 Sending request to daemon: %{public}s"
+ "📡 XPC session has been cancelled. (%{public}s)"
+ "📦 Fetched %{public}ld rows in batch %{public}ld"
+ "📦 Fetched %{public}ld rows in paginated batch %{public}ld"
+ "📦 Fetched data for select query in %{public}ld batches"
+ "📦 Fetching %{public}ld rows per batch for select request"
+ "📦 Fetching %{public}ld rows per page batch for select request"
+ "🙈 %{public}ld row(s) were dropped due to missing non-nullable values for the following required columns: %{public}s"
+ "🙈 The following columns were ignored due to access restrictions: %{public}s"
+ "🚪 Closed connection to: %{public}s, with result: %{bool,public}d"
+ "🚪🧹 Open connection deinit detected, closing for id: %{public}s"
+ "🚪🧹 Unable to close connection, reason: %{public}s"
- " row(s) were dropped due to missing non-nullable values for the following required columns: "
- " rows in paginated batch "
- " rows per batch for select request"
- " rows per page batch for select request"
- "✨ Successfully opened connection: "
- "➕ The insert request has been processed in "
- "📝 The upsert request has been processed in "
- "📡 Creating XPC session for "
- "📡 Failed to send message to XPC service. ("
- "📡 Sending request to daemon: "
- "📡 XPC message send failed: "
- "📡 XPC session has been cancelled. ("
- "📦 Fetched data for select query in "
- "🙈 The following columns were ignored due to access restrictions: "
- "🚪 Closed connection to: "
- "🚪🧹 Open connection deinit detected, closing for id: "
- "🚪🧹 Unable to close connection, reason: "
```
