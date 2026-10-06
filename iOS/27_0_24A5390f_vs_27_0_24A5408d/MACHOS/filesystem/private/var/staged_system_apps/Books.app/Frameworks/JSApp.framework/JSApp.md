## JSApp

> `/private/var/staged_system_apps/Books.app/Frameworks/JSApp.framework/JSApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x87094` | `0x87bb0` | **`+0xb1c`** |
| `__TEXT.__cstring` | `0x4719` | `0x47b9` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0xa0d1` | `0xa151` | **`+0x80`** |
| `__DATA_CONST.__cfstring` | `0x2da0` | `0x2e00` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x3964` | `0x39c4` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x6a20` | `0x6a60` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x56f9` | `0x5731` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x448c` | `0x44b4` | **`+0x28`** |
| `__DATA.__data` | `0x2fc8` | `0x2fe8` | **`+0x20`** |
| `__DATA.__objc_const` | `0x8260` | `0x8278` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x27b8` | `0x27d0` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x2176` | `0x2186` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x10a0` | `0x10aa` | **`+0xa`** |
| `__TEXT.__unwind_info` | `0x2588` | `0x2590` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-6647.0.0.0.0
+6655.0.0.0.0

-  Functions: 3166
+  Functions: 3177

-  CStrings:  3008
+  CStrings:  3017
CStrings:
+ "-[JSAEnvironment _loadScript:name:version:isBundled:completion:]"
+ "-[JSAEnvironment _loadScript:name:version:isBundled:completion:]_block_invoke"
+ "-[JSAEnvironment _loadScriptFromPackage:retryCount:completion:]"
+ "-[JSAEnvironment _loadScriptFromPackage:retryCount:completion:]_block_invoke"
+ "BKScriptEvaluationRetryCount"
+ "JS script is empty"
+ "JSAEnvironment %{public}s Retrying loading script due to corrupted script. Remaining tries: %ld"
+ "Loading script caused an exception"
+ "Unable to decode the string using ASCII encoding"
+ "_loadScript:name:version:isBundled:completion:"
+ "_loadScriptFromPackage:retryCount:completion:"
+ "scriptEvaluationRetryCount"
+ "setScriptEvaluationRetryCount:"
+ "v40@0:8@16q24@?32"
+ "yyyy-MM-dd-HHmmss.SSS"
- "-[JSAEnvironment loadScript:name:version:isBundled:completion:]"
- "-[JSAEnvironment loadScript:name:version:isBundled:completion:]_block_invoke"
- "-[JSAEnvironment loadScriptFromPackage:completion:]"
- "-[JSAEnvironment loadScriptFromPackage:completion:]_block_invoke"
- "loadScript:name:version:isBundled:completion:"
- "yyyy-MM-dd-HHmmss"
```
