## AppRestrictionsCore

> `/System/Library/PrivateFrameworks/AppRestrictionsCore.framework/AppRestrictionsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ed4` | `0x3fac` | **`+0xd8`** |
| `__AUTH_CONST.__objc_const` | `0xf38` | `0xf90` | **`+0x58`** |
| `__TEXT.__cstring` | `0xfc` | `0x13c` | **`+0x40`** |
| `__AUTH.__data` | `0x88` | `0xb8` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x78` | `0x48` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x424` | `0x43c` | **`+0x18`** |
| `__DATA_CONST.__objc_catlist` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x260` | `0x268` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x188` | `0x190` | **`+0x8`** |

### Other Changes

```diff

-14.0.0.0.0
+19.0.0.0.0

-  Functions: 113
-  Symbols:   225
-  CStrings:  7
+  Functions: 114
+  Symbols:   229
+  CStrings:  8
Symbols:
+ _OBJC_CLASS_$_ALRSceneHostedPreflightSpecification
+ _OBJC_CLASS_$_UISceneConnectionOptions
+ _OBJC_METACLASS_$_ALRSceneHostedPreflightSpecification
+ __CATEGORY_INSTANCE_METHODS_UISceneConnectionOptions_$_Preflight
+ __CATEGORY_PROPERTIES_UISceneConnectionOptions_$_Preflight
+ __CATEGORY_UISceneConnectionOptions_$_Preflight
+ __DATA_ALRSceneHostedPreflightSpecification
+ __INSTANCE_METHODS_ALRSceneHostedPreflightSpecification
+ __METACLASS_DATA_ALRSceneHostedPreflightSpecification
+ __PROPERTIES_ALRSceneHostedPreflightSpecification
- _OBJC_CLASS_$__TtC19AppRestrictionsCore33SceneHostedPreflightSpecification
- _OBJC_METACLASS_$__TtC19AppRestrictionsCore33SceneHostedPreflightSpecification
- __DATA__TtC19AppRestrictionsCore33SceneHostedPreflightSpecification
- __INSTANCE_METHODS__TtC19AppRestrictionsCore33SceneHostedPreflightSpecification
- __METACLASS_DATA__TtC19AppRestrictionsCore33SceneHostedPreflightSpecification
- __PROPERTIES__TtC19AppRestrictionsCore33SceneHostedPreflightSpecification
CStrings:
+ "AppRestrictionsCore/UISceneConnectionOptions+Preflight.swift"
```
