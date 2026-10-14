## AskPermissionUI

> `/Applications/AskPermissionUI.app/AskPermissionUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe65c` | `0xee9c` | **`+0x840`** |
| `__TEXT.__objc_methname` | `0x424f` | `0x44e8` | **`+0x299`** |
| `__TEXT.__objc_methtype` | `0x18d2` | `0x1ab4` | **`+0x1e2`** |
| `__TEXT.__objc_stubs` | `0x2640` | `0x2820` | **`+0x1e0`** |
| `__DATA.__objc_const` | `0x26f8` | `0x2898` | **`+0x1a0`** |
| `__TEXT.__objc_methlist` | `0x1480` | `0x1578` | **`+0xf8`** |
| `__DATA.__objc_selrefs` | `0xf60` | `0x1018` | **`+0xb8`** |
| `__TEXT.__oslogstring` | `0xe08` | `0xe87` | **`+0x7f`** |
| `__DATA.__data` | `0x420` | `0x480` | **`+0x60`** |
| `__DATA_CONST.__cfstring` | `0x1580` | `0x15e0` | **`+0x60`** |
| `__DATA.__objc_data` | `0x550` | `0x5a0` | **`+0x50`** |
| `__TEXT.__cstring` | `0xad8` | `0xb0b` | **`+0x33`** |
| `__TEXT.__unwind_info` | `0x308` | `0x338` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x26a` | `0x298` | **`+0x2e`** |
| `__TEXT.__gcc_except_tab` | `0x168` | `0x184` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x280` | `0x290` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x88` | `0x90` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x58` | `0x60` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__const` | `0xb0` | `0xb8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x17c` | `0x180` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-130.1.6.0.0
+130.1.7.2.2

+  - /System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/AppleMediaServicesUI

-  Functions: 276
-  Symbols:   173
-  CStrings:  1044
+  Functions: 289
+  Symbols:   177
+  CStrings:  1079
Symbols:
+ _OBJC_CLASS_$_AMSUIAlertDialogTask
+ _OBJC_CLASS_$_AMSUIAuthenticateTask
+ _OBJC_CLASS_$_AMSUIWebViewController
+ _OBJC_METACLASS_$_AMSUIWebViewController
CStrings:
+ "%{public}@: Error loading manage sandbox account URL. Error: %{public}@"
+ "%{public}@: Presenting sandbox account view controller"
+ "AMSUIWebDelegate"
+ "Accounts"
+ "B40@0:8@\"AMSUIWebViewController\"16@\"NSDictionary\"24@?<v@?@@\"NSError\">32"
+ "SandboxAccountViewController"
+ "URL"
+ "_loadManageSandboxAccountURL"
+ "_presentSandboxAccountViewController"
+ "addErrorBlock:"
+ "addFinishBlock:"
+ "ams_activeiTunesAccount"
+ "ams_sharedAccountStoreForMediaType:"
+ "arrayForKey:"
+ "host"
+ "initWithBag:account:clientInfo:"
+ "initWithRequest:presentingViewController:"
+ "loadBagValue:"
+ "manage-sandbox-account-url"
+ "manageSandboxAccountURL"
+ "performAuthentication"
+ "present"
+ "sandboxAccountsBag"
+ "trustedDomains"
+ "v32@0:8@\"AMSUIWebViewController\"16@\"NSMutableURLRequest\"24"
+ "v40@0:8@\"AMSUIWebViewController\"16@\"AMSAuthenticateRequest\"24@?<v@?@\"AMSAuthenticateResult\"@\"NSError\">32"
+ "v40@0:8@\"AMSUIWebViewController\"16@\"AMSDialogRequest\"24@?<v@?@\"AMSDialogResult\"@\"NSError\">32"
+ "v40@0:8@\"AMSUIWebViewController\"16@\"AMSPurchaseResult\"24@\"NSError\"32"
+ "v48@0:8@\"AMSUIWebViewController\"16@\"NSDictionary\"24@\"NSError\"32@?<v@?@@\"NSError\">40"
+ "webViewController:didEncodeNetworkRequest:"
+ "webViewController:didFinishPurchaseWithResult:error:"
+ "webViewController:didResolveWithResult:error:completion:"
+ "webViewController:handleAuthenticateRequest:completion:"
+ "webViewController:handleDelegateAction:completion:"
+ "webViewController:handleDialogRequest:completion:"
```
