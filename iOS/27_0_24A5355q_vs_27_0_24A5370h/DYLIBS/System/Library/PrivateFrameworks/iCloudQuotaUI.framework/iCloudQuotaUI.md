## iCloudQuotaUI

> `/System/Library/PrivateFrameworks/iCloudQuotaUI.framework/iCloudQuotaUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x161094` | `0x16140c` | **`+0x378`** |
| `__TEXT.__oslogstring` | `0xb8d2` | `0xb9b2` | **`+0xe0`** |
| `__TEXT.__swift5_reflstr` | `0x1a00` | `0x1a20` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x52e0` | `0x52d0` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2214` | `0x2220` | **`+0xc`** |

### Other Changes

```diff

-301.24.0.19.0
+301.24.0.21.0

-  Functions: 7927
+  Functions: 7929

-  CStrings:  2555
+  CStrings:  2558
CStrings:
+ "Presenter %@ not in window hierarchy; aborting present"
+ "Provided viewcontroller is already presenting! Falling back to topmost view controller"
+ "Provided viewcontroller is detached from the window hierarchy! Falling back to topmost view controller"
+ "Provided viewcontroller is nil, using topmost view controller"
- "Provided viewcontroller is already presenting! Using workaround to get topmost view controller"
```
