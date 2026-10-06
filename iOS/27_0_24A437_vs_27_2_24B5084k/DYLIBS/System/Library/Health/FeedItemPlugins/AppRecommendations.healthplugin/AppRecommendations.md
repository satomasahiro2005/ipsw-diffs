## AppRecommendations

> `/System/Library/Health/FeedItemPlugins/AppRecommendations.healthplugin/AppRecommendations`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2299c` | `0x22c10` | **`+0x274`** |
| `__TEXT.__oslogstring` | `0xf62` | `0xfd2` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x290` | `0x2a8` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0xb78` | `0xb60` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x4b0` | `0x4c8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xc20` | `0xc28` | **`+0x8`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

-  Functions: 391
-  Symbols:   177
-  CStrings:  68
+  Functions: 395
+  Symbols:   178
+  CStrings:  69
Symbols:
+ _OBJC_CLASS_$__HKBehavior
CStrings:
+ "%{public}s: App recommendations are disabled. Deleting any existing feed items and skipping generation."
```
