## AppManagedFeatures

> `/System/Library/Frameworks/AppManagedFeatures.framework/AppManagedFeatures`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x27c3` | `0x2843` | **`+0x80`** |
| `__TEXT.__text` | `0x7a228` | `0x7a260` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0xfec` | `0x101c` | **`+0x30`** |
| `__TEXT.__const` | `0x75d0` | `0x75e0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x10dc` | `0x10e8` | **`+0xc`** |

### Other Changes

```diff

-58.40.13.0.0
+58.42.1.0.0

-  CStrings:  277
+  CStrings:  279
Functions:
~ sub_20337f9dc -> sub_2038319dc : 120 -> 124
~ sub_2033a82d4 -> sub_20385a2d8 : 2616 -> 2668
CStrings:
+ "The configuration storage is not available until the device is unlocked for the first time."
+ "containerUnavailable"
```
