## TranslationDaemon

> `/System/Library/PrivateFrameworks/TranslationDaemon.framework/TranslationDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a6b80` | `0x1a6db0` | **`+0x230`** |
| `__TEXT.__oslogstring` | `0xd480` | `0xd5e0` | **`+0x160`** |
| `__TEXT.__const` | `0xa7a` | `0xa9a` | **`+0x20`** |

### Other Changes

```diff

-384.3.0.0.0
+385.0.0.0.0

-  Functions: 10393
+  Functions: 10395

-  CStrings:  2223
+  CStrings:  2227
CStrings:
+ "Client asked to download only unsupported languages, won't proceed with request"
+ "Client asked to download some invalid languages, only proceeding with filtered list: %{public}@"
+ "Client asked to remove only unsupported languages, ignoring request"
+ "Client asked to remove some invalid languages, only proceeding with removing filtered list: %{public}@"
```
