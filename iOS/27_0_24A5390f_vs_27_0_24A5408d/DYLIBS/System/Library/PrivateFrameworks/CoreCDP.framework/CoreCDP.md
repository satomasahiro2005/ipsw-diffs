## CoreCDP

> `/System/Library/PrivateFrameworks/CoreCDP.framework/CoreCDP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f648` | `0x4f6a8` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x91af` | `0x91ef` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1658` | `0x1660` | **`+0x8`** |

### Other Changes

```diff

-445.0.0.0.0
+447.0.0.0.0
CStrings:
+ "Failed to update walrus status with error domain=%{public}@ code=%{public}ld"
+ "Walrus update failed with error: domain=%{public}@ code=%{public}ld"
- "Failed to update walrus status with error %@"
- "Walrus update failed with error: %@"
```
