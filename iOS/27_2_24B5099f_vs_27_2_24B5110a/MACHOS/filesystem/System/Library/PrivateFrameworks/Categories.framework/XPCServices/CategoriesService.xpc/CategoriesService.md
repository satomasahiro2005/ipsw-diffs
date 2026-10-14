## CategoriesService

> `/System/Library/PrivateFrameworks/Categories.framework/XPCServices/CategoriesService.xpc/CategoriesService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x50b4` | `0x51e8` | **`+0x134`** |
| `__TEXT.__objc_methname` | `0xf12` | `0xfa3` | **`+0x91`** |
| `__TEXT.__objc_methtype` | `0x2ce` | `0x34f` | **`+0x81`** |
| `__TEXT.__objc_stubs` | `0xec0` | `0xf20` | **`+0x60`** |
| `__DATA.__objc_const` | `0x7c0` | `0x808` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x62c` | `0x66c` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x3cc` | `0x404` | **`+0x38`** |
| `__TEXT.__cstring` | `0x61c` | `0x641` | **`+0x25`** |
| `__DATA.__objc_selrefs` | `0x490` | `0x4b0` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0xac0` | `0xae0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x100` | `0x10c` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x188` | `0x190` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x28` | `0x2c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
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

### Other Changes

```diff

-58.1.5.0.0
+58.1.7.1.0

-  Functions: 88
+  Functions: 91

-  CStrings:  356
+  CStrings:  367
CStrings:
+ "-[Categories_Service appStoreCategoriesForBundleIDs:platform:origin:replyHandler:]"
+ "-[Categories_Service appStoreCategoriesForBundleIDs:platform:origin:replyHandler:]_block_invoke"
+ "@32@0:8@16q24"
+ "START: Media API lookup on behalf of %{private}@ (proxy: %{private}@): %{private}@"
+ "_lookupAppStoreUsing:platform:clientApplication:origin:withCompletionHandler:"
+ "_origin"
+ "appStoreCategoriesForBundleIDs:platform:origin:replyHandler:"
+ "com.apple.mobilesafari"
+ "initWithCallingProcess:origin:"
+ "platform is nil. Calling completionHandler"
+ "proxyAppBundleID"
+ "setProxyAppBundleID:"
+ "v48@0:8@\"NSArray\"16@\"NSString\"24q32@?<v@?@\"NSDictionary\"@\"NSError\">40"
+ "v48@0:8@16@24q32@?40"
+ "v56@0:8@16@24@32q40@?48"
- "-[Categories_Service appStoreCategoriesForBundleIDs:platform:replyHandler:]"
- "-[Categories_Service appStoreCategoriesForBundleIDs:platform:replyHandler:]_block_invoke"
- "START: Media API lookup on behalf of %{private}@: %{private}@"
- "_lookupAppStoreUsing:platform:clientApplication:withCompletionHandler:"
```
