## AppIntentsRunnerXPCService

> `/System/Library/PrivateFrameworks/AppIntentsServices.framework/XPCServices/AppIntentsRunnerXPCService.xpc/AppIntentsRunnerXPCService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f1f8` | `0x3df34` | **`-0x12c4`** |
| `__DATA.__common` | `0x1f0` | `0x148` | **`-0xa8`** |
| `__TEXT.__eh_frame` | `0x4338` | `0x42b8` | **`-0x80`** |
| `__TEXT.__auth_stubs` | `0x2180` | `0x21e0` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x1600` | `0x15b8` | **`-0x48`** |
| `__DATA.__data` | `0xb30` | `0xaf8` | **`-0x38`** |
| `__DATA_CONST.__auth_got` | `0x10c8` | `0x10f8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x9fc` | `0xa1d` | **`+0x21`** |
| `__DATA_CONST.__got` | `0x8a0` | `0x890` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x285` | `0x292` | **`+0xd`** |
| `__TEXT.__oslogstring` | `0xe24` | `0xe2d` | **`+0x9`** |
| `__DATA_CONST.__auth_ptr` | `0x618` | `0x620` | **`+0x8`** |
| `__TEXT.__const` | `0x21f8` | `0x21f2` | **`-0x6`** |
| `__TEXT.__swift5_typeref` | `0xc01` | `0xc02` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-41.1.10.0.0
+41.1.15.0.0

-  Functions: 1452
-  Symbols:   220
-  CStrings:  361
+  Functions: 1441
+  Symbols:   217
+  CStrings:  362
Symbols:
- _objc_retain_x27
- _swift_conformsToProtocol2
- _swift_release_x9
CStrings:
+ "%sCannot cancel execution: executor is nil"
+ "%sReceived environmentForViewSnippet request"
+ "%sReceived preferredContentSizeForViewSnippet request"
+ "%sResponding to environment for view snippet | snippetEnvironment=%@"
+ "%sResponding to preferred content size for view snippet | size=%s"
+ "ClientSessionGracePeriod"
+ "ExecutionResultRetention"
- "Cannot cancel execution: executor is nil"
- "[%s] Received environmentForViewSnippet request"
- "[%s] Received preferredContentSizeForViewSnippet request"
- "[%s] Responding to environment for view snippet | snippetEnvironment=%@"
- "[%s] Responding to preferred content size for view snippet | size=%s"
- "runnerDispatcher"
```
