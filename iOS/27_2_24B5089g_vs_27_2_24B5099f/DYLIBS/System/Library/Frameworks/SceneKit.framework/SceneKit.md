## SceneKit

> `/System/Library/Frameworks/SceneKit.framework/SceneKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x391f4c` | `0x3921d8` | **`+0x28c`** |
| `__TEXT.__oslogstring` | `0x166fc` | `0x1679c` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x402c` | `0x4094` | **`+0x68`** |
| `__TEXT.__cstring` | `0x99c1f` | `0x99bc0` | **`-0x5f`** |
| `__DATA_CONST.__const` | `0x7a00` | `0x79e0` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1758` | `0x1768` | **`+0x10`** |
| `__DATA.__data` | `0x293c` | `0x2944` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd4b8` | `0xd4c0` | **`+0x8`** |

### Other Changes

```diff

-612.0.0.0.0
+612.101.0.0.0

-  Functions: 19668
-  Symbols:   24479
+  Functions: 19675
+  Symbols:   24481
Symbols:
+ _objc_exception_rethrow
+ _objc_terminate
CStrings:
+ "Error: Cannot generate valid tangents with ill-formed normal source"
+ "Error: ERROR: GenericSource deserialize => we used to support only floats, but another type was encountered"
+ "Unreachable code: Compound type %@×%d is not supported"
+ "Unreachable code: Compound type C3DBaseType(%d)×%d is not supported"
+ "Welcome to SceneKit 612.101 (Sep 26 2026 05:57:37)"
- "(numberType == kCFNumberFloatType) || (numberType == kCFNumberFloat32Type)"
- "Assertion '%s' failed. Only one compound type per vector"
- "Assertion '%s' failed. We used to support only floats, but another type was encountered"
- "Welcome to SceneKit 612 (Sep 12 2026 06:32:54)"
- "componentCount == 1"
```
