## InputAnalytics

> `/System/Library/PrivateFrameworks/InputAnalytics.framework/InputAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fbdc` | `0x1fcac` | **`+0xd0`** |
| `__AUTH_CONST.__cfstring` | `0x9480` | `0x94c0` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x4208` | `0x4238` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x26cc` | `0x26fc` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x628` | `0x648` | **`+0x20`** |
| `__TEXT.__cstring` | `0x61a2` | `0x61c2` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x980` | `0x998` | **`+0x18`** |
| `__DATA.__bss` | `0x138` | `0x148` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1ff0` | `0x2000` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1250` | `0x1260` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x390` | `0x384` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0x4a0` | `0x4a8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x278` | `0x280` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x230` | `0x234` | **`+0x4`** |

### Other Changes

```diff

-153.0.0.0.0
+154.1.4.0.0

-  Functions: 1046
-  Symbols:   2675
-  CStrings:  1383
+  Functions: 1051
+  Symbols:   2687
+  CStrings:  1386
Symbols:
+ +[IASAnalyzer shouldSendToBiomeStream]
+ -[IASAnalyzer setTestDelegate:]
+ -[IASAnalyzer testDelegate]
+ _CTOSPlatformAll
+ _IAPayloadKeyImageGenerationNumInputImages
+ _IAPayloadValueSidecarInteractionModalitySidecar
+ _NSClassFromString
+ _OBJC_CLASS_$_CTCategory
+ _OBJC_IVAR_$_IASAnalyzer._testDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_IXAXPCProtocol
+ ___38+[IASAnalyzer shouldSendToBiomeStream]_block_invoke
+ _shouldSendToBiomeStream.isRunningUnderXCTest
+ _shouldSendToBiomeStream.onceToken
- _OBJC_CLASS_$_CTCategories
CStrings:
+ "!!"
+ "NumInputImages"
+ "XCTestCase"
```
