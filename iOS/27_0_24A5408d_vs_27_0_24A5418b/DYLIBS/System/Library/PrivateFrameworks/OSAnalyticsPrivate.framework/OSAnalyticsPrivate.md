## OSAnalyticsPrivate

> `/System/Library/PrivateFrameworks/OSAnalyticsPrivate.framework/OSAnalyticsPrivate`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a8f8` | `0x1adec` | **`+0x4f4`** |
| `__TEXT.__oslogstring` | `0x28bc` | `0x293c` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x24e0` | `0x2520` | **`+0x40`** |
| `__TEXT.__cstring` | `0x15be` | `0x15fe` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1010` | `0x1050` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xdd8` | `0xdf8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x430` | `0x438` | **`+0x8`** |

### Other Changes

```diff

-1056.0.22.0.0
+1056.2.1.0.0

-  Functions: 385
-  Symbols:   883
-  CStrings:  585
+  Functions: 390
+  Symbols:   888
+  CStrings:  592
Symbols:
+ -[PCCEndpoint modelIdentifierForDevice:]
+ -[PCCEndpoint productVersionForDevice:]
+ -[PCCIDSEndpoint deviceForTarget:]
+ -[PCCIDSEndpoint modelIdentifierForDevice:]
+ -[PCCIDSEndpoint productVersionForDevice:]
CStrings:
+ "%@ for device %@: model=%{public}@ productVersion=%{public}@ -> %{public}s"
+ "%@ for device %@: productVersion=%{public}@ -> %{public}s"
+ "<nil>"
+ "AppleTV"
+ "SKIPPING (pre-Rizz Apple TV)"
+ "SKIPPING (pre-Rizz)"
+ "supported"
```
