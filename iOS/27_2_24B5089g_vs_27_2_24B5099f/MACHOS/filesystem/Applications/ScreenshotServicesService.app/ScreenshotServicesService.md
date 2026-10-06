## ScreenshotServicesService

> `/Applications/ScreenshotServicesService.app/ScreenshotServicesService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7c734` | `0x7c800` | **`+0xcc`** |
| `__DATA.__objc_const` | `0xb998` | `0xba58` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x17e1c` | `0x17d8c` | **`-0x90`** |
| `__TEXT.__oslogstring` | `0x2168` | `0x21c8` | **`+0x60`** |
| `__DATA.__objc_data` | `0x1e20` | `0x1e70` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x10e00` | `0x10dc0` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x8334` | `0x8314` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x582f` | `0x580f` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x5528` | `0x5510` | **`-0x18`** |
| `__TEXT.__auth_stubs` | `0x2870` | `0x2860` | **`-0x10`** |
| `__TEXT.__objc_classname` | `0x1319` | `0x1329` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x7f0` | `0x7e8` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x1448` | `0x1440` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xa58` | `0xa60` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x2b0` | `0x2b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2330` | `0x2338` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-451.0.0.0.0
+452.1.2.0.0

-  Functions: 2977
+  Functions: 2976

-  CStrings:  4844
+  CStrings:  4841
Symbols:
+ _OBJC_CLASS_$_UIWindowScene
- _UIAccessibilityIsReduceTransparencyEnabled
CStrings:
+ "Application"
+ "SSSApplicationSceneDelegate"
+ "TB,R,N,V_didLaunchSuspended"
+ "connecting scene is not a UIWindowScene: %{private}@"
+ "launched as a view service, not setting up the debug UI"
- "@\"SSSDittoDebugViewController\""
- "T@\"UIWindow\",&,N,V_window"
- "TB,N,V_didLaunchSuspended"
- "_backgroundColorView"
- "_debugViewController"
- "_setUpDevelopmentUI"
- "_shouldSetUpDevelopmentUI"
- "setDidLaunchSuspended:"
```
