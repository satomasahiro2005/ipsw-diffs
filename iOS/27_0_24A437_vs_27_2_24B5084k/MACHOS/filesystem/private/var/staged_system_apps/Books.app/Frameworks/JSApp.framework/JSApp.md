## JSApp

> `/private/var/staged_system_apps/Books.app/Frameworks/JSApp.framework/JSApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x87be4` | `0x87888` | **`-0x35c`** |
| `__TEXT.__objc_stubs` | `0x6a60` | `0x6c20` | **`+0x1c0`** |
| `__TEXT.__objc_methname` | `0xa151` | `0xa2c1` | **`+0x170`** |
| `__TEXT.__cstring` | `0x47b9` | `0x4899` | **`+0xe0`** |
| `__DATA.__objc_selrefs` | `0x27d0` | `0x2840` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x39c4` | `0x3964` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x5731` | `0x5771` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x2e00` | `0x2e20` | **`+0x20`** |
| `__TEXT.__const` | `0x2be4` | `0x2c04` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0xb78` | `0xb98` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x10aa` | `0x10c6` | **`+0x1c`** |
| `__DATA.__objc_const` | `0x8278` | `0x8290` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x2960` | `0x2950` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x44b4` | `0x44a4` | **`-0x10`** |
| `__TEXT.__objc_methtype` | `0x2186` | `0x2176` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x14c0` | `0x14b8` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x5b0` | `0x5b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2590` | `0x2598` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2f8` | `0x2fc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
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
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_classname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-6655.0.0.0.0
+6713.0.0.0.0

-  Functions: 3177
-  Symbols:   744
-  CStrings:  3017
+  Functions: 3174
+  Symbols:   742
+  CStrings:  3038
Symbols:
- _JSStringCreateWithUTF8CString
- _objc_retainAutorelease
CStrings:
+ "-[JSAEnvironment loadScriptFromPackage:completion:]"
+ "-[JSAEnvironment loadScriptFromPackage:completion:]_block_invoke"
+ "T@\"UIColor\",R,N,V_semanticBackgroundColor"
+ "_semanticBackgroundColor"
+ "booksGroupedBackground"
+ "booksQuaternaryLabel"
+ "booksSecondaryBackground"
+ "booksSecondaryGroupedBackground"
+ "booksSecondaryLabel"
+ "booksTertiaryBackground"
+ "booksTertiaryGroupedBackground"
+ "booksTertiaryLabel"
+ "magentaColor"
+ "quaternaryLabelColor"
+ "secondaryLabelColor"
+ "secondarySystemGroupedBackgroundColor"
+ "semanticBackgroundColor"
+ "semanticUIColorWithName:"
+ "systemBackgroundColor"
+ "systemBlueColor"
+ "systemGreenColor"
+ "systemGroupedBackgroundColor"
+ "systemOrangeColor"
+ "systemPurpleColor"
+ "systemRedColor"
+ "systemTealColor"
+ "systemWhiteColor"
+ "tertiaryLabelColor"
+ "tertiarySystemBackgroundColor"
+ "tertiarySystemGroupedBackgroundColor"
- "-[JSAEnvironment _loadScriptFromPackage:retryCount:completion:]"
- "-[JSAEnvironment _loadScriptFromPackage:retryCount:completion:]_block_invoke"
- "BKScriptEvaluationRetryCount"
- "JSAEnvironment %{public}s Retrying loading script due to corrupted script. Remaining tries: %ld"
- "_loadScriptFromPackage:retryCount:completion:"
- "bytes"
- "scriptEvaluationRetryCount"
- "setScriptEvaluationRetryCount:"
- "v40@0:8@16q24@?32"
```
