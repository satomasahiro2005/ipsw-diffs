## WebApp

> `/System/Library/PrivateFrameworks/WebApp.framework/WebApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f18` | `0x3330` | **`+0x418`** |
| `__DATA_CONST.__got` | `0x0` | `0x108` | **`+0x108`** |
| `__DATA_CONST.__objc_selrefs` | `0x7a8` | `0x800` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x156` | `0x194` | **`+0x3e`** |
| `__AUTH_CONST.__const` | `0x40` | `0x60` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x148` | `0x168` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x824` | `0x844` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x168` | `0x188` | **`+0x20`** |
| `__TEXT.__cstring` | `0x22a` | `0x23c` | **`+0x12`** |

### Other Changes

```diff

-625.1.22.10.3
+625.1.24.10.1

-  Functions: 78
-  Symbols:   315
-  CStrings:  34
+  Functions: 83
+  Symbols:   324
+  CStrings:  36
Symbols:
+ -[WebAppSceneDelegate _liveManagedGuidedBrowserSceneExcludingSession:]
+ -[WebAppSceneDelegate _notifyMainGuidedBrowserOfBlockedNewWindowOnScene:]
+ -[WebAppViewController showGuidedBrowsingNewWindowBlockedNotice]
+ GCC_except_table22
+ GCC_except_table28
+ _OBJC_CLASS_$_UIWindowScene
+ ___58-[WebAppSceneDelegate scene:willConnectToSession:options:]_block_invoke
+ ___block_descriptor_32_e17_v16?0"NSError"8l
+ __os_log_error_impl
+ _objc_enumerationMutation
+ _objc_opt_isKindOfClass
+ _objc_retain_x25
- GCC_except_table21
- GCC_except_table27
- _objc_retain_x24
CStrings:
+ "Failed to destroy duplicate Guided Browsing scene: %{public}@"
+ "v16@?0@\"NSError\"8"
```
