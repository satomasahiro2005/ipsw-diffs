## DocumentManager

> `/System/Library/PrivateFrameworks/DocumentManager.framework/DocumentManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x950` | `0x30` | **`-0x920`** |
| `__DATA_DIRTY.__data` | `—` | `0x920` | **`+0x920`** |
| `__TEXT.__text` | `0x33a80` | `0x340e4` | **`+0x664`** |
| `__TEXT.__oslogstring` | `0x348c` | `0x3599` | **`+0x10d`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a90` | `0x2ae8` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x45e0` | `0x4620` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0x4280` | `0x42a0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2e44` | `0x2e64` | **`+0x20`** |
| `__TEXT.__cstring` | `0x4df6` | `0x4e09` | **`+0x13`** |
| `__TEXT.__unwind_info` | `0xdb8` | `0xdc8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x638` | `0x640` | **`+0x8`** |
| `__DATA_CONST.__objc_catlist` | `0x60` | `0x68` | **`+0x8`** |

### Other Changes

```diff

-401.1.5.0.0
+403.1.8.0.0

-  Functions: 1253
-  Symbols:   2237
-  CStrings:  846
+  Functions: 1261
+  Symbols:   2243
+  CStrings:  853
Symbols:
+ -[FPSandboxingURLWrapper(DOCCallerAuthorization) doc_noFollowSafeWrapper]
+ -[FPSandboxingURLWrapper(DOCCallerAuthorization) doc_wrapperAuthorizedForConnection:readonly:]
+ _FPOriginalDocumentURL
+ __OBJC_$_CATEGORY_FPSandboxingURLWrapper_$_DOCCallerAuthorization
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_FPSandboxingURLWrapper_$_DOCCallerAuthorization
+ ___73-[FPSandboxingURLWrapper(DOCCallerAuthorization) doc_noFollowSafeWrapper]_block_invoke
CStrings:
+ "%@ Could not make a no follow wrapper for %@: %@"
+ "Caller has no sandbox access to %@ readonly: %d"
+ "Could not resolve wrapped URL: %@"
+ "No connection to authorize wrapper against: %@"
+ "Resolvable URL not allowed access %@ readonly: %d"
+ "Wrapper carries no sandbox extension: %@"
+ "visibilityPriority"
```
