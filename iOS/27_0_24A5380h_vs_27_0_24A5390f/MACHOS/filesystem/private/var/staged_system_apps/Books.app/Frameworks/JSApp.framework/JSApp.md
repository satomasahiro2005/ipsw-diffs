## JSApp

> `/private/var/staged_system_apps/Books.app/Frameworks/JSApp.framework/JSApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x84d80` | `0x87094` | **`+0x2314`** |
| `__TEXT.__oslogstring` | `0x34e4` | `0x3964` | **`+0x480`** |
| `__TEXT.__cstring` | `0x4669` | `0x4719` | **`+0xb0`** |
| `__TEXT.__objc_methname` | `0xa031` | `0xa0d1` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0x6980` | `0x6a20` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x26d8` | `0x2758` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x2910` | `0x2960` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x2790` | `0x27b8` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x1498` | `0x14c0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x2560` | `0x2588` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x446c` | `0x448c` | **`+0x20`** |
| `__DATA.__common` | `0x60` | `0x78` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x930` | `0x940` | **`+0x10`** |
| `__TEXT.__const` | `0x2bf4` | `0x2be4` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-6643.0.0.0.0
+6647.0.0.0.0

-  Functions: 3148
-  Symbols:   743
-  CStrings:  2982
+  Functions: 3166
+  Symbols:   744
+  CStrings:  3008
Symbols:
+ _JSStringGetLength
CStrings:
+ "$bootstrap should return a Runtime object"
+ "-[JSAEnvironment loadScriptFromPackage:completion:]"
+ "-[JSAEnvironment loadScriptFromPackage:completion:]_block_invoke"
+ "Failed to load file from JetPack, path: %s, error: %@"
+ "Failed to load metadata from JetPack, name: %s, error: %@"
+ "Failed to load string from JetPack, path: %s, error: %@"
+ "Failed to persist diagnostics to %{public}s: %@"
+ "Failed to read dir from JetPack, path: %s, error: %@"
+ "JSABridge loadScriptFromPackage: done, success=%@"
+ "JSAEnvironment %{public}s Failed to create folder for diagnostics files for load script failure, script size=%lu, error: %@"
+ "JSAEnvironment %{public}s Failed to save app.js to diagnostics folder, size=%lu, error: %@"
+ "JSAEnvironment %{public}s JS script is empty. Something is wrong with JetPack loading"
+ "JSAEnvironment %{public}s Package is nil!"
+ "JSAEnvironment %{public}s Persisted diagnostic files to %@"
+ "JSAEnvironment %{public}s Persisting diagnostic files due to failure to load script from JetPack, path=%@"
+ "JSAEnvironment %{public}s Saved app.js to diagnostics folder, size=%lu"
+ "JSAEnvironment %{public}s Script is nil!"
+ "JSAEnvironment %{public}s script.length=%lu, name=%@, version=%@, isBundled=%@"
+ "JSAEnvironment %{public}s unable to decode the string using ASCII encoding, something is wrong with javascript app"
+ "JetPackDiagnostics"
+ "Persisted diagnostics to %{public}s"
+ "URLByAppendingPathComponent:isDirectory:"
+ "We should have App in javascript"
+ "We should have config in javascript"
+ "copyItemAtURL:toURL:error:"
+ "createNewDiagnosticsDirAndReturnError:"
+ "persistDiagnosticsTo:"
+ "setDateFormat:"
+ "setLocale:"
+ "writeToURL:options:error:"
+ "yyyy-MM-dd-HHmmss"
- "JSABridge loadScriptFromPackage: done"
- "JSAEnvironment %{public}s"
- "JSAEnvironment %{public}s unable to encode the string using ASCII encoding, something is wrong with javascript app"
- "setPrefersEdgeAttachedInCompactHeight:"
- "sheetPresentationController"
```
