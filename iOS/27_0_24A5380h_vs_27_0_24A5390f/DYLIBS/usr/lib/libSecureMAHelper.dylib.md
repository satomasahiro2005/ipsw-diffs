## libSecureMAHelper.dylib

> `/usr/lib/libSecureMAHelper.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x2e15` | `0x2e25` | **`+0x10`** |
| `__TEXT.__text` | `0x1e548` | `0x1e540` | **`-0x8`** |

### Other Changes

```diff

-2215.0.13.0.0
+2215.0.16.0.0
Functions:
~ _getPlistDictionary : 516 -> 508
CStrings:
+ "[ERROR] %{public}s: Extracted object for key %{public}@ is invalid/not a dictionary"
+ "[ERROR] %{public}s: Unable to extract plist object for key %{public}@ from dict"
- "%{public}s: Extracted object for key %{public}@ is invalid/not a dictionary"
- "%{public}s: Unable to extract plist object for key %{public}@ from dict"
```
